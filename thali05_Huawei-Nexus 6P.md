#### Test 937653176a1f39f_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-17 05:01:35.250  5587  5634 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-17 05:01:35.299  3747  4954 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-17 05:01:35.358  5587  5634 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-17 05:01:35.382  3747  4954 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-17 05:01:35.422  5587  5634 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 05:01:35.585  3747  3747 I ConfigFetchService: fetch service done; releasing wakelock
11-17 05:01:35.588  3747  3747 I ConfigFetchService: stopping self
,11-17 05:01:36.362  5644  5644 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-17 05:01:36.368  5644  5644 D AndroidRuntime: CheckJNI is OFF
11-17 05:01:36.395  5644  5644 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-17 05:01:36.427  5644  5644 I Radio-JNI: register_android_hardware_Radio DONE
11-17 05:01:36.441  5644  5644 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-17 05:01:36.457   927  3876 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-17 05:01:36.525   927  3876 I ActivityManager: Start proc 5653:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-17 05:01:36.532  5644  5644 D AndroidRuntime: Shutting down VM
,11-17 05:01:36.868   927  3910 I WindowManager: Screenshot max retries 4 of Token{e4096bb ActivityRecord{d73c74a u0 com.test.thalitest/.MainActivity t6}} appWin=Window{485f5a2 u0 Starting com.test.thalitest} drawState=4
,11-17 05:01:36.967  5653  5653 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-17 05:01:37.006  5653  5653 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-17 05:01:37.081  5653  5653 I LibraryLoader: Time to load native libraries: 71 ms (timestamps 3406-3477)
,11-17 05:01:37.081  5653  5653 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 05:01:37.121  5653  5653 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cadf604}
11-17 05:01:37.122  5653  5653 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 05:01:37.122  5653  5653 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-17 05:01:37.129  5653  5653 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-17 05:01:37.131  5653  5653 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-17 05:01:37.181  5653  5653 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-17 05:01:37.196  5653  5653 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-17 05:01:37.197  5653  5653 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 05:01:37.197  5653  5653 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-17 05:01:37.197  5653  5653 I Adreno  : Build Date                       : 12/06/15
11-17 05:01:37.197  5653  5653 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-17 05:01:37.197  5653  5653 I Adreno  : Local Branch                     : mybranch17112971
11-17 05:01:37.197  5653  5653 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-17 05:01:37.197  5653  5653 I Adreno  : Remote Branch                    : NONE
11-17 05:01:37.197  5653  5653 I Adreno  : Reconstruct Branch               : NOTHING
,11-17 05:01:37.256   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e3496fa:true
,11-17 05:01:37.286   951   951 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26244]" dev="sockfs" ino=26244 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 05:01:37.286   951   951 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[26244]" dev="sockfs" ino=26244 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 05:01:37.300  5653  5653 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-17 05:01:37.309  5653  5653 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-17 05:01:37.339   951   951 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32858]" dev="sockfs" ino=32858 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 05:01:37.339   951   951 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32858]" dev="sockfs" ino=32858 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-17 05:01:37.341  5653  5690 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-17 05:01:37.343  3596  3596 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15133]" dev="sockfs" ino=15133 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-17 05:01:37.343  3596  3596 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15133]" dev="sockfs" ino=15133 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-17 05:01:37.348  5653  5677 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-17 05:01:37.384  5653  5690 I OpenGLRenderer: Initialized EGL, version 1.4
,11-17 05:01:37.468   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +596ms (total +976ms)
,11-17 05:01:37.519  5653  5653 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5653
,11-17 05:01:37.617  5653  5653 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 05:01:37.908  5653  5692 D jxcore_app_log: JniHelper::setJavaVM(0xf517c000), pthread_self() = -563873488
,11-17 05:01:37.927  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-17 05:01:37.927  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-17 05:01:37.927  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-17 05:01:37.927  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-17 05:01:37.927  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-17 05:01:37.928  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53ac165 added. We now have 1 listener(s)
,11-17 05:01:37.934  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-17 05:01:37.937  5653  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 05:01:37.939  5653  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:01:37.940  5653  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-17 05:01:37.945  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b0ee1 added. We now have 1 listener(s)
,11-17 05:01:37.946  5653  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 05:01:37.951   927  2986 D WifiService: New client listening to asynchronous messages
,11-17 05:01:37.952  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 05:01:37.952  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-17 05:01:37.953  5653  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-17 05:01:37.953  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-17 05:01:37.953  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-17 05:01:37.953  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-17 05:01:37.953  5653  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-17 05:01:37.956  5653  5692 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-17 05:01:38.246  5653  5653 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-17 05:01:38.711  5653  5699 W jxcore-log: Initializing JXcore engine
,11-17 05:01:38.711  5653  5699 W jxcore-log: JXcore engine is ready
,11-17 05:01:38.743  5699  5699 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11734 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-17 05:01:38.743  5699  5699 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12013]" dev="sockfs" ino=12013 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 05:01:38.743  5699  5699 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-17 05:01:38.743  5699  5699 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32134]" dev="sockfs" ino=32134 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-17 05:01:38.752  5653  5699 W jxcore-log: Starting JXcore engine
,11-17 05:01:38.803  5653  5699 W jxcore-log: Platform android
11-17 05:01:38.803  5653  5699 W jxcore-log: 
,11-17 05:01:38.803  5653  5699 W jxcore-log: Process ARCH arm
11-17 05:01:38.803  5653  5699 W jxcore-log: 
,11-17 05:01:38.939  5653  5699 I jxcore-log: JXcore Cordova bridge is ready!
11-17 05:01:38.939  5653  5699 I jxcore-log: 
,11-17 05:01:38.939  5653  5699 W jxcore-log: JXcore engine is started
,11-17 05:01:38.949  5653  5692 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-17 05:01:38.958  5653  5653 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-17 05:01:40.603  3582  3582 I ConfigService: onDestroy
,11-17 05:01:48.127   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-17 05:01:48.128   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-17 05:01:48.716  5653  5699 I jxcore-log: 2016-11-17 10:01:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-17 05:01:48.716  5653  5699 I jxcore-log: 
,11-17 05:01:48.717  5653  5699 I jxcore-log: 2016-11-17 10:01:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-17 05:01:48.717  5653  5699 I jxcore-log: 
,11-17 05:01:48.723  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:01:48.724  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-17 05:01:48.728  5653  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 05:01:48.731  5653  5699 I jxcore-log: 2016-11-17 10:01:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-17 05:01:48.731  5653  5699 I jxcore-log: 
,11-17 05:01:48.732  5653  5699 I jxcore-log: 2016-11-17 10:01:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-17 05:01:48.732  5653  5699 I jxcore-log: 
,11-17 05:01:48.753  4838  4883 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-17 05:01:48.754  4838  4838 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-17 05:01:48.981  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 05:01:48.981  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3875d9 added. We now have 2 listener(s)
11-17 05:01:48.982  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:01:48.982  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:01:48.982  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-17 05:01:48.982  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:01:48.982  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c87b9e added. We now have 2 listener(s)
11-17 05:01:48.982  5653  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 05:01:48.983  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-17 05:01:48.984  5653  5699 D ExecuteNativeTests: Running unit tests
,11-17 05:01:48.985  5653  5699 D BluetoothAdapter: enable(): BT is already enabled..!
11-17 05:01:48.985   927  3170 D WifiService: setWifiEnabled: true pid=5653, uid=10077
,11-17 05:01:48.985   927  3170 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:01:53.129   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:01:54.130   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:01:54.761   927  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-17 05:01:55.132   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:01:56.133   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:01:57.135   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:01:58.136   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-17 05:01:58.561   927  5409 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-17 05:01:58.990  5653  5699 I com.test.thalitest.ThaliTestRunner: Running UT
,11-17 05:01:59.056  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 05:01:59.056  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eea9703 added. We now have 3 listener(s)
,11-17 05:01:59.057  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 05:01:59.057  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-17 05:01:59.057  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 05:01:59.057  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:01:59.057  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3376680 added. We now have 3 listener(s)
11-17 05:01:59.057  5653  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 05:01:59.058  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 05:01:59.062  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-17 05:01:59.063  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 05:01:59.063  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-17 05:01:59.063  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:01:59.063  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:01:59.064  5653  5699 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-17 05:01:59.064  5653  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-17 05:01:59.064  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-17 05:01:59.064  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-17 05:01:59.064  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-17 05:01:59.064  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:01:59.065  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-17 05:01:59.066  5653  5699 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-17 05:01:59.067  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-17 05:01:59.069  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-17 05:01:59.069  5653  5699 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-17 05:01:59.071  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:01:59.071  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:01:59.080  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-17 05:01:59.084  5653  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 05:01:59.084  5653  5699 D io.jxcore.node.ConnectivityMonitor: start: OK
11-17 05:01:59.085  5653  5699 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-17 05:01:59.085  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-17 05:01:59.086  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.086  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.086  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.086  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:01:59.086  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:01:59.086  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:01:59.088  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:01:59.088  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-17 05:01:59.090  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:01:59.090  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:01:59.090  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:01:59.090  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:01:59.090  5653  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 05:01:59.090  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:01:59.090  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:01:59.090  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-17 05:01:59.092  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:01:59.092  5653  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:01:59.092  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 05:01:59.094  5653  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 05:01:59.094  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-17 05:01:59.096  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.096  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-17 05:01:59.096  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-17 05:01:59.097  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:01:59.097  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:01:59.097  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-17 05:01:59.098  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.098  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.098  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:01:59.098  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:01:59.098  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:01:59.099  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-17 05:01:59.099  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:01:59.099  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:01:59.099  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.099  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:01:59.099  5653  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:01:59.099  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:01:59.100  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.100  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.100  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.100  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:01:59.102  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-17 05:01:59.099  4618  4618 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[26276]" dev="sockfs" ino=26276 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:01:59.104  4605  4823 D BtGatt.GattService: registerClient() - UUID=8b7f3507-7be1-4844-9898-2a63561d8d3a
11-17 05:01:59.099  4618  4618 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[26276]" dev="sockfs" ino=26276 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:01:59.105  4605  4660 D BtGatt.GattService: onClientRegistered() - UUID=8b7f3507-7be1-4844-9898-2a63561d8d3a, clientIf=5
,11-17 05:01:59.106  5653  5664 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-17 05:01:59.108  4605  4681 D BtGatt.AdvertiseManager: message : 0
,11-17 05:01:59.111  4605  4681 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:01:59.128  4605  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:01:59.136  4605  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:01:59.137  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.137  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.137  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:01:59.137  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.138  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.138  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.138  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.138  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.138  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:01:59.138  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-17 05:01:59.138  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.139  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.139  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.139  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.139  5653  5699 I io.jxcore.node.ConnectionHelper: start: OK
11-17 05:01:59.140  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:01:59.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:01:59.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:01:59.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.142  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:01:59.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:01:59.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:01:59.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.142  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:01:59.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.146  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.147  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-17 05:01:59.147  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.147  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.147  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.147  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:01:59.644  5653  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 05:01:59.644  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-17 05:01:59.644  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-17 05:01:59.644  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-17 05:01:59.644  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-17 05:01:59.644  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-17 05:01:59.644  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-17 05:01:59.645  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-17 05:01:59.646  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-17 05:01:59.647  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-17 05:01:59.647  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-17 05:01:59.647  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-17 05:01:59.647  5653  5699 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-17 05:01:59.647  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-17 05:01:59.647  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-17 05:01:59.647  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:01:59.647  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:01:59.648  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:01:59.648  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-17 05:01:59.648  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-17 05:01:59.648  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:01:59.648  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-17 05:01:59.648  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:01:59.648  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:01:59.649  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:01:59.649  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-17 05:01:59.649  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.650  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-17 05:01:59.650  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.650  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.650  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:01:59.650  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.650  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:01:59.652  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:01:59.652  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-17 05:01:59.653  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:01:59.653  5653  5699 D BluetoothLeScanner: could not find callback wrapper
11-17 05:01:59.653  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:01:59.653  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.653  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.654  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.654  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:01:59.654  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.655  4605  4681 D BtGatt.AdvertiseManager: message : 1
11-17 05:01:59.656  4605  4681 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:01:59.668  4605  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-17 05:01:59.669  4605  4660 D BtGatt.GattService: Client app is not null!
,11-17 05:01:59.671  4605  4618 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:01:59.672  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-17 05:01:59.672  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.672  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-17 05:01:59.673  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.673  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.673  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.673  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-17 05:01:59.673  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:01:59.674  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 05:01:59.674  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.677  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.677  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:01:59.677  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.677  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.678  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 05:01:59.686  4823  4823 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32874]" dev="sockfs" ino=32874 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:01:59.689  4823  4823 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32874]" dev="sockfs" ino=32874 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:01:59.678  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-17 05:01:59.679  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:01:59.679  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:01:59.679  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-17 05:01:59.680  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:01:59.680  5653  5699 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-17 05:01:59.680  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-17 05:01:59.680  5653  5699 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-17 05:01:59.680  5653  5699 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,11-17 05:01:59.680  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:01:59.680  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-17 05:01:59.680  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.680  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.680  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:01:59.680  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:01:59.680  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:01:59.680  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.681  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.681  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:01:59.681  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:01:59.681  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-17 05:01:59.681  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.681  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-17 05:01:59.681  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-17 05:01:59.681  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.682  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-17 05:01:59.682  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-17 05:01:59.682  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:01:59.683  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:01:59.683  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:01:59.683  5653  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-17 05:01:59.684  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.685  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.685  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.685  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.685  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:01:59.685  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:01:59.685  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-17 05:01:59.685  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-17 05:01:59.685  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:01:59.688  5653  5704 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:01:59.689  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:01:59.690  5653  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:01:59.690  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 05:01:59.690  5653  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-17 05:01:59.695  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.695  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:01:59.696  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:01:59.696  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:01:59.696  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-17 05:01:59.699  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.700  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.700  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-17 05:01:59.700  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:01:59.700  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:01:59.700  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-17 05:01:59.701  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:01:59.701  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:01:59.701  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.701  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-17 05:01:59.701  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:01:59.701  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.701  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.701  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.703  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:01:59.706  4605  4619 D BtGatt.GattService: registerClient() - UUID=84553c57-346d-43e7-b76b-aeedd3e9d118
11-17 05:01:59.706  4605  4660 D BtGatt.GattService: onClientRegistered() - UUID=84553c57-346d-43e7-b76b-aeedd3e9d118, clientIf=5
11-17 05:01:59.707  5653  5663 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-17 05:01:59.708  4605  4681 D BtGatt.AdvertiseManager: message : 0
,11-17 05:01:59.711  4605  4681 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:01:59.726  4605  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:01:59.732  4605  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:01:59.733  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.733  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.733  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-17 05:01:59.733  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.733  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.733  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.733  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.733  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.733  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-17 05:01:59.735  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-17 05:01:59.735  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.736  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.736  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.736  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:01:59.737  5653  5699 I io.jxcore.node.ConnectionHelper: start: OK
11-17 05:01:59.737  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:01:59.737  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.737  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-17 05:01:59.737  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:01:59.737  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.737  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.737  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:01:59.738  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.738  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:01:59.738  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:01:59.738  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.738  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.738  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:01:59.738  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 05:01:59.740  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.741  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-17 05:01:59.741  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.741  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.741  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:01:59.741  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:02:00.005   927   927 I ActivityManager: Killing 5005:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-17 05:02:00.240  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-17 05:02:00.240  5653  5699 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-17 05:02:00.240  5653  5699 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-17 05:02:00.240  5653  5699 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-17 05:02:00.240  5653  5699 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-17 05:02:00.240  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-17 05:02:00.241  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.241  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.241  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-17 05:02:00.241  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.242  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-17 05:02:00.242  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-17 05:02:00.242  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.242  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.242  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.243  4605  4681 D BtGatt.AdvertiseManager: message : 1
,11-17 05:02:00.243  4605  4681 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:02:00.250  4605  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-17 05:02:00.250  4605  4660 D BtGatt.GattService: Client app is not null!
,11-17 05:02:00.251  4605  4815 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 05:02:00.251  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 05:02:00.251  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.252  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.252  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:02:00.252  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-17 05:02:00.252  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:02:00.252  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
11-17 05:02:00.252  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-17 05:02:00.252  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:00.253  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.253  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:02:00.253  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:00.253  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.253  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.253  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.254  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:00.256  4605  4815 D BtGatt.GattService: registerClient() - UUID=9eea9de8-d040-4b65-a797-997e855a8c86
,11-17 05:02:00.256  4605  4660 D BtGatt.GattService: onClientRegistered() - UUID=9eea9de8-d040-4b65-a797-997e855a8c86, clientIf=5
11-17 05:02:00.256  5653  5664 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-17 05:02:00.258  4605  4681 D BtGatt.AdvertiseManager: message : 0
,11-17 05:02:00.261  4605  4681 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:02:00.270  4605  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:02:00.276  4605  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:02:00.276  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:00.276  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.276  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:02:00.276  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.276  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.276  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.276  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:00.277  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.277  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.277  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:02:00.277  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.277  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:02:00.277  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-17 05:02:00.277  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 05:02:00.277  5653  5699 I io.jxcore.node.ConnectionHelper: start: OK
,11-17 05:02:00.277  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.277  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:00.277  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:02:00.278  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.278  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.278  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:00.278  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.278  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:02:00.278  5653  5699 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 05:02:00.278  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:02:00.278  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-17 05:02:00.278  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-17 05:02:00.278  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-17 05:02:00.278  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.278  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:02:00.278  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:02:00.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:02:00.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-17 05:02:00.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-17 05:02:00.278  5653  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:02:00.278  5653  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:02:00.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:02:00.278  5653  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:02:00.278  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-17 05:02:00.278  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:02:00.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:02:00.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:02:00.278  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:02:00.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.280  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:00.280  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-17 05:02:00.280  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:00.280  5653  5699 D BluetoothLeScanner: could not find callback wrapper
11-17 05:02:00.280  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:02:00.280  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.281  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.281  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.281  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:02:00.281  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.281  4605  4681 D BtGatt.AdvertiseManager: message : 1
11-17 05:02:00.282  4605  4681 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:02:00.286  4605  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-17 05:02:00.286  4605  4660 D BtGatt.GattService: Client app is not null!
,11-17 05:02:00.287  4605  4618 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 05:02:00.288  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:02:00.288  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-17 05:02:00.289  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.289  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.290  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:00.290  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.290  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.290  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 05:02:00.290  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-17 05:02:00.290  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:02:00.290  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:02:00.290  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:00.290  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:00.290  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:00.290  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.290  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:02:00.290  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:02:00.290  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.290  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.291  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-17 05:02:00.291  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.291  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-17 05:02:00.291  5653  5699 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-17 05:02:00.291  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.292  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.292  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.292  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.292  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: St,ate: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:00.292  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-17 05:02:00.293  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-17 05:02:00.293  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-17 05:02:00.293  5653  5699 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-17 05:02:00.294  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-17 05:02:00.294  5653  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-17 05:02:00.295  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-17 05:02:00.295  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:02:00.295  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:02:00.295  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:02:00.295  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:02:00.296  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-17 05:02:00.296  5653  5699 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-17 05:02:00.296  5653  5699 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-17 05:02:00.298  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-17 05:02:00.299  5653  5699 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-17 05:02:00.300  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-17 05:02:00.300  5653  5699 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-17 05:02:00.300  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-17 05:02:00.301  5653  5699 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-17 05:02:00.301  5653  5699 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-17 05:02:00.301  5653  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-17 05:02:00.301  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 05:02:00.301  5653  5699 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-17 05:02:00.301  5653  5699 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-17 05:02:00.301  5653  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-17 05:02:00.301  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 05:02:00.301  5653  5699 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-17 05:02:00.301  5653  5699 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-17 05:02:00.301  5653  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-17 05:02:00.301  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 05:02:00.301  5653  5699 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-17 05:02:00.302  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-17 05:02:00.302  5653  5699 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-17 05:02:00.302  5653  5699 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-17 05:02:00.302  5653  5699 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-17 05:02:00.302  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-17 05:02:00.302  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.302  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.302  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.302  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:02:00.302  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:02:00.302  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:02:00.302  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:02:00.304  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-17 05:02:00.304  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:02:00.304  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:02:00.304  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:02:00.304  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:02:00.304  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:02:00.304  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:02:00.304  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:02:00.304  5653  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-17 05:02:00.304  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-17 05:02:00.305  5653  5708 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:02:00.306  4618  4618 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31597]" dev="sockfs" ino=31597 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:02:00.306  4618  4618 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31597]" dev="sockfs" ino=31597 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:02:00.307  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:02:00.307  5653  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:02:00.307  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 05:02:00.307  5653  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-17 05:02:00.310  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.310  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:02:00.311  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:02:00.311  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:02:00.311  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-17 05:02:00.313  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.313  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.313  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:02:00.313  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:02:00.313  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:02:00.313  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-17 05:02:00.314  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:00.314  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:00.314  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.314  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:02:00.314  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:00.315  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.315  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.315  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.316  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:00.318  4605  4619 D BtGatt.GattService: registerClient() - UUID=57ca9282-c105-488d-a535-814a7e62eceb
11-17 05:02:00.319  4605  4660 D BtGatt.GattService: onClientRegistered() - UUID=57ca9282-c105-488d-a535-814a7e62eceb, clientIf=5
11-17 05:02:00.319  5653  5664 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-17 05:02:00.320  4605  4681 D BtGatt.AdvertiseManager: message : 0
11-17 05:02:00.322  4605  4681 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:02:00.330  4605  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-17 05:02:00.335  4605  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-17 05:02:00.336  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.336  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.336  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:02:00.336  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.336  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.336  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.336  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.336  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.336  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:02:00.337  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:02:00.337  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.338  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.338  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.338  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.339  5653  5699 I io.jxcore.node.ConnectionHelper: start: OK
11-17 05:02:00.339  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.339  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:02:00.340  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-17 05:02:00.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.342  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:02:00.840  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 05:02:00.840  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:02:00.841  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:02:00.841  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:02:00.841  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-17 05:02:00.841  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-17 05:02:00.841  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:02:00.842  5653  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:02:00.842  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 05:02:00.842  5653  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:02:00.842  5653  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-17 05:02:00.842  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eea9703 removed from the list
11-17 05:02:00.842  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 05:02:00.842  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:02:00.842  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-17 05:02:00.843  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:02:00.843  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.843  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.843  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-17 05:02:00.844  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.844  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.844  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:02:00.844  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:02:00.844  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:02:00.845  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:00.846  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:02:00.847  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:00.847  5653  5699 D BluetoothLeScanner: could not find callback wrapper
11-17 05:02:00.848  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:02:00.848  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:00.848  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.848  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.848  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:02:00.848  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.850  4605  4681 D BtGatt.AdvertiseManager: message : 1
11-17 05:02:00.851  4605  4681 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:02:00.866  4605  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-17 05:02:00.866  4605  4660 D BtGatt.GattService: Client app is not null!
,11-17 05:02:00.868  4605  4823 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:02:00.869  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 05:02:00.869  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.869  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-17 05:02:00.870  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.870  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.870  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.870  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-17 05:02:00.870  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-17 05:02:00.872  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-17 05:02:00.872  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:00.875  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:00.875  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:00.875  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.875  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:00.876  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:00.876  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3376680 removed from the list
,11-17 05:02:00.876  5653  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-17 05:02:00.876  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:00.876  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:02:00.876  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:00.877  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.877  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-17 05:02:00.877  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:02:00.877  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.877  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.877  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-17 05:02:00.878  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 05:02:00.879  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.880  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.880  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.880  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:00.880  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-17 05:02:01.380  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 05:02:03.137   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:04.138   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:05.139   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:05.882  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-17 05:02:05.885  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-17 05:02:05.885  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-17 05:02:05.885  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 05:02:05.890  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-17 05:02:05.891  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-17 05:02:05.891  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-17 05:02:05.892  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:02:05.892  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:02:05.892  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-17 05:02:05.892  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:02:05.892  5653  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-17 05:02:05.894  5653  5709 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:02:05.895  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-17 05:02:05.896  5653  5699 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-17 05:02:05.896  4619  4619 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33864]" dev="sockfs" ino=33864 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:02:05.896  4619  4619 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33864]" dev="sockfs" ino=33864 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:02:05.897  5653  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-17 05:02:05.897  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 05:02:05.897  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:02:05.897  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-17 05:02:05.899  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-17 05:02:05.900  5653  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-17 05:02:05.910  5653  5699 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-17 05:02:05.911  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 05:02:05.911  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:02:05.911  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:02:05.911  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:02:05.911  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:02:05.912  5653  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:02:05.912  5653  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:02:05.912  5653  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:02:05.912  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-17 05:02:05.913  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:02:05.913  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:02:05.914  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:02:05.914  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:02:05.914  5653  5699 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eea9703 not in the list
11-17 05:02:05.914  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 05:02:05.914  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:02:05.914  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:02:05.914  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:02:05.915  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:05.917  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:05.918  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:05.918  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:05.918  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:05.918  5653  5699 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3376680 not in the list
,11-17 05:02:05.918  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:05.918  5653  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-17 05:02:05.918  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:05.918  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:05.920  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-17 05:02:05.921  5653  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-17 05:02:05.921  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 05:02:05.922  5653  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-17 05:02:05.922  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 05:02:05.922  5653  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-17 05:02:05.922  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 05:02:05.923  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-17 05:02:05.924  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-17 05:02:05.926  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-17 05:02:05.926  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-17 05:02:05.926  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-17 05:02:05.927  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-17 05:02:05.927  5653  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-17 05:02:05.927  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-17 05:02:05.927  5653  5699 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-17 05:02:05.927  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-17 05:02:05.927  5653  5699 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-17 05:02:05.927  5653  5699 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-17 05:02:05.928  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-17 05:02:05.929  5653  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-17 05:02:05.929  5653  5699 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-17 05:02:05.930  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-17 05:02:05.930  5653  5699 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-17 05:02:05.930  5653  5699 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-17 05:02:05.930  5653  5699 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-17 05:02:05.931  5653  5699 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-17 05:02:05.931  5653  5699 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-17 05:02:05.932  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 05:02:05.932  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb2c5ae added. We now have 3 listener(s)
,11-17 05:02:05.934  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 05:02:05.935  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:02:05.935  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 05:02:05.935  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:02:05.935  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ed5f4f added. We now have 3 listener(s)
11-17 05:02:05.935  5653  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 05:02:05.936  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-17 05:02:05.939  5653  5699 D BluetoothAdapter: enable(): BT is already enabled..!
,11-17 05:02:05.939   927  3771 D WifiService: setWifiEnabled: true pid=5653, uid=10077
11-17 05:02:05.939   927  3771 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:02:05.941  5653  5699 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-17 05:02:05.944  5653  5699 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-17 05:02:05.945  5653  5699 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
11-17 05:02:05.947  5653  5699 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-17 05:02:05.948  5653  5699 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-17 05:02:05.954  4605  4652 D BluetoothAdapterState: Current state: ON, message: 23
11-17 05:02:05.954  4605  4652 D BluetoothAdapterProperties: Setting state to 13
,11-17 05:02:05.954  4605  4652 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-17 05:02:05.955  4605  4652 D BluetoothAdapterProperties: onBluetoothDisable()
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:02:05.956  5653  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-17 05:02:05.956  4605  4652 I BluetoothAdapterState: Entering PendingCommandState
,11-17 05:02:05.958  4605  4605 D BluetoothMapService: onReceive
,11-17 05:02:05.958  4605  4605 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-17 05:02:05.958  4605  4605 D BluetoothMapService: STATE_TURNING_OFF
11-17 05:02:05.959  5653  5699 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 05:02:05.959  5653  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-17 05:02:05.959  4605  4605 D BluetoothMapService: MAP Service closeService in
11-17 05:02:05.959  4605  4605 D BluetoothMapMasInstance0: MAP Service shutdown
11-17 05:02:05.959  4605  4605 D ObexServerSockets0: shutdown(block = true)
11-17 05:02:05.961  4605  4605 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-17 05:02:05.961  4605  4605 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-17 05:02:05.961  4605  4827 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-17 05:02:05.961  4605  4812 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-17 05:02:05.961  4605  4829 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-17 05:02:05.963  4605  4605 I BtOppRfcommListener: stopping Accept Thread
11-17 05:02:05.963  4605  5339 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-17 05:02:05.964  4605  5339 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-17 05:02:05.972   927   940 I ActivityManager: Start proc 5712:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-17 05:02:05.973  4605  4660 D BluetoothAdapterProperties: Scan Mode:20
11-17 05:02:05.973  4605  4652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-17 05:02:05.976  4605  4605 D HeadsetService: Received stop request...Stopping profile...
,11-17 05:02:05.978  3824  4014 D BluetoothHeadset: Proxy object disconnected
,11-17 05:02:05.980  4605  4605 D A2dpService: Received stop request...Stopping profile...
,11-17 05:02:05.980  3129  3145 D BluetoothHeadset: Proxy object disconnected
11-17 05:02:05.980   927   927 D BluetoothHeadset: Proxy object disconnected
11-17 05:02:05.980   927   927 D BluetoothHeadset: Proxy object disconnected
,11-17 05:02:05.981   927   927 D BluetoothHeadset: Proxy object disconnected
11-17 05:02:05.980  4605  4818 D A2dpStateMachine: Exit Disconnected: -1
11-17 05:02:05.981  3129  3129 D HeadsetProfile: Bluetooth service disconnected
11-17 05:02:05.984  3129  3129 D BluetoothA2dp: Proxy object disconnected
11-17 05:02:05.984   927   927 D BluetoothA2dp: Proxy object disconnected
11-17 05:02:05.984  4605  4605 V BluetoothAdapterState: isTurningOff()=true
11-17 05:02:05.984  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:05.984  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:05.984  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:05.986  4605  4605 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-17 05:02:05.986  4605  4605 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-17 05:02:05.986  4605  4795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:02:05.986  4605  4795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:02:05.986  4605  4795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:02:05.986  4605  4660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-17 05:02:05.987  4605  4660 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-17 05:02:05.987  4605  4605 D HidService: Received stop request...Stopping profile...
11-17 05:02:05.987  4605  4605 D HidService: Stopping Bluetooth HidService
,11-17 05:02:05.989  4605  4605 D HealthService: Received stop request...Stopping profile...
11-17 05:02:05.988  3129  3129 D BluetoothInputDevice: Proxy object disconnected
11-17 05:02:05.989  3129  3129 D HidProfile: Bluetooth service disconnected
11-17 05:02:05.991  4605  4605 D PanService: Received stop request...Stopping profile...
11-17 05:02:05.991  3129  3129 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-17 05:02:05.991  3129  3129 D PanProfile: Bluetooth service disconnected
,11-17 05:02:05.994  4605  4605 D BluetoothMapService: Received stop request...Stopping profile...
,11-17 05:02:05.994  4605  4605 D BluetoothMapService: stop()
,11-17 05:02:05.995  4605  4605 D BluetoothMapAppObserver: deinitObservers()
11-17 05:02:05.995  4605  4605 D BluetoothMapAppObserver: removeReceiver()
11-17 05:02:05.995  3129  3129 D BluetoothMap: Proxy object disconnected
11-17 05:02:05.995  3129  3129 D MapProfile: Bluetooth service disconnected
11-17 05:02:05.996  4605  4605 V BluetoothAdapterState: isTurningOff()=true
11-17 05:02:05.996  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:05.996  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:05.996  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:05.997  4605  4660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-17 05:02:05.998  4605  4795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-17 05:02:05.998  4605  4795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:02:05.998  4605  4795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 05:02:05.998  4605  4795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 05:02:05.998  4605  4795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 05:02:05.998  4605  4795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 05:02:05.998  4605  4605 D SapService: Received stop request...Stopping profile...
11-17 05:02:05.999  4605  4605 V SapService: stop()
11-17 05:02:06.000  4605  4605 V BluetoothAdapterState: isTurningOff()=true
11-17 05:02:06.000  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:06.000  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:06.000  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:06.000  4605  4605 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-17 05:02:06.000  4605  4605 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-17 05:02:06.000  4605  4605 V BluetoothAdapterState: isTurningOff()=true
11-17 05:02:06.001  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:06.001  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:06.001  4605  4660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-17 05:02:06.001  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:06.001  4605  4605 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-17 05:02:06.001  4605  4660 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-17 05:02:06.001  4605  4605 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-17 05:02:06.001  4605  4605 V BluetoothAdapterState: isTurningOff()=true
11-17 05:02:06.001  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:06.001  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:06.001  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:06.002  4605  4605 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-17 05:02:06.002  4605  4605 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-17 05:02:06.002  4605  4605 D BluetoothMapService: MAP Service closeService in
11-17 05:02:06.002  4605  4605 V BluetoothAdapterState: isTurningOff()=true
11-17 05:02:06.002  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:06.003  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:06.003  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:06.003  4605  4605 D BluetoothMapService: cleanup()
11-17 05:02:06.003  4605  4605 D BluetoothMapService: MAP Service closeService in
11-17 05:02:06.003  4605  4605 V BluetoothAdapterState: isTurningOff()=true
11-17 05:02:06.003  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:06.003  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:06.003  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:06.003  4605  4652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-17 05:02:06.003  4605  4652 D BluetoothAdapterProperties: Setting state to 15
11-17 05:02:06.003  4605  4652 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-17 05:02:06.004  4605  4652 I BluetoothAdapterState: Entering BleOnState
11-17 05:02:06.004   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:02:06.004  3129  3140 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 05:02:06.005   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-17 05:02:06.005  3129  3970 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-17 05:02:06.005  3824  3859 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:02:06.006  3129  3145 D BluetoothPan: onBluetoothStateChange on: false
11-17 05:02:06.006   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:02:06.006   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 05:02:06.006  3129  3140 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:02:06.007  3129  3970 D BluetoothMap: onBluetoothStateChange: up=false
11-17 05:02:06.007  3129  3145 D BluetoothPbap: onBluetoothStateChange: up=false
11-17 05:02:06.008  4605  4652 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-17 05:02:06.008  4605  4652 D BluetoothAdapterProperties: Setting state to 16
11-17 05:02:06.008  4605  4652 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-17 05:02:06.009  4605  4652 D BluetoothAdapterProperties: onBleDisable
,11-17 05:02:06.009  4605  4652 I BluetoothAdapterState: Entering PendingCommandState
11-17 05:02:06.009  4605  4654 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-17 05:02:06.010  4605  4795 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-17 05:02:06.010  4605  4795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:02:06.013  4605  4660 D BluetoothAdapterProperties: Scan Mode:20
,11-17 05:02:06.034  5712  5712 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-17 05:02:06.046  5712  5712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-17 05:02:06.051   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c25835f:true
11-17 05:02:06.051  3582  3582 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 05:02:06.064   927  3771 I ActivityManager: Start proc 5724:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-17 05:02:06.071  5712  5712 D LocalBluetoothProfileManager: Adding local MAP profile
,11-17 05:02:06.075  5712  5712 D BluetoothMap: Create BluetoothMap proxy object
,11-17 05:02:06.093  5712  5712 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-17 05:02:06.100  5724  5724 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-17 05:02:06.109  5712  5712 D DockEventReceiver: finishStartingService: stopping service
,11-17 05:02:06.115   927  3170 I ActivityManager: Killing 5191:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-17 05:02:06.139   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:06.226  4605  4660 I bt_hci  : shut_down
,11-17 05:02:06.231  4605  4683 D bt_hwcfg: hw_epilog_process
,11-17 05:02:06.231  4605  4683 I bt_vendor: low_power_mode_cb
,11-17 05:02:06.234  4605  4683 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-17 05:02:06.234  4605  4683 I bt_vendor: epilog_cb
11-17 05:02:06.234  4605  4683 I bt_hci  : epilog_finished_callback
,11-17 05:02:06.237  4605  4660 I bt_hci_h4: hal_close
,11-17 05:02:06.237  4605  4660 I bt_userial_vendor: device fd = 54 close
,11-17 05:02:06.316  5724  5724 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-17 05:02:06.316  5724  5724 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.316  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:02:06.317  5724  5724 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-17 05:02:06.317  5724  5724 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:170)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.317  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:02:06.323  5724  5724 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.r.k.d(PG:583)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:170)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.323  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:02:06.324  5724  5724 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
1,1-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:02:06.324  5724  5724 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:02:06.324  5724  5724 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:02:06.324  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:02:06.328  5712  5712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-17 05:02:06.334  3582  3582 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 05:02:06.346  4605  4654 D bt_stack_manager: event_shut_down_stack finished.
11-17 05:02:06.347  4605  4652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-17 05:02:06.348  4605  4652 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-17 05:02:06.348  4605  4605 D BtGatt.DebugUtils: handleDebugAction() action=null
11-17 05:02:06.349  4605  4605 D BtGatt.GattService: Received stop request...Stopping profile...
11-17 05:02:06.349  4605  4605 D BtGatt.GattService: stop()
11-17 05:02:06.349  4605  4605 D BtGatt.AdvertiseManager: advertise clients cleared
11-17 05:02:06.351  4605  4605 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:06.351  4605  4605 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:06.351  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:06.351  4605  4605 V BluetoothAdapterState: isBleTurningOff()=true
11-17 05:02:06.351  4605  4652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-17 05:02:06.351  4605  4652 D BluetoothAdapterProperties: Setting state to 10
11-17 05:02:06.351  4605  4652 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-17 05:02:06.352  4605  4652 I BluetoothAdapterState: Entering OffState
11-17 05:02:06.352  5712  5712 D DockEventReceiver: finishStartingService: stopping service
11-17 05:02:06.353   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-17 05:02:06.354   927  3771 I ActivityManager: Killing 5442:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-17 05:02:06.384  4605  4605 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-17 05:02:06.384  4605  4605 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-17 05:02:06.384  4605  4605 I BluetoothServiceJni: cleanupNative: return from cleanup
11-17 05:02:06.385  4605  4654 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-17 05:02:06.388  4605  4605 I art     : System.exit called, status: 0
11-17 05:02:06.389  4605  4605 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-17 05:02:06.419  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 05:02:06.428   927  3771 I ActivityManager: Process com.android.bluetooth (pid 4605) has died
,11-17 05:02:06.456  5653  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:02:06.456  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-17 05:02:06.456  5653  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 05:02:06.456  5653  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 05:02:06.459  5653  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 05:02:06.471   927   944 I ActivityManager: Start proc 5756:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-17 05:02:06.529  5756  5756 D AdapterServiceConfig: Adding HeadsetService
,11-17 05:02:06.530  5756  5756 D AdapterServiceConfig: Adding A2dpService
11-17 05:02:06.530  5756  5756 D AdapterServiceConfig: Adding HidService
11-17 05:02:06.530  5756  5756 D AdapterServiceConfig: Adding HealthService
,11-17 05:02:06.531  5756  5756 D AdapterServiceConfig: Adding PanService
11-17 05:02:06.531  5756  5756 D AdapterServiceConfig: Adding GattService
11-17 05:02:06.531  5756  5756 D AdapterServiceConfig: Adding BluetoothMapService
,11-17 05:02:06.531  5756  5756 D AdapterServiceConfig: Adding SapService
,11-17 05:02:06.541   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4f6c74:true
,11-17 05:02:06.541  5756  5756 D BluetoothAdapterState: make() - Creating AdapterState
,11-17 05:02:06.543  5756  5756 I bt_bluedroid: init
,11-17 05:02:06.543  5756  5768 I BluetoothAdapterState: Entering OffState
11-17 05:02:06.545  5756  5769 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-17 05:02:06.545  5756  5769 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-17 05:02:06.545  5756  5769 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-17 05:02:06.545  5756  5769 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-17 05:02:06.546  5756  5756 I bt_bluedroid: get_profile_interface socket
,11-17 05:02:06.547  5756  5772 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 05:02:06.547  5756  5756 I bt_bluedroid: get_profile_interface sdp
11-17 05:02:06.548  5756  5772 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 05:02:06.550  5756  5767 I bt_bluedroid: config_hci_snoop_log
,11-17 05:02:06.551   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-17 05:02:06.555  5756  5768 D BluetoothAdapterState: Current state: OFF, message: 0
,11-17 05:02:06.555  5756  5768 D BluetoothAdapterProperties: Setting state to 14
,11-17 05:02:06.555  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-17 05:02:06.556  5756  5768 D BluetoothBondStateMachine: make
11-17 05:02:06.557  5724  5741 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
11-17 05:02:06.557  5756  5773 I BluetoothBondStateMachine: StableState(): Entering Off State
11-17 05:02:06.559  5756  5768 I BluetoothAdapterState: Entering PendingCommandState
,11-17 05:02:06.560  5756  5756 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-17 05:02:06.562  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
11-17 05:02:06.562  5756  5756 D BtGatt.DebugUtils: handleDebugAction() action=null
11-17 05:02:06.563  5756  5756 D BtGatt.GattService: Received start request. Starting profile...
11-17 05:02:06.563  5756  5756 D BtGatt.GattService: start()
11-17 05:02:06.563  5756  5756 I bt_bluedroid: get_profile_interface gatt
11-17 05:02:06.564  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
11-17 05:02:06.564  5756  5756 D BtGatt.AdvertiseManager: advertise manager created
,11-17 05:02:06.568  5756  5756 V BluetoothAdapterState: isTurningOff()=false
,11-17 05:02:06.568  5756  5756 V BluetoothAdapterState: isTurningOn()=false
11-17 05:02:06.568  5756  5756 V BluetoothAdapterState: isBleTurningOn()=true
11-17 05:02:06.568  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:06.568  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-17 05:02:06.569  5756  5768 I bt_bluedroid: bt_bluedroid
11-17 05:02:06.569  5756  5769 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-17 05:02:06.570  5756  5769 I bt_hci  : start_up
,11-17 05:02:06.575  5756  5769 I bt_vendor: alloc value 0xf3e3d871
,11-17 05:02:06.575  5756  5769 I bt_vendor: init
11-17 05:02:06.575  5756  5769 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-17 05:02:06.575  5756  5769 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-17 05:02:06.580   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@55246f8:true
,11-17 05:02:06.683  5756  5769 D bt_hci  : start_up starting async portion
,11-17 05:02:06.684  5756  5777 I bt_hci  : event_finish_startup
11-17 05:02:06.684  5756  5777 I bt_hci_h4: hal_open
11-17 05:02:06.684  5756  5777 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-17 05:02:06.685  5756  5777 I bt_userial_vendor: device fd = 54 open
,11-17 05:02:06.683  5779  5779 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:02:06.697  5756  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 05:02:06.699  5756  5777 D bt_hwcfg: Chipset BCM4358A3
,11-17 05:02:06.699  5756  5777 D bt_hwcfg: Target name = [BCM4358A3]
11-17 05:02:06.699  5756  5777 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-17 05:02:06.969  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-17 05:02:07.103  5756  5777 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-17 05:02:07.103  5756  5777 D bt_hwcfg: Settlement delay -- 100 ms
11-17 05:02:07.104  5756  5777 I bt_hwcfg: Setting fw settlement delay to 100 
,11-17 05:02:07.141   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:07.229  5756  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 05:02:07.229  5756  5777 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-17 05:02:07.231  5756  5777 I bt_hwcfg: vendor lib fwcfg completed
,11-17 05:02:07.231  5756  5777 I bt_vendor: firmware callback
11-17 05:02:07.231  5756  5777 I bt_hci  : firmware_config_callback
,11-17 05:02:07.240  5756  5781 I bt_btu  : btu_task pending for preload complete event
,11-17 05:02:07.240  5756  5781 I bt_btu_task: Bluetooth chip preload is complete
,11-17 05:02:07.240  5756  5781 I bt_btu  : btu_task received preload complete event
,11-17 05:02:07.248  5756  5781 I         : BTE_InitTraceLevels -- TRC_HCI
,11-17 05:02:07.248  5756  5781 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-17 05:02:07.248  5756  5781 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-17 05:02:07.248  5756  5781 I         : BTE_InitTraceLevels -- TRC_AVDT
11-17 05:02:07.248  5756  5781 I         : BTE_InitTraceLevels -- TRC_AVRC
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_A2D
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_BNEP
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_BTM
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_GAP
,11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_PAN
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_SDP
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_GATT
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_SMP
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-17 05:02:07.249  5756  5781 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-17 05:02:07.331  5756  5781 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3dbb549
,11-17 05:02:07.331  5756  5781 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3dbb549 
,11-17 05:02:07.348  5756  5772 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-17 05:02:07.350  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-17 05:02:07.351  5756  5772 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 05:02:07.354  5756  5772 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 05:02:07.356  5756  5772 D BluetoothAdapterProperties: Scan Mode:20
,11-17 05:02:07.357  5756  5772 D BluetoothAdapterProperties: Discoverable Timeout:120
11-17 05:02:07.357  5756  5772 D bt_hci  : do_postload posting postload work item
,11-17 05:02:07.357  5756  5777 I bt_hci  : event_postload
,11-17 05:02:07.357  5756  5777 I bt_vendor: sco_config_cb
11-17 05:02:07.357  5756  5777 I bt_hci  : sco_config_callback postload finished.
11-17 05:02:07.359  5756  5772 D bt_bte_conf: Device ID record 1 : primary
11-17 05:02:07.360  5756  5772 D bt_bte_conf:   vendorId            = 000f
11-17 05:02:07.360  5756  5772 D bt_bte_conf:   vendorIdSource      = 0001
11-17 05:02:07.360  5756  5772 D bt_bte_conf:   product             = 1200
11-17 05:02:07.360  5756  5772 D bt_bte_conf:   version             = 1436
11-17 05:02:07.360  5756  5772 D bt_bte_conf:   clientExecutableURL = 
11-17 05:02:07.360  5756  5772 D bt_bte_conf:   serviceDescription  = 
,11-17 05:02:07.360  5756  5772 D bt_bte_conf:   documentationURL    = 
11-17 05:02:07.360  5756  5772 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-17 05:02:07.361  5756  5769 D bt_stack_manager: event_start_up_stack finished
11-17 05:02:07.362  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-17 05:02:07.362  5756  5768 D BluetoothAdapterProperties: Setting state to 15
11-17 05:02:07.362  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-17 05:02:07.364  5756  5768 I BluetoothAdapterState: Entering BleOnState
11-17 05:02:07.366  5756  5777 I bt_vendor: low_power_mode_cb
,11-17 05:02:07.373  5756  5768 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-17 05:02:07.373  5756  5768 D BluetoothAdapterProperties: Setting state to 11
,11-17 05:02:07.373  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-17 05:02:07.381  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
,11-17 05:02:07.382  5756  5756 D HeadsetService: Received start request. Starting profile...
,11-17 05:02:07.385  5756  5756 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-17 05:02:07.385  5756  5756 D HeadsetStateMachine: make
,11-17 05:02:07.394  5756  5768 I BluetoothAdapterState: Entering PendingCommandState
,11-17 05:02:07.395  5756  5756 D HeadsetStateMachine: max_hf_connections = 1
,11-17 05:02:07.395  5756  5756 I bt_bluedroid: get_profile_interface handsfree
11-17 05:02:07.396  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-17 05:02:07.396  5756  5772 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-17 05:02:07.399  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
,11-17 05:02:07.400  5756  5756 D A2dpService: Received start request. Starting profile...
,11-17 05:02:07.400  5756  5756 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-17 05:02:07.401  5756  5756 I bt_bluedroid: get_profile_interface avrcp
,11-17 05:02:07.406  5756  5756 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-17 05:02:07.406  5756  5756 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-17 05:02:07.406  5756  5756 D A2dpStateMachine: make
,11-17 05:02:07.408  5756  5756 I bt_bluedroid: get_profile_interface a2dp
,11-17 05:02:07.408  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-17 05:02:07.409  5756  5789 D A2dpStateMachine: Enter Disconnected: -2
11-17 05:02:07.410  5756  5756 I BluetoothHidServiceJni: classInitNative: succeeds
,11-17 05:02:07.411  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
11-17 05:02:07.412  5712  5712 D BluetoothInputDevice: Proxy object connected
11-17 05:02:07.412  5756  5756 D HidService: Received start request. Starting profile...
11-17 05:02:07.413  5756  5756 I bt_bluedroid: get_profile_interface hidhost
11-17 05:02:07.413  5756  5756 D HidService: setHidService(): set to: null
11-17 05:02:07.413  5756  5772 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d9c56d
11-17 05:02:07.413  5712  5712 D HidProfile: Bluetooth service connected
11-17 05:02:07.413  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-17 05:02:07.415  5756  5756 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-17 05:02:07.416  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
11-17 05:02:07.416  3582  3582 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 05:02:07.416  5756  5756 D HealthService: Received start request. Starting profile...
,11-17 05:02:07.418  5756  5756 I bt_bluedroid: get_profile_interface health
,11-17 05:02:07.419  5756  5756 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-17 05:02:07.419  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
11-17 05:02:07.420  5712  5712 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 05:02:07.421  5756  5756 D PanService: Received start request. Starting profile...
,11-17 05:02:07.421  5756  5756 D BluetoothPanServiceJni: initializeNative(L110): pan
11-17 05:02:07.421  5756  5756 I bt_bluedroid: get_profile_interface pan
,11-17 05:02:07.421  5756  5772 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-17 05:02:07.422  5712  5712 D PanProfile: Bluetooth service connected
,11-17 05:02:07.425  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
,11-17 05:02:07.427  5712  5712 D BluetoothMap: Proxy object connected
,11-17 05:02:07.427  5712  5712 D MapProfile: Bluetooth service connected
11-17 05:02:07.427  5712  5712 D BluetoothMap: getConnectedDevices()
11-17 05:02:07.428  5756  5756 D BluetoothMapService: Received start request. Starting profile...
11-17 05:02:07.428  5756  5756 D BluetoothMapService: start()
11-17 05:02:07.431  5756  5756 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-17 05:02:07.432  5756  5756 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-17 05:02:07.432  5756  5756 D BluetoothMapAppObserver: createReceiver()
11-17 05:02:07.433  5756  5756 D BluetoothMapAppObserver: initObservers()
,11-17 05:02:07.433  5756  5756 D BluetoothMapAppObserver: getEnabledAccountItems()
11-17 05:02:07.439  5756  5756 V SapService: SapBinder()
11-17 05:02:07.439  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
11-17 05:02:07.439  5756  5756 D SapService: Received start request. Starting profile...
11-17 05:02:07.439  5756  5756 V SapService: start()
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 05:02:07.441  5756  5787 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:07.441  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:07.442  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:07.442  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-17 05:02:07.442  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 05:02:07.442  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 05:02:07.442  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:07.442  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-17 05:02:07.443  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:07.443  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isTurningOn()=true
,11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:07.444  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:07.445  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-17 05:02:07.445  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-17 05:02:07.445  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:02:07.445  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:02:07.446  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-17 05:02:07.446  5756  5768 D BluetoothAdapterProperties: ScanMode =  20
11-17 05:02:07.446  5756  5768 D BluetoothAdapterProperties: State =  11
11-17 05:02:07.446  5756  5768 D BluetoothAdapterProperties: Setting state to 12
11-17 05:02:07.446  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-17 05:02:07.447   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 05:02:07.448  5712  5712 D BluetoothMap: Bluetooth is Not enabled
11-17 05:02:07.448  5756  5768 I BluetoothAdapterState: Entering OnState
11-17 05:02:07.448  3129  3140 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 05:02:07.448  5756  5772 D BluetoothAdapterProperties: Scan Mode:21
11-17 05:02:07.449  5756  5772 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-17 05:02:07.452   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-17 05:02:07.452  5712  5723 D BluetoothPan: onBluetoothStateChange on: true
11-17 05:02:07.452  3129  3129 D BluetoothA2dp: Proxy object connected
11-17 05:02:07.453  5712  5722 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-17 05:02:07.453  3129  3145 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-17 05:02:07.455  3129  3129 D BluetoothInputDevice: Proxy object connected
,11-17 05:02:07.455  3129  3129 D HidProfile: Bluetooth service connected
11-17 05:02:07.455  3824  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 05:02:07.456  3129  3970 D BluetoothPan: onBluetoothStateChange on: true
,11-17 05:02:07.457  3129  3129 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 05:02:07.457   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 05:02:07.457   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 05:02:07.457  3129  3129 D PanProfile: Bluetooth service connected
,11-17 05:02:07.458   927   927 D BluetoothA2dp: Proxy object connected
,11-17 05:02:07.458  5712  5723 D BluetoothMap: onBluetoothStateChange: up=true
11-17 05:02:07.458  3129  3145 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 05:02:07.459  5756  5756 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-17 05:02:07.459  5712  5722 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 05:02:07.459  5756  5756 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-17 05:02:07.461  3129  3140 D BluetoothMap: onBluetoothStateChange: up=true
11-17 05:02:07.461  5756  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:02:07.463  5756  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:02:07.463  3129  3129 D BluetoothMap: Proxy object connected
11-17 05:02:07.463  3129  3145 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 05:02:07.463  3129  3129 D MapProfile: Bluetooth service connected
11-17 05:02:07.463  3129  3129 D BluetoothMap: getConnectedDevices()
11-17 05:02:07.464  5756  5756 D ObexServerSockets: Succeed to create listening sockets 
11-17 05:02:07.464  5756  5756 D ObexServerSockets0: startAccept()
11-17 05:02:07.464  5756  5756 D ObexServerSockets0: prepareForNewConnect()
11-17 05:02:07.466   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-17 05:02:07.466  5756  5756 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-17 05:02:07.466  5756  5756 D BluetoothSdpJni: SDP Create record success - handle: 0
11-17 05:02:07.467  5756  5756 D BluetoothMapService: onReceive
11-17 05:02:07.467  5756  5756 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-17 05:02:07.467  5756  5756 D BluetoothMapService: STATE_ON
11-17 05:02:07.467  5712  5712 D LocalBluetoothProfileManager: Adding local A2DP profile
11-17 05:02:07.468  5756  5794 D ObexServerSockets0: Accepting socket connection...
11-17 05:02:07.470  5756  5796 D ObexServerSockets0: Accepting socket connection...
11-17 05:02:07.471  5756  5797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:02:07.471  5712  5712 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-17 05:02:07.474  5756  5797 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-17 05:02:07.474  5756  5797 D BluetoothSdpJni: SDP Create record success - handle: 1
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:02:07.475  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-17 05:02:07.478  5653  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 05:02:07.479  5653  5699 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-17 05:02:07.480   927   937 D WifiService: setWifiEnabled: false pid=5653, uid=10077
,11-17 05:02:07.480   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:02:07.481  5712  5712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-17 05:02:07.482   927  2985 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-17 05:02:07.482   927  2985 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-17 05:02:07.482   927  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 05:02:07.483   927  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-17 05:02:07.483  5653  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 05:02:07.484  5712  5712 D BluetoothA2dp: Proxy object connected
,11-17 05:02:07.487  5756  5756 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-17 05:02:07.487  5756  5756 D ObexServerSockets0: prepareForNewConnect()
11-17 05:02:07.488  3582  3582 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 05:02:07.494  5712  5712 D DockEventReceiver: finishStartingService: stopping service
11-17 05:02:07.495   927  5412 D DhcpClient: Clearing IP address
,11-17 05:02:07.495  5712  5712 D BluetoothPbap: Proxy object connected
11-17 05:02:07.496   507   925 D CommandListener: Clearing all IP addresses on wlan0
11-17 05:02:07.497  5712  5712 D PbapServerProfile: Bluetooth service connected
11-17 05:02:07.498  3129  3129 D BluetoothPbap: Proxy object connected
11-17 05:02:07.498  3129  3129 D PbapServerProfile: Bluetooth service connected
,11-17 05:02:07.502   507   925 D CommandListener: Setting iface cfg
,11-17 05:02:07.504   927  5413 D DhcpClient: Receive thread stopped
,11-17 05:02:07.508  3582  5468 V NativeCrypto: Read error: ssl=0x7f8dd39b00: I/O error during system call, Connection timed out
,11-17 05:02:07.509  3582  5468 V NativeCrypto: SSL shutdown failed: ssl=0x7f8dd39b00: I/O error during system call, Broken pipe
11-17 05:02:07.511   927  3170 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-17 05:02:07.512   927  5408 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-17 05:02:07.512  5756  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:02:07.515   927  5408 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-17 05:02:07.516   927  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-17 05:02:07.516   927  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-17 05:02:07.517   927  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-17 05:02:07.521   927  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-17 05:02:07.522   927  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-17 05:02:07.523   533   533 E Parcel  : Reading a NULL string not supported here.
,11-17 05:02:07.530   927  2987 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-17 05:02:07.531  3790  3924 W QCNEJ   : |CORE| network lost: 100
,11-17 05:02:07.532  3790  3924 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-17 05:02:07.532   927   927 D RttService: SCAN_AVAILABLE : 1
11-17 05:02:07.532   927  3094 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-17 05:02:07.533  5756  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:02:07.535  5756  5807 I BtOppRfcommListener: Accept thread started.
,11-17 05:02:07.550   927  2985 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-17 05:02:07.552  3824  3859 D BluetoothHeadset: Proxy object connected
11-17 05:02:07.552   927   944 D BluetoothHeadset: Proxy object connected
11-17 05:02:07.552  3129  3145 D BluetoothHeadset: Proxy object connected
11-17 05:02:07.552   927   927 D BluetoothHeadset: Proxy object connected
11-17 05:02:07.553   927   927 D BluetoothHeadset: Proxy object connected
11-17 05:02:07.553   927   927 D BluetoothHeadset: Proxy object connected
,11-17 05:02:07.557  3824  3847 D BluetoothHeadset: Proxy object connected
,11-17 05:02:07.557   927  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 05:02:07.558   927   944 D BluetoothHeadset: Proxy object connected
11-17 05:02:07.559  3129  3970 D BluetoothHeadset: Proxy object connected
11-17 05:02:07.560  3129  3129 D HeadsetProfile: Bluetooth service connected
,11-17 05:02:07.562  3129  3129 D HeadsetProfile: Bluetooth service connected
,11-17 05:02:07.564   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:02:07.574  5712  5722 D BluetoothHeadset: Proxy object connected
,11-17 05:02:07.576  5712  5712 D HeadsetProfile: Bluetooth service connected
,11-17 05:02:07.586   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:02:07.586   507   925 D CommandListener: Clearing all IP addresses on wlan0
11-17 05:02:07.587   927  2987 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-17 05:02:07.587   927  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-17 05:02:07.587   507   925 D TetherController: Setting IP forward enable = 0
11-17 05:02:07.588  3582  5816 I VacuumService: Vacuum at: now=1479376927587 tag=VacuumService
11-17 05:02:07.588   927   944 D Tethering: MasterInitialState.processMessage what=3
11-17 05:02:07.590   927  2985 D DhcpClient: doQuit
11-17 05:02:07.590   927  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-17 05:02:07.591   927  5412 D DhcpClient: onQuitting
11-17 05:02:07.592  3453  3453 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-17 05:02:07.593  4965  4965 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-17 05:02:07.602  5324  5324 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3980b30 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-17 05:02:07.606  5072  5102 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-17 05:02:07.606  5072  5102 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-17 05:02:07.606  5072  5102 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-17 05:02:07.606  5072  5102 E SarControlService: no key has been found,reset the power
11-17 05:02:07.606  5072  5116 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 05:02:07.606  5072  5116 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 05:02:07.606  5072  5116 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 05:02:07.607  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:02:07.607  5104  5104 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 05:02:07.608  5072  5116 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 05:02:07.613  5072  5116 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-17 05:02:07.613  5072  5116 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 05:02:07.613  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:02:07.614  3453  3453 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-17 05:02:07.614  5104  5119 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5877696 HexData = [00000000ea03000000000000ffffffff]
11-17 05:02:07.614  5104  5119 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 05:02:07.614  5104  5119 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-17 05:02:07.615  5104  5104 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 05:02:07.616  3747  3747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-17 05:02:07.618  3453  3453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-17 05:02:07.619  3747  3747 D SystemUpdateService: onCreate
11-17 05:02:07.621   507   918 W SocketClient: write error (Broken pipe)
11-17 05:02:07.621   507   918 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
,11-17 05:02:07.621   507   918 W SocketListener: Error sending broadcast (Broken pipe)
11-17 05:02:07.623  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 05:02:07.623  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 05:02:07.625  3582  5824 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-17 05:02:07.626  5104  5119 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5877696 HexData = [00000000eb03000000000000ffffffff]
11-17 05:02:07.626  5104  5119 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 05:02:07.626  5104  5119 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-17 05:02:07.628  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 05:02:07.628  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-17 05:02:07.633  3747  3747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 05:02:07.639  3747  5826 I SystemUpdateService: active receiver: enabled
,11-17 05:02:07.641  3747  5826 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 05:02:07.643  3747  5826 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-17 05:02:07.643  3747  5826 I SystemUpdateService: now status is 0 (complete)
11-17 05:02:07.643  3747  5826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 05:02:07.643  3747  5826 I SystemUpdateService: file has been verified
11-17 05:02:07.643  3747  5826 I SystemUpdateService: OTA package size = 21989297
,11-17 05:02:07.645  3453  3453 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-17 05:02:07.652  3747  5826 I SystemUpdateService: showing system update notification
,11-17 05:02:07.654  3747  3747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-17 05:02:07.660  3453  3453 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-17 05:02:07.662  3747  5439 I iu.UploadsManager: num queued entries: 0
11-17 05:02:07.662  3747  5439 I iu.UploadsManager: num updated entries: 0
11-17 05:02:07.663  3582  5817 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-17 05:02:07.664   507   918 W SocketClient: write error (Broken pipe)
11-17 05:02:07.664   507   918 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-17 05:02:07.664   507   918 W SocketListener: Error sending broadcast (Broken pipe)
11-17 05:02:07.664  3747  3747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 05:02:07.665  3747  3747 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 05:02:07.666  3582  5817 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-17 05:02:07.668  3747  5439 I iu.SyncManager: NEXT; no task
,11-17 05:02:07.677   927   938 I ActivityManager: Start proc 5830:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-17 05:02:07.680  3747  3747 D SystemUpdateService: onDestroy
,11-17 05:02:07.710  3582  5817 W Uploader:  no longer exists, so no auth token.
,11-17 05:02:07.715  5830  5830 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-17 05:02:07.715  3582  5824 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-17 05:02:07.718  5830  5830 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 05:02:07.725  5830  5830 D SprintDMHelper: simOperator: 
,11-17 05:02:07.725  5830  5830 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 05:02:07.738  5046  5842 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-17 05:02:07.749   927  3905 I ActivityManager: Start proc 5843:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-17 05:02:07.751   927  3876 I ActivityManager: Killing 5324:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-17 05:02:07.779  5046  5046 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 05:02:07.779   927  2985 D wifi    : In wifi stop Hal
11-17 05:02:07.779   927  2985 D wifi    : halHandle = 0x7f7c208680, mVM = 0x7f9888d140, mCls = 0x100a02
11-17 05:02:07.779   927  3451 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-17 05:02:07.780   927  3451 D WifiHAL : Got a signal to exit!!!
,11-17 05:02:07.780   927  3451 I WifiHAL : Exit wifi_event_loop
11-17 05:02:07.780   927  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-17 05:02:07.780   927  2985 E WifiHAL : Event processing terminated
11-17 05:02:07.780   927  2985 D wifi    : In wifi cleaned up handler
11-17 05:02:07.780   927  2985 I WifiHAL : Internal cleanup completed
11-17 05:02:07.781  4078  4242 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 05:02:07.792  5843  5843 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-17 05:02:07.799   927  3771 I ActivityManager: Killing 4702:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-17 05:02:07.801   507   918 W SocketClient: write error (Broken pipe)
,11-17 05:02:07.801   507   918 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
11-17 05:02:07.801   507   918 W SocketListener: Error sending broadcast (Broken pipe)
11-17 05:02:07.802   927  3451 D wifi    : set interface wlan0 flags (DOWN)
11-17 05:02:07.802   927  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 05:02:07.991  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 05:02:07.999  5653  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-17 05:02:08.003   927  3596 D WifiService: setWifiEnabled: true pid=5653, uid=10077
11-17 05:02:08.003   927  3596 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:02:08.006   927   944 D Tethering: InitialState.processMessage what=4
,11-17 05:02:08.008  5653  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 05:02:08.011   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-17 05:02:08.141   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-17 05:02:08.508   927  3916 D WifiService: setWifiEnabled: true pid=5653, uid=10077
,11-17 05:02:08.508   927  3916 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:02:08.675   507   925 E Netd    : netlink response contains error (No such file or directory)
,11-17 05:02:08.677   927  2987 E NetdConnector: NDC Command {118 network destroy 100} took too long (1089ms)
11-17 05:02:08.677   927  2987 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-17 05:02:08.678   927  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-17 05:02:08.679  3582  5817 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,11-17 05:02:08.680   927  2983 E NetdConnector: NDC Command {119 bandwidth setglobalalert 2097152} took too long (1086ms)
11-17 05:02:08.680   507   925 D SoftapController: Softap fwReload - Ok
,11-17 05:02:08.681   927  2985 E NetdConnector: NDC Command {120 softap fwreload wlan0 STA} took too long (673ms)
,11-17 05:02:08.682   927  2982 E NetdConnector: NDC Command {121 bandwidth gettetherstats} took too long (670ms)
,11-17 05:02:08.683   507   925 D TetherController: Setting IP forward enable = 0
,11-17 05:02:08.686   507   925 D CommandListener: Setting iface cfg
,11-17 05:02:08.687   507   925 D CommandListener: Trying to bring down wlan0
11-17 05:02:08.690   507   925 D CommandListener: Clearing all IP addresses on wlan0
11-17 05:02:08.694   927  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-17 05:02:09.010   927  3910 D WifiService: setWifiEnabled: true pid=5653, uid=10077
11-17 05:02:09.014   927  3910 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:02:09.298   927  2985 D wifi    : set interface wlan0 flags (UP)
,11-17 05:02:09.298   927  2985 I WifiHAL : Initializing wifi
,11-17 05:02:09.298   927  2985 I WifiHAL : Creating socket
,11-17 05:02:09.302   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-17 05:02:09.308   927  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-17 05:02:09.308   927  2985 D wifi    : Did set static halHandle = 0x7f7c208680
11-17 05:02:09.308   927  2985 D wifi    : halHandle = 0x7f7c208680, mVM = 0x7f9888d140, mCls = 0x10199a
11-17 05:02:09.308   927  2985 D wifi    : array field set
11-17 05:02:09.308   927  2985 I WifiNative-HAL: interface[0] = wlan0
11-17 05:02:09.310   927  5866 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547543352960
,11-17 05:02:09.310   927  5866 D wifi    : waitForHalEvents called, vm = 0x7f9888d140, obj = 0x10199a, env = 0x7f7c262d40
,11-17 05:02:09.315   927  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-17 05:02:09.316   927  2985 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-17 05:02:09.384  5867  5867 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-17 05:02:09.406  5867  5867 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 05:02:09.417  5867  5867 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 05:02:09.417  5867  5867 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-17 05:02:09.516   927  3910 D WifiService: setWifiEnabled: true pid=5653, uid=10077
,11-17 05:02:09.516   927  3910 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:02:10.019   927  3916 D WifiService: setWifiEnabled: true pid=5653, uid=10077
,11-17 05:02:10.019   927  3916 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:02:10.333   927  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-17 05:02:10.357   927  2985 D WifiConfigStore: loaded 0 passpoint configs
,11-17 05:02:10.358   927  2985 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-17 05:02:10.359   927  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-17 05:02:10.361   927  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-17 05:02:10.362   927  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-17 05:02:10.363   927  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-17 05:02:10.363   927  2985 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,11-17 05:02:10.363   927  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-17 05:02:10.368   927  2985 D WifiNative-HAL: Setting external_sim to 1
11-17 05:02:10.368  5046  5046 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 05:02:10.368   927  2985 D wifi    : setting dfs flag to true, 0x7f80f7e360
,11-17 05:02:10.369   927  2985 D WifiStateMachine: Setting OUI to DA-A1-19
11-17 05:02:10.369   927  2985 D wifi    : setting scan oui 0x7f80f7e360
11-17 05:02:10.369   927  2985 D WifiHAL : Sending mac address OUI
,11-17 05:02:10.375   927  2985 E native  : do suspend false
,11-17 05:02:10.384   927  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-17 05:02:10.384   927   927 D RttService: SCAN_AVAILABLE : 3
11-17 05:02:10.385   507   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-17 05:02:10.385   927  3094 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-17 05:02:10.386   507   925 D CommandListener: Setting iface cfg
,11-17 05:02:10.390   927  2984 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
11-17 05:02:10.390   927  2984 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-17 05:02:10.401   927  2984 D WifiNative-HAL: p2pGetDeviceAddress
11-17 05:02:10.402   927  2984 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-17 05:02:10.408   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=136804 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 05:02:10.528  5653  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 05:02:10.534  5653  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-17 05:02:10.539  5653  5699 D BluetoothAdapter: enable(): BT is already enabled..!
,11-17 05:02:10.540   927  3910 D WifiService: setWifiEnabled: true pid=5653, uid=10077
11-17 05:02:10.541   927  3910 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 05:02:10.541  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 05:02:10.542  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:02:10.542  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-17 05:02:10.542  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb2c5ae removed from the list
,11-17 05:02:10.542  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 05:02:10.542  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ed5f4f removed from the list
,11-17 05:02:10.542  5653  5699 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 05:02:10.545  5653  5699 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-17 05:02:10.547  5653  5699 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-17 05:02:10.549  5653  5699 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-17 05:02:10.550  5653  5699 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-17 05:02:10.553  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-17 05:02:10.553  5653  5699 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-17 05:02:10.555  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-17 05:02:10.555  5653  5699 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-17 05:02:10.556  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-17 05:02:10.561  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-17 05:02:10.562  5653  5699 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@eb8977a Bundle[{}]
11-17 05:02:10.563  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-17 05:02:10.563  5653  5699 I io.jxcore.node.LifeCycleMonitor: start: OK
11-17 05:02:10.564  5653  5699 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-17 05:02:10.565  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-17 05:02:10.565  5653  5699 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-17 05:02:10.567  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-17 05:02:10.567  5653  5699 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-17 05:02:10.568  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-17 05:02:10.569  5653  5699 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-17 05:02:10.570  5653  5699 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-17 05:02:10.571  5653  5699 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-17 05:02:10.573  5653  5699 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-17 05:02:10.575  5653  5699 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-17 05:02:10.576  5653  5699 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-17 05:02:10.577  5653  5699 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-17 05:02:10.578  5653  5699 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-17 05:02:10.578  5653  5699 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-17 05:02:10.580  5653  5699 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-17 05:02:10.581  5653  5699 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-17 05:02:10.582  5653  5699 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-17 05:02:10.585  5653  5699 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-17 05:02:10.586  5653  5699 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-17 05:02:10.587  5653  5699 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-17 05:02:10.587  5653  5699 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-17 05:02:10.588  5653  5699 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-17 05:02:10.588  5653  5699 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-17 05:02:10.589  5653  5699 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-17 05:02:10.589  5653  5699 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-17 05:02:10.590  5653  5699 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-17 05:02:10.591  5653  5699 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-17 05:02:10.591  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 05:02:10.591  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bb3e5 added. We now have 3 listener(s)
,11-17 05:02:10.593  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:02:10.593  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:02:10.593  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 05:02:10.593  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:02:10.593  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4698eba added. We now have 3 listener(s)
11-17 05:02:10.593  5653  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 05:02:10.594  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-17 05:02:10.600  5653  5699 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-17 05:02:10.600  5653  5699 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-17 05:02:10.601  5653  5699 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-17 05:02:10.601  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-17 05:02:10.601  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.601  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.601  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.601  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:02:10.601  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:02:10.601  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:02:10.602  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:02:10.602  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 05:02:10.605  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-17 05:02:10.606  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-17 05:02:10.606  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:02:10.606  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:02:10.606  5653  5870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-17 05:02:10.607  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:02:10.608  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:02:10.608  5653  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:02:10.608  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:02:10.608  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-17 05:02:10.609  5795  5795 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31736]" dev="sockfs" ino=31736 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:02:10.609  5795  5795 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31736]" dev="sockfs" ino=31736 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:02:10.609  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 05:02:10.612  5653  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-17 05:02:10.616  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:02:10.616  5653  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:02:10.616  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-17 05:02:10.620  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:10.620  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-17 05:02:10.621  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:02:10.621  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:02:10.621  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-17 05:02:10.623  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.623  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.623  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:02:10.623  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-17 05:02:10.624  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:02:10.624  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
11-17 05:02:10.624  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:10.624  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:10.624  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.624  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:02:10.624  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:10.624  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:10.624  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.624  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.625  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:10.628  5756  5795 D BtGatt.GattService: registerClient() - UUID=7fc65523-469b-48f3-bf88-98f751a98ef7
11-17 05:02:10.628  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=7fc65523-469b-48f3-bf88-98f751a98ef7, clientIf=5
11-17 05:02:10.629  5653  5663 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-17 05:02:10.632  5756  5774 D BtGatt.AdvertiseManager: message : 0
,11-17 05:02:10.634  5756  5774 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:02:10.658  5756  5772 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:02:10.665  5756  5772 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:02:10.665  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:10.665  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.665  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:02:10.665  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.665  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.666  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.666  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.666  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.666  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-17 05:02:10.667  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:02:10.667  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:10.668  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:10.668  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.669  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:10.669  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:02:10.669  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.669  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:10.669  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:02:10.669  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.669  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.669  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-17 05:02:10.669  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.670  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:02:10.670  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:02:10.670  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.670  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.670  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:02:10.670  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 05:02:10.673  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-17 05:02:10.673  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-17 05:02:10.673  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.673  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.673  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:10.673  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:02:11.174  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-17 05:02:11.174  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-17 05:02:11.174  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-17 05:02:13.461  5867  5867 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 05:02:13.464  5867  5867 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 05:02:13.468  5867  5867 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 05:02:13.521   927  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-17 05:02:13.522   927  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-17 05:02:13.522   927  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 05:02:13.536   927  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-17 05:02:13.571   927  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-17 05:02:13.574  5867  5867 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-17 05:02:13.996  5867  5867 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-17 05:02:14.037  5867  5867 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-17 05:02:14.038  5867  5867 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-17 05:02:14.045   927  2985 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 05:02:14.045   927  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 05:02:14.045   927  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-17 05:02:14.062   927  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 05:02:14.074   507   925 D CommandListener: Setting iface cfg
,11-17 05:02:14.080   927  2985 D WifiStateMachine: Start Dhcp Watchdog 2
,11-17 05:02:14.091   927  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:02:14.091   927  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-17 05:02:14.091   927  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-17 05:02:14.093   927  5877 D DhcpClient: Receive thread started
,11-17 05:02:14.173  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-17 05:02:14.173  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-17 05:02:14.173   927  2985 E native  : do suspend false
11-17 05:02:14.173  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-17 05:02:14.174  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-17 05:02:14.174  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:02:14.175  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-17 05:02:14.175  5653  5870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:02:14.175  5653  5870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-17 05:02:14.175  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-17 05:02:14.176  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-17 05:02:14.176  5653  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:02:14.176  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-17 05:02:14.176  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:02:14.176  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:02:14.176  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:02:14.177  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-17 05:02:14.177  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:02:14.177  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:02:14.177  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.177  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.177  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:14.178  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.180  5653  5699 D BluetoothAdapter: STATE_ON
,11-17 05:02:14.180  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:02:14.183  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:14.183  5653  5699 D BluetoothLeScanner: could not find callback wrapper
,11-17 05:02:14.183  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-17 05:02:14.184  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.184  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.185  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.185  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-17 05:02:14.185  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.192  5756  5774 D BtGatt.AdvertiseManager: message : 1
11-17 05:02:14.192   927  5876 D DhcpClient: Broadcasting DHCPDISCOVER
11-17 05:02:14.193  5756  5774 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:02:14.200  5756  5772 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-17 05:02:14.201  5756  5772 D BtGatt.GattService: Client app is not null!
,11-17 05:02:14.202  5756  5767 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 05:02:14.202  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 05:02:14.202  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:14.203  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-17 05:02:14.203  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.203  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.203  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.204  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-17 05:02:14.204  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:02:14.204  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:02:14.205  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.206  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.206  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-17 05:02:14.206  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.207  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.207  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 05:02:14.207  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-17 05:02:14.207  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:14.207  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:14.207  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:14.207  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.207  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:02:14.208  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:02:14.208  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-17 05:02:14.208  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.208  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-17 05:02:14.208  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.210  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.211  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.211  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.211  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.211  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:14.211   927  5877 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172701, domain null
,11-17 05:02:14.212   927  5876 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172701 seconds
11-17 05:02:14.212   927  5876 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-17 05:02:14.213  5653  5699 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-17 05:02:14.214  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 05:02:14.215  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 05:02:14.215  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-17 05:02:14.215  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-17 05:02:14.215  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:02:14.215  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-17 05:02:14.217  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 05:02:14.221  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-17 05:02:14.222  5653  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-17 05:02:14.222  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-17 05:02:14.227   927  5877 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-17 05:02:14.227   927  5876 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-17 05:02:14.227  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:14.227  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-17 05:02:14.228  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-17 05:02:14.228  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:02:14.228  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-17 05:02:14.228   507   925 D CommandListener: Setting iface cfg
,11-17 05:02:14.230   927  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-17 05:02:14.232  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-17 05:02:14.234   927  5876 D DhcpClient: Scheduling renewal in 86399s
11-17 05:02:14.235  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-17 05:02:14.235  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.235  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-17 05:02:14.235  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-17 05:02:14.235  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-17 05:02:14.236  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-17 05:02:14.236  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.237  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:14.239  5756  5795 D BtGatt.GattService: registerClient() - UUID=a266459c-b011-4bff-b29b-678be5d810b6
11-17 05:02:14.239  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=a266459c-b011-4bff-b29b-678be5d810b6, clientIf=5
,11-17 05:02:14.240  5653  5664 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-17 05:02:14.242  5756  5766 D BtGatt.GattService: start scan with filters
,11-17 05:02:14.243   927  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-17 05:02:14.244   927  2985 D WifiConfigStore: No blacklist allowed without epno enabled
,11-17 05:02:14.245   927  2985 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-17 05:02:14.246  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-17 05:02:14.246  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.246  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-17 05:02:14.246   927  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-17 05:02:14.246  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.247  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:02:14.247  5756  5776 D BtGatt.ScanManager: handling starting scan
,11-17 05:02:14.248   927  2987 D ConnectivityService: Adding iface wlan0 to network 101
11-17 05:02:14.248  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:14.248  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.248  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-17 05:02:14.248  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:02:14.249  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.249  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-17 05:02:14.249  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-17 05:02:14.249  5756  5776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@faa7d0f
11-17 05:02:14.249  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:02:14.249  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.255  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.255  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-17 05:02:14.255  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.255  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:14.256  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.258  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.258  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.258  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.258  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:14.258  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 05:02:14.259  5756  5772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-17 05:02:14.259  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:14.260  5756  5776 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-17 05:02:14.266  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-17 05:02:14.266  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:14.266  5756  5776 D BtGatt.ScanManager: Starting BLE batch scan
,11-17 05:02:14.267  5756  5776 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-17 05:02:14.277   927  2987 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-17 05:02:14.277  5756  5772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-17 05:02:14.277  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:14.277   927  2987 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-17 05:02:14.278   927  2987 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-17 05:02:14.279   927  2987 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-17 05:02:14.281   927  2987 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-17 05:02:14.282  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-17 05:02:14.282  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:14.287   927  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:02:14.291   927  2987 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-17 05:02:14.291   927  2987 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-17 05:02:14.291   927  2987 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-17 05:02:14.291   927  2987 D ConnectivityService:    accepting network in place of null
11-17 05:02:14.291   927  2985 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-17 05:02:14.291   927  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 05:02:14.292   927  2987 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 05:02:14.313   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:02:14.331   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:02:14.333   927  2987 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-17 05:02:14.333   927  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-17 05:02:14.333  3790  3924 W QCNEJ   : |CORE| network available: 101
11-17 05:02:14.334   927  2987 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-17 05:02:14.334   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-17 05:02:14.338  3790  3924 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-17 05:02:14.339  3790  3924 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-17 05:02:14.339  3790  3924 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-17 05:02:14.346  5072  5102 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-17 05:02:14.347  5072  5102 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 05:02:14.347  5072  5102 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-17 05:02:14.347  5072  5102 E SarControlService: no key has been found,reset the power
,11-17 05:02:14.347  5072  5116 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 05:02:14.348  5072  5116 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-17 05:02:14.348  5072  5116 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 05:02:14.348  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:02:14.349  5104  5104 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 05:02:14.350  4965  4965 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-17 05:02:14.352  3747  3747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-17 05:02:14.356  5104  5119 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5877696 HexData = [00000000ec03000000000000ffffffff]
,11-17 05:02:14.356  5104  5119 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 05:02:14.356  5104  5119 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-17 05:02:14.356  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 05:02:14.357  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-17 05:02:14.357  3747  3747 D SystemUpdateService: onCreate
,11-17 05:02:14.358  5072  5116 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-17 05:02:14.359  5072  5116 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 05:02:14.359  5072  5116 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 05:02:14.359  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:02:14.359  5104  5104 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-17 05:02:14.362  5104  5119 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5877696 HexData = [00000000ed03000000000000ffffffff]
11-17 05:02:14.362  5104  5119 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-17 05:02:14.362  5104  5119 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-17 05:02:14.362  5104  5104 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 05:02:14.363  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-17 05:02:14.365  3747  3747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 05:02:14.375  3747  3747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-17 05:02:14.379  3747  5439 I iu.UploadsManager: num queued entries: 0
,11-17 05:02:14.379  3747  5439 I iu.UploadsManager: num updated entries: 0
,11-17 05:02:14.387  3747  3747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 05:02:14.387   927  5875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-17 05:02:14.390  3747  5888 I SystemUpdateService: active receiver: enabled
,11-17 05:02:14.391  3747  3747 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 05:02:14.393  5830  5830 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 05:02:14.397  5830  5830 D SprintDMHelper: simOperator: 
11-17 05:02:14.397  5830  5830 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-17 05:02:14.397  3747  5439 I iu.SyncManager: NEXT; no task
,11-17 05:02:14.416  3747  5888 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 05:02:14.430  3747  5888 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-17 05:02:14.430  3747  5888 I SystemUpdateService: now status is 0 (complete)
11-17 05:02:14.430  3747  5888 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 05:02:14.430  3747  5888 I SystemUpdateService: file has been verified
11-17 05:02:14.431  3747  5888 I SystemUpdateService: OTA package size = 21989297
,11-17 05:02:14.438  3747  5888 I SystemUpdateService: showing system update notification
,11-17 05:02:14.448  3747  3747 D SystemUpdateService: onDestroy
,11-17 05:02:14.482   927  5874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-17 05:02:14.514  5046  5893 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-17 05:02:14.549   927  5874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Nov 2016 10:02:14 GMT], X-Android-Received-Millis=[1479376934548], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479376934505]}
,11-17 05:02:14.550   927  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-17 05:02:14.550   927  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-17 05:02:14.550   927  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-17 05:02:14.551   927  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-17 05:02:14.760  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-17 05:02:14.760  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-17 05:02:14.760  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-17 05:02:14.762   927  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,11-17 05:02:14.786  5756  5756 D BtGatt.ScanManager: awakened up at time 141182
,11-17 05:02:14.788  5756  5776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:02:14.815  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-17 05:02:14.815  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:14.816  5756  5772 D BtGatt.GattService: current time is 141212539424
,11-17 05:02:14.816  5756  5772 D BtGatt.GattService: Batch record : [-9, 64, -60, 50, 69, 101, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111, 0]
,11-17 05:02:14.819  5756  5772 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111]
,11-17 05:02:14.825  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
,11-17 05:02:14.826  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=65:45:32:C4:40:F7, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=141113184164}
11-17 05:02:14.826  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=65:45:32:C4:40:F7, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=141113184164}
,11-17 05:02:14.827  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
11-17 05:02:14.827  5653  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
,11-17 05:02:14.828  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 4]
11-17 05:02:14.828  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 4]
11-17 05:02:14.828  5653  5653 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 4]
11-17 05:02:14.828  5653  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
11-17 05:02:14.828  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [<no peer name> A8:81:95:E9:5F:6F 4]
,11-17 05:02:14.829  5653  5653 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 4], added - the peer count is 1
11-17 05:02:14.829  5653  5653 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 4], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
,11-17 05:02:15.320  5756  5756 D BtGatt.ScanManager: awakened up at time 141716
,11-17 05:02:15.323  5756  5776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:02:15.334   927  2987 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-17 05:02:15.350  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-17 05:02:15.350  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:15.350  5756  5772 D BtGatt.GattService: current time is 141747015206
11-17 05:02:15.351  5756  5772 D BtGatt.GattService: Batch record : [-9, 64, -60, 50, 69, 101, 1, -128, -61, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
11-17 05:02:15.351  5756  5772 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111]
,11-17 05:02:15.351  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-17 05:02:15.352  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
11-17 05:02:15.353  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-91, mTimestampNanos=141447438071}
11-17 05:02:15.353  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-91, mTimestampNanos=141447438071}
11-17 05:02:15.354  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=65:45:32:C4:40:F7, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=141397438071}
,11-17 05:02:15.354  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=65:45:32:C4:40:F7, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=141397438071}
11-17 05:02:15.354  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
11-17 05:02:15.354  5653  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
,11-17 05:02:15.355  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 4]
11-17 05:02:15.355  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 4]
,11-17 05:02:15.355  5653  5653 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 4]
11-17 05:02:15.355  5653  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
,11-17 05:02:15.355  5653  5653 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 4] updated - the peer count is 1
,11-17 05:02:17.113   927  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:02:17.258  5653  5699 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-17 05:02:17.258  5653  5699 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-17 05:02:17.259  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-17 05:02:17.259  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.259  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.260  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-17 05:02:17.260  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:17.260  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-17 05:02:17.261  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:17.261  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.261  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:02:17.261  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:02:17.261  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:17.262  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.262  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.265  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:17.266  5756  5795 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-17 05:02:17.267  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:02:17.269  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:17.271  5756  5786 D BtGatt.GattService: stopScan() - queue size =1
,11-17 05:02:17.276  5756  5776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-17 05:02:17.276  5756  5767 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 05:02:17.277  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-17 05:02:17.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-17 05:02:17.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.278  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:02:17.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.278  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.278  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-17 05:02:17.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-17 05:02:17.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-17 05:02:17.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-17 05:02:17.279  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.280  5653  5699 D BluetoothAdapter: STATE_ON
,11-17 05:02:17.283  5756  5756 D BtGatt.ScanManager: awakened up at time 143679
11-17 05:02:17.284  5756  5766 D BtGatt.GattService: registerClient() - UUID=4b8f67d7-ff5d-4c4f-b16e-96b5d8fa3812
,11-17 05:02:17.285  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=4b8f67d7-ff5d-4c4f-b16e-96b5d8fa3812, clientIf=5
,11-17 05:02:17.285  5653  5663 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-17 05:02:17.286  5756  5786 D BtGatt.GattService: start scan with filters
,11-17 05:02:17.290  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-17 05:02:17.291  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.291  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-17 05:02:17.291  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.291  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.291  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:17.291  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.291  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-17 05:02:17.291  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-17 05:02:17.291  5653  5699 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:02:17.291  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-17 05:02:17.291  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:02:17.291  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:02:17.292  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-17 05:02:17.292  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:17.292  5756  5772 D BtGatt.GattService: current time is 143688594614
11-17 05:02:17.292  5756  5772 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-17 05:02:17.292  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-17 05:02:17.292  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-17 05:02:17.293  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-17 05:02:17.293  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:02:17.293  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:02:17.293  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:02:17.293  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:02:17.293  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-17 05:02:17.291  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.293  5653  5900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-17 05:02:17.293  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.294  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:02:17.294  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:02:17.294  5653  5699 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-17 05:02:17.297  5653  5900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:02:17.296  5795  5795 W Binder_4: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[34867]" dev="sockfs" ino=34867 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:02:17.296  5795  5795 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34867]" dev="sockfs" ino=34867 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:02:17.300  5653  5900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-17 05:02:17.301  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-17 05:02:17.301  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:17.301  5756  5776 D BtGatt.ScanManager: stopping BLe Batch
,11-17 05:02:17.302  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.302  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:17.302  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.302  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:02:17.303  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:02:17.303  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:02:17.303  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
11-17 05:02:17.303  5653  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:17.303  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:17.303  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.303  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-17 05:02:17.303  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:02:17.303  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.303  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.304  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.304  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:17.306  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-17 05:02:17.306  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:17.306  5756  5786 D BtGatt.GattService: registerClient() - UUID=599585d7-b4a9-42d3-b390-682a45ce2325
11-17 05:02:17.306  5756  5776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-17 05:02:17.307  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=599585d7-b4a9-42d3-b390-682a45ce2325, clientIf=6
,11-17 05:02:17.307  5653  5663 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-17 05:02:17.308  5756  5774 D BtGatt.AdvertiseManager: message : 0
,11-17 05:02:17.312  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-17 05:02:17.312  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:17.313  5756  5774 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:02:17.314  5756  5776 D BtGatt.ScanManager: handling starting scan
,11-17 05:02:17.322  5756  5772 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-17 05:02:17.325  5756  5772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-17 05:02:17.326  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:17.326  5756  5776 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-17 05:02:17.329  5756  5772 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-17 05:02:17.330  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:17.330  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.330  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:02:17.330  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.330  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.330  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.331  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.331  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.331  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.331  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.331  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.331  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-17 05:02:17.331  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-17 05:02:17.331  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:02:17.332  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:02:17.332  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.334  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-17 05:02:17.334  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:17.334  5756  5776 D BtGatt.ScanManager: Starting BLE batch scan
11-17 05:02:17.334  5756  5776 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-17 05:02:17.335  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.335  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.335  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:17.335  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-17 05:02:17.335  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.335  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -1,1, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-85, mTimestampNanos=141788857427}
,11-17 05:02:17.335  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-85, mTimestampNanos=141788857427}
11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
,11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=142138857427}
11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=142138857427}
11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-17 05:02:17.336  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.337  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-17 05:02:17.337  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-17 05:02:17.337  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.339  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.340  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-17 05:02:17.340  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.340  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.340  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:17.340  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-17 05:02:17.343  5756  5772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-17 05:02:17.343  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:17.347  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-17 05:02:17.348  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:17.841  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-17 05:02:17.841  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-17 05:02:17.841  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-17 05:02:18.142   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:19.143   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:20.144   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:20.338  5653  5699 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-17 05:02:20.339  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 05:02:20.339  5653  5699 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-17 05:02:20.339  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:02:20.340  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:02:20.340  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-17 05:02:20.340  5653  5900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:02:20.340  5653  5900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:02:20.340  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-17 05:02:20.341  5653  5900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:02:20.341  5653  5699 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-17 05:02:20.341  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 05:02:20.341  5653  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bb3e5 removed from the list
11-17 05:02:20.341  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 05:02:20.341  5653  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:02:20.342  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:02:20.342  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:02:20.343  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:02:20.343  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:02:20.343  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:02:20.343  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.344  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.344  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.344  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-17 05:02:20.344  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.346  5653  5699 D BluetoothAdapter: STATE_ON
11-17 05:02:20.346  5756  5795 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-17 05:02:20.347  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:02:20.348  5756  5776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-17 05:02:20.349  5653  5699 D BluetoothAdapter: STATE_ON
,11-17 05:02:20.350  5756  5786 D BtGatt.GattService: stopScan() - queue size =1
11-17 05:02:20.352  5756  5766 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:02:20.353  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:02:20.353  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.354  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-17 05:02:20.354  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.354  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:20.354  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.354  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:02:20.354  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.356  5756  5774 D BtGatt.AdvertiseManager: message : 1
11-17 05:02:20.357  5756  5756 D BtGatt.ScanManager: awakened up at time 146754
11-17 05:02:20.359  5756  5774 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-17 05:02:20.372  5756  5772 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-17 05:02:20.372  5756  5772 D BtGatt.GattService: Client app is not null!
11-17 05:02:20.373  5756  5766 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-17 05:02:20.374  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-17 05:02:20.374  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.374  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-17 05:02:20.374  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.374  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.374  5653  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.375  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 05:02:20.375  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:02:20.375  5653  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:02:20.376  5653  5699 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,11-17 05:02:20.376  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.381  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:02:20.381  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:20.381  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:20.381  5653  5699 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:02:20.381  5653  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4698eba removed from the list
11-17 05:02:20.381  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:20.381  5653  5699 D io.jxcore.node.ConnectivityMonitor: stop
11-17 05:02:20.381  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:02:20.381  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:20.382  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.382  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:02:20.382  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-17 05:02:20.382  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-17 05:02:20.382  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.382  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-17 05:02:20.382  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.383  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-17 05:02:20.383  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-17 05:02:20.383  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-17 05:02:20.383  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-17 05:02:20.383  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 05:02:20.383  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.383  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.383  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.384  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.384  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-17 05:02:20.384  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:02:20.384  5653  5699 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-17 05:02:20.384  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.384  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:02:20.384  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:02:20.384  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.384  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:02:20.384  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:02:20.384  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-17 05:02:20.386  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-17 05:02:20.386  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-17 05:02:20.388  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-17 05:02:20.389  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-17 05:02:20.389  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-17 05:02:20.390  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-17 05:02:20.391  5653  5699 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-17 05:02:20.403  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,11-17 05:02:20.403  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:20.403  5756  5772 D BtGatt.GattService: current time is 146800042494
11-17 05:02:20.404  5756  5772 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -85, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -89, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -124, -38, -16, 14, -89, 117, 1, -128, -58, 43, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111, 0, 28, -25, 115, 7, 71, 121, 1, -128, -58, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -90, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-17 05:02:20.404  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-17 05:02:20.404  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-17 05:02:20.404  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-17 05:02:20.404  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-17 05:02:20.405  5756  5772 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111]
,11-17 05:02:20.405  5756  5772 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -88, -127, -107, -23, 95, 111]
11-17 05:02:20.405  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-17 05:02:20.405  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-17 05:02:20.411  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-17 05:02:20.411  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:20.411  5756  5776 D BtGatt.ScanManager: stopping BLe Batch
,11-17 05:02:20.416  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-17 05:02:20.416  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:02:20.416  5756  5776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:02:20.421  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-17 05:02:20.421  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:02:20.884  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 05:02:21.145   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:22.146   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:22.296   927  2987 D ConnectivityService: handlePromptUnvalidated 101
,11-17 05:02:22.396  5653  5699 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-17 05:02:22.566  5653  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 05:02:22.566  5653  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:02:23.147   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-17 05:02:23.368  5653  5902 W !!      : call onHalfStreamCopied
,11-17 05:02:23.368  5653  5902 I testCopyDataAndClose: closing input stream
,11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 05:02:24.147  5653  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-17 05:02:25.404   927  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-17 05:02:27.952  5653  5699 I StreamCopyingThreadTest: Starting test: testRun
,11-17 05:02:27.955  5653  5903 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:02:27.955  5653  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:02:32.964  5653  5904 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-17 05:02:32.967  5653  5699 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-17 05:02:33.082  5653  5905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 05:02:33.082  5653  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 05:02:34.766  5653  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-17 05:02:37.888   927  5875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164284, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-17 05:02:38.148   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:38.515  5653  5699 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-17 05:02:38.517  5653  5906 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:02:38.517  5653  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 05:02:38.518  5653  5906 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-17 05:02:38.519  5653  5906 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-17 05:02:38.519  5653  5906 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:02:38.519  5653  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-17 05:02:38.520  5653  5699 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-17 05:02:38.521  5653  5699 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-17 05:02:38.522  5653  5699 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-17 05:02:38.524  5653  5907 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:02:38.524  5653  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:02:38.524  5653  5907 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-17 05:02:38.524  5653  5907 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:02:38.524  5653  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-17 05:02:38.525  5653  5907 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-17 05:02:38.525  5653  5907 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:02:38.525  5653  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-17 05:02:38.526  5653  5699 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-17 05:02:38.527  5653  5699 E com.test.thalitest.ThaliTestRunner: 
11-17 05:02:38.527  5653  5699 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-17 05:02:38.527  5653  5699 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:,268)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessag,e(Handler.java:95)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:02:38.528  5653  5699 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.jun,it.runners.Suite.runChild(Suite.java:128)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-17 05:02:38.529  5653  5699 E co,m.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunn,er.java:325)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-17 05:02:38.529  5653  5699 E com.,test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:38.529  5653  5699 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-17 05:02:38.532  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG UnitTest_app: 'Running unit tests'
11-17 05:02:38.532  5653  5699 I jxcore-log: 
11-17 05:02:38.532  5653  5699 I jxcore-log: *Native tests were executed*
11-17 05:02:38.532  5653  5699 I jxcore-log: 
11-17 05:02:38.532  5653  5699 I jxcore-log: Total number of executed tests:  82
11-17 05:02:38.532  5653  5699 I jxcore-log: 
11-17 05:02:38.532  5653  5699 I jxcore-log: Number of passed tests:  79
11-17 05:02:38.532  5653  5699 I jxcore-log: 
11-17 05:02:38.532  5653  5699 I jxcore-log: Number of failed tests:  3
11-17 05:02:38.532  5653  5699 I jxcore-log: 
11-17 05:02:38.532  5653  5699 I jxcore-log: Number of ignored tests:  0
11-17 05:02:38.532  5653  5699 I jxcore-log: 
11-17 05:02:38.533  5653  5699 I jxcore-log: Total duration:  39471
11-17 05:02:38.533  5653  5699 I jxcore-log: 
11-17 05:02:38.533  5653  5699 I jxcore-log: Failed to execute UT.
11-17 05:02:38.533  5653  5699 I jxcore-log: 
11-17 05:02:38.534  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-17 05:02:38.534  5653  5699 I jxcore-log: 
11-17 05:02:38.535  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-17 05:02:38.535  5653  5699 I jxcore-log: 
11-17 05:02:38.538  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:02:38.538  5653  5699 I jxcore-log: 
11-17 05:02:38.538  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:02:38.538  5653  5699 I jxcore-log: 
,11-17 05:02:38.539  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:02:38.539  5653  5699 I jxcore-log: 
,11-17 05:02:38.540  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:02:38.540  5653  5699 I jxcore-log: 
11-17 05:02:38.540  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:02:38.540  5653  5699 I jxcore-log: 
11-17 05:02:38.541  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:02:38.541  5653  5699 I jxcore-log: 
11-17 05:02:38.541  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.541  5653  5699 I jxcore-log: 
,11-17 05:02:38.541  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:02:38.541  5653  5699 I jxcore-log: 
11-17 05:02:38.541  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:02:38.541  5653  5699 I jxcore-log: 
11-17 05:02:38.542  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.542  5653  5699 I jxcore-log: 
,11-17 05:02:38.542  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:02:38.542  5653  5699 I jxcore-log: 
11-17 05:02:38.542  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:02:38.542  5653  5699 I jxcore-log: 
11-17 05:02:38.542  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.542  5653  5699 I jxcore-log: 
,11-17 05:02:38.543  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 05:02:38.543  5653  5699 I jxcore-log: 
11-17 05:02:38.543  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.543  5653  5699 I jxcore-log: 
11-17 05:02:38.543  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:02:38.543  5653  5699 I jxcore-log: 
11-17 05:02:38.543  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:02:38.543  5653  5699 I jxcore-log: 
11-17 05:02:38.543  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 05:02:38.543  5653  5699 I jxcore-log: 
11-17 05:02:38.544  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.544  5653  5699 I jxcore-log: 
11-17 05:02:38.544  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:02:38.544  5653  5699 I jxcore-log: 
11-17 05:02:38.544  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:02:38.544  5653  5699 I jxcore-log: 
11-17 05:02:38.544  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:02:38.544  5653  5699 I jxcore-log: 
11-17 05:02:38.544  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:02:38.544  5653  5699 I jxcore-log: 
11-17 05:02:38.545  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-17 05:02:38.545  5653  5699 I jxcore-log: 
11-17 05:02:38.545  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:02:38.545  5653  5699 I jxcore-log: 
11-17 05:02:38.545  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-17 05:02:38.545  5653  5699 I jxcore-log: 
11-17 05:02:38.545  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:02:38.545  5653  5699 I jxcore-log: 
11-17 05:02:38.545  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:02:38.545  5653  5699 I jxcore-log: 
11-17 05:02:38.547  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:02:38.547  5653  5699 I jxcore-log: 
11-17 05:02:38.547  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.547  5653  5699 I jxcore-log: 
11-17 05:02:38.547  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-17 05:02:38.547  5653  5699 I jxcore-log: 
11-17 05:02:38.548  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:02:38.548  5653  5699 I jxcore-log: 
11-17 05:02:38.548  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.548  5653  5699 I jxcore-log: 
11-17 05:02:38.548  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"A8:81:95:E9:5F:6F-4","peerAvailable":true,"pleaseConnect":false}]'
11-17 05:02:38.548  5653  5699 I jxcore-log: 
11-17 05:02:38.549  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8:81:95:E9:5F:6F-4","peerAvailable":true,"pleaseConnect":false}'
11-17 05:02:38.549  5653  5699 I jxcore-log: 
11-17 05:02:38.549  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
11-17 05:02:38.549  5653  5699 I jxcore-log: 
11-17 05:02:38.549  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-17 05:02:38.549  5653  5699 I jxcore-log: 
11-17 05:02:38.549  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:02:38.549  5653  5699 I jxcore-log: 
11-17 05:02:38.549  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.549  5653  5699 I jxcore-log: 
11-17 05:02:38.550  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 05:02:38.550  5653  5699 I jxcore-log: 
11-17 05:02:38.550  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:02:38.550  5653  5699 I jxcore-log: 
11-17 05:02:38.554  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-17 05:02:38.554  5653  5699 I jxcore-log: 
11-17 05:02:38.555  5653  5699 I jxcore-log: 2016-11-17 10:02:38 - WARN testUtils: 'myNameCallback not set!'
11-17 05:02:38.555  5653  5699 I jxcore-log: 
11-17 05:02:38.557  5653  5653 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-17 05:02:39.149   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:40.151   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:40.627  5653  5699 I jxcore-log: 2016-11-17 10:02:40 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-17 05:02:40.627  5653  5699 I jxcore-log: 
,11-17 05:02:40.628  5653  5699 I jxcore-log: 2016-11-17 10:02:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-17 05:02:40.628  5653  5699 I jxcore-log: 
,11-17 05:02:40.969  5653  5699 I jxcore-log: 2016-11-17 10:02:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-17 05:02:40.969  5653  5699 I jxcore-log: 
,11-17 05:02:40.981  5653  5699 I jxcore-log: 2016-11-17 10:02:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-17 05:02:40.981  5653  5699 I jxcore-log: 
,11-17 05:02:41.152   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:42.083  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-17 05:02:42.083  5653  5699 I jxcore-log: 
,11-17 05:02:42.153   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:02:42.249  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-17 05:02:42.249  5653  5699 I jxcore-log: 
,11-17 05:02:42.254  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-17 05:02:42.254  5653  5699 I jxcore-log: 
,11-17 05:02:42.266  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-17 05:02:42.266  5653  5699 I jxcore-log: 
,11-17 05:02:42.752  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-17 05:02:42.752  5653  5699 I jxcore-log: 
,11-17 05:02:42.796  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-17 05:02:42.796  5653  5699 I jxcore-log: 
,11-17 05:02:42.810  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-17 05:02:42.810  5653  5699 I jxcore-log: 
,11-17 05:02:42.814  5653  5699 I jxcore-log: 2016-11-17 10:02:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-17 05:02:42.814  5653  5699 I jxcore-log: 
,11-17 05:02:43.090  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-17 05:02:43.090  5653  5699 I jxcore-log: 
,11-17 05:02:43.154   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-17 05:02:43.216  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-17 05:02:43.216  5653  5699 I jxcore-log: 
,11-17 05:02:43.605  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-17 05:02:43.605  5653  5699 I jxcore-log: 
,11-17 05:02:43.612  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-17 05:02:43.612  5653  5699 I jxcore-log: 
,11-17 05:02:43.616  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-17 05:02:43.616  5653  5699 I jxcore-log: 
,11-17 05:02:43.620  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-17 05:02:43.620  5653  5699 I jxcore-log: 
,11-17 05:02:43.625  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-17 05:02:43.625  5653  5699 I jxcore-log: 
,11-17 05:02:43.663  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-17 05:02:43.663  5653  5699 I jxcore-log: 
,11-17 05:02:43.670  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-17 05:02:43.670  5653  5699 I jxcore-log: 
,11-17 05:02:43.698  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-17 05:02:43.698  5653  5699 I jxcore-log: 
,11-17 05:02:43.736  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-17 05:02:43.736  5653  5699 I jxcore-log: 
,11-17 05:02:43.744  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-17 05:02:43.744  5653  5699 I jxcore-log: 
,11-17 05:02:43.750  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-17 05:02:43.750  5653  5699 I jxcore-log: 
,11-17 05:02:43.766  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-17 05:02:43.766  5653  5699 I jxcore-log: 
,11-17 05:02:43.781  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-17 05:02:43.781  5653  5699 I jxcore-log: 
,11-17 05:02:43.787  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-17 05:02:43.787  5653  5699 I jxcore-log: 
,11-17 05:02:43.792  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-17 05:02:43.792  5653  5699 I jxcore-log: 
,11-17 05:02:43.806  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-17 05:02:43.806  5653  5699 I jxcore-log: 
,11-17 05:02:43.823  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-17 05:02:43.823  5653  5699 I jxcore-log: 
,11-17 05:02:43.838  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-17 05:02:43.838  5653  5699 I jxcore-log: 
,11-17 05:02:43.849  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-17 05:02:43.849  5653  5699 I jxcore-log: 
,11-17 05:02:43.861  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-17 05:02:43.861  5653  5699 I jxcore-log: 
,11-17 05:02:43.871  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-17 05:02:43.871  5653  5699 I jxcore-log: 
,11-17 05:02:43.885  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-17 05:02:43.885  5653  5699 I jxcore-log: 
,11-17 05:02:43.895  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-17 05:02:43.895  5653  5699 I jxcore-log: 
,11-17 05:02:43.902  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-17 05:02:43.902  5653  5699 I jxcore-log: 
,11-17 05:02:43.923  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-17 05:02:43.923  5653  5699 I jxcore-log: 
,11-17 05:02:43.929  5653  5699 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-17 05:02:43.930  5653  5699 I jxcore-log: 2016-11-17 10:02:43 - INFO testUtils: 'BLE multiple advertisement supported'
11-17 05:02:43.930  5653  5699 I jxcore-log: 
,11-17 05:02:44.007  5653  5699 I jxcore-log: 2016-11-17 10:02:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:44.007  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:44.007  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:44.007  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:44.007  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:44.007  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:44.007  5653  5699 I jxcore-log: 
,11-17 05:02:44.292  5653  5699 I jxcore-log: 2016-11-17 10:02:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:44.292  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:44.292  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:44.292  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:44.292  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:44.292  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:44.292  5653  5699 I jxcore-log: 
,11-17 05:02:44.295  5653  5699 I jxcore-log: 2016-11-17 10:02:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:44.295  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:44.295  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:44.295  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:44.295  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:44.295  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:44.295  5653  5699 I jxcore-log: 
,11-17 05:02:44.654  5653  5699 I jxcore-log: 2016-11-17 10:02:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:44.654  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:44.654  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:44.654  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:44.654  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:44.654  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:44.654  5653  5699 I jxcore-log: 
,11-17 05:02:44.656  5653  5699 I jxcore-log: 2016-11-17 10:02:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:44.656  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:44.656  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:44.656  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:44.656  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:44.656  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:44.656  5653  5699 I jxcore-log: 
,11-17 05:02:45.244  5653  5699 I jxcore-log: 2016-11-17 10:02:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:45.244  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:45.244  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:45.244  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:45.244  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:45.244  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:45.244  5653  5699 I jxcore-log: 
,11-17 05:02:45.248  5653  5699 I jxcore-log: 2016-11-17 10:02:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:45.248  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:45.248  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:45.248  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:45.248  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:45.248  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:45.248  5653  5699 I jxcore-log: 
,11-17 05:02:46.212  5653  5699 I jxcore-log: 2016-11-17 10:02:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:46.212  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:46.212  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:46.212  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:46.212  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:46.212  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:46.212  5653  5699 I jxcore-log: 
,11-17 05:02:46.218  5653  5699 I jxcore-log: 2016-11-17 10:02:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:46.218  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:46.218  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:46.218  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:46.218  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:46.218  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:46.218  5653  5699 I jxcore-log: 
,11-17 05:02:47.302  5653  5699 I jxcore-log: 2016-11-17 10:02:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:47.302  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:47.302  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:47.302  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:47.302  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:47.302  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:47.302  5653  5699 I jxcore-log: 
,11-17 05:02:47.305  5653  5699 I jxcore-log: 2016-11-17 10:02:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:47.305  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:47.305  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:47.305  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:47.305  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:47.305  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:47.305  5653  5699 I jxcore-log: 
,11-17 05:02:48.337  5653  5699 I jxcore-log: 2016-11-17 10:02:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:48.337  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:48.337  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:48.337  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:48.337  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:48.337  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:48.337  5653  5699 I jxcore-log: 
,11-17 05:02:48.342  5653  5699 I jxcore-log: 2016-11-17 10:02:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:48.342  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:48.342  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:48.342  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:48.342  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:48.342  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:48.342  5653  5699 I jxcore-log: 
,11-17 05:02:49.001   927  5875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-17 05:02:49.380  5653  5699 I jxcore-log: 2016-11-17 10:02:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:49.380  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:49.380  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:49.380  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:49.380  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:49.380  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:49.380  5653  5699 I jxcore-log: 
,11-17 05:02:49.384  5653  5699 I jxcore-log: 2016-11-17 10:02:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:49.384  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:49.384  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:49.384  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:49.384  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:49.384  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:49.384  5653  5699 I jxcore-log: 
,11-17 05:02:50.418  5653  5699 I jxcore-log: 2016-11-17 10:02:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:50.418  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:50.418  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:50.418  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:50.418  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:50.418  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:50.418  5653  5699 I jxcore-log: 
,11-17 05:02:50.422  5653  5699 I jxcore-log: 2016-11-17 10:02:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:50.422  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:50.422  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:50.422  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:50.422  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:50.422  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:50.422  5653  5699 I jxcore-log: 
,11-17 05:02:51.471  5653  5699 I jxcore-log: 2016-11-17 10:02:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:51.471  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:51.471  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:51.471  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:51.471  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:51.471  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:51.471  5653  5699 I jxcore-log: 
,11-17 05:02:51.474  5653  5699 I jxcore-log: 2016-11-17 10:02:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:51.474  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:51.474  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:51.474  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:51.474  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:51.474  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:51.474  5653  5699 I jxcore-log: 
,11-17 05:02:52.570  5653  5699 I jxcore-log: 2016-11-17 10:02:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:52.570  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:52.570  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:52.570  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:52.570  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:52.570  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:52.570  5653  5699 I jxcore-log: 
,11-17 05:02:52.578  5653  5699 I jxcore-log: 2016-11-17 10:02:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:52.578  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:52.578  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:52.578  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:52.578  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:52.578  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:52.578  5653  5699 I jxcore-log: 
,11-17 05:02:53.612  5653  5699 I jxcore-log: 2016-11-17 10:02:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:53.612  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:53.612  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:53.612  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:53.612  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:53.612  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:53.612  5653  5699 I jxcore-log: 
,11-17 05:02:53.617  5653  5699 I jxcore-log: 2016-11-17 10:02:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:53.617  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:53.617  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:53.617  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:53.617  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:53.617  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:53.617  5653  5699 I jxcore-log: 
,11-17 05:02:54.252   927  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-17 05:02:54.657  5653  5699 I jxcore-log: 2016-11-17 10:02:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:54.657  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:54.657  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:54.657  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:54.657  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:54.657  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:54.657  5653  5699 I jxcore-log: 
,11-17 05:02:54.661  5653  5699 I jxcore-log: 2016-11-17 10:02:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:54.661  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:54.661  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:54.661  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:54.661  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:54.661  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:54.661  5653  5699 I jxcore-log: 
,11-17 05:02:55.700  5653  5699 I jxcore-log: 2016-11-17 10:02:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:55.700  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:55.700  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:55.700  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:55.700  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:55.700  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:55.700  5653  5699 I jxcore-log: 
,11-17 05:02:55.703  5653  5699 I jxcore-log: 2016-11-17 10:02:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:55.703  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:55.703  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:55.703  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:55.703  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:55.703  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:55.703  5653  5699 I jxcore-log: 
,11-17 05:02:56.731  5653  5699 I jxcore-log: 2016-11-17 10:02:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:56.731  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:56.731  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:56.731  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:56.731  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:56.731  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:56.731  5653  5699 I jxcore-log: 
,11-17 05:02:56.738  5653  5699 I jxcore-log: 2016-11-17 10:02:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:56.738  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:56.738  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:56.738  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:56.738  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:56.738  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:56.738  5653  5699 I jxcore-log: 
,11-17 05:02:57.774  5653  5699 I jxcore-log: 2016-11-17 10:02:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:02:57.774  5653  5699 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:02:57.774  5653  5699 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:02:57.774  5653  5699 I jxcore-log: emit@events.js:82:1
11-17 05:02:57.774  5653  5699 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:02:57.774  5653  5699 I jxcore-log: emit@events.js:82:1'
11-17 05:02:57.774  5653  5699 I jxcore-log: 
,11-17 05:02:57.781  5653  5699 E jxcore  : Error!: error is undefined
11-17 05:02:57.781  5653  5699 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-17 05:02:57.783  5653  5699 I jxcore-log: 2016-11-17 10:02:57 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-17 05:02:57.783  5653  5699 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-17 05:02:57.783  5653  5699 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-17 05:02:57.783  5653  5699 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-17 05:02:57.783  5653  5699 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-17 05:02:57.783  5653  5699 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-17 05:02:57.783  5653  5699 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-17 05:02:57.783  5653  5699 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
11-17 05:02:57.784  5653  5699 I jxcore-log: 2016-11-17 10:02:57 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-17 05:02:57.784  5653  5699 I jxcore-log: 
11-17 05:02:57.785  5653  5699 E jxcore-log: TypeError: 
11-17 05:02:57.785  5653  5699 E jxcore-log: error is undefined
11-17 05:02:57.785  5653  5699 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-17 05:02:57.785  5653  5699 E jxcore-log: 
,11-17 05:02:58.302  5908  5908 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-17 05:02:58.322  5908  5908 D AndroidRuntime: CheckJNI is OFF
,11-17 05:02:58.351  5908  5908 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-17 05:02:58.380  5908  5908 I Radio-JNI: register_android_hardware_Radio DONE
,11-17 05:02:58.402  5908  5908 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 05:02:58.416   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-17 05:02:58.416   927   940 I ActivityManager: Killing 5653:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-17 05:02:58.531   927  3771 I WindowState: WIN DEATH: Window{f995211 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-17 05:02:58.532   927  2986 D WifiService: Client connection lost with reason: 4
11-17 05:02:58.531   927  3596 D GraphicsStats: Buffer count: 2
,11-17 05:02:58.561   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-17 05:02:58.561   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-17 05:02:58.562   927   940 E ActivityManager: Failure starting process com.test.thalitest
11-17 05:02:58.562   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-17 05:02:58.562   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:58.562   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.562   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:02:58.562   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-17 05:02:58.563   927   940 I ActivityManager:   Force finishing activity ActivityRecord{d73c74a u0 com.test.thalitest/.MainActivity t6}
11-17 05:02:58.563   927   952 I art     : Starting a blocking GC Explicit
,11-17 05:02:58.569   927  3421 W ActivityManager: Spurious death for ProcessRecord{bf01745 0:com.test.thalitest/u0a77}, curProc for 5653: null
,11-17 05:02:58.573   927   945 W WindowManager: Attempted to add application window with unknown token Token{e4096bb ActivityRecord{d73c74a u0 com.test.thalitest/.MainActivity t6 f}}.  Aborting.
,11-17 05:02:58.574   927   945 W WindowManager: Token{e4096bb ActivityRecord{d73c74a u0 com.test.thalitest/.MainActivity t6 f}} already running, starting window not displayed. Unable to add window -- token Token{e4096bb ActivityRecord{d73c74a u0 com.test.thalitest/.MainActivity t6 f}} is not valid; is your activity running?
11-17 05:02:58.574   927   945 W WindowManager: view not successfully added to wm, removing view
11-17 05:02:58.574   927   945 W WindowManager: Exception when adding starting window
11-17 05:02:58.574   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a323654 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-17 05:02:58.574   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-17 05:02:58.574   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-17 05:02:58.574   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-17 05:02:58.574   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-17 05:02:58.574   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-17 05:02:58.574   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:58.574   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.574   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:02:58.574   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-17 05:02:58.648   927   952 I art     : Explicit concurrent mark sweep GC freed 70861(4MB) AllocSpace objects, 21(668KB) LOS objects, 33% free, 28MB/43MB, paused 1.560ms total 84.240ms
,11-17 05:02:58.672   927   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-17 05:02:58.676  5908  5908 I art     : System.exit called, status: 0
,11-17 05:02:58.676  5908  5908 I AndroidRuntime: VM exiting with result code 0.
,11-17 05:02:58.683   927   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-17 05:02:58.693   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-17 05:02:58.696  3682  3682 I Keyboard.Facilitator: resetDictionaries() : en_US
11-17 05:02:58.699  5756  5756 D BluetoothMapAppObserver: onReceive
11-17 05:02:58.699  5756  5756 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-17 05:02:58.700   927  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-17 05:02:58.703  4078  4209 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 05:02:58.748  3824  3824 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-17 05:02:58.752  3682  5919 I Keyboard.Facilitator.DecoderInitializer: run()
11-17 05:02:58.753  3407  5920 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-17 05:02:58.756  3582  3582 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-17 05:02:58.756  3582  3582 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 05:02:58.763   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 05:02:58.791  3682  5919 I Decoder : createOrResetDecoder
,11-17 05:02:58.789    29    29 W kworker/3:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:02:58.793    29    29 W kworker/3:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:02:58.801  3747  5925 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-17 05:02:58.801  3747  5925 D AccountUtils: Clearing selected account for com.test.thalitest
,11-17 05:02:58.816    29    29 W kworker/3:1: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:02:58.824  3582  3582 I ConfigService: onCreate
,11-17 05:02:58.825  3851  3950 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-17 05:02:58.826  3582  5928 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-17 05:02:58.826  3582  5928 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 05:02:58.827  3407  3434 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjA3B17D957) - 
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 05:02:58.827 , 3582  5928 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-17 05:02:58.827  3582  5928 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-17 05:02:58.827   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-17 05:02:58.828   927   939 E PackageManager: Failed to write settings, restoring backup
11-17 05:02:58.828   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-17 05:02:58.828   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-17 05:02:58.828   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-17 05:02:58.828   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-17 05:02:58.828   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-17 05:02:58.828   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:58.828   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.828   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:02:58.830   927   940 E DropBoxManagerService: Can't write: system_server_wtf
11-17 05:02:58.830   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-17 05:02:58.830   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-17 05:02:58.830   927   940 E DropBoxManagerService: 	... 13 more
11-17 05:02:58.833  3582  5928 W SQLiteOpenHelper: Opened config.db in read-only mode
11-17 05:02:58.840   927   937 I ActivityManager: Start proc 5929:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-17 05:02:58.841  3851  3950 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-17 05:02:58.841  3851  3950 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3851
11-17 05:02:58.841  3851  3950 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.841  3851  3950 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:02:58.846   927  3596 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-17 05:02:58.851   927  5936 E DropBoxManagerService: Can't write: system_app_crash
11-17 05:02:58.851   927  5936 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-17 05:02:58.851   927  5936 E DropBoxManagerService: 	... 5 more
11-17 05:02:58.852  3851  3950 I Process : Sending signal. PID: 3851 SIG: 9
,11-17 05:02:58.857  3747  5925 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-17 05:02:58.867  3682  5919 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.879  3747  5925 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.879  3747  5925 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:02:58.880  3747  5925 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-17 05:02:58.906  3407  3434 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-17 05:02:58.906  3407  3434 E AndroidRuntime: Process: android.process.acore, PID: 3407
11-17 05:02:58.906  3407  3434 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:02:58.906  3407  3434 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 05:02:58.908   927  5944 E DropBoxManagerService: Can't write: system_app_crash
11-17 05:02:58.908   927  5944 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-17 05:02:58.908   927  5944 E DropBoxManagerService: 	... 5 more
,11-17 05:02:58.947   927  2948 W InputDispatcher: channel 'f668581 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-17 05:02:58.947   927  2948 E InputDispatcher: channel 'f668581 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
11-17 05:02:58.947  3407  3434 I Process : Sending signal. PID: 3407 SIG: 9
11-17 05:02:58.947   927   938 D GraphicsStats: Buffer count: 1
11-17 05:02:58.947   927  3596 I WindowState: WIN DEATH: Window{f668581 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-17 05:02:58.947   927  3596 W InputDispatcher: Attempted to unregister already unregistered input channel 'f668581 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-17 05:02:58.963   927  3910 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3851) has died
,11-17 05:02:58.964   927  3910 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-17 05:02:58.991  3747  5947 I GMPM-SVC: App measurement is starting up
,11-17 05:02:59.001  3747  5947 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-17 05:02:59.002  3747  5947 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-17 05:02:59.196   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
