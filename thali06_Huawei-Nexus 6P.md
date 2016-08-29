#### Test 8288334166fab8f_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 10:41:36.828   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:41:37.312  5611  5611 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 10:41:37.319  5611  5611 D AndroidRuntime: CheckJNI is OFF
08-29 10:41:37.344  5611  5611 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 10:41:37.381  5611  5611 I Radio-JNI: register_android_hardware_Radio DONE
08-29 10:41:37.398  5611  5611 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 10:41:37.406   932  3154 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 10:41:37.457   932  3154 I ActivityManager: Start proc 5620:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 10:41:37.462  5611  5611 D AndroidRuntime: Shutting down VM
08-29 10:41:37.550  5620  5620 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 10:41:37.581  5620  5620 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 10:41:37.611  5620  5620 I LibraryLoader: Time to load native libraries: 24 ms (timestamps 6329-6353)
08-29 10:41:37.611  5620  5620 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:41:37.633  5620  5620 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cdec27}
08-29 10:41:37.633  5620  5620 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:41:37.633  5620  5620 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 10:41:37.638  5620  5620 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 10:41:37.640  5620  5620 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 10:41:37.675  5620  5620 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 10:41:37.688  5620  5620 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 10:41:37.688  5620  5620 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 10:41:37.689  5620  5620 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 10:41:37.689  5620  5620 I Adreno  : Build Date                       : 10/21/15
08-29 10:41:37.689  5620  5620 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 10:41:37.689  5620  5620 I Adreno  : Local Branch                     : 
08-29 10:41:37.689  5620  5620 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 10:41:37.689  5620  5620 I Adreno  : Remote Branch                    : NONE
08-29 10:41:37.689  5620  5620 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 10:41:37.743   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e1a207c:true
,08-29 10:41:37.795  5620  5620 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 10:41:37.805  5620  5620 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 10:41:37.829   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:41:37.833  5620  5657 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 10:41:37.840  5620  5644 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 10:41:37.866  5620  5657 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 10:41:37.968   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +466ms (total +542ms)
,08-29 10:41:37.998  5620  5620 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5620
,08-29 10:41:38.092  5620  5620 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 10:41:38.252  5620  5660 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -575928016
,08-29 10:41:38.258  5620  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 10:41:38.258  5620  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 10:41:38.258  5620  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 10:41:38.258  5620  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 10:41:38.258  5620  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 10:41:38.258  5620  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98d93f5 added. We now have 1 listener(s)
,08-29 10:41:38.262  5620  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
08-29 10:41:38.262  5620  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:41:38.263  5620  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:41:38.263  5620  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 10:41:38.266  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 10:41:38.267  5620  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f66b018 added. We now have 1 listener(s)
08-29 10:41:38.267  5620  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:41:38.270   932  2977 D WifiService: New client listening to asynchronous messages
,08-29 10:41:38.271  5620  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:41:38.271  5620  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 10:41:38.271  5620  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 10:41:38.271  5620  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 10:41:38.271  5620  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 10:41:38.275  5620  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:41:38.275  5620  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 10:41:38.282  5620  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:38.283  5620  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:41:38.283  5620  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 10:41:38.283  5620  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:41:38.283  5620  5660 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 10:41:38.287  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:41:38.291  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:41:38.305  5620  5620 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 10:41:38.770  5620  5629 I art     : Background sticky concurrent mark sweep GC freed 77432(8MB) AllocSpace objects, 19(2MB) LOS objects, 27% free, 23MB/32MB, paused 1.580ms total 240.539ms
,08-29 10:41:38.829   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:41:38.831  5620  5666 W jxcore-log: Initializing JXcore engine
,08-29 10:41:38.831  5620  5666 W jxcore-log: JXcore engine is ready
,08-29 10:41:38.868  5666  5666 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1323 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 10:41:38.868  5666  5666 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[15492]" dev="sockfs" ino=15492 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 10:41:38.868  5666  5666 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=7220 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 10:41:38.868  5666  5666 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[33813]" dev="sockfs" ino=33813 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 10:41:38.900  5620  5666 W jxcore-log: Starting JXcore engine
,08-29 10:41:38.968  5620  5666 W jxcore-log: Platform android
08-29 10:41:38.968  5620  5666 W jxcore-log: 
,08-29 10:41:38.969  5620  5666 W jxcore-log: Process ARCH arm
08-29 10:41:38.969  5620  5666 W jxcore-log: 
,08-29 10:41:39.061  5620  5666 I jxcore-log: JXcore Cordova bridge is ready!
08-29 10:41:39.061  5620  5666 I jxcore-log: 
,08-29 10:41:39.061  5620  5666 W jxcore-log: JXcore engine is started
,08-29 10:41:39.074  5620  5660 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 10:41:39.080  5620  5620 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 10:41:39.830   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:41:39.928   932  5206 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168670, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 10:41:40.831   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:41:41.831   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:41:45.572  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 10:41:45.572  5620  5666 I jxcore-log: 
,08-29 10:41:45.573  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 10:41:45.573  5620  5666 I jxcore-log: 
,08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:45.577  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:41:45.579  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:41:45.580  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 10:41:45.580  5620  5666 I jxcore-log: 
,08-29 10:41:45.581  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 10:41:45.581  5620  5666 I jxcore-log: 
,08-29 10:41:45.934   932  3556 D WifiService: setWifiEnabled: true pid=5620, uid=10077
,08-29 10:41:45.934   932  3556 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:41:45.936  5620  5666 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 10:41:45.938  5620  5666 I jxcore-log: Unit Test app is loaded
08-29 10:41:45.938  5620  5666 I jxcore-log: 
08-29 10:41:45.940  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:41:45.940  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d5ee2a added. We now have 2 listener(s)
,08-29 10:41:45.941  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 10:41:45.941  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:41:45.941  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:41:45.941  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:41:45.942  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@523641b added. We now have 2 listener(s)
08-29 10:41:45.942  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:41:45.942  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:41:45.944  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:45.947  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:41:45.948  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:45.948  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:41:45.948  5620  5666 D ExecuteNativeTests: Running unit tests
,08-29 10:41:45.953  3654  3654 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 10:41:45.958  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:41:45.963  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:41:45.965  5620  5620 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 10:41:45.982  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:41:45.982  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 added. We now have 3 listener(s)
,08-29 10:41:45.983  3654  3654 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,08-29 10:41:45.983  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:41:45.983  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:41:45.983  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:41:45.983  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:41:45.983  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 added. We now have 3 listener(s)
08-29 10:41:45.983  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:41:45.983   932  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 10:41:45.984   932  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 10:41:45.984  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:41:45.984   932  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:41:45.984   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:41:45.985  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:45.990  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:41:45.990  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:45.990  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:41:45.992  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:41:45.992  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:41:45.992  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:41:45.992  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:41:45.992  5620  5666 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 10:41:45.993  5620  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:41:45.993  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:41:45.993  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:41:45.993  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:41:45.993  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:41:45.993  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:41:45.994  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:41:45.994  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:41:45.994  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:41:45.994  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:45.994  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:41:45.994  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:41:45.994  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 removed from the list
08-29 10:41:45.994  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:41:45.994  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 removed from the list
08-29 10:41:45.996  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:41:45.996  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:41:45.996  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:41:45.997  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:45.997  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:41:45.998  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:41:45.998  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:41:45.998  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:41:45.998  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:41:45.998  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:41:45.999  5620  5666 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 10:41:45.999  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:41:45.999  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:41:45.999  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:41:45.999  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:41:45.999  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:45.999  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:41:45.999  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
,08-29 10:41:45.999  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:41:45.999  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:41:45.999  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:41:45.999  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:45.999  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:41:45.999  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:45.999  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:41:46.000   932  2976 E native  : do suspend true
,08-29 10:41:46.000  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:41:46.000  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:41:46.000  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:41:46.000  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:41:46.002  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 10:41:46.003  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:41:46.003  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:41:46.003  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:41:46.003  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:41:46.003  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:46.003  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:41:46.003  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
,08-29 10:41:46.003  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:41:46.003  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:41:46.003  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:41:46.003  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:46.003  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:41:46.003  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:41:46.003  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:41:46.004  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:41:46.004  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:41:46.004  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:41:46.004  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:41:46.005  5620  5666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-29 10:41:46.006  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:41:46.008   932  5207 D DhcpClient: Clearing IP address
08-29 10:41:46.008   512   926 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:46.008  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:41:46.009  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:46.009  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:41:46.009  5620  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-29 10:41:46.009  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-29 10:41:46.009  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 10:41:46.009  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 10:41:46.009  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:41:46.009  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:41:46.010  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 10:41:46.010  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 10:41:46.010  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:41:46.011  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:41:46.011  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 10:41:46.011  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:41:46.011  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:41:46.013  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:41:46.013  5620  5667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:41:46.014  5620  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:41:46.014  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:41:46.017  5620  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-29 10:41:46.018   512   926 D CommandListener: Setting iface cfg
08-29 10:41:46.018  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:41:46.018  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 10:41:46.018  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:41:46.019  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:41:46.019  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:41:46.020  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 10:41:46.020  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:41:46.021  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
08-29 10:41:46.021  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 10:41:46.021  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 10:41:46.021  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-29 10:41:46.021  5620  5666 D BluetoothAdapter: STATE_ON
,08-29 10:41:46.022  3629  5264 V NativeCrypto: Read error: ssl=0x7fa1b22700: I/O error during system call, Connection timed out
08-29 10:41:46.022   932  5208 D DhcpClient: Receive thread stopped
08-29 10:41:46.024  3629  5264 V NativeCrypto: SSL shutdown failed: ssl=0x7fa1b22700: I/O error during system call, Broken pipe
08-29 10:41:46.024  4398  4654 D BtGatt.GattService: registerClient() - UUID=9b522424-6de5-4cbd-8d36-eb91c617442a
08-29 10:41:46.026  4398  4471 D BtGatt.GattService: onClientRegistered() - UUID=9b522424-6de5-4cbd-8d36-eb91c617442a, clientIf=5
08-29 10:41:46.026  5620  5631 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-29 10:41:46.026   932  3155 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,08-29 10:41:46.027   932  5205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 10:41:46.027  4398  4489 D BtGatt.AdvertiseManager: message : 0
08-29 10:41:46.029   932  5205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 10:41:46.029   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 10:41:46.029   932  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 10:41:46.029  4398  4489 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 10:41:46.030   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 10:41:46.036   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 10:41:46.036   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 10:41:46.038   932  2976 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 10:41:46.038   538   538 E Parcel  : Reading a NULL string not supported here.
08-29 10:41:46.041   932  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:41:46.041   932  2976 E native  : do suspend true
,08-29 10:41:46.044  4398  4471 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 10:41:46.047   932  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 10:41:46.048  3498  3707 W QCNEJ   : |CORE| network lost: 100
,08-29 10:41:46.049  3498  3707 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-29 10:41:46.052  4398  4471 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 10:41:46.053  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 10:41:46.053  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:41:46.054  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:41:46.055  5620  5666 I io.jxcore.node.ConnectionHelper: start: OK
08-29 10:41:46.055  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 10:41:46.055  5620  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 10:41:46.055  5620  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 10:41:46.056  5620  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 10:41:46.056  5620  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 10:41:46.056  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 10:41:46.058  5620  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 10:41:46.058  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 10:41:46.069   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:41:46.086   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 10:41:46.087   512   926 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:41:46.087   512   926 D TetherController: Setting IP forward enable = 0
08-29 10:41:46.087   932  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 10:41:46.088   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:41:46.091   932   949 D Tethering: MasterInitialState.processMessage what=3
08-29 10:41:46.092  5093  5093 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ff1c100 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:41:46.095  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:41:46.096  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 10:41:46.097  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:41:46.098  4834  4867 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 10:41:46.098  4834  4867 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:41:46.098  4834  4867 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 10:41:46.098  4834  4867 E SarControlService: no key has been found,reset the power
08-29 10:41:46.098  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,08-29 10:41:46.098  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 10:41:46.098  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 10:41:46.099  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:41:46.099  4872  4872 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 10:41:46.099   932  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:41:46.100  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:41:46.100  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:41:46.100  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 10:41:46.101  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 10:41:46.102  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:41:46.102  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:41:46.102  4872  4872 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:41:46.106  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:41:46.107  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000ea03000000000000ffffffff]
08-29 10:41:46.107  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:41:46.107  4872  4889 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,08-29 10:41:46.109  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,08-29 10:41:46.109  4834  4844 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 10:41:46.110  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:41:46.111  3828  3828 D SystemUpdateService: onCreate
08-29 10:41:46.116  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 10:41:46.116  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000eb03000000000000ffffffff]
08-29 10:41:46.116  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:41:46.116  4872  4889 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-29 10:41:46.117  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:41:46.117  4834  4845 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 10:41:46.127  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 10:41:46.128  3828  5681 I SystemUpdateService: active receiver: enabled
,08-29 10:41:46.133  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 10:41:46.135  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 10:41:46.137  5239  5239 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:41:46.141  5239  5239 D SprintDMHelper: simOperator: 
08-29 10:41:46.141  5239  5239 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:41:46.150   512   926 E Netd    : netlink response contains error (No such file or directory)
,08-29 10:41:46.151   512   926 D TetherController: Setting IP forward enable = 0
08-29 10:41:46.152  4250  5688 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-29 10:41:46.152   932  2978 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 10:41:46.152   932  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 10:41:46.166  3828  5235 I iu.UploadsManager: num queued entries: 0
,08-29 10:41:46.166  3828  5235 I iu.UploadsManager: num updated entries: 0
08-29 10:41:46.167  3828  5235 I iu.SyncManager: NEXT; no task
,08-29 10:41:46.169  3828  5681 I SystemUpdateService: showing system update notification
,08-29 10:41:46.176  3828  5681 V SystemUpdateService: retry (wakeup: false) in 3599953 ms
,08-29 10:41:46.177  3828  3828 D SystemUpdateService: onDestroy
,08-29 10:41:46.560  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-29 10:41:46.561  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 10:41:46.561  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:41:49.828   932  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=71.00 rxSuccessRate=75.50 delta 1000 -> 1
,08-29 10:41:49.830   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-29 10:41:49.830   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 10:41:49.854   932  2976 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:41:49.871   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 10:41:49.874  3654  3654 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 10:41:50.294  3654  3654 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:41:50.333  3654  3654 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 10:41:50.334  3654  3654 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 10:41:50.348   932  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:41:50.348   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:41:50.348   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 10:41:50.365   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:41:50.378   512   926 D CommandListener: Setting iface cfg
,08-29 10:41:50.380   932  2976 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 10:41:50.386   932  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 10:41:50.399   932  5694 D DhcpClient: Receive thread started
,08-29 10:41:50.484   932  2976 E native  : do suspend false
,08-29 10:41:50.501   932  5207 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 10:41:50.518   932  5694 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172664, domain null
,08-29 10:41:50.519   932  5207 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172664 seconds
,08-29 10:41:50.521   932  5207 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 10:41:50.564   932  5694 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 10:41:50.565   932  5207 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-29 10:41:50.568   512   926 D CommandListener: Setting iface cfg
,08-29 10:41:50.577   932  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 10:41:50.580   932  5207 D DhcpClient: Scheduling renewal in 86399s
08-29 10:41:50.582   932  2976 E native  : do suspend true
,08-29 10:41:50.598   932  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 10:41:50.602   932  2976 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 10:41:50.602   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 10:41:50.606   932  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 10:41:50.609   932  2978 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 10:41:50.648   932  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 10:41:50.649   932  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 10:41:50.651   932  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 10:41:50.653   932  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 10:41:50.655   932  2978 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 10:41:50.662   932  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 10:41:50.667   932  2978 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 10:41:50.667   932  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 10:41:50.667   932  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 10:41:50.667   932  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 10:41:50.667   932  2978 D ConnectivityService:    accepting network in place of null
08-29 10:41:50.668   932  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:41:50.668   932  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:41:50.696   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:41:50.719   932  5693 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179461, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:41:50.726   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:41:50.731   932  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 10:41:50.731  3498  3707 W QCNEJ   : |CORE| network available: 101
08-29 10:41:50.731   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:41:50.733  3498  3707 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,08-29 10:41:50.734   932  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 10:41:50.735  3498  3707 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-29 10:41:50.735  3498  3707 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-29 10:41:50.739  5093  5093 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ff1c100 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 10:41:50.740   932   949 D Tethering: MasterInitialState.processMessage what=3
,08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:50.745  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:41:50.748  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:41:50.752  4834  4867 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 10:41:50.752  4834  4867 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:41:50.752  4834  4867 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 10:41:50.752  4834  4867 E SarControlService: no key has been found,reset the power
08-29 10:41:50.752  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:50.752  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:41:50.752  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 10:41:50.752  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 10:41:50.753  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:41:50.753  4872  4872 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 10:41:50.754  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:41:50.754  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:50.754  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-29 10:41:50.754  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 10:41:50.755  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:41:50.755  4872  4872 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 10:41:50.755  5093  5093 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-29 10:41:50.758  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:50.758  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:41:50.761  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:50.762  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000ec03000000000000ffffffff]
08-29 10:41:50.762  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:41:50.762  4872  4889 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
08-29 10:41:50.762  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:41:50.762  4834  4844 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 10:41:50.763  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000ed03000000000000ffffffff]
08-29 10:41:50.763  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:41:50.763  4872  4889 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
08-29 10:41:50.764  3828  3828 D SystemUpdateService: onCreate
08-29 10:41:50.764  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:41:50.767  4834  4845 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 10:41:50.771  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:41:50.783  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 10:41:50.789  3828  5235 I iu.UploadsManager: num queued entries: 0
,08-29 10:41:50.789  3828  5235 I iu.UploadsManager: num updated entries: 0
08-29 10:41:50.789  3828  5235 I iu.SyncManager: NEXT; no task
,08-29 10:41:50.791  3828  5704 I SystemUpdateService: active receiver: enabled
,08-29 10:41:50.792  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:41:50.793  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 10:41:50.795  5239  5239 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:41:50.798  5239  5239 D SprintDMHelper: simOperator: 
,08-29 10:41:50.798  5239  5239 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:41:50.812   932  5692 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:812::200e
,08-29 10:41:50.832  3828  5704 I SystemUpdateService: showing system update notification
,08-29 10:41:50.839  3828  5704 V SystemUpdateService: retry (wakeup: false) in 3599953 ms
08-29 10:41:50.841  3828  3828 D SystemUpdateService: onDestroy
,08-29 10:41:50.883   932  5692 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:41:50 GMT], X-Android-Received-Millis=[1472481710882], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472481710849]}
,08-29 10:41:50.884   932  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 10:41:50.884   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-29 10:41:50.884   932  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 10:41:50.885   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 10:41:50.940  4250  5708 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 10:41:51.057  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:41:51.057  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 10:41:51.057  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:41:51.057  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 10:41:51.057  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:41:51.058  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 10:41:51.058  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:41:51.058  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 10:41:51.058  5620  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 10:41:51.058  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:41:51.058  5620  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 10:41:51.058  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:41:51.058  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:41:51.058  5620  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:41:51.058  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 10:41:51.058  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:41:51.058  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 10:41:51.059  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:41:51.059  5620  5666 D BluetoothLeScanner: could not find callback wrapper
08-29 10:41:51.059  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:41:51.060  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 10:41:51.060  4398  4489 D BtGatt.AdvertiseManager: message : 1
,08-29 10:41:51.061  4398  4489 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 10:41:51.066  4398  4471 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-29 10:41:51.066  4398  4471 D BtGatt.GattService: Client app is not null!
08-29 10:41:51.067  4398  4413 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:41:51.067  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:41:51.067  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 10:41:51.067  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-29 10:41:51.067  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 10:41:51.067  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-29 10:41:51.068  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:41:51.068  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:41:51.068  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:41:51.069  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:41:51.069  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:41:51.069  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:41:51.069  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:41:51.069  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:41:51.069  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:41:51.069  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:41:51.069  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:41:51.069  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:41:51.069  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:41:51.069  5620  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:41:51.070  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:41:51.070  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:41:51.571  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:41:51.732   932  2978 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 10:41:56.075  5620  5666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-29 10:41:56.080  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:41:56.090  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:41:56.094  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:41:56.094  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:41:56.094  5620  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-29 10:41:56.094  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
08-29 10:41:56.095  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 10:41:56.095  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 10:41:56.095  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:41:56.095  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:41:56.098  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 10:41:56.099  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 10:41:56.099  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:41:56.099  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:41:56.100  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 10:41:56.100  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:41:56.100  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:41:56.100  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:41:56.102  5620  5717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:41:56.106  5620  5717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-29 10:41:56.107  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:41:56.107  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 10:41:56.109  5620  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:41:56.109  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:41:56.117  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:41:56.120  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:41:56.120  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:41:56.122  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 10:41:56.123  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:41:56.123  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
,08-29 10:41:56.123  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 10:41:56.123  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 10:41:56.123  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 10:41:56.124  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:41:56.126  4398  4654 D BtGatt.GattService: registerClient() - UUID=0b24008e-9902-4cc1-8e9d-94ce0a7dbea1
08-29 10:41:56.127  4398  4471 D BtGatt.GattService: onClientRegistered() - UUID=0b24008e-9902-4cc1-8e9d-94ce0a7dbea1, clientIf=5
08-29 10:41:56.127  5620  5630 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 10:41:56.128  4398  4489 D BtGatt.AdvertiseManager: message : 0
08-29 10:41:56.130  4398  4489 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 10:41:56.142  4398  4471 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 10:41:56.148  4398  4471 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 10:41:56.149  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 10:41:56.149  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:41:56.151  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 10:41:56.152  5620  5666 I io.jxcore.node.ConnectionHelper: start: OK
08-29 10:41:56.152  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 10:41:56.152  5620  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-29 10:41:56.152  5620  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 10:41:56.152  5620  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 10:41:56.152  5620  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 10:41:56.153  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 10:41:56.156  5620  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 10:41:56.156  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 10:41:56.657  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 10:41:56.658  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 10:41:56.658  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:41:58.675   932  2978 D ConnectivityService: handlePromptUnvalidated 101
,08-29 10:42:01.158  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:42:01.158  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 10:42:01.159  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:42:01.159  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 10:42:01.159  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:42:01.159  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 10:42:01.160  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:42:01.160  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 10:42:01.160  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:42:01.160  5620  5717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 10:42:01.160  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:42:01.160  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 10:42:01.160  5620  5717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 10:42:01.160  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:42:01.160  5620  5717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:42:01.160  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:42:01.161  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:42:01.163  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:42:01.163  5620  5666 D BluetoothLeScanner: could not find callback wrapper
,08-29 10:42:01.163  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:42:01.163  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-29 10:42:01.166  4398  4489 D BtGatt.AdvertiseManager: message : 1
,08-29 10:42:01.168  4398  4489 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 10:42:01.180  4398  4471 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 10:42:01.180  4398  4471 D BtGatt.GattService: Client app is not null!
,08-29 10:42:01.182  4398  4416 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 10:42:01.183  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:42:01.184  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 10:42:01.184  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 10:42:01.184  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 10:42:01.184  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 10:42:01.186  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:42:01.186  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:42:01.187  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:42:01.187  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:42:01.190  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:01.190  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:42:01.190  5620  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:42:01.191  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:42:01.191  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:42:01.191  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:42:01.191  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:01.191  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:01.191  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:42:01.191  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:01.191  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:01.191  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:01.192  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:01.192  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:01.192  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:01.193  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:01.194  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:01.194  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:42:01.194  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:01.194  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:01.195  5620  5666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:42:01.199  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:42:01.203  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:42:01.204  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:42:01.204  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:42:01.205  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:42:01.205  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:42:01.205  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:42:01.205  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:42:01.205  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:42:01.208  5620  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:42:01.208  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:42:01.208  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:01.212  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:42:01.213  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:42:01.213  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:42:01.214  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:01.216  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 10:42:01.219  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 10:42:01.220  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:42:01.220  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:42:01.221  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:42:01.221  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:42:01.224  4398  4416 D BtGatt.GattService: registerClient() - UUID=96017668-217e-4216-a195-4dab5ddefe05
,08-29 10:42:01.224  4398  4471 D BtGatt.GattService: onClientRegistered() - UUID=96017668-217e-4216-a195-4dab5ddefe05, clientIf=5
,08-29 10:42:01.224  5620  5630 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 10:42:01.226  4398  4654 D BtGatt.GattService: start scan with filters
,08-29 10:42:01.230  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:42:01.230  4398  4490 D BtGatt.ScanManager: handling starting scan
08-29 10:42:01.231  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:42:01.231  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:42:01.231  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:42:01.232  4398  4490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:01.233  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:42:01.234  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:42:01.234  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:42:01.235  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:42:01.238  5620  5666 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:42:01.239  4398  4471 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:42:01.239  4398  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:42:01.240  4398  4490 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:42:01.245  4398  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 10:42:01.245  4398  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:42:01.246  4398  4490 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:42:01.246  4398  4490 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:42:01.255  4398  4471 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:42:01.255  4398  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:42:01.261  4398  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:42:01.261  4398  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:42:01.735  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 10:42:01.735  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:42:01.736  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:42:01.833   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:02.834   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:03.835   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:04.836   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:05.837   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:06.239  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:42:06.239  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:06.239  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:42:06.239  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:06.240  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:42:06.240  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:42:06.240  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:42:06.240  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:42:06.240  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:42:06.241  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:42:06.241  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:42:06.243  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:42:06.244  4398  4634 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:42:06.248  4398  4413 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 10:42:06.249  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:42:06.250  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:42:06.250  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:42:06.250  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:42:06.250  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:42:06.253  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:42:06.254  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 10:42:06.254  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:42:06.254  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:42:06.256  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:42:06.258  4398  4398 D BtGatt.ScanManager: awakened up at time 195000
,08-29 10:42:06.260  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:42:06.260  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:42:06.260  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:42:06.266  4398  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 10:42:06.266  4398  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:42:06.267  4398  4490 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:42:06.275  4398  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 10:42:06.275  4398  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:42:06.275  4398  4490 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:42:06.293  4398  4471 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,08-29 10:42:06.293  4398  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:42:06.293  4398  4471 D BtGatt.GattService: current time is 195035735393
08-29 10:42:06.294  4398  4471 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -76, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -77, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -93, 107, 4, 44, -19, 70, 1, -128, -73, 4, 0, 0, 0, -93, 107, 4, 44, -19, 70, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17, 0]
,08-29 10:42:06.295  4398  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-29 10:42:06.295  4398  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 10:42:06.296  4398  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 10:42:06.296  4398  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 10:42:06.296  4398  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 10:42:06.296  4398  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-29 10:42:06.296  4398  4471 D BtGatt.GattService: ScanRecord : []
08-29 10:42:06.296  4398  4471 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17]
,08-29 10:42:06.761  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:42:06.762  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:06.762  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:42:06.837   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:42:11.261  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:42:11.261  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.261  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.261  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.262  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.262  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:42:11.262  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.262  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.262  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:11.262  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:42:11.263  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.264  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:11.264  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:11.267  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:42:11.267  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.267  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.267  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.269  5620  5666 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 10:42:11.271  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.271  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.271  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.271  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.272  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.272  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.272  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.272  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.272  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.272  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.272  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.273  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.273  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.273  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.276  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.276  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.276  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.276  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.279  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:42:11.279  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:42:11.279  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.279  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.279  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.279  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.279  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.279  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.279  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.279  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.280  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.280  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:11.280  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.280  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.280  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.281  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.281  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.281  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.281  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.282  5620  5666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 10:42:11.282  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.283  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.283  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.283  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.283  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.283  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.283  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.283  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.283  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.283  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.283  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:11.283  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.283  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.283  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.285  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.285  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.285  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.285  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:11.286  5620  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 10:42:11.286  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.286  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.286  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.286  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:42:11.286  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.286  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.287  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.287  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.287  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.287  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.287  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.287  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:11.287  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.287  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:11.288  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.289  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.289  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.289  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:11.290  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:42:11.290  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:42:11.290  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:42:11.290  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:42:11.290  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:42:11.290  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:42:11.290  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:42:11.290  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:42:11.290  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:42:11.291  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.291  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.291  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.291  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.291  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.291  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.291  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.291  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.291  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:11.291  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.291  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.291  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.291  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.292  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.293  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.293  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.293  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.293  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.294  5620  5666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:42:11.294  5620  5666 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:42:11.294  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 10:42:11.298  5620  5666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 10:42:11.298  5620  5666 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 10:42:11.298  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:42:11.298  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:42:11.298  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:42:11.298  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:42:11.298  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:42:11.298  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:42:11.299  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:42:11.300  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:42:11.300  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 10:42:11.300  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:42:11.300  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:42:11.300  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:42:11.300  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-29 10:42:11.300  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 10:42:11.300  5620  5666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 10:42:11.300  5620  5666 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:42:11.300  5620  5666 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 10:42:11.301  5620  5666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:42:11.301  5620  5666 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:42:11.301  5620  5666 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 10:42:11.301  5620  5666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:42:11.301  5620  5666 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:42:11.301  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 10:42:11.305  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 10:42:11.306  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 10:42:11.306  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 10:42:11.306  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-29 10:42:11.306  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 10:42:11.306  5620  5666 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 10:42:11.307  5620  5666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:42:11.307  5620  5666 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 10:42:11.307  5620  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 123)
08-29 10:42:11.308  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.308  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.308  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.308  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.308  5620  5718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:42:11.308  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.308  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.308  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 10:42:11.309  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.309  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.309  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.309  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.310  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.310  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.310  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:11.310  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.310  5620  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 123
08-29 10:42:11.311  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.311  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.311  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.311  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.310  5620  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 123)
08-29 10:42:11.312  5620  5666 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 10:42:11.312  4398  4616 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: -1
08-29 10:42:11.312  5620  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 123)
08-29 10:42:11.312  5620  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 123)
08-29 10:42:11.312  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.312  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.312  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.313  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.313  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.313  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.313  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.313  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.313  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:11.313  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.313  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.313  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.313  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.313  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.314  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.314  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.314  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.314  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.315  5620  5666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 10:42:11.315  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.316  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.316  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.316  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.316  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.316  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.316  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
,08-29 10:42:11.316  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.316  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.316  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.316  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.316  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.316  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.316  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.317  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.317  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:11.317  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.317  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.318  5620  5666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 10:42:11.318  5620  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 10:42:11.318  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:42:11.318  5620  5666 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 10:42:11.319  5620  5666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:42:11.319  5620  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 10:42:11.319  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 10:42:11.319  5620  5666 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 10:42:11.319  5620  5666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:42:11.319  5620  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:42:11.319  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:42:11.319  5620  5666 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 10:42:11.319  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:11.319  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:11.319  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:11.319  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.319  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.319  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.319  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.319  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.319  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.320  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.320  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.320  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.320  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.320  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.321  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:11.321  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:42:11.321  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.321  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.321  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:11.321  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.321  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:11.322  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:11.322  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:11.322  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:11.322  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:11.322  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:11.322  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:16.323  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:42:16.323  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:16.323  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:16.323  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:16.323  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.324  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
,08-29 10:42:16.324  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:16.324  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:42:16.324  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:16.325  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:42:16.325  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.325  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.325  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
,08-29 10:42:16.325  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.325  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:16.326  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:16.326  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:16.326  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.326  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.326  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:16.329  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:16.329  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:42:16.330  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.330  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:16.334  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:42:16.334  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:42:16.336  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 10:42:16.338  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 10:42:16.338  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:42:16.338  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-29 10:42:16.338  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:42:16.339  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 10:42:16.339  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:16.340  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 10:42:16.340  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:42:16.340  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 10:42:16.340  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.340  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 10:42:16.340  5620  5720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:42:16.340  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:16.340  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 10:42:16.340  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.340  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:42:16.340  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:42:16.340  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:42:16.341  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:16.341  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.343  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:42:16.344  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:16.344  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:42:16.344  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:16.344  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:42:16.344  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:16.344  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:16.344  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:42:16.344  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:42:16.344  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.344  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.344  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:16.344  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.345  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:16.345  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:42:16.345  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.345  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.345  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.345  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.346  5620  5720 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 10:42:16.346  5620  5720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 10:42:16.346  5620  5720 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:42:16.346  5620  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:42:16.347  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:16.347  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:16.347  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.347  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:16.349  5620  5666 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 10:42:16.349  5620  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 10:42:16.349  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:42:16.350  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:42:16.350  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:42:16.350  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:42:16.350  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:16.350  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:16.350  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:16.350  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.350  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.350  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:16.351  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.351  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:16.351  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:16.351  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.351  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.351  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.351  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:16.353  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:16.353  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:16.353  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.353  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:16.360  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:42:16.360  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:16.360  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:16.360  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:16.360  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.360  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.360  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
,08-29 10:42:16.360  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.360  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:16.360  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:16.360  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:16.360  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.361  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.361  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.361  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:16.362  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:16.362  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.362  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
,08-29 10:42:16.363  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:42:16.363  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:42:16.364  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:42:16.364  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:42:16.364  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.364  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.364  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49e5301 not in the list
08-29 10:42:16.364  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.364  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:16.364  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:16.364  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:42:16.364  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.364  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:16.364  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:16.365  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:42:16.365  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:42:16.365  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:16.365  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d5a6 not in the list
08-29 10:42:16.366  5620  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 10:42:16.366  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-29 10:42:16.366  5620  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 10:42:16.366  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:42:16.366  5620  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 10:42:16.366  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:42:16.368  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:42:16.368  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 10:42:16.369  5620  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 10:42:16.369  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:42:16.369  5620  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 10:42:16.369  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:42:16.369  5620  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 10:42:16.369  5620  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 10:42:16.370  5620  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 10:42:16.370  5620  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 10:42:16.370  5620  5666 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 10:42:16.370  5620  5666 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-29 10:42:16.371  5620  5666 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 10:42:16.371  5620  5666 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 10:42:16.372  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:42:16.372  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@676c418 added. We now have 3 listener(s)
08-29 10:42:16.372  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:42:16.373  5620  5666 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 10:42:16.374   932   942 D WifiService: setWifiEnabled: true pid=5620, uid=10077
08-29 10:42:16.374   932   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:42:16.438  4398  4603 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-29 10:42:16.438  4398  4603 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,08-29 10:42:16.845  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:42:18.318   932  5693 D NetlinkSocketObserver: NeighborEvent{elapsedMs=207060, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:42:21.379  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:42:21.380  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e0fe71 added. We now have 4 listener(s)
,08-29 10:42:21.380  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:42:21.391  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:21.391  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e0fe71 removed from the list
08-29 10:42:21.391  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:21.391  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:21.391  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:21.392  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:42:21.392  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b8f456 added. We now have 4 listener(s)
08-29 10:42:21.392  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:42:21.394  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:21.394  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b8f456 removed from the list
08-29 10:42:21.394  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:21.394  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:21.394  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:21.395  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:42:21.395  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b66cd7 added. We now have 4 listener(s)
08-29 10:42:21.395  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:42:21.398   932   942 D WifiService: setWifiEnabled: false pid=5620, uid=10077
08-29 10:42:21.398   932   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:42:21.406   932  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 10:42:21.407   932  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 10:42:21.407   932  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:42:21.407   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:42:21.413  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:42:21.415  4398  4459 D BluetoothAdapterState: Current state: ON, message: 23
08-29 10:42:21.415  4398  4459 D BluetoothAdapterProperties: Setting state to 13
,08-29 10:42:21.415  4398  4459 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 10:42:21.417  4398  4459 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 10:42:21.419  4398  4459 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:42:21.420  4398  4471 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:42:21.420  4398  4459 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 10:42:21.421  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:42:21.421  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:42:21.422  4398  4398 D BluetoothMapService: onReceive
08-29 10:42:21.422  4398  4398 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:42:21.422  4398  4398 D BluetoothMapService: STATE_TURNING_OFF
08-29 10:42:21.422  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.422  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:42:21.423  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:42:21.423  4398  4398 D BluetoothMapService: MAP Service closeService in
08-29 10:42:21.423  4398  4398 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 10:42:21.423  4398  4398 D ObexServerSockets0: shutdown(block = true)
08-29 10:42:21.424  4398  4398 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:42:21.424  4398  4656 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-29 10:42:21.424  4398  4398 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:42:21.424   932  2976 E native  : do suspend true
08-29 10:42:21.424  4398  4657 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 10:42:21.424  4398  4616 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 10:42:21.428  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.428  4398  4398 I BtOppRfcommListener: stopping Accept Thread
,08-29 10:42:21.429  4398  5151 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:42:21.429  4398  5151 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 10:42:21.430  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.433  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:42:21.433  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:42:21.434  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.434  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:42:21.438  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:42:21.438  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:42:21.439  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:42:21.439  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:42:21.442  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:21.444   932   945 I ActivityManager: Start proc 5724:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 10:42:21.446  4398  4398 D HeadsetService: Received stop request...Stopping profile...
,08-29 10:42:21.448  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.450   932  5207 D DhcpClient: Clearing IP address
08-29 10:42:21.451   512   926 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:42:21.452  3526  3549 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:21.452   932   932 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:21.452   932   932 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:21.452   932   932 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:21.453  3143  3157 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:21.453  3143  3143 D HeadsetProfile: Bluetooth service disconnected
,08-29 10:42:21.455  4398  4398 D A2dpService: Received stop request...Stopping profile...
08-29 10:42:21.455  4398  4639 D A2dpStateMachine: Exit Disconnected: -1
,08-29 10:42:21.456   512   926 D CommandListener: Setting iface cfg
08-29 10:42:21.456  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:21.458  3629  5714 V NativeCrypto: Read error: ssl=0x7fa636c680: I/O error during system call, Connection timed out
08-29 10:42:21.458  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.459  3629  5714 V NativeCrypto: SSL shutdown failed: ssl=0x7fa636c680: I/O error during system call, Broken pipe
08-29 10:42:21.461   932   932 D BluetoothA2dp: Proxy object disconnected
08-29 10:42:21.461   932   942 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
08-29 10:42:21.461  3143  3143 D BluetoothA2dp: Proxy object disconnected
08-29 10:42:21.461  4398  4398 D HidService: Received stop request...Stopping profile...
08-29 10:42:21.461   932  5692 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
08-29 10:42:21.461  4398  4398 D HidService: Stopping Bluetooth HidService
08-29 10:42:21.462  3143  3143 D BluetoothInputDevice: Proxy object disconnected
08-29 10:42:21.462  3143  3143 D HidProfile: Bluetooth service disconnected
08-29 10:42:21.462  4398  4398 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:21.462  4398  4398 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:21.462  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.462  4398  4398 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:21.464   932  5692 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 10:42:21.464   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-29 10:42:21.464   932  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 10:42:21.465   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 10:42:21.469  4398  4398 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 10:42:21.469  4398  4398 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:42:21.469  4398  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:21.469  4398  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:21.469  4398  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:21.470  4398  4471 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 10:42:21.470  4398  4398 D HealthService: Received stop request...Stopping profile...
08-29 10:42:21.470  4398  4471 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 10:42:21.471   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 10:42:21.471   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 10:42:21.472  4398  4398 D PanService: Received stop request...Stopping profile...
08-29 10:42:21.474   538   538 E Parcel  : Reading a NULL string not supported here.
08-29 10:42:21.474  4398  4398 D BluetoothMapService: Received stop request...Stopping profile...
08-29 10:42:21.474  4398  4398 D BluetoothMapService: stop()
08-29 10:42:21.474  3143  3143 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:42:21.474  3143  3143 D PanProfile: Bluetooth service disconnected
,08-29 10:42:21.478   932   932 D RttService: SCAN_AVAILABLE : 1
,08-29 10:42:21.478  4398  4398 D BluetoothMapAppObserver: deinitObservers()
08-29 10:42:21.479  4398  4398 D BluetoothMapAppObserver: removeReceiver()
08-29 10:42:21.479   932  3084 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:42:21.480   932  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 10:42:21.482  4398  4398 D SapService: Received stop request...Stopping profile...
08-29 10:42:21.482  4398  4398 V SapService: stop()
08-29 10:42:21.483  4398  4398 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:21.483  4398  4398 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:21.483  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.483  4398  4398 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:21.483  3498  3707 W QCNEJ   : |CORE| network lost: 101
,08-29 10:42:21.484  4398  4398 V BluetoothAdapterState: isTurningOff()=true
,08-29 10:42:21.484  4398  4398 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:42:21.484  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.484  4398  4398 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:21.484  4398  4398 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:42:21.484  4398  4398 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:42:21.485  4398  4398 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:21.485  4398  4398 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:21.485  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.485  4398  4398 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:21.485  4398  4398 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:42:21.485  4398  4398 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:42:21.485  5724  5724 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 10:42:21.486  4398  4398 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:21.486  4398  4398 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:21.486  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.486  4398  4398 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:21.486  4398  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:21.486  4398  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:21.486  4398  4398 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:42:21.486  4398  4603 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:42:21.486  4398  4398 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 10:42:21.486  4398  4603 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:42:21.486  4398  4603 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:42:21.486  4398  4603 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:42:21.487  4398  4471 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:42:21.487  4398  4471 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:42:21.487  4398  4471 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 10:42:21.487  4398  4398 D BluetoothMapService: MAP Service closeService in
08-29 10:42:21.487  4398  4398 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:21.487  3498  3707 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 10:42:21.487  4398  4398 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:21.487  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.487  4398  4398 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:21.488  4398  4398 D BluetoothMapService: cleanup()
08-29 10:42:21.488  4398  4398 D BluetoothMapService: MAP Service closeService in
08-29 10:42:21.488  4398  4398 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:21.488  4398  4398 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:21.488  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.488  4398  4398 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:21.488  4398  4459 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 10:42:21.488  4398  4459 D BluetoothAdapterProperties: Setting state to 15
,08-29 10:42:21.488  4398  4459 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 10:42:21.489  4398  4459 I BluetoothAdapterState: Entering BleOnState
08-29 10:42:21.489   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:42:21.489   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:21.489  3526  3549 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:21.489  3143  3156 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:42:21.490  3143  3900 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:21.491   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:21.491  3143  3157 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:42:21.491  3143  3156 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:42:21.492  3143  3900 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:42:21.492   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:21.493  3143  3157 D BluetoothPan: onBluetoothStateChange on: false
08-29 10:42:21.496  4398  4459 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 10:42:21.496  4398  4459 D BluetoothAdapterProperties: Setting state to 16
08-29 10:42:21.496  4398  4459 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 10:42:21.496  4398  4459 D BluetoothAdapterProperties: onBleDisable
08-29 10:42:21.496  4398  4459 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:42:21.497  4398  4462 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 10:42:21.498  5724  5724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 10:42:21.499  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:21.499  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:21.499  4398  4603 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 10:42:21.499  4398  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:21.499  4398  4471 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:42:21.500  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.500  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:21.502  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.502  5620  5620 V io.jxcore.node.Conne,ctivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.502  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.502  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.502  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:21.502  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.502  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:21.502  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:21.502  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:21.503   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f264a96:true
08-29 10:42:21.503  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.503  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:21.503  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:42:21.505  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:21.505  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:21.506  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.506  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:21.508  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.508   932  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 10:42:21.508   932  5694 D DhcpClient: Receive thread stopped
08-29 10:42:21.509  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.510  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.512   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 10:42:21.522   932   943 I ActivityManager: Start proc 5740:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-29 10:42:21.524   932  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:42:21.524   932  2976 E native  : do suspend true
08-29 10:42:21.535  5724  5724 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 10:42:21.537  5724  5724 D BluetoothMap: Create BluetoothMap proxy object
,08-29 10:42:21.543  5724  5724 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 10:42:21.548  5724  5724 D DockEventReceiver: finishStartingService: stopping service
08-29 10:42:21.548   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 10:42:21.549   512   926 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:42:21.549   932  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 10:42:21.549   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:42:21.550   932   949 D Tethering: MasterInitialState.processMessage what=3
08-29 10:42:21.552   932  2976 D DhcpClient: doQuit
08-29 10:42:21.552   932  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 10:42:21.552   932  5207 D DhcpClient: onQuitting
08-29 10:42:21.553  3654  3654 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 10:42:21.553  5093  5093 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ff1c100 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 10:42:21.553  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.555  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:21.556  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:21.556  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.556  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:21.557  4834  4867 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 10:42:21.557  4834  4867 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:42:21.557  4834  4867 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 10:42:21.557  4834  4867 E SarControlService: no key has been found,reset the power
08-29 10:42:21.557  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 10:42:21.557  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 10:42:21.557  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 10:42:21.558  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:21.558  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:21.558  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:42:21.558  4872  4872 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 10:42:21.558  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.558  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:21.560  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:21.560  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:21.561  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:21.561  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:21.562  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.563  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.563  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:42:21.563  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 10:42:21.563  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 10:42:21.564  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:42:21.564  4872  4872 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 10:42:21.566  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000ee03000000000000ffffffff]
08-29 10:42:21.566  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:42:21.566  4872  4889 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
08-29 10:42:21.566  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:42:21.566  4834  4845 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 10:42:21.572  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000ef03000000000000ffffffff]
08-29 10:42:21.572  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:42:21.573  4872  4889 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
08-29 10:42:21.573  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:42:21.573  4834  4844 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 10:42:21.584  5740  5740 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
08-29 10:42:21.586   932  3432 I ActivityManager: Killing 5093:com.google.android.music:main/u0a59 (adj 15): empty #17
08-29 10:42:21.592   512   926 E Netd    : netlink response contains error (No such file or directory)
08-29 10:42:21.593   932  2978 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 10:42:21.593   932  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 10:42:21.666  3654  3654 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:42:21.672  3654  3654 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 10:42:21.704  4398  4471 I bt_hci  : shut_down
,08-29 10:42:21.708  4398  4491 D bt_hwcfg: hw_epilog_process
,08-29 10:42:21.708  4398  4491 I bt_vendor: low_power_mode_cb
,08-29 10:42:21.711  4398  4491 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 10:42:21.711  4398  4491 I bt_vendor: epilog_cb
08-29 10:42:21.711  4398  4491 I bt_hci  : epilog_finished_callback
,08-29 10:42:21.713  4398  4471 I bt_hci_h4: hal_close
,08-29 10:42:21.714  4398  4471 I bt_userial_vendor: device fd = 51 close
,08-29 10:42:21.760  3654  3654 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 10:42:21.778  3654  3654 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:42:21.801  5740  5740 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:42:21.801  5740  5740 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:42:21.801  5740  5740 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:42:21.801  5740  5740 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.801  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:42:21.802  5740  5740 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:42:21.802  5740  5740 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:42:21.802  5740  5740 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:42:21.802  5740  5740 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:42:21.802  5740  5740 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:42:21.813  5724  5724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 10:42:21.819  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:42:21.821  5724  5724 D DockEventReceiver: finishStartingService: stopping service
08-29 10:42:21.826  4398  4462 D bt_stack_manager: event_shut_down_stack finished.
08-29 10:42:21.826  4398  4459 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-29 10:42:21.828  4398  4459 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 10:42:21.828  4398  4398 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:42:21.828  4398  4398 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:42:21.828  4398  4398 D BtGatt.GattService: stop()
08-29 10:42:21.829  4398  4398 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 10:42:21.830  4398  4398 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:21.830  4398  4398 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:21.830  4398  4398 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:21.830  4398  4398 V BluetoothAdapterState: isBleTurningOff()=true
08-29 10:42:21.830  4398  4459 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 10:42:21.831  4398  4459 D BluetoothAdapterProperties: Setting state to 10
08-29 10:42:21.831  4398  4459 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 10:42:21.831  4398  4459 I BluetoothAdapterState: Entering OffState
08-29 10:42:21.832   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 10:42:21.837  4398  4398 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 10:42:21.838  4398  4398 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 10:42:21.838  4398  4398 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 10:42:21.839  4398  4462 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 10:42:21.840  4398  4462 D bt_stack_manager: event_clean_up_stack finished.
,08-29 10:42:21.845  4398  4398 I art     : System.exit called, status: 0
08-29 10:42:21.845  4398  4398 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 10:42:21.859   932  3430 I ActivityManager: Killing 4497:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 10:42:21.923  4250  4250 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:42:21.924   932  3556 I ActivityManager: Process com.android.bluetooth (pid 4398) has died
,08-29 10:42:21.926   932  2976 D wifi    : In wifi stop Hal
08-29 10:42:21.926   932  2976 D wifi    : halHandle = 0x7f90f31080, mVM = 0x7fac50d140, mCls = 0x100b26
,08-29 10:42:21.926   932  3631 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 10:42:21.926   932  3631 D WifiHAL : Got a signal to exit!!!
08-29 10:42:21.926   932  3631 I WifiHAL : Exit wifi_event_loop
08-29 10:42:21.928  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:21.928   932  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
08-29 10:42:21.928   932  2976 E WifiHAL : Event processing terminated
08-29 10:42:21.928   932  2976 D wifi    : In wifi cleaned up handler
08-29 10:42:21.928   932  2976 I WifiHAL : Internal cleanup completed
08-29 10:42:21.929  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:21.929  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 10:42:21.929  3473  3989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:42:21.930  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:21.932  3828  3828 D SystemUpdateService: onCreate
,08-29 10:42:21.940  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:42:21.945  3828  5778 I SystemUpdateService: active receiver: enabled
,08-29 10:42:21.946  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 10:42:21.950   932  3631 D wifi    : set interface wlan0 flags (DOWN)
08-29 10:42:21.950   932  2976 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 10:42:21.952  3828  5235 I iu.UploadsManager: num queued entries: 0
,08-29 10:42:21.952  3828  5235 I iu.UploadsManager: num updated entries: 0
08-29 10:42:21.953  3828  5235 I iu.SyncManager: NEXT; no task
,08-29 10:42:21.955  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:42:21.956  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 10:42:21.958  5239  5239 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:42:21.961  5239  5239 D SprintDMHelper: simOperator: 
08-29 10:42:21.961  5239  5239 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:42:21.973  3828  5778 I SystemUpdateService: showing system update notification
,08-29 10:42:21.973  4250  5780 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 10:42:21.984   932   943 I ActivityManager: Start proc 5781:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 10:42:22.019  5781  5781 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 10:42:22.067  5781  5781 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 10:42:22.072  3828  5778 V SystemUpdateService: retry (wakeup: false) in 3599878 ms
,08-29 10:42:22.074  3828  3828 D SystemUpdateService: onDestroy
,08-29 10:42:22.077   932   942 I ActivityManager: Killing 5496:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 10:42:22.141  5740  5763 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 10:42:22.149   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bbe91b:true
,08-29 10:42:22.153   932   949 D Tethering: InitialState.processMessage what=4
08-29 10:42:22.154   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 10:42:26.426   932  3431 D WifiService: setWifiEnabled: true pid=5620, uid=10077
08-29 10:42:26.426   932  3431 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:42:26.433   512   926 D SoftapController: Softap fwReload - Ok
,08-29 10:42:26.439   512   926 D CommandListener: Setting iface cfg
,08-29 10:42:26.439   512   926 D CommandListener: Trying to bring down wlan0
08-29 10:42:26.440   512   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:42:26.443   932  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 10:42:27.030   932  2976 D wifi    : set interface wlan0 flags (UP)
,08-29 10:42:27.034   932  2976 I WifiHAL : Initializing wifi
,08-29 10:42:27.034   932  2976 I WifiHAL : Creating socket
08-29 10:42:27.035   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 10:42:27.040   932  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 10:42:27.040   932  2976 D wifi    : Did set static halHandle = 0x7f90f31080
08-29 10:42:27.040   932  2976 D wifi    : halHandle = 0x7f90f31080, mVM = 0x7fac50d140, mCls = 0x1017ae
08-29 10:42:27.041   932  2976 D wifi    : array field set
08-29 10:42:27.041   932  2976 I WifiNative-HAL: interface[0] = wlan0
08-29 10:42:27.043   932  5810 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547892695168
08-29 10:42:27.043   932  5810 D wifi    : waitForHalEvents called, vm = 0x7fac50d140, obj = 0x1017ae, env = 0x7f9163dd80
,08-29 10:42:27.045   932  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 10:42:27.046   932  2976 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-29 10:42:27.048  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:27.049  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:27.050  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:27.082  5811  5811 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 10:42:27.102  5811  5811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:42:27.150  5811  5811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:42:27.151  5811  5811 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 10:42:28.064   932  2976 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:42:28.065  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:28.065  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:28.065  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:42:28.066  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:28.071  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:28.071  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:28.072  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:42:28.072  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:28.074  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:28.074  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:28.074  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:28.074  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:42:28.079   932  2976 D WifiConfigStore: loaded 0 passpoint configs
08-29 10:42:28.080   932  2976 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:42:28.080   932  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 10:42:28.081   932  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:42:28.081   932  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 10:42:28.081   932  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 10:42:28.085   932  2976 D WifiNative-HAL: Setting external_sim to 1
08-29 10:42:28.085  4250  4250 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:42:28.085   932  2976 D wifi    : setting dfs flag to true, 0x7f92a63420
08-29 10:42:28.085   932  2976 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:42:28.086   932  2976 D wifi    : setting scan oui 0x7f92a63420
08-29 10:42:28.086   932  2976 D WifiHAL : Sending mac address OUI
,08-29 10:42:28.101   932  2976 E native  : do suspend true
,08-29 10:42:28.107   932   932 D RttService: SCAN_AVAILABLE : 3
08-29 10:42:28.107   932  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-29 10:42:28.107   512   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 10:42:28.107   932  3084 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:42:28.109   512   926 D CommandListener: Setting iface cfg
,08-29 10:42:28.113   932  2975 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '86 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 86 Failed to set address (No such device)'
,08-29 10:42:28.114   932  2975 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 10:42:28.122   932  2975 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 10:42:28.122   932  2975 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 10:42:28.129   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=216871 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,08-29 10:42:31.333  5811  5811 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 10:42:31.370   932  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
08-29 10:42:31.380   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
08-29 10:42:31.380   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:42:31.397   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 10:42:31.430   932  3154 D WifiService: setWifiEnabled: false pid=5620, uid=10077
08-29 10:42:31.431   932  3154 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:42:31.440   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 10:42:31.446   932   932 D RttService: SCAN_AVAILABLE : 1
,08-29 10:42:31.446   932  3084 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:42:31.460   932  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:42:31.461   512   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:42:31.468   932  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 10:42:31.469  5811  5811 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 10:42:31.473  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:31.473  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:31.473  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:31.473  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:31.474  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:31.475  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:31.475  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:31.475  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:31.476  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:31.476  5620  5620 V io.jxcore.node.ConnectivityMonit,or:     - active network type is Wi-Fi: false
08-29 10:42:31.476  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:31.476  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:42:31.482  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:42:31.486  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,08-29 10:42:31.548  5811  5811 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 10:42:31.558  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:42:31.662   932  2976 D wifi    : In wifi stop Hal
08-29 10:42:31.663   932  2976 D wifi    : halHandle = 0x7f90f31080, mVM = 0x7fac50d140, mCls = 0x1017ae
,08-29 10:42:31.663   932  5810 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 10:42:31.663   932  5810 D WifiHAL : Got a signal to exit!!!
08-29 10:42:31.663   932  5810 I WifiHAL : Exit wifi_event_loop
08-29 10:42:31.664   932  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 10:42:31.664   932  2976 E WifiHAL : Event processing terminated
08-29 10:42:31.665   932  2976 D wifi    : In wifi cleaned up handler
08-29 10:42:31.666  4250  4250 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:42:31.666   932  2976 I WifiHAL : Internal cleanup completed
08-29 10:42:31.670  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:31.672  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:31.675  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:31.676  3473  3989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:42:31.688   932  5810 D wifi    : set interface wlan0 flags (DOWN)
,08-29 10:42:31.689   932  2976 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 10:42:31.838   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 10:42:31.838   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:42:31.897   932   949 D Tethering: InitialState.processMessage what=4
,08-29 10:42:31.905   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 10:42:36.471   932   949 I ActivityManager: Start proc 5815:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 10:42:36.556  5815  5815 D AdapterServiceConfig: Adding HeadsetService
,08-29 10:42:36.557  5815  5815 D AdapterServiceConfig: Adding A2dpService
08-29 10:42:36.557  5815  5815 D AdapterServiceConfig: Adding HidService
08-29 10:42:36.557  5815  5815 D AdapterServiceConfig: Adding HealthService
08-29 10:42:36.557  5815  5815 D AdapterServiceConfig: Adding PanService
08-29 10:42:36.557  5815  5815 D AdapterServiceConfig: Adding GattService
08-29 10:42:36.557  5815  5815 D AdapterServiceConfig: Adding BluetoothMapService
08-29 10:42:36.558  5815  5815 D AdapterServiceConfig: Adding SapService
,08-29 10:42:36.569   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ba31e8:true
,08-29 10:42:36.569  5815  5815 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 10:42:36.573  5815  5815 I bt_bluedroid: init
,08-29 10:42:36.573  5815  5827 I BluetoothAdapterState: Entering OffState
,08-29 10:42:36.576  5815  5828 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 10:42:36.576  5815  5828 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:42:36.576  5815  5828 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 10:42:36.576  5815  5828 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 10:42:36.577  5815  5815 I bt_bluedroid: get_profile_interface socket
,08-29 10:42:36.579  5815  5815 I bt_bluedroid: get_profile_interface sdp
,08-29 10:42:36.579  5815  5831 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 10:42:36.582  5815  5831 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 10:42:36.584  5815  5826 I bt_bluedroid: config_hci_snoop_log
,08-29 10:42:36.585   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-29 10:42:36.589  5815  5827 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 10:42:36.589  5815  5827 D BluetoothAdapterProperties: Setting state to 14
,08-29 10:42:36.589  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 10:42:36.591  5815  5827 D BluetoothBondStateMachine: make
,08-29 10:42:36.592  5815  5832 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 10:42:36.595  5815  5827 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:42:36.596  5815  5815 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 10:42:36.598  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:36.598  5815  5815 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:42:36.599  5815  5815 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:42:36.599  5815  5815 D BtGatt.GattService: start()
08-29 10:42:36.599  5815  5815 I bt_bluedroid: get_profile_interface gatt
08-29 10:42:36.600  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:36.600  5815  5815 D BtGatt.AdvertiseManager: advertise manager created
,08-29 10:42:36.605  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:36.605  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:36.605  5815  5815 V BluetoothAdapterState: isBleTurningOn()=true
08-29 10:42:36.605  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:36.606  5815  5827 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 10:42:36.606  5815  5827 I bt_bluedroid: enable
08-29 10:42:36.606  5815  5828 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 10:42:36.606  5815  5828 I bt_hci  : start_up
,08-29 10:42:36.611  5815  5828 I bt_vendor: alloc value 0xf422904d
,08-29 10:42:36.611  5815  5828 I bt_vendor: init
08-29 10:42:36.611  5815  5828 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 10:42:36.612  5815  5828 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 10:42:36.732  5815  5828 D bt_hci  : start_up starting async portion
,08-29 10:42:36.732  5815  5835 I bt_hci  : event_finish_startup
08-29 10:42:36.733  5815  5835 I bt_hci_h4: hal_open
08-29 10:42:36.733  5815  5835 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 10:42:36.736  5815  5835 I bt_userial_vendor: device fd = 51 open
08-29 10:42:36.718  5836  5836 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 10:42:36.749  5815  5835 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:42:36.752  5815  5835 D bt_hwcfg: Chipset BCM4358A3
,08-29 10:42:36.752  5815  5835 D bt_hwcfg: Target name = [BCM4358A3]
08-29 10:42:36.753  5815  5835 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 10:42:37.150  5815  5835 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 10:42:37.150  5815  5835 D bt_hwcfg: Settlement delay -- 100 ms
08-29 10:42:37.150  5815  5835 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 10:42:37.285  5815  5835 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 10:42:37.285  5815  5835 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 10:42:37.287  5815  5835 I bt_hwcfg: vendor lib fwcfg completed
08-29 10:42:37.287  5815  5835 I bt_vendor: firmware callback
08-29 10:42:37.287  5815  5835 I bt_hci  : firmware_config_callback
,08-29 10:42:37.296  5815  5838 I bt_btu  : btu_task pending for preload complete event
,08-29 10:42:37.297  5815  5838 I bt_btu_task: Bluetooth chip preload is complete
08-29 10:42:37.297  5815  5838 I bt_btu  : btu_task received preload complete event
,08-29 10:42:37.304  5815  5838 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 10:42:37.304  5815  5838 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 10:42:37.304  5815  5838 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 10:42:37.304  5815  5838 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:42:37.304  5815  5838 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 10:42:37.304  5815  5838 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 10:42:37.304  5815  5838 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 10:42:37.305  5815  5838 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:42:37.401  5815  5838 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41a6c99
,08-29 10:42:37.401  5815  5838 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41a6c99 
,08-29 10:42:37.427  5815  5831 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 10:42:37.429  5815  5831 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 10:42:37.430  5815  5831 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 10:42:37.433  5815  5831 D BluetoothAdapterProperties: Name is: Nexus 6P
08-29 10:42:37.436  5815  5831 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:42:37.436  5815  5831 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 10:42:37.436  5815  5831 D bt_hci  : do_postload posting postload work item
08-29 10:42:37.437  5815  5835 I bt_hci  : event_postload
08-29 10:42:37.437  5815  5835 I bt_vendor: sco_config_cb
08-29 10:42:37.437  5815  5835 I bt_hci  : sco_config_callback postload finished.
,08-29 10:42:37.441  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:37.444  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:37.447  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:37.447  5815  5835 I bt_vendor: low_power_mode_cb
,08-29 10:42:37.450  5815  5831 D bt_bte_conf: Device ID record 1 : primary
,08-29 10:42:37.450  5815  5831 D bt_bte_conf:   vendorId            = 000f
08-29 10:42:37.450  5815  5831 D bt_bte_conf:   vendorIdSource      = 0001
08-29 10:42:37.450  5815  5831 D bt_bte_conf:   product             = 1200
08-29 10:42:37.450  5815  5831 D bt_bte_conf:   version             = 1436
08-29 10:42:37.450  5815  5831 D bt_bte_conf:   clientExecutableURL = 
08-29 10:42:37.450  5815  5831 D bt_bte_conf:   serviceDescription  = 
,08-29 10:42:37.451  5815  5831 D bt_bte_conf:   documentationURL    = 
08-29 10:42:37.451  5815  5831 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 10:42:37.451  5815  5828 D bt_stack_manager: event_start_up_stack finished
08-29 10:42:37.452  5815  5827 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 10:42:37.452  5815  5827 D BluetoothAdapterProperties: Setting state to 15
08-29 10:42:37.452  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 10:42:37.453  5815  5827 I BluetoothAdapterState: Entering BleOnState
,08-29 10:42:37.459  5815  5827 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 10:42:37.459  5815  5827 D BluetoothAdapterProperties: Setting state to 11
08-29 10:42:37.459  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 10:42:37.465  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:37.466  5815  5815 D HeadsetService: Received start request. Starting profile...
,08-29 10:42:37.470  5815  5815 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:42:37.470  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:37.471  5815  5815 D HeadsetStateMachine: make
,08-29 10:42:37.472  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:37.474  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:37.483  5815  5815 D HeadsetStateMachine: max_hf_connections = 1
08-29 10:42:37.483  5815  5815 I bt_bluedroid: get_profile_interface handsfree
,08-29 10:42:37.483  5815  5831 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 10:42:37.483  5815  5831 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,08-29 10:42:37.487  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:37.488  5815  5815 D A2dpService: Received start request. Starting profile...
08-29 10:42:37.489  5815  5815 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 10:42:37.489  5815  5815 I bt_bluedroid: get_profile_interface avrcp
08-29 10:42:37.490  5815  5827 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:42:37.496  5815  5815 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 10:42:37.497  5815  5815 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 10:42:37.497  5815  5815 D A2dpStateMachine: make
08-29 10:42:37.498  5815  5815 I bt_bluedroid: get_profile_interface a2dp
08-29 10:42:37.499  5815  5831 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 10:42:37.500  5815  5846 D A2dpStateMachine: Enter Disconnected: -2
,08-29 10:42:37.503  5815  5815 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 10:42:37.503  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:42:37.504  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:37.505  5815  5815 D HidService: Received start request. Starting profile...
,08-29 10:42:37.506  5815  5815 I bt_bluedroid: get_profile_interface hidhost
08-29 10:42:37.506  5815  5831 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41882d9
08-29 10:42:37.506  5815  5815 D HidService: setHidService(): set to: null
08-29 10:42:37.506  5815  5831 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 10:42:37.507  5815  5815 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:42:37.507  5724  5724 D BluetoothInputDevice: Proxy object connected
08-29 10:42:37.507  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:37.508  5724  5724 D HidProfile: Bluetooth service connected
08-29 10:42:37.508  5815  5815 D HealthService: Received start request. Starting profile...
,08-29 10:42:37.510  5815  5815 I bt_bluedroid: get_profile_interface health
08-29 10:42:37.511  5815  5815 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 10:42:37.511  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:37.513  5815  5815 D PanService: Received start request. Starting profile...
08-29 10:42:37.513  5815  5815 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:42:37.513  5815  5815 I bt_bluedroid: get_profile_interface pan
,08-29 10:42:37.514  5815  5831 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 10:42:37.514  5815  5815 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:42:37.515  5815  5815 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:37.515  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:37.515  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:37.515  5815  5844 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:42:37.516  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:37.518  5815  5815 D BluetoothMapService: Received start request. Starting profile...
08-29 10:42:37.518  5815  5815 D BluetoothMapService: start()
08-29 10:42:37.520  5815  5815 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 10:42:37.521  5815  5815 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 10:42:37.521  5815  5815 D BluetoothMapAppObserver: createReceiver()
08-29 10:42:37.517  5724  5724 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:42:37.523  5724  5724 D PanProfile: Bluetooth service connected
08-29 10:42:37.523  5724  5724 D BluetoothMap: Proxy object connected
08-29 10:42:37.523  5724  5724 D MapProfile: Bluetooth service connected
08-29 10:42:37.523  5724  5724 D BluetoothMap: getConnectedDevices()
,08-29 10:42:37.524  5815  5815 D BluetoothMapAppObserver: initObservers()
08-29 10:42:37.524  5815  5815 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 10:42:37.532  5815  5815 V SapService: SapBinder()
08-29 10:42:37.532  5815  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:37.532  5815  5815 D SapService: Received start request. Starting profile...
08-29 10:42:37.532  5815  5815 V SapService: start()
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:37.534  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:37.535  5815  5815 V BluetoothAdapterState: isTurningOn()=true
,08-29 10:42:37.536  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:37.536  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:37.536  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:37.536  5815  5815 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:37.536  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:37.536  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:37.537  5815  5827 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 10:42:37.537  5815  5827 D BluetoothAdapterProperties: ScanMode =  20
,08-29 10:42:37.537  5815  5827 D BluetoothAdapterProperties: State =  11
08-29 10:42:37.537  5815  5827 D BluetoothAdapterProperties: Setting state to 12
08-29 10:42:37.537  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 10:42:37.538   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:42:37.538  5815  5827 I BluetoothAdapterState: Entering OnState
08-29 10:42:37.540  5724  5724 D BluetoothMap: Bluetooth is Not enabled
08-29 10:42:37.540  5815  5831 D BluetoothAdapterProperties: Scan Mode:21
08-29 10:42:37.540  5815  5831 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:42:37.541   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:42:37.541  5724  5734 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:42:37.542  5724  5735 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:42:37.542   932   932 D BluetoothA2dp: Proxy object connected
08-29 10:42:37.543  3526  3551 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:42:37.544  3143  3900 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:37.545  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:37.547  3143  3157 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:42:37.547  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:42:37.550  5815  5815 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 10:42:37.550  5815  5815 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:37.550  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:37.552  5815  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:42:37.552  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:42:37.554  5815  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:42:37.555  5815  5815 D ObexServerSockets: Succeed to create listening sockets 
08-29 10:42:37.555  5815  5815 D ObexServerSockets0: startAccept()
,08-29 10:42:37.555  5815  5815 D ObexServerSockets0: prepareForNewConnect()
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:37.555  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:37.557  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:37.558  5815  5815 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 10:42:37.558  5724  5734 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:42:37.558  5815  5815 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 10:42:37.558   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:42:37.558  5724  5735 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 10:42:37.559  3143  3156 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:42:37.559  5815  5851 D ObexServerSockets0: Accepting socket connection...
08-29 10:42:37.560  5815  5852 D ObexServerSockets0: Accepting socket connection...
08-29 10:42:37.561  3143  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:42:37.561  3143  3143 D BluetoothMap: Proxy object connected
08-29 10:42:37.561  3143  3143 D MapProfile: Bluetooth service connected
08-29 10:42:37.561  3143  3143 D BluetoothMap: getConnectedDevices()
08-29 10:42:37.563  3143  3157 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:42:37.563  3143  3143 D BluetoothInputDevice: Proxy object connected
08-29 10:42:37.563  3143  3143 D HidProfile: Bluetooth service connected
08-29 10:42:37.564   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:42:37.564  3143  3900 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:42:37.565  3143  3143 D BluetoothA2dp: Proxy object connected
08-29 10:42:37.566  3143  3143 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:42:37.566  3143  3143 D PanProfile: Bluetooth service connected
,08-29 10:42:37.569  5815  5815 D BluetoothMapService: onReceive
08-29 10:42:37.569   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 10:42:37.569  5815  5815 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:42:37.569  5815  5815 D BluetoothMapService: STATE_ON
08-29 10:42:37.569  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:37.570  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:37.572  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:37.573  5815  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:42:37.574  5724  5724 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 10:42:37.574  5815  5854 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,08-29 10:42:37.574  5815  5854 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 10:42:37.577  5724  5724 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 10:42:37.583  5724  5724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:42:37.584  5724  5724 D BluetoothA2dp: Proxy object connected
,08-29 10:42:37.589  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:42:37.589  5724  5724 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:42:37.596  5724  5724 D BluetoothPbap: Proxy object connected
,08-29 10:42:37.596  5815  5815 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 10:42:37.596  5815  5815 D ObexServerSockets0: prepareForNewConnect()
08-29 10:42:37.596  5724  5724 D PbapServerProfile: Bluetooth service connected
,08-29 10:42:37.598  3143  3143 D BluetoothPbap: Proxy object connected
08-29 10:42:37.598  3143  3143 D PbapServerProfile: Bluetooth service connected
,08-29 10:42:37.605  5815  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:42:37.621  5815  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:42:37.622  5815  5862 I BtOppRfcommListener: Accept thread started.
,08-29 10:42:37.643  3526  3549 D BluetoothHeadset: Proxy object connected
,08-29 10:42:37.643  3526  3763 D BluetoothHeadset: Proxy object connected
08-29 10:42:37.644   932   932 D BluetoothHeadset: Proxy object connected
08-29 10:42:37.644   932   932 D BluetoothHeadset: Proxy object connected
,08-29 10:42:37.644   932   932 D BluetoothHeadset: Proxy object connected
,08-29 10:42:37.644  3143  3157 D BluetoothHeadset: Proxy object connected
,08-29 10:42:37.644  3143  3143 D HeadsetProfile: Bluetooth service connected
,08-29 10:42:37.647  3143  3156 D BluetoothHeadset: Proxy object connected
08-29 10:42:37.647  3143  3143 D HeadsetProfile: Bluetooth service connected
,08-29 10:42:37.659   932   949 D BluetoothHeadset: Proxy object connected
,08-29 10:42:37.665   932   949 D BluetoothHeadset: Proxy object connected
,08-29 10:42:37.681  5724  5735 D BluetoothHeadset: Proxy object connected
,08-29 10:42:37.682  5724  5724 D HeadsetProfile: Bluetooth service connected
,08-29 10:42:41.444  5815  5827 D BluetoothAdapterState: Current state: ON, message: 23
08-29 10:42:41.444  5815  5827 D BluetoothAdapterProperties: Setting state to 13
08-29 10:42:41.444  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 10:42:41.445  5815  5827 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 10:42:41.447  5815  5827 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:42:41.449  5815  5815 D BluetoothMapService: onReceive
08-29 10:42:41.449  5815  5815 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:42:41.450  5815  5815 D BluetoothMapService: STATE_TURNING_OFF
08-29 10:42:41.450  5815  5815 D BluetoothMapService: MAP Service closeService in
08-29 10:42:41.450  5815  5815 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 10:42:41.450  5815  5815 D ObexServerSockets0: shutdown(block = true)
08-29 10:42:41.451  5815  5815 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:42:41.452  5815  5852 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 10:42:41.453  5815  5851 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 10:42:41.453  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:41.453  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:41.455  5815  5831 D BluetoothAdapterProperties: Scan Mode:20
,08-29 10:42:41.455  5724  5724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:42:41.455  5815  5827 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 10:42:41.456  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:41.456  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:41.457  5815  5815 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:42:41.457  5815  5840 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 10:42:41.458  5815  5815 I BtOppRfcommListener: stopping Accept Thread
08-29 10:42:41.458  5815  5862 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 10:42:41.459  5815  5862 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 10:42:41.470  5815  5815 D HeadsetService: Received stop request...Stopping profile...
08-29 10:42:41.472  5724  5734 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:41.472  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:41.472  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:41.473  3526  3551 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:41.473   932   932 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:41.473   932   932 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:41.473   932   932 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:41.473  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:41.473  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:41.473  3143  3900 D BluetoothHeadset: Proxy object disconnected
08-29 10:42:41.474  5724  5724 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:42:41.475  5724  5724 D HeadsetProfile: Bluetooth service disconnected
08-29 10:42:41.476  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:42:41.476  5815  5815 D A2dpService: Received stop request...Stopping profile...
08-29 10:42:41.477  5815  5846 D A2dpStateMachine: Exit Disconnected: -1
08-29 10:42:41.478  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:41.478  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:41.479  5620  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:42:41.479  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:41.479   932   932 D BluetoothA2dp: Proxy object disconnected
08-29 10:42:41.480  5724  5724 D BluetoothA2dp: Proxy object disconnected
,08-29 10:42:41.482  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:41.484  5815  5815 D HidService: Received stop request...Stopping profile...
08-29 10:42:41.484  5815  5815 D HidService: Stopping Bluetooth HidService
,08-29 10:42:41.485  5815  5815 V BluetoothAdapterState: isTurningOff()=true
,08-29 10:42:41.485  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.485  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.485  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:41.485  5724  5724 D BluetoothInputDevice: Proxy object disconnected
08-29 10:42:41.485  5724  5724 D HidProfile: Bluetooth service disconnected
08-29 10:42:41.486  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:41.487  3143  3143 D HeadsetProfile: Bluetooth service disconnected
08-29 10:42:41.487  5815  5815 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:42:41.487  5815  5815 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:42:41.487  3143  3143 D BluetoothA2dp: Proxy object disconnected
,08-29 10:42:41.487  5815  5831 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 10:42:41.488  3143  3143 D BluetoothInputDevice: Proxy object disconnected
,08-29 10:42:41.488  3143  3143 D HidProfile: Bluetooth service disconnected
08-29 10:42:41.488  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:41.488  5815  5838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:41.488  5815  5838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:41.488  5815  5838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:41.488  5815  5831 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 10:42:41.489  3143  3143 D BluetoothPbap: Proxy object disconnected
08-29 10:42:41.490  3143  3143 D PbapServerProfile: Bluetooth service disconnected
08-29 10:42:41.490  5815  5815 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:41.490  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.490  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.490  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:41.490  5724  5724 D BluetoothPbap: Proxy object disconnected
08-29 10:42:41.490  5724  5724 D PbapServerProfile: Bluetooth service disconnected
,08-29 10:42:41.493  5815  5838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:41.493  5815  5838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:41.493  5815  5815 D HealthService: Received stop request...Stopping profile...
08-29 10:42:41.493  5815  5831 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 10:42:41.493  5815  5838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:42:41.493  5815  5838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 10:42:41.493  5815  5838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:42:41.494  5815  5838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:42:41.495  5815  5815 D PanService: Received stop request...Stopping profile...
08-29 10:42:41.496  3143  3143 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:42:41.496  3143  3143 D PanProfile: Bluetooth service disconnected
08-29 10:42:41.496  5724  5724 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:42:41.496  5724  5724 D PanProfile: Bluetooth service disconnected
08-29 10:42:41.497  5815  5815 D BluetoothMapService: Received stop request...Stopping profile...
08-29 10:42:41.497  5815  5815 D BluetoothMapService: stop()
,08-29 10:42:41.499  5815  5815 D BluetoothMapAppObserver: deinitObservers()
,08-29 10:42:41.499  5815  5815 D BluetoothMapAppObserver: removeReceiver()
08-29 10:42:41.500  3143  3143 D BluetoothMap: Proxy object disconnected
08-29 10:42:41.500  3143  3143 D MapProfile: Bluetooth service disconnected
08-29 10:42:41.500  5815  5815 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:41.500  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.500  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.500  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:41.501  5815  5815 D SapService: Received stop request...Stopping profile...
,08-29 10:42:41.501  5815  5815 V SapService: stop()
08-29 10:42:41.502  5815  5815 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:42:41.502  5815  5815 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:42:41.503  5815  5831 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:42:41.503  5815  5815 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:41.503  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.503  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.503  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:41.503  5815  5815 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:42:41.504  5815  5831 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 10:42:41.504  5815  5815 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:42:41.504  5815  5815 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:41.504  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.504  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.505  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:41.505  5815  5815 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:42:41.505  5815  5815 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 10:42:41.506  5815  5815 D BluetoothMapService: MAP Service closeService in
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:41.506  5724  5724 D BluetoothMap: Proxy object disconnected
08-29 10:42:41.506  5815  5815 D BluetoothMapService: cleanup()
08-29 10:42:41.506  5724  5724 D MapProfile: Bluetooth service disconnected
08-29 10:42:41.506  5815  5815 D BluetoothMapService: MAP Service closeService in
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isTurningOff()=true
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.506  5815  5815 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:42:41.507  5815  5827 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 10:42:41.507  5815  5827 D BluetoothAdapterProperties: Setting state to 15
08-29 10:42:41.507  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 10:42:41.508   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:42:41.508  5724  5734 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:42:41.508   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:42:41.508  5724  5735 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 10:42:41.509  5724  5734 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:42:41.510  5724  5735 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:42:41.510  5815  5827 I BluetoothAdapterState: Entering BleOnState
08-29 10:42:41.510  3526  3763 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:41.511  3143  3156 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:42:41.511  3143  3157 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:41.512  5724  5734 D BluetoothPan: onBluetoothStateChange on: false
,08-29 10:42:41.512   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:41.512  5724  5735 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:42:41.513  3143  3900 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:42:41.513  3143  3156 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:42:41.514  3143  3157 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:42:41.514   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:42:41.514  3143  3900 D BluetoothPan: onBluetoothStateChange on: false
08-29 10:42:41.515  5815  5827 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 10:42:41.515  5815  5827 D BluetoothAdapterProperties: Setting state to 16
08-29 10:42:41.515  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 10:42:41.516  5815  5827 D BluetoothAdapterProperties: onBleDisable
,08-29 10:42:41.516  5815  5827 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:42:41.516  5815  5828 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 10:42:41.517  5815  5838 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 10:42:41.517  5815  5838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:42:41.518  5815  5831 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:42:41.518  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:41.519  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:41.519  5724  5724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 10:42:41.521  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:41.523  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:41.524  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:41.524  5724  5724 D DockEventReceiver: finishStartingService: stopping service
08-29 10:42:41.525  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:42:41.525  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:41.735  5815  5831 I bt_hci  : shut_down
,08-29 10:42:41.740  5815  5835 D bt_hwcfg: hw_epilog_process
,08-29 10:42:41.741  5815  5835 I bt_vendor: low_power_mode_cb
,08-29 10:42:41.744  5815  5835 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 10:42:41.744  5815  5835 I bt_vendor: epilog_cb
08-29 10:42:41.744  5815  5835 I bt_hci  : epilog_finished_callback
,08-29 10:42:41.748  5815  5831 I bt_hci_h4: hal_close
,08-29 10:42:41.749  5815  5831 I bt_userial_vendor: device fd = 51 close
,08-29 10:42:41.838   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:41.877  5815  5828 D bt_stack_manager: event_shut_down_stack finished.
,08-29 10:42:41.878  5815  5827 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 10:42:41.882  5815  5827 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 10:42:41.882  5815  5815 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:42:41.883  5815  5815 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:42:41.883  5815  5815 D BtGatt.GattService: stop()
08-29 10:42:41.883  5815  5815 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 10:42:41.886  5815  5815 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:41.886  5815  5815 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:41.886  5815  5815 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:41.886  5815  5815 V BluetoothAdapterState: isBleTurningOff()=true
08-29 10:42:41.887  5815  5827 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 10:42:41.887  5815  5827 D BluetoothAdapterProperties: Setting state to 10
,08-29 10:42:41.887  5815  5827 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 10:42:41.888  5815  5827 I BluetoothAdapterState: Entering OffState
08-29 10:42:41.889   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 10:42:41.902  5815  5815 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 10:42:41.902  5815  5815 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 10:42:41.902  5815  5815 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 10:42:41.904  5815  5828 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 10:42:41.907  5815  5828 D bt_stack_manager: event_clean_up_stack finished.
,08-29 10:42:41.909  5815  5815 I art     : System.exit called, status: 0
,08-29 10:42:41.909  5815  5815 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 10:42:41.942   932  3155 I ActivityManager: Process com.android.bluetooth (pid 5815) has died
,08-29 10:42:42.839   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:43.840   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:44.841   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:45.842   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:46.441  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:42:46.441  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:46.445  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:46.445  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b66cd7 removed from the list
08-29 10:42:46.445  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:46.446  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:46.446  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:46.449  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:42:46.449  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3610ad added. We now have 4 listener(s)
08-29 10:42:46.449  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:42:46.450  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:46.451  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3610ad removed from the list
08-29 10:42:46.451  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:46.451  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:46.451  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:42:46.453  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:42:46.453  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e7ffe2 added. We now have 4 listener(s)
,08-29 10:42:46.453  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:42:46.842   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:42:51.464  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:51.491   932   949 I ActivityManager: Start proc 5870:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 10:42:51.559  5870  5870 D AdapterServiceConfig: Adding HeadsetService
08-29 10:42:51.559  5870  5870 D AdapterServiceConfig: Adding A2dpService
08-29 10:42:51.559  5870  5870 D AdapterServiceConfig: Adding HidService
08-29 10:42:51.559  5870  5870 D AdapterServiceConfig: Adding HealthService
08-29 10:42:51.559  5870  5870 D AdapterServiceConfig: Adding PanService
08-29 10:42:51.560  5870  5870 D AdapterServiceConfig: Adding GattService
08-29 10:42:51.560  5870  5870 D AdapterServiceConfig: Adding BluetoothMapService
08-29 10:42:51.560  5870  5870 D AdapterServiceConfig: Adding SapService
,08-29 10:42:51.569   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@84235c1:true
,08-29 10:42:51.569  5870  5870 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 10:42:51.572  5870  5870 I bt_bluedroid: init
,08-29 10:42:51.573  5870  5882 I BluetoothAdapterState: Entering OffState
,08-29 10:42:51.576  5870  5883 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 10:42:51.576  5870  5883 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:42:51.576  5870  5883 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 10:42:51.576  5870  5883 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 10:42:51.577  5870  5870 I bt_bluedroid: get_profile_interface socket
,08-29 10:42:51.579  5870  5886 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 10:42:51.579  5870  5870 I bt_bluedroid: get_profile_interface sdp
08-29 10:42:51.580  5870  5886 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 10:42:51.582  5870  5881 I bt_bluedroid: config_hci_snoop_log
,08-29 10:42:51.583   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-29 10:42:51.587  5870  5882 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 10:42:51.587  5870  5882 D BluetoothAdapterProperties: Setting state to 14
08-29 10:42:51.587  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 10:42:51.589  5870  5882 D BluetoothBondStateMachine: make
,08-29 10:42:51.591  5870  5887 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 10:42:51.594  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:42:51.595  5870  5870 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-29 10:42:51.597  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:51.598  5870  5870 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:42:51.599  5870  5870 D BtGatt.GattService: Received start request. Starting profile...
,08-29 10:42:51.599  5870  5870 D BtGatt.GattService: start()
08-29 10:42:51.599  5870  5870 I bt_bluedroid: get_profile_interface gatt
08-29 10:42:51.600  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:51.601  5870  5870 D BtGatt.AdvertiseManager: advertise manager created
,08-29 10:42:51.606  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:42:51.606  5870  5870 V BluetoothAdapterState: isTurningOn()=false
08-29 10:42:51.606  5870  5870 V BluetoothAdapterState: isBleTurningOn()=true
08-29 10:42:51.606  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:51.607  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 10:42:51.607  5870  5882 I bt_bluedroid: enable
08-29 10:42:51.607  5870  5883 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 10:42:51.607  5870  5883 I bt_hci  : start_up
,08-29 10:42:51.612  5870  5883 I bt_vendor: alloc value 0xf422904d
08-29 10:42:51.612  5870  5883 I bt_vendor: init
08-29 10:42:51.612  5870  5883 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 10:42:51.612  5870  5883 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 10:42:51.732  5870  5883 D bt_hci  : start_up starting async portion
,08-29 10:42:51.733  5870  5890 I bt_hci  : event_finish_startup
08-29 10:42:51.733  5870  5890 I bt_hci_h4: hal_open
08-29 10:42:51.734  5870  5890 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 10:42:51.718  5891  5891 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 10:42:51.737  5870  5890 I bt_userial_vendor: device fd = 51 open
,08-29 10:42:51.753  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:42:51.757  5870  5890 D bt_hwcfg: Chipset BCM4358A3
,08-29 10:42:51.757  5870  5890 D bt_hwcfg: Target name = [BCM4358A3]
08-29 10:42:51.758  5870  5890 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 10:42:51.844   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:52.260  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 10:42:52.260  5870  5890 D bt_hwcfg: Settlement delay -- 100 ms
08-29 10:42:52.260  5870  5890 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 10:42:52.394  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:42:52.394  5870  5890 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
08-29 10:42:52.397  5870  5890 I bt_hwcfg: vendor lib fwcfg completed
08-29 10:42:52.397  5870  5890 I bt_vendor: firmware callback
08-29 10:42:52.398  5870  5890 I bt_hci  : firmware_config_callback
,08-29 10:42:52.406  5870  5893 I bt_btu  : btu_task pending for preload complete event
,08-29 10:42:52.406  5870  5893 I bt_btu_task: Bluetooth chip preload is complete
08-29 10:42:52.406  5870  5893 I bt_btu  : btu_task received preload complete event
,08-29 10:42:52.413  5870  5893 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 10:42:52.413  5870  5893 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 10:42:52.413  5870  5893 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:42:52.414  5870  5893 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 10:42:52.415  5870  5893 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:42:52.415  5870  5893 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:42:52.415  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 10:42:52.415  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:42:52.513  5870  5893 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41a6c99
08-29 10:42:52.513  5870  5893 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41a6c99 
,08-29 10:42:52.526  5870  5886 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 10:42:52.528  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 10:42:52.529  5870  5886 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 10:42:52.531  5870  5886 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 10:42:52.535  5870  5886 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:42:52.535  5870  5886 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 10:42:52.535  5870  5886 D bt_hci  : do_postload posting postload work item
08-29 10:42:52.535  5870  5890 I bt_hci  : event_postload
08-29 10:42:52.536  5870  5890 I bt_vendor: sco_config_cb
08-29 10:42:52.536  5870  5890 I bt_hci  : sco_config_callback postload finished.
,08-29 10:42:52.540  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:52.541  5870  5886 D bt_bte_conf: Device ID record 1 : primary
,08-29 10:42:52.541  5870  5886 D bt_bte_conf:   vendorId            = 000f
08-29 10:42:52.541  5870  5886 D bt_bte_conf:   vendorIdSource      = 0001
08-29 10:42:52.541  5870  5886 D bt_bte_conf:   product             = 1200
08-29 10:42:52.541  5870  5886 D bt_bte_conf:   version             = 1436
,08-29 10:42:52.541  5870  5886 D bt_bte_conf:   clientExecutableURL = 
08-29 10:42:52.541  5870  5886 D bt_bte_conf:   serviceDescription  = 
08-29 10:42:52.542  5870  5886 D bt_bte_conf:   documentationURL    = 
08-29 10:42:52.542  5870  5886 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 10:42:52.542  5870  5883 D bt_stack_manager: event_start_up_stack finished
08-29 10:42:52.544  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 10:42:52.544  5870  5882 D BluetoothAdapterProperties: Setting state to 15
08-29 10:42:52.544  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 10:42:52.546  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:52.546  5870  5882 I BluetoothAdapterState: Entering BleOnState
,08-29 10:42:52.549  5870  5890 I bt_vendor: low_power_mode_cb
08-29 10:42:52.550  5870  5882 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 10:42:52.550  5870  5882 D BluetoothAdapterProperties: Setting state to 11
08-29 10:42:52.550  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 10:42:52.554  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:52.556  5870  5870 D HeadsetService: Received start request. Starting profile...
,08-29 10:42:52.558  5870  5870 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:42:52.559  5870  5870 D HeadsetStateMachine: make
,08-29 10:42:52.560  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:52.565  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:42:52.574  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:42:52.574  5870  5870 D HeadsetStateMachine: max_hf_connections = 1
,08-29 10:42:52.574  5870  5870 I bt_bluedroid: get_profile_interface handsfree
08-29 10:42:52.574  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 10:42:52.575  5870  5886 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-29 10:42:52.579  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:52.579  5870  5870 D A2dpService: Received start request. Starting profile...
08-29 10:42:52.580  5870  5870 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 10:42:52.580  5870  5870 I bt_bluedroid: get_profile_interface avrcp
,08-29 10:42:52.586  5870  5870 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 10:42:52.586  5870  5870 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:42:52.586  5870  5870 D A2dpStateMachine: make
08-29 10:42:52.589  5870  5870 I bt_bluedroid: get_profile_interface a2dp
,08-29 10:42:52.589  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 10:42:52.591  5870  5902 D A2dpStateMachine: Enter Disconnected: -2
,08-29 10:42:52.591  5870  5870 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 10:42:52.592  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:52.592  5870  5870 D HidService: Received start request. Starting profile...
08-29 10:42:52.592  5870  5870 I bt_bluedroid: get_profile_interface hidhost
08-29 10:42:52.592  5870  5870 D HidService: setHidService(): set to: null
08-29 10:42:52.593  5870  5870 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:42:52.593  5870  5886 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41882d9
08-29 10:42:52.593  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 10:42:52.594  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:52.594  5870  5870 D HealthService: Received start request. Starting profile...
,08-29 10:42:52.596  5870  5870 I bt_bluedroid: get_profile_interface health
08-29 10:42:52.596  5870  5870 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 10:42:52.597  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:52.598  5870  5870 D PanService: Received start request. Starting profile...
08-29 10:42:52.598  5870  5870 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:42:52.598  5870  5870 I bt_bluedroid: get_profile_interface pan
08-29 10:42:52.598  5870  5886 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 10:42:52.601  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:42:52.602  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:42:52.603  5870  5870 D BluetoothMapService: Received start request. Starting profile...
08-29 10:42:52.603  5870  5870 D BluetoothMapService: start()
08-29 10:42:52.606  5870  5870 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 10:42:52.606  5870  5870 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 10:42:52.607  5870  5870 D BluetoothMapAppObserver: createReceiver()
08-29 10:42:52.609  5870  5870 D BluetoothMapAppObserver: initObservers()
08-29 10:42:52.609  5870  5870 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 10:42:52.614  5870  5870 V SapService: SapBinder()
08-29 10:42:52.614  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
,08-29 10:42:52.615  5870  5870 D SapService: Received start request. Starting profile...
08-29 10:42:52.616  5870  5870 V SapService: start()
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isTurningOn()=true
,08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:52.617  5870  5899 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:52.617  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:52.618  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:52.619  5870  5870 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:52.619  5870  5870 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:52.619  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:52.619  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:52.620  5870  5870 V BluetoothAdapterState: isTurningOff()=false
08-29 10:42:52.620  5870  5870 V BluetoothAdapterState: isTurningOn()=true
08-29 10:42:52.620  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:42:52.620  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:42:52.620  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 10:42:52.620  5870  5882 D BluetoothAdapterProperties: ScanMode =  20
08-29 10:42:52.620  5870  5882 D BluetoothAdapterProperties: State =  11
08-29 10:42:52.620  5870  5882 D BluetoothAdapterProperties: Setting state to 12
08-29 10:42:52.620  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 10:42:52.621   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:42:52.621  5870  5886 D BluetoothAdapterProperties: Scan Mode:21
08-29 10:42:52.621  5870  5886 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:42:52.621  5870  5882 I BluetoothAdapterState: Entering OnState
,08-29 10:42:52.625  5724  5734 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:42:52.625   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:42:52.625   932   932 D BluetoothA2dp: Proxy object connected
08-29 10:42:52.626  5724  5735 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:52.627  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:52.628  5724  5734 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 10:42:52.629  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:52.630  5724  5735 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:42:52.632  3526  3549 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:42:52.632  3143  3157 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:42:52.633  5870  5870 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 10:42:52.633  5870  5870 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:52.633  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:42:52.634  3143  3156 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:42:52.634  5870  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:42:52.634  5724  5735 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:42:52.635  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:52.636  5870  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:42:52.636  5724  5724 D BluetoothA2dp: Proxy object connected
08-29 10:42:52.637   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:42:52.637  5870  5870 D ObexServerSockets: Succeed to create listening sockets 
08-29 10:42:52.637  5724  5734 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:42:52.637  5870  5870 D ObexServerSockets0: startAccept()
08-29 10:42:52.637  5870  5870 D ObexServerSockets0: prepareForNewConnect()
,08-29 10:42:52.639  3143  3156 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:42:52.639  5870  5870 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 10:42:52.639  5870  5870 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 10:42:52.639  5870  5908 D ObexServerSockets0: Accepting socket connection...
08-29 10:42:52.640  5870  5909 D ObexServerSockets0: Accepting socket connection...
08-29 10:42:52.641  3143  3143 D BluetoothMap: Proxy object connected
08-29 10:42:52.641  3143  3143 D MapProfile: Bluetooth service connected
08-29 10:42:52.641  3143  3143 D BluetoothMap: getConnectedDevices()
08-29 10:42:52.641  5724  5724 D BluetoothMap: Proxy object connected
08-29 10:42:52.641  5724  5724 D MapProfile: Bluetooth service connected
08-29 10:42:52.641  5724  5724 D BluetoothMap: getConnectedDevices()
08-29 10:42:52.642  3143  3157 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 10:42:52.643  5724  5724 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:42:52.643  5724  5724 D PanProfile: Bluetooth service connected
08-29 10:42:52.643  5724  5724 D BluetoothInputDevice: Proxy object connected
08-29 10:42:52.643  5724  5724 D HidProfile: Bluetooth service connected
08-29 10:42:52.643  3143  3143 D BluetoothInputDevice: Proxy object connected
08-29 10:42:52.644  3143  3156 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:42:52.644  3143  3143 D HidProfile: Bluetooth service connected
08-29 10:42:52.645   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:42:52.645  3143  3157 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:42:52.645  3143  3143 D BluetoothA2dp: Proxy object connected
08-29 10:42:52.646  3143  3143 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:42:52.647  3143  3143 D PanProfile: Bluetooth service connected
08-29 10:42:52.647   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 10:42:52.648  5870  5870 D BluetoothMapService: onReceive
08-29 10:42:52.648  5870  5870 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:42:52.648  5870  5870 D BluetoothMapService: STATE_ON
08-29 10:42:52.650  5870  5911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:42:52.650  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:52.651  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:42:52.651  5870  5911 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 10:42:52.651  5870  5911 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 10:42:52.653  5724  5724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:42:52.658  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:42:52.660  5724  5724 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:42:52.662  5724  5724 D BluetoothPbap: Proxy object connected
08-29 10:42:52.662  5724  5724 D PbapServerProfile: Bluetooth service connected
08-29 10:42:52.663  5870  5913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:42:52.673  5870  5870 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 10:42:52.673  5870  5870 D ObexServerSockets0: prepareForNewConnect()
,08-29 10:42:52.676  3143  3143 D BluetoothPbap: Proxy object connected
,08-29 10:42:52.676  3143  3143 D PbapServerProfile: Bluetooth service connected
,08-29 10:42:52.678  5870  5919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:42:52.679  5870  5919 I BtOppRfcommListener: Accept thread started.
,08-29 10:42:52.727  5724  5735 D BluetoothHeadset: Proxy object connected
08-29 10:42:52.728  3526  3551 D BluetoothHeadset: Proxy object connected
,08-29 10:42:52.728   932   932 D BluetoothHeadset: Proxy object connected
,08-29 10:42:52.728   932   932 D BluetoothHeadset: Proxy object connected
08-29 10:42:52.728   932   932 D BluetoothHeadset: Proxy object connected
08-29 10:42:52.728  3143  3157 D BluetoothHeadset: Proxy object connected
08-29 10:42:52.728  3143  3143 D HeadsetProfile: Bluetooth service connected
08-29 10:42:52.729  5724  5724 D HeadsetProfile: Bluetooth service connected
,08-29 10:42:52.732  3526  3763 D BluetoothHeadset: Proxy object connected
,08-29 10:42:52.735  3143  3156 D BluetoothHeadset: Proxy object connected
,08-29 10:42:52.735  3143  3143 D HeadsetProfile: Bluetooth service connected
,08-29 10:42:52.737   932   949 D BluetoothHeadset: Proxy object connected
,08-29 10:42:52.746   932   949 D BluetoothHeadset: Proxy object connected
,08-29 10:42:52.845   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:53.845   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:54.846   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:55.847   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:42:56.482  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:42:56.486  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:42:56.487  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:42:56.489  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e7ffe2 removed from the list
08-29 10:42:56.489  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:42:56.489  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:42:56.489  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:42:56.492  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:42:56.492  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18aff73 added. We now have 4 listener(s)
08-29 10:42:56.492  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:42:56.494   932  3432 D WifiService: setWifiEnabled: false pid=5620, uid=10077
,08-29 10:42:56.495   932  3432 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:42:56.848   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:43:01.503  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:43:01.504   932   942 D WifiService: setWifiEnabled: true pid=5620, uid=10077
08-29 10:43:01.504   932   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:43:01.513   512   926 D SoftapController: Softap fwReload - Ok
,08-29 10:43:01.517   512   926 D CommandListener: Setting iface cfg
,08-29 10:43:01.518   512   926 D CommandListener: Trying to bring down wlan0
08-29 10:43:01.519   512   926 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:43:01.523   932  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 10:43:02.195   932  2976 D wifi    : set interface wlan0 flags (UP)
,08-29 10:43:02.201   932  2976 I WifiHAL : Initializing wifi
08-29 10:43:02.201   932  2976 I WifiHAL : Creating socket
,08-29 10:43:02.205   932  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 10:43:02.206   932  2976 D wifi    : Did set static halHandle = 0x7f90f31080
,08-29 10:43:02.206   932  2976 D wifi    : halHandle = 0x7f90f31080, mVM = 0x7fac50d140, mCls = 0x20158e
,08-29 10:43:02.206   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 10:43:02.206   932  2976 D wifi    : array field set
,08-29 10:43:02.206   932  2976 I WifiNative-HAL: interface[0] = wlan0
08-29 10:43:02.208   932  5924 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547892695168
08-29 10:43:02.209   932  5924 D wifi    : waitForHalEvents called, vm = 0x7fac50d140, obj = 0x20158e, env = 0x7f9163df00
,08-29 10:43:02.264  5925  5925 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 10:43:02.284  5925  5925 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:43:02.310   932  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 10:43:02.315  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:43:02.316  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:43:02.331  5925  5925 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 10:43:02.331  5925  5925 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 10:43:02.357   932  2976 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:43:02.360  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:43:02.363  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:43:02.364   932  2976 D WifiConfigStore: loaded 0 passpoint configs
08-29 10:43:02.364   932  2976 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:43:02.365   932  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 10:43:02.366   932  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:43:02.366   932  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 10:43:02.366   932  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:43:02.366  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:43:02.369  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:43:02.371   932  2976 D WifiNative-HAL: Setting external_sim to 1
,08-29 10:43:02.371   932  2976 D wifi    : setting dfs flag to true, 0x7f91d3f780
,08-29 10:43:02.372  4250  4250 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:43:02.372   932  2976 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:43:02.372   932  2976 D wifi    : setting scan oui 0x7f91d3f780
08-29 10:43:02.372   932  2976 D WifiHAL : Sending mac address OUI
,08-29 10:43:02.392   932  2976 E native  : do suspend true
,08-29 10:43:02.400   932  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 10:43:02.400   932   932 D RttService: SCAN_AVAILABLE : 3
08-29 10:43:02.400   512   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 10:43:02.400   932  3084 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:43:02.401   512   926 D CommandListener: Setting iface cfg
,08-29 10:43:02.408   932  2975 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '98 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 98 Failed to set address (No such device)'
08-29 10:43:02.408   932  2975 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 10:43:02.411   932  2975 D WifiNative-HAL: p2pGetDeviceAddress
08-29 10:43:02.411   932  2975 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 10:43:02.444   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=251186 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=27 mControllerEnergyUsed=102 }
,08-29 10:43:05.646  5925  5925 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 10:43:05.677   932  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 10:43:05.684   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-29 10:43:05.686   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:43:05.702   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 10:43:05.741   932  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 10:43:06.078  5925  5925 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:43:06.113  5925  5925 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:43:06.114  5925  5925 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 10:43:06.124   932  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:43:06.125   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:43:06.125   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 10:43:06.140   932  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:43:06.153   512   926 D CommandListener: Setting iface cfg
,08-29 10:43:06.159   932  2976 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 10:43:06.167   932  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 10:43:06.200   932  5930 D DhcpClient: Receive thread started
,08-29 10:43:06.284   932  2976 E native  : do suspend false
,08-29 10:43:06.300   932  5929 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 10:43:06.313   932  5930 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172724, domain null
,08-29 10:43:06.314   932  5929 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172724 seconds
,08-29 10:43:06.316   932  5929 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 10:43:06.328   932  5930 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 10:43:06.329   932  5929 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-29 10:43:06.332   512   926 D CommandListener: Setting iface cfg
08-29 10:43:06.341   932  5929 D DhcpClient: Scheduling renewal in 86399s
08-29 10:43:06.341   932  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-29 10:43:06.344   932  2976 E native  : do suspend true
,08-29 10:43:06.362   932  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 10:43:06.366   932  2976 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 10:43:06.367   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 10:43:06.371   932  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 10:43:06.376   932  2978 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 10:43:06.419   932  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 10:43:06.419   932  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 10:43:06.421   932  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 10:43:06.422   932  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 10:43:06.424   932  2978 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 10:43:06.434   932  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 10:43:06.438   932  2978 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 10:43:06.438   932  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 10:43:06.439   932  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 10:43:06.439   932  2978 D ConnectivityService:    accepting network in place of null
08-29 10:43:06.439   932  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 10:43:06.439   932  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:43:06.439   932  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:43:06.448   932  5928 D NetlinkSocketObserver: NeighborEvent{elapsedMs=255190, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:43:06.463   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:43:06.484   512   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:43:06.487   932  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 10:43:06.487   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:43:06.487  3498  3707 W QCNEJ   : |CORE| network available: 102
,08-29 10:43:06.488   932  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 10:43:06.489   932   949 D Tethering: MasterInitialState.processMessage what=3
,08-29 10:43:06.493  3498  3707 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,08-29 10:43:06.496  3498  3707 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-29 10:43:06.496  3498  3707 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:06.501  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:43:06.503  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:06.504  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:06.508  5620  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:43:06.509  4834  4867 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-29 10:43:06.509  4834  4867 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:43:06.509  4834  4867 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 10:43:06.509  4834  4867 E SarControlService: no key has been found,reset the power
08-29 10:43:06.509  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 10:43:06.509  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 10:43:06.510  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 10:43:06.510  5620  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:06.510  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:43:06.510  4872  4872 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 10:43:06.511  4834  4881 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:43:06.511  4834  4881 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 10:43:06.511  4834  4881 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 10:43:06.512  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:43:06.512  4872  4872 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,08-29 10:43:06.514  3828  3828 D SystemUpdateService: onCreate
,08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:06.518  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:43:06.518  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:43:06.519  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000f003000000000000ffffffff]
,08-29 10:43:06.519  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:43:06.519  4872  4889 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
08-29 10:43:06.520  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:43:06.520  4834  4845 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 10:43:06.520  4872  4889 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fac9ee6 HexData = [00000000f103000000000000ffffffff]
08-29 10:43:06.520  4872  4889 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:43:06.520  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:06.520  4872  4889 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
08-29 10:43:06.521  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:06.521  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18aff73 removed from the list
08-29 10:43:06.521  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:43:06.521  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:06.521  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:06.521  4872  4872 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:43:06.522  4834  4844 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 10:43:06.525  5620  5941 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-29 10:43:06.525  5620  5941 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 10:43:06.528   932  5927 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:810::200e
,08-29 10:43:06.532  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 10:43:06.539  3828  5940 I SystemUpdateService: active receiver: enabled
,08-29 10:43:06.540  3828  5235 I iu.UploadsManager: num queued entries: 0
,08-29 10:43:06.540  3828  5235 I iu.UploadsManager: num updated entries: 0
08-29 10:43:06.541  3828  5235 I iu.SyncManager: NEXT; no task
,08-29 10:43:06.543  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:43:06.544  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
08-29 10:43:06.545  5239  5239 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:43:06.549  5239  5239 D SprintDMHelper: simOperator: 
08-29 10:43:06.549  5239  5239 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:43:06.581  3828  5940 I SystemUpdateService: showing system update notification
,08-29 10:43:06.587  3828  5940 V SystemUpdateService: retry (wakeup: false) in 3599953 ms
,08-29 10:43:06.589  3828  3828 D SystemUpdateService: onDestroy
,08-29 10:43:06.598   932  5927 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:43:06 GMT], X-Android-Received-Millis=[1472481786597], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472481786560]}
,08-29 10:43:06.598   932  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 10:43:06.598   932  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-29 10:43:06.599   932  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 10:43:06.599   932  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 10:43:06.667  4250  5945 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 10:43:06.849   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:07.488   932  2978 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 10:43:07.850   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:08.851   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:09.535  5620  5941 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-29 10:43:09.536  5620  5941 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 10:43:09.537  5620  5941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:43:09.538  5620  5941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 10:43:09.539  5620  5953 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-29 10:43:09.539  5620  5953 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-29 10:43:09.540  5620  5941 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 10:43:09.542  5620  5953 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 10:43:09.543  5620  5955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Sender)
,08-29 10:43:09.545  5620  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
,08-29 10:43:09.547  5620  5953 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:43:09.548  5620  5956 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
,08-29 10:43:09.548  5620  5956 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 10:43:09.549  5620  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 10:43:09.549  5620  5953 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-29 10:43:09.550  5620  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Receiver)
08-29 10:43:09.555  5620  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: IncomingSocketThread/Receiver)
08-29 10:43:09.556  5620  5958 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-29 10:43:09.556  5620  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-29 10:43:09.549  5620  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Sender)
,08-29 10:43:09.852   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:10.853   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:11.853   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:43:12.532  5620  5666 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 10:43:12.533  5620  5666 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 10:43:12.540  5620  5666 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9082a35 Bundle[{}]
,08-29 10:43:12.541  5620  5666 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 10:43:12.541  5620  5666 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 10:43:12.541  5620  5666 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 10:43:12.542  5620  5666 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 10:43:12.542  5620  5666 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 10:43:12.543  5620  5666 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 10:43:12.548  5620  5666 I System.out: Running OutgoingSocketThread
,08-29 10:43:12.551  5620  5959 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-29 10:43:12.551  5620  5959 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 10:43:14.446   932  2978 D ConnectivityService: handlePromptUnvalidated 102
,08-29 10:43:15.561  5620  5960 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-29 10:43:15.561  5620  5959 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-29 10:43:15.561  5620  5960 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 10:43:15.561  5620  5959 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-29 10:43:15.561  5620  5960 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:43:15.561  5620  5959 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 10:43:15.563  5620  5960 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
08-29 10:43:15.563  5620  5959 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 10:43:15.566  5620  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
,08-29 10:43:15.569  5620  5960 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 10:43:15.570  5620  5959 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 10:43:15.574  5620  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: OutgoingSocketThread/Sender)
,08-29 10:43:15.576  5620  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Receiver)
,08-29 10:43:15.577  5620  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Receiver)
08-29 10:43:15.578  5620  5964 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: IncomingSocketThread/Receiver)
08-29 10:43:15.578  5620  5964 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-29 10:43:15.578  5620  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-29 10:43:15.578  5620  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: OutgoingSocketThread/Receiver)
08-29 10:43:15.579  5620  5965 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 10:43:15.579  5620  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 10:43:18.560  5620  5666 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
08-29 10:43:18.561  5620  5666 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 10:43:18.562  5620  5666 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 179)
08-29 10:43:18.566  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:43:18.566  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f5fe30 added. We now have 3 listener(s)
,08-29 10:43:18.571  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:43:18.571  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:43:18.571  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:43:18.571  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:43:18.572  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500aa9 added. We now have 4 listener(s)
08-29 10:43:18.572  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:43:18.573  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:43:18.578  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:18.584  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:43:18.587  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:43:18.587  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:43:18.589  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:43:18.589  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:43:18.589  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:43:18.589  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:18.589  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:18.590  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:43:18.590  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:43:18.590  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f5fe30 removed from the list
08-29 10:43:18.590  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:18.590  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500aa9 removed from the list
,08-29 10:43:18.592  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:43:18.595  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:43:18.595  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:43:18.596  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:18.596  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:43:18.596  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:18.598  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:18.598  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:18.598  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:18.598  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500aa9 not in the list
08-29 10:43:18.598  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:18.598  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:18.599  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:18.600  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:18.600  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:18.600  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500aa9 not in the list
08-29 10:43:18.600  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:18.600  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:18.600  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:18.600  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f5fe30 not in the list
08-29 10:43:18.601  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:43:18.601  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0c1fcf added. We now have 3 listener(s)
,08-29 10:43:18.603  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:43:18.603  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:43:18.603  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:43:18.603  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:43:18.603  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4cd5c added. We now have 4 listener(s)
08-29 10:43:18.603  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:43:18.604  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:43:18.607  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:18.612  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:43:18.614  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:18.614  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:43:18.614  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:43:18.614  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 10:43:18.614  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:43:18.614  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:43:18.614  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:43:18.617  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:43:18.618  5620  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:43:18.619  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:43:18.620  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:43:18.623  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:43:18.624  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:43:18.624  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:43:18.629  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:43:18.629  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 10:43:18.629  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:43:18.630  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:43:18.632  5870  5900 D BtGatt.GattService: registerClient() - UUID=6d15df8b-9b1c-430a-b55d-b548d9ec938e
,08-29 10:43:18.634  5870  5886 D BtGatt.GattService: onClientRegistered() - UUID=6d15df8b-9b1c-430a-b55d-b548d9ec938e, clientIf=5
,08-29 10:43:18.635  5620  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 10:43:18.636  5870  5880 D BtGatt.GattService: start scan with filters
,08-29 10:43:18.640  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:43:18.640  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:43:18.640  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:43:18.640  5870  5889 D BtGatt.ScanManager: handling starting scan
08-29 10:43:18.641  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:43:18.644  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:43:18.644  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:43:18.644  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:43:18.646  5870  5889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c2f0f79
08-29 10:43:18.646  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 10:43:18.648  5620  5666 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:43:18.649  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:43:18.649  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:43:18.649  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:18.649  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:43:18.649  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:43:18.649  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:43:18.649  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:43:18.649  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:43:18.649  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:43:18.649  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:43:18.650  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:43:18.651  5870  5880 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:43:18.652  5870  5881 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:43:18.652  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:43:18.652  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:43:18.652  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:43:18.652  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:43:18.652  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:43:18.653  5870  5886 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:43:18.653  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:43:18.654  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:43:18.654  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:43:18.654  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:43:18.654  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:43:18.654  5870  5889 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 10:43:18.654  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:43:18.656  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:43:18.656  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:43:18.656  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:43:18.660  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 10:43:18.660  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:43:18.661  5870  5889 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:43:18.661  5870  5889 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:43:18.671  5870  5886 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 10:43:18.671  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:43:18.676  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:43:18.676  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:43:18.683  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 10:43:18.684  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:43:18.684  5870  5889 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:43:18.690  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:43:18.690  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:43:18.690  5870  5889 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:43:18.696  5870  5886 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 10:43:18.696  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:43:19.158  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:43:19.158  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:43:19.158  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:43:21.656  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:43:21.657  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:43:21.657  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:43:21.657  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:21.658  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:21.658  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:43:21.658  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:43:21.658  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0c1fcf removed from the list
08-29 10:43:21.658  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:21.659  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4cd5c removed from the list
08-29 10:43:21.659  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:43:21.659  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:21.660  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:21.660  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:21.663  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:21.663  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:21.663  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:43:21.663  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4cd5c not in the list
08-29 10:43:21.663  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:21.663  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:21.667  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:43:21.667  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:21.668  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:21.669  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4cd5c not in the list
,08-29 10:43:21.669  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:21.669  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:21.669  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:21.669  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0c1fcf not in the list
08-29 10:43:21.671  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:43:21.671  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9d65e1 added. We now have 3 listener(s)
08-29 10:43:21.673  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:43:21.673  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:43:21.673  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:43:21.673  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:43:21.674  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4151f06 added. We now have 4 listener(s)
08-29 10:43:21.674  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:43:21.674  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:43:21.678  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:21.683  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:43:21.685  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:21.685  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:43:21.685  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 10:43:21.687  5620  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
08-29 10:43:21.687  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-29 10:43:21.688  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 10:43:21.689  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:43:21.689  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 10:43:21.689  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:43:21.689  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:43:21.690  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 10:43:21.693  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 10:43:21.694  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:43:21.694  5620  5966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:43:21.695  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:43:21.695  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 10:43:21.695  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:43:21.695  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 10:43:21.695  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:43:21.695  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:43:21.697  5620  5966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 10:43:21.699  5620  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:43:21.699  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:43:21.702  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:43:21.703  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:43:21.703  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:43:21.705  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 10:43:21.705  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:43:21.705  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
08-29 10:43:21.705  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 10:43:21.705  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-29 10:43:21.705  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 10:43:21.706  5620  5666 D BluetoothAdapter: STATE_ON
,08-29 10:43:21.709  5870  5900 D BtGatt.GattService: registerClient() - UUID=3aca71af-4e1f-4b7d-97d5-d870b45a97c6
,08-29 10:43:21.709  5870  5886 D BtGatt.GattService: onClientRegistered() - UUID=3aca71af-4e1f-4b7d-97d5-d870b45a97c6, clientIf=5
08-29 10:43:21.709  5620  5630 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 10:43:21.711  5870  5888 D BtGatt.AdvertiseManager: message : 0
,08-29 10:43:21.713  5870  5888 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 10:43:21.724  5870  5886 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 10:43:21.730  5870  5886 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 10:43:21.730  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 10:43:21.730  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:43:21.732  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:43:21.733  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 10:43:21.733  5620  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 10:43:21.733  5620  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 10:43:21.733  5620  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 10:43:21.733  5620  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 10:43:21.733  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-29 10:43:21.735  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 10:43:21.736  5620  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 10:43:21.736  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 10:43:22.237  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 10:43:22.238  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 10:43:22.238  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:43:24.736  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:43:24.736  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 10:43:24.737  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:43:24.737  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 10:43:24.737  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:43:24.737  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 10:43:24.738  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:43:24.738  5620  5966 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 10:43:24.738  5620  5966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 10:43:24.738  5620  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 10:43:24.738  5620  5966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:43:24.738  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:43:24.739  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:43:24.739  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:43:24.739  5620  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 10:43:24.739  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:43:24.739  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:43:24.741  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:43:24.741  5620  5666 D BluetoothLeScanner: could not find callback wrapper
,08-29 10:43:24.742  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:43:24.742  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 10:43:24.743  5870  5888 D BtGatt.AdvertiseManager: message : 1
08-29 10:43:24.744  5870  5888 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 10:43:24.754  5870  5886 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 10:43:24.754  5870  5886 D BtGatt.GattService: Client app is not null!
,08-29 10:43:24.755  5870  5900 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:43:24.755  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 10:43:24.755  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 10:43:24.756  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 10:43:24.756  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 10:43:24.756  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 10:43:24.757  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:43:24.758  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:43:24.758  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:43:24.758  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:43:24.760  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:24.760  5620  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:43:24.760  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:24.760  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:43:24.760  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:43:24.760  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:43:24.760  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:43:24.760  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9d65e1 removed from the list
08-29 10:43:24.761  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:43:24.761  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:24.761  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4151f06 removed from the list
08-29 10:43:24.761  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:43:24.761  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:24.762  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:24.762  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:24.763  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:24.763  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:24.763  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:43:24.763  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4151f06 not in the list
08-29 10:43:24.763  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:24.763  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:24.764  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:24.764  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:24.764  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:24.764  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4151f06 not in the list
08-29 10:43:24.765  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:24.765  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:24.765  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:24.765  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9d65e1 not in the list
,08-29 10:43:24.766  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:43:24.766  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32ab63 added. We now have 3 listener(s)
08-29 10:43:24.769  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:43:24.769  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:43:24.769  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:43:24.769  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:43:24.769  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d5360 added. We now have 4 listener(s)
08-29 10:43:24.769  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:43:24.770  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:43:24.773  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:24.776  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:43:24.778  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:24.779  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:43:24.779  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:43:24.779  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:43:24.779  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:43:24.779  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:43:24.779  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:43:24.782  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:43:24.783  5620  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:43:24.783  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:43:24.785  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:43:24.787  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:43:24.788  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:43:24.789  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:43:24.792  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:43:24.792  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:43:24.792  5620  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:43:24.793  5620  5666 D BluetoothAdapter: STATE_ON
08-29 10:43:24.795  5870  5898 D BtGatt.GattService: registerClient() - UUID=ccac3d60-5eee-4036-98ca-2180b2a706be
08-29 10:43:24.796  5870  5886 D BtGatt.GattService: onClientRegistered() - UUID=ccac3d60-5eee-4036-98ca-2180b2a706be, clientIf=5
,08-29 10:43:24.796  5620  5630 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:43:24.796  5870  5900 D BtGatt.GattService: start scan with filters
08-29 10:43:24.799  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:43:24.799  5870  5889 D BtGatt.ScanManager: handling starting scan
08-29 10:43:24.799  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:43:24.800  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:43:24.800  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:43:24.802  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:43:24.803  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:43:24.803  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:43:24.804  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:43:24.807  5870  5886 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:43:24.807  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:43:24.807  5870  5889 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:43:24.812  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 10:43:24.812  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:43:24.812  5870  5889 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 10:43:24.812  5870  5889 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:43:24.821  5870  5886 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:43:24.821  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:43:24.827  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 10:43:24.827  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:43:25.262  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:43:25.304  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 10:43:25.304  5620  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:43:25.304  5620  5620 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:43:26.854   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:27.813  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:43:27.813  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:43:27.814  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:43:27.814  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:27.814  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:43:27.814  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:43:27.814  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:43:27.814  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:43:27.815  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:43:27.815  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:43:27.815  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:43:27.816  5620  5666 D BluetoothAdapter: STATE_ON
,08-29 10:43:27.819  5870  5910 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:43:27.820  5870  5898 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 10:43:27.821  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:43:27.822  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:43:27.822  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:43:27.822  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:43:27.822  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:43:27.824  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:43:27.824  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:43:27.824  5620  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:43:27.825  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:43:27.826  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:43:27.831  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:43:27.831  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:43:27.831  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:27.832  5620  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:43:27.832  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:43:27.832  5620  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:43:27.832  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:43:27.832  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32ab63 removed from the list
08-29 10:43:27.832  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:27.832  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d5360 removed from the list
,08-29 10:43:27.832  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:43:27.832  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:27.836  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:27.836  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:27.838  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:43:27.838  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:27.838  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:27.838  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d5360 not in the list
,08-29 10:43:27.838  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:43:27.838  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:27.838  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 10:43:27.838  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:43:27.839  5870  5889 D BtGatt.ScanManager: stopping BLe Batch
08-29 10:43:27.841  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:27.841  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:27.841  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:27.841  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d5360 not in the list
08-29 10:43:27.841  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:27.841  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:27.841  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:27.841  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32ab63 not in the list
,08-29 10:43:27.842  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:43:27.842  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ba74d5 added. We now have 3 listener(s)
08-29 10:43:27.844  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:43:27.844  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:43:27.844  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:43:27.845  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:43:27.845  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bad4ea added. We now have 4 listener(s)
08-29 10:43:27.845  5620  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:43:27.846  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:43:27.846  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:43:27.846  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:43:27.847  5870  5889 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:43:27.850  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:43:27.852  5870  5870 D BtGatt.ScanManager: awakened up at time 276594
08-29 10:43:27.855   540   540 I ServiceManager: Waiting for service AtCmdFwd...
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:43:27.856  5620  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:43:27.861  5620  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:43:27.861  5620  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:43:27.862  5620  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:43:27.862  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:43:27.862  5620  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:43:27.862  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:27.862  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:27.862  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:43:27.862  5620  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:43:27.862  5620  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ba74d5 removed from the list
08-29 10:43:27.862  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:27.862  5620  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bad4ea removed from the list
,08-29 10:43:27.866  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:43:27.866  5620  5666 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:43:27.867  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:27.868  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:43:27.869  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:43:27.870  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:43:27.870  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:43:27.870  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:27.871  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bad4ea not in the list
08-29 10:43:27.871  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:27.871  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:27.871  5870  5886 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-29 10:43:27.871  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:43:27.871  5870  5886 D BtGatt.GattService: current time is 276613994060
08-29 10:43:27.872  5870  5886 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -77, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -85, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 10:43:27.873  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 10:43:27.873  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:43:27.873  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:43:27.873  5620  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:43:27.873  5620  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bad4ea not in the list
08-29 10:43:27.873  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 10:43:27.873  5620  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:43:27.873  5620  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:43:27.873  5620  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:43:27.873  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 10:43:27.873  5620  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:43:27.873  5620  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ba74d5 not in the list
08-29 10:43:27.874  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 10:43:27.874  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 10:43:27.874  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 10:43:27.874  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 10:43:27.875  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 10:43:27.875  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:43:27.875  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 10:43:27.875  5620  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:43:27.878  3828  5967 I EventLogService: Aggregate from 1472479982282 (log), 1472479982282 (data)
,08-29 10:43:28.332  5620  5620 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:43:28.856   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:29.856   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:29.884  5620  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
,08-29 10:43:30.857   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:43:31.858   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:43:31.883  5620  5666 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 188
,08-29 10:43:31.884  5620  5666 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 188, name: My test thread name)
,08-29 10:43:31.887  5620  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name)
08-29 10:43:31.888  5620  5970 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: My test thread name)
08-29 10:43:31.889  5620  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-29 10:43:31.894  5620  5666 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:43:31.899  5620  5971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name)
,08-29 10:43:31.899  5620  5971 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 193, thread name: My test thread name): Test exception.
08-29 10:43:31.900  5620  5971 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-29 10:43:31.904  5620  5666 I jxcore-log: Total number of executed tests:  82
08-29 10:43:31.904  5620  5666 I jxcore-log: 
,08-29 10:43:31.904  5620  5666 I jxcore-log: Number of passed tests:  82
08-29 10:43:31.904  5620  5666 I jxcore-log: 
,08-29 10:43:31.905  5620  5666 I jxcore-log: Number of failed tests:  0
08-29 10:43:31.905  5620  5666 I jxcore-log: 
,08-29 10:43:31.905  5620  5666 I jxcore-log: Number of ignored tests:  0
08-29 10:43:31.905  5620  5666 I jxcore-log: 
08-29 10:43:31.907  5620  5666 I jxcore-log: Total duration:  105920
08-29 10:43:31.907  5620  5666 I jxcore-log: 
,08-29 10:43:31.909  5620  5666 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 10:43:31.909  5620  5666 I jxcore-log: 
,08-29 10:43:31.920  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.920  5620  5666 I jxcore-log: 
,08-29 10:43:31.928  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.928  5620  5666 I jxcore-log: 
,08-29 10:43:31.930  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.930  5620  5666 I jxcore-log: 
,08-29 10:43:31.932  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.932  5620  5666 I jxcore-log: 
,08-29 10:43:31.933  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.933  5620  5666 I jxcore-log: 
,08-29 10:43:31.935  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.935  5620  5666 I jxcore-log: 
,08-29 10:43:31.938  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.938  5620  5666 I jxcore-log: 
,08-29 10:43:31.941  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 10:43:31.941  5620  5666 I jxcore-log: 
08-29 10:43:31.942  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.942  5620  5666 I jxcore-log: 
08-29 10:43:31.943  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.943  5620  5666 I jxcore-log: 
08-29 10:43:31.943  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.943  5620  5666 I jxcore-log: 
08-29 10:43:31.944  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:43:31.944  5620  5666 I jxcore-log: 
08-29 10:43:31.945  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.945  5620  5666 I jxcore-log: 
,08-29 10:43:31.947  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 10:43:31.947  5620  5666 I jxcore-log: 
08-29 10:43:31.948  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.948  5620  5666 I jxcore-log: 
08-29 10:43:31.948  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 10:43:31.948  5620  5666 I jxcore-log: 
08-29 10:43:31.950  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:43:31.950  5620  5666 I jxcore-log: 
,08-29 10:43:31.951  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:43:31.951  5620  5666 I jxcore-log: 
,08-29 10:43:31.952  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.952  5620  5666 I jxcore-log: 
,08-29 10:43:31.953  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.953  5620  5666 I jxcore-log: 
08-29 10:43:31.954  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.954  5620  5666 I jxcore-log: 
08-29 10:43:31.954  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.954  5620  5666 I jxcore-log: 
08-29 10:43:31.955  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.955  5620  5666 I jxcore-log: 
08-29 10:43:31.955  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.955  5620  5666 I jxcore-log: 
08-29 10:43:31.956  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.956  5620  5666 I jxcore-log: 
08-29 10:43:31.956  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.956  5620  5666 I jxcore-log: 
08-29 10:43:31.957  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.957  5620  5666 I jxcore-log: 
,08-29 10:43:31.957  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.957  5620  5666 I jxcore-log: 
08-29 10:43:31.958  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.958  5620  5666 I jxcore-log: 
,08-29 10:43:31.959  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.959  5620  5666 I jxcore-log: 
,08-29 10:43:31.960  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.960  5620  5666 I jxcore-log: 
,08-29 10:43:31.961  5620  5969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
08-29 10:43:31.961  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.961  5620  5666 I jxcore-log: 
,08-29 10:43:31.963  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.963  5620  5666 I jxcore-log: 
08-29 10:43:31.964  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.964  5620  5666 I jxcore-log: 
,08-29 10:43:31.964  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.964  5620  5666 I jxcore-log: 
08-29 10:43:31.965  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.965  5620  5666 I jxcore-log: 
08-29 10:43:31.965  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.965  5620  5666 I jxcore-log: 
08-29 10:43:31.966  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.966  5620  5666 I jxcore-log: 
08-29 10:43:31.966  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.966  5620  5666 I jxcore-log: 
08-29 10:43:31.967  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.967  5620  5666 I jxcore-log: 
08-29 10:43:31.967  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.967  5620  5666 I jxcore-log: 
08-29 10:43:31.968  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:43:31.968  5620  5666 I jxcore-log: 
,08-29 10:43:31.969  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.969  5620  5666 I jxcore-log: 
,08-29 10:43:31.970  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:43:31.970  5620  5666 I jxcore-log: 
,08-29 10:43:31.971  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.971  5620  5666 I jxcore-log: 
08-29 10:43:31.972  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.972  5620  5666 I jxcore-log: 
08-29 10:43:31.973  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.973  5620  5666 I jxcore-log: 
08-29 10:43:31.973  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.973  5620  5666 I jxcore-log: 
08-29 10:43:31.973  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.973  5620  5666 I jxcore-log: 
08-29 10:43:31.974  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:43:31.974  5620  5666 I jxcore-log: 
,08-29 10:43:31.976  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.976  5620  5666 I jxcore-log: 
,08-29 10:43:31.977  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 10:43:31.977  5620  5666 I jxcore-log: 
,08-29 10:43:31.978  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.978  5620  5666 I jxcore-log: 
,08-29 10:43:31.979  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:43:31.979  5620  5666 I jxcore-log: 
08-29 10:43:31.980  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 10:43:31.980  5620  5666 I jxcore-log: 
08-29 10:43:31.981  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:43:31.981  5620  5666 I jxcore-log: 
08-29 10:43:31.982  5620  5666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:43:31.982  5620  5666 I jxcore-log: 
08-29 10:43:31.985  5620  5666 I jxcore-log: My device name is: Huawei-Nexus 6P
08-29 10:43:31.985  5620  5666 I jxcore-log: 
,08-29 10:43:32.326  5972  5972 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 10:43:32.331  5972  5972 D AndroidRuntime: CheckJNI is OFF
,08-29 10:43:32.359  5972  5972 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 10:43:32.391  5972  5972 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 10:43:32.407  5972  5972 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 10:43:32.415   932   945 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 10:43:32.416   932   945 I ActivityManager: Killing 5620:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 10:43:32.500   932  2977 D WifiService: Client connection lost with reason: 4
08-29 10:43:32.500   932  3155 D GraphicsStats: Buffer count: 2
,08-29 10:43:32.501   932  3431 I WindowState: WIN DEATH: Window{a24117b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 10:43:32.552   932   945 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 10:43:32.552   932   945 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 10:43:32.553   932   955 I art     : Starting a blocking GC Explicit
08-29 10:43:32.553   932   945 E ActivityManager: Failure starting process com.test.thalitest
08-29 10:43:32.553   932   945 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 10:43:32.553   932   945 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:43:32.553   932   945 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:43:32.553   932   945 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 10:43:32.553   932   945 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 10:43:32.556   932   945 I ActivityManager:   Force finishing activity ActivityRecord{42698e4 u0 com.test.thalitest/.MainActivity t4}
,08-29 10:43:32.566   932  3430 W ActivityManager: Spurious death for ProcessRecord{c1112ed 0:com.test.thalitest/u0a77}, curProc for 5620: null
,08-29 10:43:32.634   932   955 I art     : Explicit concurrent mark sweep GC freed 49962(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 1.667ms total 80.916ms
,08-29 10:43:32.655   932   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 10:43:32.657  5972  5972 I art     : System.exit called, status: 0
,08-29 10:43:32.658  5972  5972 I AndroidRuntime: VM exiting with result code 0.
,08-29 10:43:32.673   932   955 I ActivityManager: Start proc 5982:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-29 10:43:32.673   932   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 10:43:32.682   932   945 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 10:43:32.687  5870  5870 D BluetoothMapAppObserver: onReceive
08-29 10:43:32.688  5870  5870 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 10:43:32.689  3404  3404 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 10:43:32.692  3473  3902 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 10:43:32.699   932  2941 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 10:43:32.722  3404  5993 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 10:43:32.731  5338  5994 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 10:43:32.734  3526  3526 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 10:43:32.740  3629  3629 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-29 10:43:32.740  3629  3629 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 10:43:32.744  3404  5993 I Decoder : createOrResetDecoder
,08-29 10:43:32.757  3828  6001 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 10:43:32.758  3828  6001 D AccountUtils: Clearing selected account for com.test.thalitest
08-29 10:43:32.759   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 10:43:32.768   214   214 W kworker/3:3: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 10:43:32.789  3629  3629 I ConfigService: onCreate
,08-29 10:43:32.778   214   214 W kworker/3:3: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 10:43:32.810  3828  6001 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-29 10:43:32.798   214   214 W kworker/3:3: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 10:43:32.825  3828  6001 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:43:32.825  3828  6001 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:43:32.826  3828  6001 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 10:43:32.828  5338  5354 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj925A3A90E) - 
08-29 10:43:32.830  3404  5993 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 10:43:32.837  3828  6001 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-29 10:43:32.866  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-29 10:43:32.867  3828  3828 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 10:43:32.875  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 10:43:32.875  3828  3828 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-29 10:43:32.886   382   484 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
