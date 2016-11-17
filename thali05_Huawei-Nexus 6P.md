#### Test 937653172c2e8c7_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-17 05:52:33.361  5546  5591 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-17 05:52:33.416  5546  5591 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-17 05:52:33.444  5546  5591 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 05:52:33.534  3655  4897 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-17 05:52:33.574  3655  3655 I ConfigFetchService: fetch service done; releasing wakelock
11-17 05:52:33.575  3655  3655 I ConfigFetchService: stopping self
11-17 05:52:33.633  3655  4897 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,11-17 05:52:34.528  5604  5604 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-17 05:52:34.534  5604  5604 D AndroidRuntime: CheckJNI is OFF
11-17 05:52:34.564  5604  5604 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-17 05:52:34.601  5604  5604 I Radio-JNI: register_android_hardware_Radio DONE
11-17 05:52:34.615  5604  5604 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-17 05:52:34.619   928  3797 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-17 05:52:34.661   928  3797 I ActivityManager: Start proc 5614:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-17 05:52:34.670  5604  5604 D AndroidRuntime: Shutting down VM
,11-17 05:52:35.009   928  3782 I WindowManager: Screenshot max retries 4 of Token{ef70763 ActivityRecord{8407192 u0 com.test.thalitest/.MainActivity t6}} appWin=Window{964a0ea u0 Starting com.test.thalitest} drawState=4
,11-17 05:52:35.080  5614  5614 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-17 05:52:35.113  5614  5614 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-17 05:52:35.172  5614  5614 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 1620-1674)
11-17 05:52:35.172  5614  5614 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 05:52:35.207  5614  5614 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2bfaef8}
11-17 05:52:35.208  5614  5614 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 05:52:35.208  5614  5614 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 05:52:35.213  5614  5614 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-17 05:52:35.214  5614  5614 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-17 05:52:35.265  5614  5614 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-17 05:52:35.288  5614  5614 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-17 05:52:35.288  5614  5614 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 05:52:35.289  5614  5614 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-17 05:52:35.289  5614  5614 I Adreno  : Build Date                       : 12/06/15
11-17 05:52:35.289  5614  5614 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-17 05:52:35.289  5614  5614 I Adreno  : Local Branch                     : mybranch17112971
11-17 05:52:35.289  5614  5614 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-17 05:52:35.289  5614  5614 I Adreno  : Remote Branch                    : NONE
11-17 05:52:35.289  5614  5614 I Adreno  : Reconstruct Branch               : NOTHING
,11-17 05:52:35.333   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e7ccd89:true
,11-17 05:52:35.364   685   685 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[31054]" dev="sockfs" ino=31054 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 05:52:35.364   685   685 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31054]" dev="sockfs" ino=31054 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 05:52:35.378  5614  5614 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-17 05:52:35.387  5614  5614 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-17 05:52:35.414  5614  5651 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-17 05:52:35.411   685   685 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33898]" dev="sockfs" ino=33898 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-17 05:52:35.411   685   685 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33898]" dev="sockfs" ino=33898 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 05:52:35.414  3114  3114 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31066]" dev="sockfs" ino=31066 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-17 05:52:35.414  3114  3114 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31066]" dev="sockfs" ino=31066 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-17 05:52:35.420  5614  5638 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-17 05:52:35.450  5614  5651 I OpenGLRenderer: Initialized EGL, version 1.4
,11-17 05:52:35.531   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +521ms (total +898ms)
,11-17 05:52:35.556  5614  5614 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5614
,11-17 05:52:35.627  5614  5614 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 05:52:35.756  5614  5654 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -590870224
,11-17 05:52:35.761  5614  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-17 05:52:35.761  5614  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-17 05:52:35.761  5614  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-17 05:52:35.761  5614  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-17 05:52:35.761  5614  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-17 05:52:35.761  5614  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9875c9 added. We now have 1 listener(s)
,11-17 05:52:35.764  5614  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
11-17 05:52:35.765  5614  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:52:35.765  5614  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:52:35.766  5614  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-17 05:52:35.768  5614  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa9a585 added. We now have 1 listener(s)
11-17 05:52:35.768  5614  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 05:52:35.772   928  2897 D WifiService: New client listening to asynchronous messages
11-17 05:52:35.773  5614  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 05:52:35.773  5614  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-17 05:52:35.773  5614  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-17 05:52:35.773  5614  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-17 05:52:35.773  5614  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-17 05:52:35.773  5614  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-17 05:52:35.774  5614  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-17 05:52:35.775  5614  5654 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-17 05:52:35.903  5614  5614 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-17 05:52:36.200  5614  5660 W jxcore-log: Initializing JXcore engine
11-17 05:52:36.200  5614  5660 W jxcore-log: JXcore engine is ready
,11-17 05:52:36.231  5660  5660 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11658 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-17 05:52:36.231  5660  5660 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15428]" dev="sockfs" ino=15428 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 05:52:36.231  5660  5660 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-17 05:52:36.231  5660  5660 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33478]" dev="sockfs" ino=33478 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-17 05:52:36.242  5614  5660 W jxcore-log: Starting JXcore engine
,11-17 05:52:36.302  5614  5660 W jxcore-log: Platform android
11-17 05:52:36.302  5614  5660 W jxcore-log: 
,11-17 05:52:36.302  5614  5660 W jxcore-log: Process ARCH arm
11-17 05:52:36.302  5614  5660 W jxcore-log: 
,11-17 05:52:36.448  5614  5660 I jxcore-log: JXcore Cordova bridge is ready!
11-17 05:52:36.448  5614  5660 I jxcore-log: 
,11-17 05:52:36.449  5614  5660 W jxcore-log: JXcore engine is started
,11-17 05:52:36.457  5614  5654 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-17 05:52:36.460  5614  5614 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-17 05:52:38.584  3539  3539 I ConfigService: onDestroy
,11-17 05:52:43.661   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-17 05:52:46.338  5614  5660 I jxcore-log: 2016-11-17 10:52:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-17 05:52:46.338  5614  5660 I jxcore-log: 
,11-17 05:52:46.339  5614  5660 I jxcore-log: 2016-11-17 10:52:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-17 05:52:46.339  5614  5660 I jxcore-log: 
,11-17 05:52:46.345  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:52:46.345  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-17 05:52:46.346  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 05:52:46.349  5614  5660 I jxcore-log: 2016-11-17 10:52:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-17 05:52:46.349  5614  5660 I jxcore-log: 
,11-17 05:52:46.350  5614  5660 I jxcore-log: 2016-11-17 10:52:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-17 05:52:46.350  5614  5660 I jxcore-log: 
,11-17 05:52:46.601  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 05:52:46.602  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38e10fd added. We now have 2 listener(s)
11-17 05:52:46.602  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:52:46.602  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:52:46.602  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-17 05:52:46.603  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:52:46.603  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5881f2 added. We now have 2 listener(s)
,11-17 05:52:46.603  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 05:52:46.603  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 05:52:46.605  5614  5660 D ExecuteNativeTests: Running unit tests
,11-17 05:52:46.605  5614  5660 D BluetoothAdapter: enable(): BT is already enabled..!
,11-17 05:52:46.605   928  3807 D WifiService: setWifiEnabled: true pid=5614, uid=10077
11-17 05:52:46.606   928  3807 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:52:46.949  4791  4854 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-17 05:52:46.951  4791  4791 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-17 05:52:48.311   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-17 05:52:48.311   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-17 05:52:53.313   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:52:54.316   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:52:54.325   928  2889 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-17 05:52:55.317   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:52:56.319   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:52:56.612  5614  5660 I com.test.thalitest.ThaliTestRunner: Running UT
,11-17 05:52:56.683  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 05:52:56.683  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d181e87 added. We now have 3 listener(s)
11-17 05:52:56.684  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:52:56.684  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-17 05:52:56.684  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 05:52:56.684  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:52:56.684  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffc51b4 added. We now have 3 listener(s)
11-17 05:52:56.684  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 05:52:56.685  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-17 05:52:56.689  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-17 05:52:56.689  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 05:52:56.690  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:56.690  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:56.690  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:56.691  5614  5660 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-17 05:52:56.691  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-17 05:52:56.691  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 05:52:56.691  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:52:56.691  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:52:56.691  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-17 05:52:56.692  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-17 05:52:56.692  5614  5660 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-17 05:52:56.693  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-17 05:52:56.695  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-17 05:52:56.695  5614  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-17 05:52:56.697  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:52:56.697  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:52:56.702  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-17 05:52:56.703  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 05:52:56.703  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
11-17 05:52:56.703  5614  5660 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,11-17 05:52:56.704  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-17 05:52:56.704  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.704  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.704  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:56.704  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:52:56.704  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:52:56.704  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:52:56.704  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:52:56.704  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-17 05:52:56.705  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:52:56.705  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:52:56.705  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:52:56.705  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:52:56.705  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:52:56.706  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:52:56.706  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 05:52:56.709  5614  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-17 05:52:56.710  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 05:52:56.713  5614  5663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:52:56.717  5614  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-17 05:52:56.711  4832  4832 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30477]" dev="sockfs" ino=30477 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:52:56.711  4832  4832 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30477]" dev="sockfs" ino=30477 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:52:56.718  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:52:56.718  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:52:56.718  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 05:52:56.719  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 05:52:56.720  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-17 05:52:56.722  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.722  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:52:56.723  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:52:56.723  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-17 05:52:56.723  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-17 05:52:56.724  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.724  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.724  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-17 05:52:56.724  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:52:56.724  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:52:56.724  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-17 05:52:56.725  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:56.725  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:56.725  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.725  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:52:56.725  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-17 05:52:56.725  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.725  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.725  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.726  5614  5660 D BluetoothAdapter: STATE_ON
,11-17 05:52:56.728  4575  4589 D BtGatt.GattService: registerClient() - UUID=57046337-70a2-4057-89f8-97172bef494d
,11-17 05:52:56.729  4575  4662 D BtGatt.GattService: onClientRegistered() - UUID=57046337-70a2-4057-89f8-97172bef494d, clientIf=5
,11-17 05:52:56.730  5614  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-17 05:52:56.733  4575  4664 D BtGatt.AdvertiseManager: message : 0
,11-17 05:52:56.736  4575  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:52:56.751  4575  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:52:56.760  4575  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:52:56.761  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.761  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:56.761  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:52:56.761  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.761  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:56.762  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.762  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.762  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:56.762  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:52:56.762  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:52:56.762  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.763  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:56.763  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.763  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:56.763  5614  5660 I io.jxcore.node.ConnectionHelper: start: OK
11-17 05:52:56.764  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:52:56.764  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-17 05:52:56.764  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:56.764  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:52:56.765  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-17 05:52:56.765  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:56.765  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:56.765  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:52:56.766  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:52:56.766  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:52:56.766  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:52:56.766  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:52:56.766  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:52:56.766  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 05:52:56.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-17 05:52:56.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-17 05:52:56.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:56.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:56.771  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:52:56.771  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:52:57.267  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 05:52:57.267  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-17 05:52:57.267  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-17 05:52:57.267  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-17 05:52:57.267  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-17 05:52:57.267  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-17 05:52:57.268  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-17 05:52:57.269  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-17 05:52:57.270  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-17 05:52:57.270  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-17 05:52:57.270  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-17 05:52:57.270  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-17 05:52:57.270  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-17 05:52:57.270  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-17 05:52:57.270  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-17 05:52:57.271  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-17 05:52:57.271  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-17 05:52:57.271  5614  5660 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-17 05:52:57.271  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-17 05:52:57.271  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-17 05:52:57.271  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-17 05:52:57.271  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:52:57.271  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-17 05:52:57.272  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:52:57.272  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-17 05:52:57.272  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-17 05:52:57.272  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:52:57.272  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-17 05:52:57.272  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:52:57.273  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:52:57.273  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:52:57.273  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.273  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.273  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.274  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.274  5614  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:52:57.274  5614  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-17 05:52:57.275  5614  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:52:57.275  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:57.275  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:52:57.276  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:57.276  5614  5660 D BluetoothLeScanner: could not find callback wrapper
,11-17 05:52:57.276  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:52:57.277  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.277  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.277  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.277  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-17 05:52:57.277  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.278  4575  4664 D BtGatt.AdvertiseManager: message : 1
11-17 05:52:57.280  4575  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:52:57.293  4575  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-17 05:52:57.293  4575  4662 D BtGatt.GattService: Client app is not null!
,11-17 05:52:57.294  4575  4802 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 05:52:57.296  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-17 05:52:57.296  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.296  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-17 05:52:57.296  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.296  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.296  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.296  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 05:52:57.297  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:52:57.298  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 05:52:57.298  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.300  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.300  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:52:57.300  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.300  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.301  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 05:52:57.301  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-17 05:52:57.302  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:52:57.302  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:52:57.302  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:52:57.302  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:52:57.303  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:52:57.303  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.303  5614  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-17 05:52:57.303  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.303  5614  5660 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-17 05:52:57.303  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:52:57.303  5614  5660 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-17 05:52:57.303  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:52:57.303  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-17 05:52:57.303  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.303  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.303  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.303  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-17 05:52:57.304  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.304  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.304  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.304  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:52:57.304  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:52:57.304  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:52:57.305  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:52:57.307  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-17 05:52:57.308  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:52:57.308  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:52:57.308  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:52:57.308  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:52:57.309  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.309  5614  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-17 05:52:57.309  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.309  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.309  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.309  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:52:57.309  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:52:57.309  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:52:57.309  5614  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:52:57.308  4588  4588 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33909]" dev="sockfs" ino=33909 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:52:57.308  4588  4588 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33909]" dev="sockfs" ino=33909 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:52:57.310  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:52:57.310  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-17 05:52:57.314  5614  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-17 05:52:57.318  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:52:57.318  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:52:57.318  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 05:52:57.319   534   534 I ServiceManager: Waiting for service AtCmdFwd...
11-17 05:52:57.322  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.323  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:52:57.323  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:52:57.324  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:52:57.324  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-17 05:52:57.326  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.326  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.327  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:52:57.327  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:52:57.327  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:52:57.327  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-17 05:52:57.327  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.327  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.327  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.327  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:52:57.328  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.328  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.328  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.328  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.328  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:57.330  4575  4831 D BtGatt.GattService: registerClient() - UUID=4201e4e9-dbee-425b-8d38-de9c3e9e6d50
11-17 05:52:57.331  4575  4662 D BtGatt.GattService: onClientRegistered() - UUID=4201e4e9-dbee-425b-8d38-de9c3e9e6d50, clientIf=5
11-17 05:52:57.331  5614  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-17 05:52:57.332  4575  4664 D BtGatt.AdvertiseManager: message : 0
11-17 05:52:57.334  4575  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:52:57.345  4575  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-17 05:52:57.352  4575  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-17 05:52:57.353  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.353  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.353  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:52:57.353  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.354  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:52:57.355  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:52:57.355  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.356  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.356  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.356  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.356  5614  5660 I io.jxcore.node.ConnectionHelper: start: OK
11-17 05:52:57.356  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.357  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:52:57.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.359  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.360  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-17 05:52:57.360  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.360  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.360  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.360  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:52:57.859  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-17 05:52:57.860  5614  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-17 05:52:57.860  5614  5660 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-17 05:52:57.860  5614  5660 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-17 05:52:57.860  5614  5660 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-17 05:52:57.860  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-17 05:52:57.861  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-17 05:52:57.861  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.861  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.862  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-17 05:52:57.863  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.863  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-17 05:52:57.864  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.864  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.865  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.866  4575  4664 D BtGatt.AdvertiseManager: message : 1
11-17 05:52:57.868  4575  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:52:57.881  4575  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-17 05:52:57.881  4575  4662 D BtGatt.GattService: Client app is not null!
,11-17 05:52:57.882  4575  4831 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:52:57.882  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-17 05:52:57.882  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.882  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-17 05:52:57.883  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.883  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.883  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.883  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:52:57.883  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.883  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.883  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.883  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:52:57.883  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:52:57.883  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 05:52:57.883  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
11-17 05:52:57.884  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.884  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.884  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.884  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:52:57.884  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.884  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.884  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.884  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.885  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:57.888  4575  4831 D BtGatt.GattService: registerClient() - UUID=7bdeb812-c6e5-4824-a4db-8c0b67bfd215
11-17 05:52:57.889  4575  4662 D BtGatt.GattService: onClientRegistered() - UUID=7bdeb812-c6e5-4824-a4db-8c0b67bfd215, clientIf=5
,11-17 05:52:57.889  5614  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-17 05:52:57.891  4575  4664 D BtGatt.AdvertiseManager: message : 0
,11-17 05:52:57.894  4575  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:52:57.905  4575  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:52:57.911  4575  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:52:57.912  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.912  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-17 05:52:57.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.912  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:52:57.912  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-17 05:52:57.913  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 05:52:57.913  5614  5660 I io.jxcore.node.ConnectionHelper: start: OK
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.913  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:52:57.913  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.914  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 05:52:57.914  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.914  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-17 05:52:57.914  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-17 05:52:57.914  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:52:57.914  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:52:57.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:52:57.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-17 05:52:57.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-17 05:52:57.914  5614  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-17 05:52:57.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:52:57.914  5614  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:52:57.914  5614  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:52:57.914  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-17 05:52:57.914  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:52:57.914  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:52:57.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:52:57.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:52:57.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.915  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.915  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.915  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.915  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:57.915  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:52:57.916  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:57.916  5614  5660 D BluetoothLeScanner: could not find callback wrapper
11-17 05:52:57.916  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:52:57.916  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.916  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.916  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.916  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:52:57.916  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.917  4575  4664 D BtGatt.AdvertiseManager: message : 1
11-17 05:52:57.917  4575  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:52:57.924  4575  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-17 05:52:57.924  4575  4662 D BtGatt.GattService: Client app is not null!
,11-17 05:52:57.924  4575  4802 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:52:57.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 05:52:57.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-17 05:52:57.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-17 05:52:57.925  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:52:57.926  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 05:52:57.926  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.927  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.927  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:52:57.927  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.927  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.927  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 05:52:57.927  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-17 05:52:57.928  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:52:57.928  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:52:57.928  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:52:57.928  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:52:57.928  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.928  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-17 05:52:57.929  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-17 05:52:57.929  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:52:57.929  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.929  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.929  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-17 05:52:57.929  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.931  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-17 05:52:57.931  5614  5660 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-17 05:52:57.931  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.931  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-17 05:52:57.931  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.931  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.931  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:52:57.932  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-17 05:52:57.932  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-17 05:52:57.933  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-17 05:52:57.933  5614  5660 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-17 05:52:57.934  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,11-17 05:52:57.934  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-17 05:52:57.935  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-17 05:52:57.935  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 05:52:57.935  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:57.935  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:57.935  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:57.935  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 05:52:57.936  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-17 05:52:57.936  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:52:57.936  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:52:57.936  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 05:52:57.936  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:57.936  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:57.936  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 05:52:57.937  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-17 05:52:57.938  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-17 05:52:57.938  5614  5660 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-17 05:52:57.942  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-17 05:52:57.942  5614  5660 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-17 05:52:57.945  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-17 05:52:57.945  5614  5660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-17 05:52:57.946  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-17 05:52:57.946  5614  5660 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-17 05:52:57.946  5614  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-17 05:52:57.946  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-17 05:52:57.947  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 05:52:57.947  5614  5660 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-17 05:52:57.947  5614  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-17 05:52:57.947  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-17 05:52:57.947  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 05:52:57.947  5614  5660 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-17 05:52:57.947  5614  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-17 05:52:57.947  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-17 05:52:57.947  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 05:52:57.947  5614  5660 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-17 05:52:57.948  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-17 05:52:57.948  5614  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-17 05:52:57.948  5614  5660 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-17 05:52:57.948  5614  5660 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-17 05:52:57.948  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-17 05:52:57.948  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.949  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.949  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.949  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:52:57.949  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:52:57.949  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:52:57.949  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:52:57.950  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-17 05:52:57.951  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:52:57.951  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:52:57.951  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:52:57.951  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:52:57.951  5614  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-17 05:52:57.951  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:52:57.951  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:52:57.951  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:52:57.951  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-17 05:52:57.951  4802  4802 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33921]" dev="sockfs" ino=33921 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:52:57.951  4802  4802 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33921]" dev="sockfs" ino=33921 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:52:57.952  5614  5670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:52:57.955  5614  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-17 05:52:57.955  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:52:57.955  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:52:57.955  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 05:52:57.959  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.959  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:52:57.959  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:52:57.959  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:52:57.959  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-17 05:52:57.961  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.961  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.961  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:52:57.961  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:52:57.961  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:52:57.961  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-17 05:52:57.962  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.962  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.962  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.962  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:52:57.962  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:52:57.962  56,14  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.962  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.962  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.962  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:57.964  4575  4588 D BtGatt.GattService: registerClient() - UUID=a9ce0658-274d-48b1-8ffc-f9347a8a06bc
11-17 05:52:57.964  4575  4662 D BtGatt.GattService: onClientRegistered() - UUID=a9ce0658-274d-48b1-8ffc-f9347a8a06bc, clientIf=5
11-17 05:52:57.965  5614  5625 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-17 05:52:57.966  4575  4664 D BtGatt.AdvertiseManager: message : 0
,11-17 05:52:57.968  4575  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:52:57.976  4575  4662 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:52:57.981  4575  4662 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:52:57.982  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:52:57.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.982  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:52:57.984  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:52:57.984  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:57.985  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.985  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.985  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:57.985  5614  5660 I io.jxcore.node.ConnectionHelper: start: OK
,11-17 05:52:57.985  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-17 05:52:57.985  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-17 05:52:57.985  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.985  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:52:57.985  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.986  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.986  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:57.986  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-17 05:52:57.986  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:52:57.986  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:52:57.986  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.986  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.986  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:52:57.986  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.988  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.988  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:52:57.988  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.988  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.988  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:52:57.988  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:52:58.320   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-17 05:52:58.486  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 05:52:58.486  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:52:58.486  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:52:58.486  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:52:58.487  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-17 05:52:58.487  5614  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:52:58.487  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-17 05:52:58.487  5614  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:52:58.487  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:52:58.487  5614  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-17 05:52:58.488  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 05:52:58.488  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:52:58.488  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d181e87 removed from the list
11-17 05:52:58.488  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:52:58.488  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 05:52:58.488  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:52:58.488  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:52:58.489  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-17 05:52:58.489  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-17 05:52:58.489  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:52:58.489  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.489  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.489  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:58.490  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.493  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:52:58.494  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:52:58.495  5614  5660 D BluetoothAdapter: STATE_ON
,11-17 05:52:58.495  5614  5660 D BluetoothLeScanner: could not find callback wrapper
11-17 05:52:58.495  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:52:58.496  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.496  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:58.496  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.496  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:52:58.496  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.498  4575  4664 D BtGatt.AdvertiseManager: message : 1
11-17 05:52:58.499  4575  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-17 05:52:58.512  4575  4662 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-17 05:52:58.512  4575  4662 D BtGatt.GattService: Client app is not null!
,11-17 05:52:58.514  4575  4831 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 05:52:58.515  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-17 05:52:58.515  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:58.515  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-17 05:52:58.515  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.515  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.516  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.516  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 05:52:58.516  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:52:58.517  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 05:52:58.517  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.519  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.519  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:52:58.520  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:52:58.520  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:52:58.520  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffc51b4 removed from the list
11-17 05:52:58.520  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:52:58.520  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-17 05:52:58.520  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:52:58.520  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:52:58.521  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:52:58.521  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.521  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:52:58.521  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:52:58.521  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.521  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.521  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-17 05:52:58.522  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.524  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.524  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.525  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.525  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:52:58.525  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-17 05:52:59.026  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 05:53:00.008   928   939 I ActivityManager: Killing 5051:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-17 05:53:03.321   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:03.525  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-17 05:53:03.528  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-17 05:53:03.528  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:53:03.528  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 05:53:03.536  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-17 05:53:03.537  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-17 05:53:03.537  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-17 05:53:03.537  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-17 05:53:03.537  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-17 05:53:03.538  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-17 05:53:03.538  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:53:03.538  5614  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-17 05:53:03.539  5614  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:53:03.540  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-17 05:53:03.542  5614  5660 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-17 05:53:03.542  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-17 05:53:03.542  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 05:53:03.542  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:53:03.542  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 05:53:03.544  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-17 05:53:03.541  4831  4831 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33532]" dev="sockfs" ino=33532 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:53:03.544  4831  4831 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33532]" dev="sockfs" ino=33532 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:53:03.549  5614  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-17 05:53:03.552  5614  5660 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
11-17 05:53:03.553  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 05:53:03.553  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-17 05:53:03.553  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:53:03.553  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:53:03.554  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:53:03.554  5614  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:53:03.554  5614  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:53:03.554  5614  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-17 05:53:03.555  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-17 05:53:03.555  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:53:03.555  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:53:03.555  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d181e87 not in the list
11-17 05:53:03.556  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 05:53:03.556  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-17 05:53:03.556  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:53:03.555  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:53:03.556  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:53:03.556  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:53:03.556  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:03.557  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:03.558  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:53:03.558  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:03.558  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:03.558  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffc51b4 not in the list
11-17 05:53:03.558  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:53:03.558  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 05:53:03.558  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:53:03.558  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:53:03.559  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-17 05:53:03.561  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-17 05:53:03.561  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 05:53:03.561  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-17 05:53:03.561  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 05:53:03.561  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-17 05:53:03.561  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 05:53:03.562  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-17 05:53:03.562  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-17 05:53:03.563  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-17 05:53:03.563  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-17 05:53:03.563  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-17 05:53:03.564  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-17 05:53:03.564  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-17 05:53:03.564  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-17 05:53:03.564  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-17 05:53:03.564  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-17 05:53:03.564  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-17 05:53:03.564  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-17 05:53:03.565  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-17 05:53:03.565  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-17 05:53:03.565  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-17 05:53:03.566  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-17 05:53:03.566  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-17 05:53:03.566  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-17 05:53:03.566  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-17 05:53:03.566  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-17 05:53:03.567  5614  5660 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-17 05:53:03.567  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 05:53:03.567  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e074302 added. We now have 3 listener(s)
11-17 05:53:03.569  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 05:53:03.569  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:53:03.569  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 05:53:03.569  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:53:03.569  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50e5413 added. We now have 3 listener(s)
11-17 05:53:03.569  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 05:53:03.570  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-17 05:53:03.572  5614  5660 D BluetoothAdapter: enable(): BT is already enabled..!
11-17 05:53:03.572   928   939 D WifiService: setWifiEnabled: true pid=5614, uid=10077
,11-17 05:53:03.572   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 05:53:03.574  5614  5660 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-17 05:53:03.576  5614  5660 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-17 05:53:03.577  5614  5660 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-17 05:53:03.579  5614  5660 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-17 05:53:03.580  5614  5660 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:53:03.585  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-17 05:53:03.585  4575  4657 D BluetoothAdapterState: Current state: ON, message: 23
11-17 05:53:03.585  4575  4657 D BluetoothAdapterProperties: Setting state to 13
11-17 05:53:03.585  4575  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-17 05:53:03.586  4575  4657 D BluetoothAdapterProperties: onBluetoothDisable()
11-17 05:53:03.586  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-17 05:53:03.586  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-17 05:53:03.587  4575  4657 I BluetoothAdapterState: Entering PendingCommandState
,11-17 05:53:03.590  4575  4575 D BluetoothMapService: onReceive
11-17 05:53:03.590  4575  4575 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-17 05:53:03.590  4575  4575 D BluetoothMapService: STATE_TURNING_OFF
11-17 05:53:03.590  4575  4575 D BluetoothMapService: MAP Service closeService in
11-17 05:53:03.590  4575  4575 D BluetoothMapMasInstance0: MAP Service shutdown
11-17 05:53:03.590  4575  4575 D ObexServerSockets0: shutdown(block = true)
11-17 05:53:03.591  4575  4575 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-17 05:53:03.591  4575  4575 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-17 05:53:03.591  4575  4834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-17 05:53:03.591  4575  4784 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-17 05:53:03.591  4575  4835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-17 05:53:03.594  4575  4575 I BtOppRfcommListener: stopping Accept Thread
,11-17 05:53:03.594  4575  5335 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-17 05:53:03.594  4575  5335 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-17 05:53:03.603   928   941 I ActivityManager: Start proc 5674:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-17 05:53:03.605  4575  4662 D BluetoothAdapterProperties: Scan Mode:20
,11-17 05:53:03.605  4575  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-17 05:53:03.607  4575  4575 D HeadsetService: Received stop request...Stopping profile...
,11-17 05:53:03.611   928   928 D BluetoothHeadset: Proxy object disconnected
11-17 05:53:03.611   928   928 D BluetoothHeadset: Proxy object disconnected
11-17 05:53:03.612  3742  3956 D BluetoothHeadset: Proxy object disconnected
11-17 05:53:03.612  3085  3938 D BluetoothHeadset: Proxy object disconnected
,11-17 05:53:03.612   928   928 D BluetoothHeadset: Proxy object disconnected
,11-17 05:53:03.614  4575  4575 D A2dpService: Received stop request...Stopping profile...
11-17 05:53:03.614  4575  4816 D A2dpStateMachine: Exit Disconnected: -1
11-17 05:53:03.616   928   928 D BluetoothA2dp: Proxy object disconnected
11-17 05:53:03.616  4575  4575 D HidService: Received stop request...Stopping profile...
11-17 05:53:03.617  4575  4575 D HidService: Stopping Bluetooth HidService
11-17 05:53:03.617  3085  3085 D HeadsetProfile: Bluetooth service disconnected
11-17 05:53:03.617  3085  3085 D BluetoothA2dp: Proxy object disconnected
11-17 05:53:03.618  3085  3085 D BluetoothInputDevice: Proxy object disconnected
11-17 05:53:03.618  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-17 05:53:03.619  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:03.619  3085  3085 D HidProfile: Bluetooth service disconnected
11-17 05:53:03.619  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:03.619  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:03.621  4575  4575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-17 05:53:03.621  4575  4575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-17 05:53:03.621  4575  4780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:53:03.621  4575  4780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:53:03.621  4575  4780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:53:03.621  4575  4662 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-17 05:53:03.621  4575  4575 D HealthService: Received stop request...Stopping profile...
11-17 05:53:03.622  4575  4662 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-17 05:53:03.623  4575  4575 D PanService: Received stop request...Stopping profile...
11-17 05:53:03.625  3085  3085 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-17 05:53:03.625  3085  3085 D PanProfile: Bluetooth service disconnected
11-17 05:53:03.627  4575  4575 D BluetoothMapService: Received stop request...Stopping profile...
11-17 05:53:03.628  4575  4575 D BluetoothMapService: stop()
11-17 05:53:03.628  4575  4575 D BluetoothMapAppObserver: deinitObservers()
11-17 05:53:03.628  4575  4575 D BluetoothMapAppObserver: removeReceiver()
11-17 05:53:03.629  3085  3085 D BluetoothMap: Proxy object disconnected
11-17 05:53:03.630  3085  3085 D MapProfile: Bluetooth service disconnected
11-17 05:53:03.630  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-17 05:53:03.630  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:03.630  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 05:53:03.630  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 05:53:03.631  4575  4575 D SapService: Received stop request...Stopping profile...
11-17 05:53:03.631  4575  4575 V SapService: stop()
,11-17 05:53:03.633  4575  4780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isTurningOff()=true
,11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:03.633  4575  4780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:03.633  4575  4575 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-17 05:53:03.633  4575  4575 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:03.633  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:03.633  4575  4662 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-17 05:53:03.634  4575  4575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-17 05:53:03.634  4575  4662 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-17 05:53:03.634  4575  4662 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-17 05:53:03.634  4575  4575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-17 05:53:03.634  4575  4780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 05:53:03.634  4575  4780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 05:53:03.634  4575  4780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 05:53:03.634  4575  4780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 05:53:03.634  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-17 05:53:03.634  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:03.634  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:03.634  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:03.634  4575  4575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-17 05:53:03.635  4575  4575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-17 05:53:03.635  4575  4575 D BluetoothMapService: MAP Service closeService in
11-17 05:53:03.635  4575  4575 V BluetoothAdapterState: isTurningOff()=true
11-17 05:53:03.635  4575  4575 V BluetoothAdapterState: isTurningOn()=false
,11-17 05:53:03.635  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:03.636  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:03.636  4575  4575 D BluetoothMapService: cleanup()
11-17 05:53:03.636  4575  4575 D BluetoothMapService: MAP Service closeService in
11-17 05:53:03.636  4575  4575 V BluetoothAdapterState: isTurningOff()=true
,11-17 05:53:03.636  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:03.636  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:03.636  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:03.636  4575  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-17 05:53:03.637  4575  4657 D BluetoothAdapterProperties: Setting state to 15
11-17 05:53:03.637  4575  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-17 05:53:03.637  4575  4657 I BluetoothAdapterState: Entering BleOnState
,11-17 05:53:03.639  3085  5613 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-17 05:53:03.640  3742  3765 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-17 05:53:03.641   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:53:03.641   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 05:53:03.641  3085  3097 D BluetoothPbap: onBluetoothStateChange: up=false
11-17 05:53:03.642  3085  3938 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:53:03.642  3085  5613 D BluetoothMap: onBluetoothStateChange: up=false
11-17 05:53:03.643   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:53:03.643   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 05:53:03.643  3085  3097 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 05:53:03.644  3085  3938 D BluetoothPan: onBluetoothStateChange on: false
11-17 05:53:03.646  4575  4657 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-17 05:53:03.646  4575  4657 D BluetoothAdapterProperties: Setting state to 16
11-17 05:53:03.646  4575  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-17 05:53:03.647  4575  4657 D BluetoothAdapterProperties: onBleDisable
11-17 05:53:03.648  4575  4657 I BluetoothAdapterState: Entering PendingCommandState
11-17 05:53:03.648  4575  4659 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-17 05:53:03.649  4575  4662 D BluetoothAdapterProperties: Scan Mode:20
,11-17 05:53:03.650  4575  4780 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-17 05:53:03.650  4575  4780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-17 05:53:03.659  5674  5674 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-17 05:53:03.670  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-17 05:53:03.675   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bf12187:true
,11-17 05:53:03.676  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 05:53:03.689   928  3375 I ActivityManager: Start proc 5686:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-17 05:53:03.701  5674  5674 D LocalBluetoothProfileManager: Adding local MAP profile
,11-17 05:53:03.704  5674  5674 D BluetoothMap: Create BluetoothMap proxy object
,11-17 05:53:03.723  5686  5686 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-17 05:53:03.727  5674  5674 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-17 05:53:03.738  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,11-17 05:53:03.749   928  3807 I ActivityManager: Killing 4972:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-17 05:53:03.854  4575  4662 I bt_hci  : shut_down
,11-17 05:53:03.858  4575  4667 D bt_hwcfg: hw_epilog_process
,11-17 05:53:03.859  4575  4667 I bt_vendor: low_power_mode_cb
,11-17 05:53:03.861  4575  4667 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-17 05:53:03.861  4575  4667 I bt_vendor: epilog_cb
,11-17 05:53:03.861  4575  4667 I bt_hci  : epilog_finished_callback
11-17 05:53:03.863  4575  4662 I bt_hci_h4: hal_close
11-17 05:53:03.863  4575  4662 I bt_userial_vendor: device fd = 54 close
,11-17 05:53:03.936  5686  5686 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-17 05:53:03.936  5686  5686 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:53:03.936  5686  5686 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:53:03.936  5686  5686 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.e.b(PG:170)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:53:03.936  5686  5686 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.k.d(PG:583)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.e.b(PG:170)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.936  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:53:03.937  5686  5686 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:53:03.937  5686  5686 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:53:03.937  5686  5686 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 05:53:03.937  5686  5686 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 05:53:03.944  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-17 05:53:03.949  5674  5674 D DockEventReceiver: finishStartingService: stopping service
11-17 05:53:03.949  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 05:53:03.951   928  3375 I ActivityManager: Killing 5399:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
11-17 05:53:03.969  4575  4659 D bt_stack_manager: event_shut_down_stack finished.
11-17 05:53:03.969  4575  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-17 05:53:03.977  4575  4657 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-17 05:53:03.977  4575  4575 D BtGatt.DebugUtils: handleDebugAction() action=null
11-17 05:53:03.977  4575  4575 D BtGatt.GattService: Received stop request...Stopping profile...
11-17 05:53:03.978  4575  4575 D BtGatt.GattService: stop()
11-17 05:53:03.978  4575  4575 D BtGatt.AdvertiseManager: advertise clients cleared
11-17 05:53:03.979  4575  4575 V BluetoothAdapterState: isTurningOff()=false
11-17 05:53:03.979  4575  4575 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:03.979  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:03.979  4575  4575 V BluetoothAdapterState: isBleTurningOff()=true
11-17 05:53:03.979  4575  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-17 05:53:03.979  4575  4657 D BluetoothAdapterProperties: Setting state to 10
11-17 05:53:03.979  4575  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-17 05:53:03.980  4575  4657 I BluetoothAdapterState: Entering OffState
11-17 05:53:03.981   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-17 05:53:03.986  4575  4575 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-17 05:53:03.986  4575  4575 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-17 05:53:03.986  4575  4575 I BluetoothServiceJni: cleanupNative: return from cleanup
11-17 05:53:03.988  4575  4659 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-17 05:53:03.993  4575  4575 I art     : System.exit called, status: 0
11-17 05:53:03.993  4575  4575 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-17 05:53:04.052   928  3375 I ActivityManager: Process com.android.bluetooth (pid 4575) has died
,11-17 05:53:04.059  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 05:53:04.086  5614  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:53:04.086  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-17 05:53:04.086  5614  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 05:53:04.086  5614  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 05:53:04.089  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 05:53:04.100   928   945 I ActivityManager: Start proc 5718:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-17 05:53:04.154  5686  5705 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-17 05:53:04.159  5718  5718 D AdapterServiceConfig: Adding HeadsetService
,11-17 05:53:04.159  5718  5718 D AdapterServiceConfig: Adding A2dpService
11-17 05:53:04.159  5718  5718 D AdapterServiceConfig: Adding HidService
11-17 05:53:04.160  5718  5718 D AdapterServiceConfig: Adding HealthService
11-17 05:53:04.160  5718  5718 D AdapterServiceConfig: Adding PanService
,11-17 05:53:04.160  5718  5718 D AdapterServiceConfig: Adding GattService
11-17 05:53:04.160  5718  5718 D AdapterServiceConfig: Adding BluetoothMapService
11-17 05:53:04.160  5718  5718 D AdapterServiceConfig: Adding SapService
,11-17 05:53:04.167   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@136de7c:true
,11-17 05:53:04.167   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7abef5a:true
,11-17 05:53:04.168  5718  5718 D BluetoothAdapterState: make() - Creating AdapterState
,11-17 05:53:04.170  5718  5718 I bt_bluedroid: init
,11-17 05:53:04.170  5718  5731 I BluetoothAdapterState: Entering OffState
,11-17 05:53:04.172  5718  5732 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-17 05:53:04.172  5718  5732 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-17 05:53:04.172  5718  5732 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-17 05:53:04.172  5718  5732 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-17 05:53:04.173  5718  5718 I bt_bluedroid: get_profile_interface socket
,11-17 05:53:04.174  5718  5718 I bt_bluedroid: get_profile_interface sdp
,11-17 05:53:04.174  5718  5735 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 05:53:04.177  5718  5735 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 05:53:04.180  5718  5729 I bt_bluedroid: config_hci_snoop_log
,11-17 05:53:04.181   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-17 05:53:04.185  5718  5731 D BluetoothAdapterState: Current state: OFF, message: 0
,11-17 05:53:04.185  5718  5731 D BluetoothAdapterProperties: Setting state to 14
11-17 05:53:04.185  5718  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-17 05:53:04.186  5718  5731 D BluetoothBondStateMachine: make
,11-17 05:53:04.187  5718  5737 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-17 05:53:04.190  5718  5731 I BluetoothAdapterState: Entering PendingCommandState
11-17 05:53:04.190  5718  5718 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-17 05:53:04.191  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
,11-17 05:53:04.192  5718  5718 D BtGatt.DebugUtils: handleDebugAction() action=null
11-17 05:53:04.192  5718  5718 D BtGatt.GattService: Received start request. Starting profile...
11-17 05:53:04.192  5718  5718 D BtGatt.GattService: start()
11-17 05:53:04.192  5718  5718 I bt_bluedroid: get_profile_interface gatt
,11-17 05:53:04.193  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
11-17 05:53:04.193  5718  5718 D BtGatt.AdvertiseManager: advertise manager created
,11-17 05:53:04.196  5718  5718 V BluetoothAdapterState: isTurningOff()=false
11-17 05:53:04.196  5718  5718 V BluetoothAdapterState: isTurningOn()=false
11-17 05:53:04.196  5718  5718 V BluetoothAdapterState: isBleTurningOn()=true
11-17 05:53:04.196  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 05:53:04.196  5718  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-17 05:53:04.198  5718  5731 I bt_bluedroid: bt_bluedroid
11-17 05:53:04.198  5718  5732 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-17 05:53:04.198  5718  5732 I bt_hci  : start_up
,11-17 05:53:04.203  5718  5732 I bt_vendor: alloc value 0xf3fcf871
,11-17 05:53:04.203  5718  5732 I bt_vendor: init
11-17 05:53:04.204  5718  5732 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-17 05:53:04.204  5718  5732 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-17 05:53:04.311  5718  5732 D bt_hci  : start_up starting async portion
,11-17 05:53:04.311  5718  5740 I bt_hci  : event_finish_startup
11-17 05:53:04.311  5718  5740 I bt_hci_h4: hal_open
11-17 05:53:04.311  5718  5740 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-17 05:53:04.308  5741  5741 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:53:04.314  5718  5740 I bt_userial_vendor: device fd = 54 open
,11-17 05:53:04.321   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:04.326  5718  5740 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 05:53:04.328  5718  5740 D bt_hwcfg: Chipset BCM4358A3
,11-17 05:53:04.328  5718  5740 D bt_hwcfg: Target name = [BCM4358A3]
11-17 05:53:04.328  5718  5740 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-17 05:53:04.600  5718  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-17 05:53:04.698  5718  5740 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-17 05:53:04.699  5718  5740 D bt_hwcfg: Settlement delay -- 100 ms
,11-17 05:53:04.699  5718  5740 I bt_hwcfg: Setting fw settlement delay to 100 
,11-17 05:53:04.823  5718  5740 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 05:53:04.823  5718  5740 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-17 05:53:04.824  5718  5740 I bt_hwcfg: vendor lib fwcfg completed
,11-17 05:53:04.825  5718  5740 I bt_vendor: firmware callback
11-17 05:53:04.825  5718  5740 I bt_hci  : firmware_config_callback
,11-17 05:53:04.838  5718  5743 I bt_btu  : btu_task pending for preload complete event
,11-17 05:53:04.839  5718  5743 I bt_btu_task: Bluetooth chip preload is complete
11-17 05:53:04.839  5718  5743 I bt_btu  : btu_task received preload complete event
11-17 05:53:04.846  5718  5743 I         : BTE_InitTraceLevels -- TRC_HCI
,11-17 05:53:04.846  5718  5743 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-17 05:53:04.846  5718  5743 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-17 05:53:04.847  5718  5743 I         : BTE_InitTraceLevels -- TRC_AVDT
11-17 05:53:04.847  5718  5743 I         : BTE_InitTraceLevels -- TRC_AVRC
11-17 05:53:04.847  5718  5743 I         : BTE_InitTraceLevels -- TRC_A2D
11-17 05:53:04.847  5718  5743 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-17 05:53:04.847  5718  5743 I         : BTE_InitTraceLevels -- TRC_BTM
11-17 05:53:04.847  5718  5743 I         : BTE_InitTraceLevels -- TRC_GAP
11-17 05:53:04.847  5718  5743 I         : BTE_InitTraceLevels -- TRC_PAN
11-17 05:53:04.848  5718  5743 I         : BTE_InitTraceLevels -- TRC_SDP
11-17 05:53:04.848  5718  5743 I         : BTE_InitTraceLevels -- TRC_GATT
,11-17 05:53:04.848  5718  5743 I         : BTE_InitTraceLevels -- TRC_SMP
11-17 05:53:04.848  5718  5743 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-17 05:53:04.848  5718  5743 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-17 05:53:04.931  5718  5743 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f4d549
,11-17 05:53:04.931  5718  5743 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f4d549 
,11-17 05:53:04.947  5718  5735 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-17 05:53:04.948  5718  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-17 05:53:04.949  5718  5735 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 05:53:04.952  5718  5735 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 05:53:04.955  5718  5735 D BluetoothAdapterProperties: Scan Mode:20
11-17 05:53:04.955  5718  5735 D BluetoothAdapterProperties: Discoverable Timeout:120
11-17 05:53:04.955  5718  5735 D bt_hci  : do_postload posting postload work item
11-17 05:53:04.955  5718  5740 I bt_hci  : event_postload
11-17 05:53:04.955  5718  5740 I bt_vendor: sco_config_cb
11-17 05:53:04.956  5718  5740 I bt_hci  : sco_config_callback postload finished.
11-17 05:53:04.959  5718  5735 D bt_bte_conf: Device ID record 1 : primary
11-17 05:53:04.959  5718  5735 D bt_bte_conf:   vendorId            = 000f
11-17 05:53:04.959  5718  5735 D bt_bte_conf:   vendorIdSource      = 0001
11-17 05:53:04.959  5718  5735 D bt_bte_conf:   product             = 1200
11-17 05:53:04.959  5718  5735 D bt_bte_conf:   version             = 1436
11-17 05:53:04.959  5718  5735 D bt_bte_conf:   clientExecutableURL = 
11-17 05:53:04.959  5718  5735 D bt_bte_conf:   serviceDescription  = 
11-17 05:53:04.959  5718  5735 D bt_bte_conf:   documentationURL    = 
11-17 05:53:04.959  5718  5735 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-17 05:53:04.960  5718  5732 D bt_stack_manager: event_start_up_stack finished
11-17 05:53:04.961  5718  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-17 05:53:04.962  5718  5731 D BluetoothAdapterProperties: Setting state to 15
11-17 05:53:04.962  5718  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-17 05:53:04.964  5718  5731 I BluetoothAdapterState: Entering BleOnState
,11-17 05:53:04.967  5718  5740 I bt_vendor: low_power_mode_cb
,11-17 05:53:04.972  5718  5731 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-17 05:53:04.973  5718  5731 D BluetoothAdapterProperties: Setting state to 11
11-17 05:53:04.973  5718  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-17 05:53:04.982  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
,11-17 05:53:04.983  5718  5718 D HeadsetService: Received start request. Starting profile...
11-17 05:53:04.986  5718  5718 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-17 05:53:04.987  5718  5718 D HeadsetStateMachine: make
,11-17 05:53:04.996  5718  5731 I BluetoothAdapterState: Entering PendingCommandState
,11-17 05:53:05.000  5718  5718 D HeadsetStateMachine: max_hf_connections = 1
,11-17 05:53:05.000  5718  5718 I bt_bluedroid: get_profile_interface handsfree
11-17 05:53:05.000  5718  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-17 05:53:05.001  5718  5735 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-17 05:53:05.004  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
,11-17 05:53:05.005  5718  5718 D A2dpService: Received start request. Starting profile...
,11-17 05:53:05.005  5718  5718 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-17 05:53:05.006  5718  5718 I bt_bluedroid: get_profile_interface avrcp
,11-17 05:53:05.014  5718  5718 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-17 05:53:05.014  5718  5718 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-17 05:53:05.014  5718  5718 D A2dpStateMachine: make
,11-17 05:53:05.016  5718  5718 I bt_bluedroid: get_profile_interface a2dp
,11-17 05:53:05.016  5718  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-17 05:53:05.019  5718  5751 D A2dpStateMachine: Enter Disconnected: -2
,11-17 05:53:05.020  5718  5718 I BluetoothHidServiceJni: classInitNative: succeeds
,11-17 05:53:05.021  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
,11-17 05:53:05.022  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 05:53:05.023  5718  5718 D HidService: Received start request. Starting profile...
11-17 05:53:05.023  5718  5718 I bt_bluedroid: get_profile_interface hidhost
11-17 05:53:05.023  5718  5735 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f2e56d
11-17 05:53:05.023  5718  5718 D HidService: setHidService(): set to: null
11-17 05:53:05.024  5718  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-17 05:53:05.024  5674  5674 D BluetoothInputDevice: Proxy object connected
,11-17 05:53:05.025  5718  5718 I BluetoothHealthServiceJni: classInitNative: succeeds
11-17 05:53:05.025  5674  5674 D HidProfile: Bluetooth service connected
11-17 05:53:05.026  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
11-17 05:53:05.026  5718  5718 D HealthService: Received start request. Starting profile...
,11-17 05:53:05.028  5718  5718 I bt_bluedroid: get_profile_interface health
,11-17 05:53:05.029  5718  5718 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-17 05:53:05.030  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
,11-17 05:53:05.031  5674  5674 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 05:53:05.031  5674  5674 D PanProfile: Bluetooth service connected
11-17 05:53:05.032  5718  5718 D PanService: Received start request. Starting profile...
,11-17 05:53:05.032  5718  5718 D BluetoothPanServiceJni: initializeNative(L110): pan
11-17 05:53:05.032  5718  5718 I bt_bluedroid: get_profile_interface pan
11-17 05:53:05.033  5718  5735 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-17 05:53:05.036  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
11-17 05:53:05.038  5718  5718 D BluetoothMapService: Received start request. Starting profile...
11-17 05:53:05.038  5718  5718 D BluetoothMapService: start()
11-17 05:53:05.041  5674  5674 D BluetoothMap: Proxy object connected
,11-17 05:53:05.041  5718  5718 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-17 05:53:05.042  5674  5674 D MapProfile: Bluetooth service connected
11-17 05:53:05.042  5674  5674 D BluetoothMap: getConnectedDevices()
11-17 05:53:05.042  5674  5674 D BluetoothMap: Bluetooth is Not enabled
11-17 05:53:05.042  5718  5718 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-17 05:53:05.043  5718  5718 D BluetoothMapAppObserver: createReceiver()
,11-17 05:53:05.044  5718  5718 D BluetoothMapAppObserver: initObservers()
,11-17 05:53:05.044  5718  5718 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-17 05:53:05.052  5718  5718 V SapService: SapBinder()
,11-17 05:53:05.052  5718  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
,11-17 05:53:05.052  5718  5718 D SapService: Received start request. Starting profile...
11-17 05:53:05.052  5718  5718 V SapService: start()
,11-17 05:53:05.054  5718  5718 V BluetoothAdapterState: isTurningOff()=false
,11-17 05:53:05.054  5718  5718 V BluetoothAdapterState: isTurningOn()=true
11-17 05:53:05.054  5718  5718 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:05.055  5718  5748 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isTurningOff()=false
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isTurningOn()=true
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isTurningOff()=false
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isTurningOn()=true
11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 05:53:05.055  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isTurningOff()=false
,11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isTurningOn()=true
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isTurningOff()=false
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isTurningOn()=true
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isTurningOff()=false
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isTurningOn()=true
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isBleTurningOn()=false
11-17 05:53:05.056  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:05.057  5718  5718 V BluetoothAdapterState: isTurningOff()=false
11-17 05:53:05.057  5718  5718 V BluetoothAdapterState: isTurningOn()=true
11-17 05:53:05.057  5718  5718 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 05:53:05.057  5718  5718 V BluetoothAdapterState: isBleTurningOff()=false
11-17 05:53:05.057  5718  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-17 05:53:05.058  5718  5731 D BluetoothAdapterProperties: ScanMode =  20
11-17 05:53:05.058  5718  5731 D BluetoothAdapterProperties: State =  11
11-17 05:53:05.058  5718  5731 D BluetoothAdapterProperties: Setting state to 12
11-17 05:53:05.058  5718  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-17 05:53:05.059  5718  5735 D BluetoothAdapterProperties: Scan Mode:21
11-17 05:53:05.059  5718  5731 I BluetoothAdapterState: Entering OnState
11-17 05:53:05.059  3085  3938 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-17 05:53:05.059  5718  5735 D BluetoothAdapterProperties: Discoverable Timeout:120
11-17 05:53:05.062  3085  3085 D BluetoothInputDevice: Proxy object connected
,11-17 05:53:05.062  3085  3085 D HidProfile: Bluetooth service connected
11-17 05:53:05.062  3742  3994 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-17 05:53:05.063  5674  5684 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 05:53:05.065   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 05:53:05.065  5674  5685 D BluetoothMap: onBluetoothStateChange: up=true
11-17 05:53:05.065   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 05:53:05.066  3085  5613 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 05:53:05.066   928   928 D BluetoothA2dp: Proxy object connected
11-17 05:53:05.067  3085  3097 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 05:53:05.068  3085  3098 D BluetoothMap: onBluetoothStateChange: up=true
11-17 05:53:05.069  5718  5718 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-17 05:53:05.069  3085  3085 D BluetoothMap: Proxy object connected
,11-17 05:53:05.069  3085  3085 D MapProfile: Bluetooth service connected
11-17 05:53:05.069  3085  3085 D BluetoothMap: getConnectedDevices()
11-17 05:53:05.070  5718  5718 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-17 05:53:05.071   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 05:53:05.071   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-17 05:53:05.071  5674  5684 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-17 05:53:05.071  5718  5718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:53:05.072  3085  5613 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-17 05:53:05.073  5718  5718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:53:05.073  3085  3085 D BluetoothA2dp: Proxy object connected
11-17 05:53:05.073  5674  5685 D BluetoothPan: onBluetoothStateChange on: true
11-17 05:53:05.074  3085  3098 D BluetoothPan: onBluetoothStateChange on: true
11-17 05:53:05.074  5718  5718 D ObexServerSockets: Succeed to create listening sockets 
11-17 05:53:05.075  5718  5718 D ObexServerSockets0: startAccept()
11-17 05:53:05.075  5718  5718 D ObexServerSockets0: prepareForNewConnect()
11-17 05:53:05.075  3085  3085 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 05:53:05.075  3085  3085 D PanProfile: Bluetooth service connected
11-17 05:53:05.076   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-17 05:53:05.077  5718  5718 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-17 05:53:05.077  5718  5718 D BluetoothSdpJni: SDP Create record success - handle: 0
11-17 05:53:05.077  5718  5718 D BluetoothMapService: onReceive
11-17 05:53:05.077  5718  5718 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-17 05:53:05.077  5718  5718 D BluetoothMapService: STATE_ON
11-17 05:53:05.079  5674  5674 D LocalBluetoothProfileManager: Adding local A2DP profile
11-17 05:53:05.080  5718  5756 D ObexServerSockets0: Accepting socket connection...
11-17 05:53:05.080  5718  5757 D ObexServerSockets0: Accepting socket connection...
,11-17 05:53:05.081  5718  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:53:05.082  5674  5674 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-17 05:53:05.082  5718  5759 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-17 05:53:05.083  5718  5759 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-17 05:53:05.090  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-17 05:53:05.092  5674  5674 D BluetoothA2dp: Proxy object connected
,11-17 05:53:05.096  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 05:53:05.103  5718  5718 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-17 05:53:05.103  5718  5718 D ObexServerSockets0: prepareForNewConnect()
11-17 05:53:05.104  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 05:53:05.105  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-17 05:53:05.108  5614  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-17 05:53:05.108  5674  5674 D BluetoothPbap: Proxy object connected
,11-17 05:53:05.108  5674  5674 D PbapServerProfile: Bluetooth service connected
11-17 05:53:05.109  3085  3085 D BluetoothPbap: Proxy object connected
11-17 05:53:05.109  3085  3085 D PbapServerProfile: Bluetooth service connected
11-17 05:53:05.111  5614  5660 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-17 05:53:05.113  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 05:53:05.114   928   938 D WifiService: setWifiEnabled: false pid=5614, uid=10077
11-17 05:53:05.114   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:53:05.115   928  2889 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-17 05:53:05.115   928  2889 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-17 05:53:05.115   928  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 05:53:05.115   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 05:53:05.117  5718  5763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:53:05.126   928  5370 D DhcpClient: Clearing IP address
,11-17 05:53:05.126   506   925 D CommandListener: Clearing all IP addresses on wlan0
,11-17 05:53:05.130  5718  5768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:53:05.132  5718  5768 I BtOppRfcommListener: Accept thread started.
11-17 05:53:05.135   506   925 D CommandListener: Setting iface cfg
,11-17 05:53:05.143  3539  5427 V NativeCrypto: Read error: ssl=0x7f99ac6180: I/O error during system call, Connection timed out
,11-17 05:53:05.145  3539  5427 V NativeCrypto: SSL shutdown failed: ssl=0x7f99ac6180: I/O error during system call, Broken pipe
,11-17 05:53:05.151   928   938 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-17 05:53:05.151   928  5368 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-17 05:53:05.153   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-17 05:53:05.153   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-17 05:53:05.153   928  5368 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-17 05:53:05.155   532   532 E Parcel  : Reading a NULL string not supported here.
,11-17 05:53:05.158   928  2901 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-17 05:53:05.158   928   928 D RttService: SCAN_AVAILABLE : 1
11-17 05:53:05.158   928  3000 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-17 05:53:05.159  3711  3854 W QCNEJ   : |CORE| network lost: 100
11-17 05:53:05.159  3711  3854 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-17 05:53:05.164   928   928 D BluetoothHeadset: Proxy object connected
11-17 05:53:05.164   928   928 D BluetoothHeadset: Proxy object connected
11-17 05:53:05.164  3742  3994 D BluetoothHeadset: Proxy object connected
11-17 05:53:05.165  3085  3938 D BluetoothHeadset: Proxy object connected
11-17 05:53:05.165   928   945 D BluetoothHeadset: Proxy object connected
,11-17 05:53:05.165   928   928 D BluetoothHeadset: Proxy object connected
11-17 05:53:05.167   928  5371 D DhcpClient: Receive thread stopped
,11-17 05:53:05.169  3085  5613 D BluetoothHeadset: Proxy object connected
,11-17 05:53:05.171   928   945 D BluetoothHeadset: Proxy object connected
,11-17 05:53:05.171   928   945 D BluetoothHeadset: Proxy object connected
,11-17 05:53:05.174  3085  3085 D HeadsetProfile: Bluetooth service connected
,11-17 05:53:05.176  3085  3085 D HeadsetProfile: Bluetooth service connected
,11-17 05:53:05.181   928  2889 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-17 05:53:05.182   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:53:05.186  5674  5685 D BluetoothHeadset: Proxy object connected
,11-17 05:53:05.188   928  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 05:53:05.191  5674  5674 D HeadsetProfile: Bluetooth service connected
,11-17 05:53:05.206   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:53:05.207   506   925 D CommandListener: Clearing all IP addresses on wlan0
11-17 05:53:05.207   506   925 D TetherController: Setting IP forward enable = 0
,11-17 05:53:05.208   928  2901 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-17 05:53:05.208   928  2901 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 05:53:05.210   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-17 05:53:05.212   928  2889 D DhcpClient: doQuit
11-17 05:53:05.212   928  2889 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-17 05:53:05.213  3409  3409 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-17 05:53:05.213   928  5370 D DhcpClient: onQuitting
11-17 05:53:05.219  5254  5254 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3c7b364 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-17 05:53:05.223  5039  5062 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-17 05:53:05.223  5039  5062 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 05:53:05.223  5039  5062 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-17 05:53:05.223  5039  5062 E SarControlService: no key has been found,reset the power
11-17 05:53:05.223  5039  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 05:53:05.223  5039  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 05:53:05.223  5039  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 05:53:05.224  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:53:05.224  5064  5064 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-17 05:53:05.227  3655  3655 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-17 05:53:05.228  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@223416a HexData = [00000000ea03000000000000ffffffff]
,11-17 05:53:05.228  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 05:53:05.228  5064  5078 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-17 05:53:05.229  5039  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 05:53:05.230  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 05:53:05.230  5039  5049 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-17 05:53:05.230  5039  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 05:53:05.230  5039  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 05:53:05.232  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:53:05.232  5064  5064 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 05:53:05.235  3655  3655 D SystemUpdateService: onCreate
,11-17 05:53:05.239  3655  3655 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 05:53:05.242  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@223416a HexData = [00000000eb03000000000000ffffffff]
11-17 05:53:05.242  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 05:53:05.242  5064  5078 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-17 05:53:05.243  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-17 05:53:05.243  5039  5050 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-17 05:53:05.245  3655  5785 I SystemUpdateService: active receiver: enabled
11-17 05:53:05.247  3409  3409 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-17 05:53:05.248  3655  3655 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-17 05:53:05.251  3409  3409 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-17 05:53:05.252   506   918 W SocketClient: write error (Broken pipe)
11-17 05:53:05.252   506   918 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-17 05:53:05.252   506   918 W SocketListener: Error sending broadcast (Broken pipe)
11-17 05:53:05.253  3655  5397 I iu.UploadsManager: num queued entries: 0
11-17 05:53:05.253  3655  5397 I iu.UploadsManager: num updated entries: 0
,11-17 05:53:05.255  3655  3655 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 05:53:05.258  3655  5785 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 05:53:05.260  3655  5785 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-17 05:53:05.260  3655  5785 I SystemUpdateService: now status is 0 (complete)
11-17 05:53:05.260  3655  5785 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 05:53:05.260  3655  5785 I SystemUpdateService: file has been verified
11-17 05:53:05.260  3655  5785 I SystemUpdateService: OTA package size = 21989297
,11-17 05:53:05.261  3655  3655 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 05:53:05.261  3655  5397 I iu.SyncManager: NEXT; no task
,11-17 05:53:05.266  3655  5785 I SystemUpdateService: showing system update notification
,11-17 05:53:05.273  3409  3409 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-17 05:53:05.273   928  3782 I ActivityManager: Start proc 5787:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-17 05:53:05.285  3655  3655 D SystemUpdateService: onDestroy
,11-17 05:53:05.288  3409  3409 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-17 05:53:05.291   506   918 W SocketClient: write error (Broken pipe)
11-17 05:53:05.291   506   918 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-17 05:53:05.291   506   918 W SocketListener: Error sending broadcast (Broken pipe)
,11-17 05:53:05.305  5787  5787 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-17 05:53:05.308  5787  5787 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 05:53:05.314  5787  5787 D SprintDMHelper: simOperator: 
11-17 05:53:05.314  5787  5787 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 05:53:05.322   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:05.326  5014  5799 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-17 05:53:05.328   928  3815 I ActivityManager: Killing 5254:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-17 05:53:05.357   928  3815 I ActivityManager: Start proc 5800:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-17 05:53:05.384  5800  5800 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-17 05:53:05.392   928  3815 I ActivityManager: Killing 4672:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-17 05:53:05.409   928  2889 D wifi    : In wifi stop Hal
11-17 05:53:05.409  5014  5014 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 05:53:05.409   928  2889 D wifi    : halHandle = 0x7f8354df40, mVM = 0x7f9fb8d140, mCls = 0x100a02
11-17 05:53:05.410   928  3408 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-17 05:53:05.410   928  3408 D WifiHAL : Got a signal to exit!!!
,11-17 05:53:05.410   928  3408 I WifiHAL : Exit wifi_event_loop
11-17 05:53:05.410   928  2889 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-17 05:53:05.410   928  2889 E WifiHAL : Event processing terminated
11-17 05:53:05.411   928  2889 D wifi    : In wifi cleaned up handler
,11-17 05:53:05.411   928  2889 I WifiHAL : Internal cleanup completed
11-17 05:53:05.412  4012  4165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 05:53:05.429   506   918 W SocketClient: write error (Broken pipe)
,11-17 05:53:05.429   506   918 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
11-17 05:53:05.429   506   918 W SocketListener: Error sending broadcast (Broken pipe)
11-17 05:53:05.430   928  3408 D wifi    : set interface wlan0 flags (DOWN)
11-17 05:53:05.430   928  2889 D WifiNative-HAL: HAL event thread stopped successfully
,11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 05:53:05.626  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 05:53:05.634  5614  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-17 05:53:05.638   928   945 D Tethering: InitialState.processMessage what=4
,11-17 05:53:05.639   928  3114 D WifiService: setWifiEnabled: true pid=5614, uid=10077
11-17 05:53:05.639   928  3114 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 05:53:05.640  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 05:53:05.646   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-17 05:53:06.145   928  3375 D WifiService: setWifiEnabled: true pid=5614, uid=10077
,11-17 05:53:06.145   928  3375 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:53:06.303   506   925 E Netd    : netlink response contains error (No such file or directory)
,11-17 05:53:06.306   928  2901 E NetdConnector: NDC Command {118 network destroy 100} took too long (1096ms)
,11-17 05:53:06.306   928  2901 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-17 05:53:06.306   928  2901 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-17 05:53:06.307   928  2865 E NetdConnector: NDC Command {119 bandwidth setglobalalert 2097152} took too long (1090ms)
,11-17 05:53:06.308   506   925 D SoftapController: Softap fwReload - Ok
,11-17 05:53:06.309   928  2889 E NetdConnector: NDC Command {120 softap fwreload wlan0 STA} took too long (662ms)
,11-17 05:53:06.309   928  2864 E NetdConnector: NDC Command {121 bandwidth gettetherstats} took too long (663ms)
,11-17 05:53:06.310   506   925 D TetherController: Setting IP forward enable = 0
11-17 05:53:06.318   506   925 D CommandListener: Setting iface cfg
11-17 05:53:06.319   506   925 D CommandListener: Trying to bring down wlan0
11-17 05:53:06.320   506   925 D CommandListener: Clearing all IP addresses on wlan0
11-17 05:53:06.322   534   534 I ServiceManager: Waiting for service AtCmdFwd...
11-17 05:53:06.323   928  2889 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-17 05:53:06.647   928  3797 D WifiService: setWifiEnabled: true pid=5614, uid=10077
11-17 05:53:06.650   928  3797 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 05:53:06.934   928  2889 D wifi    : set interface wlan0 flags (UP)
,11-17 05:53:06.934   928  2889 I WifiHAL : Initializing wifi
11-17 05:53:06.934   928  2889 I WifiHAL : Creating socket
,11-17 05:53:06.940   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-17 05:53:06.946   928  2889 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-17 05:53:06.946   928  2889 D wifi    : Did set static halHandle = 0x7f8354df40
11-17 05:53:06.946   928  2889 D wifi    : halHandle = 0x7f8354df40, mVM = 0x7f9fb8d140, mCls = 0x18ee
11-17 05:53:06.946   928  2889 D wifi    : array field set
11-17 05:53:06.947   928  2889 I WifiNative-HAL: interface[0] = wlan0
11-17 05:53:06.949   928  5820 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547664224064
,11-17 05:53:06.949   928  5820 D wifi    : waitForHalEvents called, vm = 0x7f9fb8d140, obj = 0x18ee, env = 0x7f82a512c0
,11-17 05:53:07.019  5821  5821 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-17 05:53:07.041  5821  5821 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 05:53:07.050  5821  5821 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-17 05:53:07.050  5821  5821 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
11-17 05:53:07.050   928  2889 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-17 05:53:07.071   928  2889 D WifiConfigStore: Loading config and enabling all networks 
,11-17 05:53:07.082   928  2889 D WifiConfigStore: loaded 0 passpoint configs
,11-17 05:53:07.082   928  2889 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-17 05:53:07.083   928  2889 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-17 05:53:07.084   928  2889 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-17 05:53:07.085   928  2889 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-17 05:53:07.085   928  2889 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-17 05:53:07.086   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-17 05:53:07.086   928  2889 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-17 05:53:07.090   928  2889 D WifiNative-HAL: Setting external_sim to 1
,11-17 05:53:07.090  5014  5014 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 05:53:07.090   928  2889 D wifi    : setting dfs flag to true, 0x7f886ffc80
,11-17 05:53:07.091   928  2889 D WifiStateMachine: Setting OUI to DA-A1-19
11-17 05:53:07.091   928  2889 D wifi    : setting scan oui 0x7f886ffc80
11-17 05:53:07.091   928  2889 D WifiHAL : Sending mac address OUI
,11-17 05:53:07.095   928  2889 E native  : do suspend false
,11-17 05:53:07.102   928  2889 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-17 05:53:07.102   928   928 D RttService: SCAN_AVAILABLE : 3
11-17 05:53:07.102   928  3000 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-17 05:53:07.102   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-17 05:53:07.103   506   925 D CommandListener: Setting iface cfg
,11-17 05:53:07.107   928  2868 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
11-17 05:53:07.107   928  2868 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-17 05:53:07.119   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=133622 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-17 05:53:07.120   928  2868 D WifiNative-HAL: p2pGetDeviceAddress
,11-17 05:53:07.120   928  2868 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 05:53:07.155  5614  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 05:53:07.157  5614  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-17 05:53:07.158  5614  5660 D BluetoothAdapter: enable(): BT is already enabled..!
11-17 05:53:07.159   928  3376 D WifiService: setWifiEnabled: true pid=5614, uid=10077
11-17 05:53:07.159   928  3376 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 05:53:07.159  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 05:53:07.160  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:53:07.160  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 05:53:07.160  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e074302 removed from the list
11-17 05:53:07.160  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 05:53:07.160  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50e5413 removed from the list
,11-17 05:53:07.160  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 05:53:07.162  5614  5660 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-17 05:53:07.164  5614  5660 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-17 05:53:07.165  5614  5660 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-17 05:53:07.166  5614  5660 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-17 05:53:07.168  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-17 05:53:07.169  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-17 05:53:07.170  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-17 05:53:07.171  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-17 05:53:07.172  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-17 05:53:07.174  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-17 05:53:07.175  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6ce2a0e Bundle[{}]
11-17 05:53:07.175  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-17 05:53:07.175  5614  5660 I io.jxcore.node.LifeCycleMonitor: start: OK
11-17 05:53:07.176  5614  5660 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-17 05:53:07.176  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-17 05:53:07.176  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-17 05:53:07.176  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-17 05:53:07.176  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-17 05:53:07.177  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-17 05:53:07.177  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-17 05:53:07.177  5614  5660 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-17 05:53:07.178  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-17 05:53:07.180  5614  5660 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-17 05:53:07.182  5614  5660 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-17 05:53:07.183  5614  5660 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-17 05:53:07.183  5614  5660 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-17 05:53:07.183  5614  5660 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-17 05:53:07.184  5614  5660 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-17 05:53:07.186  5614  5660 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-17 05:53:07.187  5614  5660 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-17 05:53:07.188  5614  5660 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-17 05:53:07.189  5614  5660 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-17 05:53:07.190  5614  5660 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-17 05:53:07.190  5614  5660 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-17 05:53:07.190  5614  5660 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-17 05:53:07.191  5614  5660 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-17 05:53:07.191  5614  5660 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-17 05:53:07.191  5614  5660 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-17 05:53:07.192  5614  5660 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-17 05:53:07.193  5614  5660 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-17 05:53:07.194  5614  5660 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-17 05:53:07.195  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 05:53:07.195  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f560049 added. We now have 3 listener(s)
,11-17 05:53:07.196  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 05:53:07.196  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 05:53:07.196  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 05:53:07.197  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 05:53:07.197  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a8d4e added. We now have 3 listener(s)
11-17 05:53:07.197  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 05:53:07.197  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-17 05:53:07.201  5614  5660 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-17 05:53:07.202  5614  5660 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-17 05:53:07.202  5614  5660 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-17 05:53:07.202  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-17 05:53:07.202  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:07.202  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.202  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.202  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:53:07.202  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:53:07.202  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:53:07.202  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:53:07.202  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 05:53:07.205  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-17 05:53:07.205  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:53:07.206  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:53:07.206  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:53:07.206  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-17 05:53:07.206  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-17 05:53:07.206  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-17 05:53:07.206  5614  5824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-17 05:53:07.206  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-17 05:53:07.206  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 05:53:07.207  5614  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 05:53:07.204  5758  5758 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30607]" dev="sockfs" ino=30607 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:53:07.204  5758  5758 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[30607]" dev="sockfs" ino=30607 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:53:07.210  5614  5824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-17 05:53:07.210  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:53:07.210  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:53:07.210  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-17 05:53:07.215  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:07.215  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:53:07.215  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:53:07.216  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:53:07.216  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-17 05:53:07.217  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.217  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.217  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:53:07.217  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:53:07.217  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:53:07.218  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
11-17 05:53:07.218  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:53:07.218  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:53:07.218  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.218  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:53:07.218  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:53:07.218  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.218  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.218  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.219  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:53:07.221  5718  5758 D BtGatt.GattService: registerClient() - UUID=a14fcfb3-ee83-4213-9c9e-0a6c7c5d053f
11-17 05:53:07.222  5718  5735 D BtGatt.GattService: onClientRegistered() - UUID=a14fcfb3-ee83-4213-9c9e-0a6c7c5d053f, clientIf=5
,11-17 05:53:07.222  5614  5625 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-17 05:53:07.224  5718  5738 D BtGatt.AdvertiseManager: message : 0
,11-17 05:53:07.226  5718  5738 D BtGatt.AdvertiseManager: starting multi advertising
,11-17 05:53:07.235  5718  5735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-17 05:53:07.241  5718  5735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-17 05:53:07.242  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:07.242  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.242  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:53:07.243  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.243  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.243  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.243  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.243  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.243  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:53:07.244  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:53:07.244  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:07.245  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:07.245  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.245  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:07.245  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-17 05:53:07.245  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.246  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-17 05:53:07.246  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-17 05:53:07.246  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 05:53:07.248  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.248  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:53:07.249  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.249  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.249  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:53:07.249  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-17 05:53:07.323   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:07.750  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-17 05:53:07.750  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-17 05:53:07.750  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-17 05:53:08.323   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-17 05:53:10.163  5821  5821 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 05:53:10.167  5821  5821 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 05:53:10.171  5821  5821 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 05:53:10.217   928  2889 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-17 05:53:10.217   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-17 05:53:10.218   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 05:53:10.229   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-17 05:53:10.258   928  2889 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-17 05:53:10.260  5821  5821 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-17 05:53:10.677  5821  5821 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-17 05:53:10.714  5821  5821 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-17 05:53:10.715  5821  5821 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-17 05:53:10.723   928  2889 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 05:53:10.723   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-17 05:53:10.723   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-17 05:53:10.738   928  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 05:53:10.747  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-17 05:53:10.747  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-17 05:53:10.747  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-17 05:53:10.748  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-17 05:53:10.748  5614  5824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-17 05:53:10.748  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-17 05:53:10.748  5614  5824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:53:10.748  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-17 05:53:10.748  5614  5824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-17 05:53:10.748  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.749  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.749  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.750  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:53:10.750   506   925 D CommandListener: Setting iface cfg
11-17 05:53:10.750  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:53:10.751  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:53:10.751  5614  5660 D BluetoothLeScanner: could not find callback wrapper
11-17 05:53:10.751  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:53:10.751  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.751  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.751  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.751  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:53:10.751  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.753  5718  5738 D BtGatt.AdvertiseManager: message : 1
11-17 05:53:10.753  5718  5738 D BtGatt.AdvertiseManager: stop advertise for client 5
11-17 05:53:10.755   928  2889 D WifiStateMachine: Start Dhcp Watchdog 2
,11-17 05:53:10.762  5718  5735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-17 05:53:10.762  5718  5735 D BtGatt.GattService: Client app is not null!
,11-17 05:53:10.763  5718  5758 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:53:10.763  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-17 05:53:10.764  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.764  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-17 05:53:10.764  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.764  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.764  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.764  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 05:53:10.764  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:53:10.765  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:53:10.765  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.767  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.767  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:53:10.767  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.767  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.767  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 05:53:10.768  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-17 05:53:10.768  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:53:10.768  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:53:10.768  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:53:10.768  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:53:10.768  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-17 05:53:10.768  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.768  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:53:10.768  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-17 05:53:10.768  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.768  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.768  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-17 05:53:10.769  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.770  5614  5660 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-17 05:53:10.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.770  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-17 05:53:10.770  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.770  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:53:10.771  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 05:53:10.771  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-17 05:53:10.771  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-17 05:53:10.771  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:53:10.772  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-17 05:53:10.774  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 05:53:10.777   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-17 05:53:10.778   928  2901 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-17 05:53:10.778   928  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-17 05:53:10.778   928  5832 D DhcpClient: Receive thread started
11-17 05:53:10.780  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:53:10.780  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:53:10.780  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-17 05:53:10.783  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.783  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:53:10.784  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:53:10.784  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:53:10.784  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-17 05:53:10.786  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-17 05:53:10.789  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-17 05:53:10.789  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.789  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-17 05:53:10.790  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-17 05:53:10.790  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-17 05:53:10.790  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-17 05:53:10.791  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.791  5614  5660 D BluetoothAdapter: STATE_ON
,11-17 05:53:10.794  5718  5729 D BtGatt.GattService: registerClient() - UUID=b55b3d4b-c438-43c0-b7d4-0de496106b69
,11-17 05:53:10.795  5718  5735 D BtGatt.GattService: onClientRegistered() - UUID=b55b3d4b-c438-43c0-b7d4-0de496106b69, clientIf=5
,11-17 05:53:10.795  5614  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-17 05:53:10.796  5718  5728 D BtGatt.GattService: start scan with filters
,11-17 05:53:10.799  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-17 05:53:10.800  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.800  5718  5739 D BtGatt.ScanManager: handling starting scan
11-17 05:53:10.800  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-17 05:53:10.801  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.802  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 05:53:10.802  5718  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e35d3
11-17 05:53:10.802  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:10.802  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.802  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-17 05:53:10.802  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-17 05:53:10.802  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.803  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.803  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-17 05:53:10.803  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:53:10.804  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.806  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:10.806  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 05:53:10.806  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.806  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:10.807  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 05:53:10.809  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-17 05:53:10.809  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.809  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.809  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:53:10.810  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 05:53:10.811  5718  5735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-17 05:53:10.811  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:10.811  5718  5739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-17 05:53:10.816  5718  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-17 05:53:10.816  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:10.817  5718  5739 D BtGatt.ScanManager: Starting BLE batch scan
11-17 05:53:10.817  5718  5739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-17 05:53:10.824  5718  5735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-17 05:53:10.825  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:53:10.829  5718  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-17 05:53:10.829  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:53:10.859   928  2889 E native  : do suspend false
,11-17 05:53:10.872   928  5830 D DhcpClient: Broadcasting DHCPDISCOVER
,11-17 05:53:10.907   928  5832 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172703, domain null
11-17 05:53:10.907   928  5830 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172703 seconds
,11-17 05:53:10.908   928  5830 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-17 05:53:10.927   928  5832 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-17 05:53:10.927   928  5830 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-17 05:53:10.929   506   925 D CommandListener: Setting iface cfg
,11-17 05:53:10.933   928  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-17 05:53:10.936   928  5830 D DhcpClient: Scheduling renewal in 86399s
,11-17 05:53:10.944   928  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-17 05:53:10.944   928  2889 D WifiConfigStore: No blacklist allowed without epno enabled
11-17 05:53:10.945   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-17 05:53:10.946   928  2901 D ConnectivityService: Adding iface wlan0 to network 101
,11-17 05:53:10.949   928  2889 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-17 05:53:10.980   928  2901 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-17 05:53:10.980   928  2901 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-17 05:53:10.981   928  2901 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-17 05:53:10.985   928  2901 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-17 05:53:10.987   928  2901 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-17 05:53:10.995   928  2901 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:53:10.999   928  2901 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-17 05:53:10.999   928  2901 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-17 05:53:10.999   928  2901 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-17 05:53:10.999   928  2889 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-17 05:53:10.999   928  2901 D ConnectivityService:    accepting network in place of null
,11-17 05:53:10.999   928  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-17 05:53:11.000   928  2901 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -57]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 05:53:11.021   928  5829 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137524, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-17 05:53:11.021   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:53:11.040   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 05:53:11.042   928  2901 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-17 05:53:11.043   928  2901 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 05:53:11.044   928  2901 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-17 05:53:11.044  3711  3854 W QCNEJ   : |CORE| network available: 101
11-17 05:53:11.047  3711  3854 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-17 05:53:11.047   928   945 D Tethering: MasterInitialState.processMessage what=3
11-17 05:53:11.048  3711  3854 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-17 05:53:11.049  3711  3854 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-17 05:53:11.052  5039  5062 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-17 05:53:11.052  5039  5062 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 05:53:11.052  5039  5062 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-17 05:53:11.052  5039  5062 E SarControlService: no key has been found,reset the power
11-17 05:53:11.052  5039  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 05:53:11.053  5039  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 05:53:11.053  5039  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 05:53:11.054  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:53:11.054  5064  5064 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 05:53:11.055  5039  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 05:53:11.055  5039  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 05:53:11.055  5039  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 05:53:11.056  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 05:53:11.056  5064  5064 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 05:53:11.058  3655  3655 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-17 05:53:11.060  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@223416a HexData = [00000000ec03000000000000ffffffff]
11-17 05:53:11.060  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 05:53:11.060  5064  5078 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-17 05:53:11.061  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 05:53:11.061  5039  5049 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 05:53:11.062  3655  3655 D SystemUpdateService: onCreate
11-17 05:53:11.065  3655  3655 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-17 05:53:11.066  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@223416a HexData = [00000000ed03000000000000ffffffff]
11-17 05:53:11.067  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 05:53:11.067  5064  5078 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-17 05:53:11.067  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-17 05:53:11.067  5039  5050 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-17 05:53:11.077  3655  3655 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-17 05:53:11.083  3655  5397 I iu.UploadsManager: num queued entries: 0
,11-17 05:53:11.084  3655  5397 I iu.UploadsManager: num updated entries: 0
,11-17 05:53:11.085  3655  5397 I iu.SyncManager: NEXT; no task
,11-17 05:53:11.086  3655  5843 I SystemUpdateService: active receiver: enabled
,11-17 05:53:11.088  3655  3655 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 05:53:11.089  3655  3655 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 05:53:11.091   928  5828 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-17 05:53:11.091  5787  5787 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 05:53:11.095  5787  5787 D SprintDMHelper: simOperator: 
11-17 05:53:11.095  5787  5787 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 05:53:11.117  3655  5843 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 05:53:11.129  3655  5843 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-17 05:53:11.130  3655  5843 I SystemUpdateService: now status is 0 (complete)
11-17 05:53:11.130  3655  5843 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 05:53:11.130  3655  5843 I SystemUpdateService: file has been verified
11-17 05:53:11.130  3655  5843 I SystemUpdateService: OTA package size = 21989297
,11-17 05:53:11.135  3655  5843 I SystemUpdateService: showing system update notification
,11-17 05:53:11.139   928  5828 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Nov 2016 10:53:11 GMT], X-Android-Received-Millis=[1479379991138], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479379991114]}
,11-17 05:53:11.139   928  2901 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-17 05:53:11.139   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-17 05:53:11.140   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:53:11.141   928  2901 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-17 05:53:11.144  3655  3655 D SystemUpdateService: onDestroy
,11-17 05:53:11.210  5014  5848 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-17 05:53:11.310  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-17 05:53:11.310  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 05:53:11.311  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-17 05:53:11.332  5718  5718 D BtGatt.ScanManager: awakened up at time 137834
,11-17 05:53:11.337  5718  5739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:53:11.354  5718  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-17 05:53:11.354  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:11.357  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-17 05:53:11.858  5718  5718 D BtGatt.ScanManager: awakened up at time 138360
,11-17 05:53:11.860  5718  5739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:53:11.891  5718  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-17 05:53:11.891  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:11.891  5718  5735 D BtGatt.GattService: current time is 138394304033
11-17 05:53:11.892  5718  5735 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
11-17 05:53:11.895  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-17 05:53:11.897  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-17 05:53:11.898  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,11-17 05:53:11.905  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
11-17 05:53:11.905  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=138045332524}
11-17 05:53:11.906  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=138045332524}
11-17 05:53:11.906  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=137895332524}
11-17 05:53:11.907  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=137895332524}
,11-17 05:53:11.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
11-17 05:53:11.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-17 05:53:11.909  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=137895332524}
,11-17 05:53:11.909  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=137895332524}
11-17 05:53:11.910  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
11-17 05:53:11.910  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-17 05:53:12.043   928  2901 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-17 05:53:13.809  5614  5660 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation,
11-17 05:53:13.809  5614  5660 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-17 05:53:13.810  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-17 05:53:13.810  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.811  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.811  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-17 05:53:13.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.811  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-17 05:53:13.811  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.812  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.812  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 05:53:13.812  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 05:53:13.812  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.812  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.813  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.818  5614  5660 D BluetoothAdapter: STATE_ON
,11-17 05:53:13.822  5718  5729 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-17 05:53:13.825  5718  5739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:53:13.825  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-17 05:53:13.829  5614  5660 D BluetoothAdapter: STATE_ON
,11-17 05:53:13.830  5718  5749 D BtGatt.GattService: stopScan() - queue size =1
,11-17 05:53:13.832  5718  5758 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 05:53:13.833  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:53:13.834  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.834  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-17 05:53:13.835  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.835  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 05:53:13.835  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:13.835  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.835  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-17 05:53:13.835  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-17 05:53:13.835  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-17 05:53:13.836  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-17 05:53:13.836  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.837  5614  5660 D BluetoothAdapter: STATE_ON
,11-17 05:53:13.841  5718  5718 D BtGatt.ScanManager: awakened up at time 140343
,11-17 05:53:13.846  5718  5729 D BtGatt.GattService: registerClient() - UUID=535e6fb6-431f-4fea-9b26-63eaae6df6d7
,11-17 05:53:13.846  5718  5735 D BtGatt.GattService: onClientRegistered() - UUID=535e6fb6-431f-4fea-9b26-63eaae6df6d7, clientIf=5
11-17 05:53:13.847  5614  5624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-17 05:53:13.847  5718  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-17 05:53:13.847  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:13.847  5718  5735 D BtGatt.GattService: current time is 140349914916
11-17 05:53:13.847  5718  5749 D BtGatt.GattService: start scan with filters
,11-17 05:53:13.847  5718  5735 D BtGatt.GattService: Batch record : [-2, 77, 105, 26, -81, 70, 1, -128, -58, 35, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -88, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -2, 77, 105, 26, -81, 70, 1, -128, -58, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-17 05:53:13.848  5718  5735 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
11-17 05:53:13.848  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-17 05:53:13.848  5718  5735 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
11-17 05:53:13.849  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-17 05:53:13.853  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-17 05:53:13.853  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:13.854  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-17 05:53:13.854  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.854  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 4. Current thread: Thread[main,5,main], id: 1
,11-17 05:53:13.854  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:13.854  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-17 05:53:13.854  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-17 05:53:13.854  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=138650352936}
,11-17 05:53:13.854  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-17 05:53:13.854  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 05:53:13.854  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=138650352936}
,11-17 05:53:13.855  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
11-17 05:53:13.855  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-17 05:53:13.855  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=138800352936}
11-17 05:53:13.855  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=138800352936}
11-17 05:53:13.855  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
11-17 05:53:13.855  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-17 05:53:13.855  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-17 05:53:13.856  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=46:AF:1A:69:4D:FE, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=138850352936}
11-17 05:53:13.856  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-17 05:53:13.856  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=46:AF:1A:69:4D:FE, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=138850352936}
11-17 05:53:13.856  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-17 05:53:13.856  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-17 05:53:13.856  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-17 05:53:13.856  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 6]
11-17 05:53:13.856  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-17 05:53:13.856  5718  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-17 05:53:13.856  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:13.854  5729  5729 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31111]" dev="sockfs" ino=31111 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-17 05:53:13.858  5729  5729 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31111]" dev="sockfs" ino=31111 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-17 05:53:13.857  5718  5739 D BtGatt.ScanManager: stopping BLe Batch
11-17 05:53:13.857  5614  5614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-17 05:53:13.857  5614  5855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-17 05:53:13.858  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 05:53:13.858  5614  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 05:53:13.858  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 05:53:13.858  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 6]
11-17 05:53:13.858  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
11-17 05:53:13.858  5614  5614 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 6]
,11-17 05:53:13.858  5614  5614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
11-17 05:53:13.858  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [<no peer name> A8:81:95:E9:5F:6F 6]
11-17 05:53:13.859  5614  5614 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 6], added - the peer count is 1
11-17 05:53:13.860  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=46:AF:1A:69:4D:FE, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=138600352936}
11-17 05:53:13.860  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=46:AF:1A:69:4D:FE, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=138600352936}
11-17 05:53:13.860  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
11-17 05:53:13.861  5614  5614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
,11-17 05:53:13.861  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 5]
11-17 05:53:13.861  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5]
11-17 05:53:13.861  5614  5614 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 5]
11-17 05:53:13.861  5614  5855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-17 05:53:13.861  5614  5614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: true
11-17 05:53:13.861  5614  5614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerUpdated. Listeners size = 1
11-17 05:53:13.861  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 5]
,11-17 05:53:13.862  5614  5614 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 5] updated - the peer count is 1
11-17 05:53:13.862  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:13.862  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.862  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-17 05:53:13.862  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-17 05:53:13.862  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.862  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.863  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-17 05:53:13.864  5718  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-17 05:53:13.864  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:13.864  5718  5739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:53:13.871  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:13.871  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.871  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.871  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-17 05:53:13.871  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-17 05:53:13.872  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 05:53:13.872  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
11-17 05:53:13.872  5718  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-17 05:53:13.872  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:13.872  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:53:13.872  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:53:13.872  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.872  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-17 05:53:13.872  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-17 05:53:13.872  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.872  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.873  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.873  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:53:13.875  5718  5739 D BtGatt.ScanManager: handling starting scan
11-17 05:53:13.877  5718  5758 D BtGatt.GattService: registerClient() - UUID=aff67fe8-b6e0-4e44-be64-6f807e0e5cd2
11-17 05:53:13.877  5718  5735 D BtGatt.GattService: onClientRegistered() - UUID=aff67fe8-b6e0-4e44-be64-6f807e0e5cd2, clientIf=6
11-17 05:53:13.878  5614  5625 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientI,f=6
11-17 05:53:13.878  5718  5738 D BtGatt.AdvertiseManager: message : 0
11-17 05:53:13.881  5718  5738 D BtGatt.AdvertiseManager: starting multi advertising
11-17 05:53:13.883  5718  5735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-17 05:53:13.883  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:13.883  5718  5739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-17 05:53:13.892  5718  5735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-17 05:53:13.896  5718  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-17 05:53:13.896  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:13.897  5718  5739 D BtGatt.ScanManager: Starting BLE batch scan
11-17 05:53:13.897  5718  5739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-17 05:53:13.901  5718  5735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-17 05:53:13.901  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-17 05:53:13.902  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-17 05:53:13.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-17 05:53:13.904  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 05:53:13.904  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:13.906  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:13.906  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.907  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:13.907  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-17 05:53:13.907  5614  5614 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
11-17 05:53:13.907  5614  5614 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 5], device name: '', device address: ''
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.908  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
,11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.908  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-17 05:53:13.908  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.910  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.910  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-17 05:53:13.910  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.910  5718  5735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-17 05:53:13.911  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.911  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:13.911  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:53:13.911  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-17 05:53:13.915  5718  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-17 05:53:13.915  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:53:14.324   928  2889 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,11-17 05:53:14.412  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-17 05:53:14.412  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-17 05:53:14.412  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-17 05:53:16.910  5614  5660 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-17 05:53:16.910  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 05:53:16.911  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-17 05:53:16.911  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-17 05:53:16.911  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-17 05:53:16.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-17 05:53:16.912  5614  5855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-17 05:53:16.912  5614  5855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-17 05:53:16.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-17 05:53:16.912  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-17 05:53:16.912  5614  5855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-17 05:53:16.912  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 05:53:16.913  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f560049 removed from the list
11-17 05:53:16.913  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 05:53:16.913  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 05:53:16.913  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-17 05:53:16.913  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 05:53:16.914  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 05:53:16.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:16.914  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.915  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-17 05:53:16.915  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.914  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-17 05:53:16.915  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 05:53:16.917  5614  5660 D BluetoothAdapter: STATE_ON
,11-17 05:53:16.918  5718  5729 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-17 05:53:16.918  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 05:53:16.919  5718  5739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-17 05:53:16.920  5614  5660 D BluetoothAdapter: STATE_ON
11-17 05:53:16.922  5718  5728 D BtGatt.GattService: stopScan() - queue size =1
11-17 05:53:16.923  5718  5758 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 05:53:16.924  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 05:53:16.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-17 05:53:16.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.925  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.926  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.926  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-17 05:53:16.926  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.926  5718  5718 D BtGatt.ScanManager: awakened up at time 143429
11-17 05:53:16.928  5718  5738 D BtGatt.AdvertiseManager: message : 1
11-17 05:53:16.929  5718  5738 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-17 05:53:16.942  5718  5735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-17 05:53:16.942  5718  5735 D BtGatt.GattService: Client app is not null!
,11-17 05:53:16.943  5718  5728 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-17 05:53:16.945  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 05:53:16.945  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.945  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-17 05:53:16.945  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.945  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.946  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.946  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 05:53:16.946  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 05:53:16.946  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 05:53:16.947  5614  5660 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
11-17 05:53:16.947  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-17 05:53:16.948  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.949  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:53:16.949  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.949  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-17 05:53:16.949  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a8d4e removed from the list
11-17 05:53:16.949  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:53:16.949  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-17 05:53:16.949  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 05:53:16.949  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:16.949  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.949  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:53:16.949  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-17 05:53:16.950  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.950  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.950  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-17 05:53:16.950  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.950  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-17 05:53:16.951  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-17 05:53:16.951  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-17 05:53:16.951  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-17 05:53:16.951  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 05:53:16.951  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-17 05:53:16.951  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-17 05:53:16.951  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.951  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.951  5614  5614 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.951  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.951  5614  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 05:53:16.952  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.952  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 05:53:16.952  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 05:53:16.952  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 05:53:16.952  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-17 05:53:16.952  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-17 05:53:16.952  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 05:53:16.953  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-17 05:53:16.953  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-17 05:53:16.954  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-17 05:53:16.955  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-17 05:53:16.955  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-17 05:53:16.956  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-17 05:53:16.956  5614  5660 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-17 05:53:16.966  5718  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-17 05:53:16.966  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:53:16.966  5718  5735 D BtGatt.GattService: current time is 143469319390
,11-17 05:53:16.967  5718  5735 D BtGatt.GattService: Batch record : [-2, 77, 105, 26, -81, 70, 1, -128, -54, 39, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -87, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -83, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -91, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -90, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -88, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-17 05:53:16.967  5718  5735 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
11-17 05:53:16.967  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-17 05:53:16.968  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-17 05:53:16.968  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-17 05:53:16.968  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-17 05:53:16.968  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-17 05:53:16.968  5718  5735 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-17 05:53:16.968  5718  5735 E BtGatt.ContextMap: Context not found for ID 5
,11-17 05:53:16.975  5718  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-17 05:53:16.975  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:16.975  5718  5739 D BtGatt.ScanManager: stopping BLe Batch
,11-17 05:53:16.979  5718  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-17 05:53:16.980  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 05:53:16.980  5718  5739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 05:53:16.985  5718  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-17 05:53:16.985  5718  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 05:53:17.453  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 05:53:18.324   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:18.962  5614  5660 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-17 05:53:19.004   928  2901 D ConnectivityService: handlePromptUnvalidated 101
,11-17 05:53:19.092  5614  5857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 05:53:19.092  5614  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:19.325   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:19.897  5614  5857 W !!      : call onHalfStreamCopied
,11-17 05:53:19.897  5614  5857 I testCopyDataAndClose: closing input stream
,11-17 05:53:20.327   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:20.671  5614  5857 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 05:53:20.671  5614  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:20.671  5614  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 05:53:20.671  5614  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:20.672  5614  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-17 05:53:20.672  5614  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-17 05:53:20.672  5614  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 05:53:20.672  5614  5857 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-17 05:53:20.672  5614  5857 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-17 05:53:20.672  5614  5857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 05:53:20.672  5614  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-17 05:53:21.328   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:22.122   928  2889 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-17 05:53:22.329   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:23.330   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-17 05:53:24.408  5614  5660 I StreamCopyingThreadTest: Starting test: testRun
,11-17 05:53:24.415  5614  5858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:53:24.415  5614  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:29.424  5614  5859 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-17 05:53:29.426  5614  5660 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-17 05:53:29.630  5614  5860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 05:53:29.630  5614  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 05:53:31.268  5614  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-17 05:53:34.991  5614  5660 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-17 05:53:34.993  5614  5861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:53:34.993  5614  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:34.994  5614  5861 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:53:34.994  5614  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:34.994  5614  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 05:53:34.994  5614  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:34.995  5614  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-17 05:53:34.995  5614  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-17 05:53:34.995  5614  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 05:53:34.995  5614  5861 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-17 05:53:34.995  5614  5861 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-17 05:53:34.995  5614  5861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:53:34.995  5614  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-17 05:53:34.997  5614  5660 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-17 05:53:34.997  5614  5660 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-17 05:53:34.998  5614  5660 I StreamCopyingThreadTest: Starting test: testRunWithException
11-17 05:53:35.001  5614  5862 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:53:35.001  5614  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 05:53:35.002  5614  5862 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-17 05:53:35.002  5614  5862 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:53:35.002  5614  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-17 05:53:35.002  5614  5862 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-17 05:53:35.003  5614  5862 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-17 05:53:35.003  5614  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-17 05:53:35.005  5614  5660 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-17 05:53:35.005  5614  5660 E com.test.thalitest.ThaliTestRunner: 
11-17 05:53:35.005  5614  5660 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-17 05:53:35.005  5614  5660 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.006  5614,  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:53:35.006  5614  5660 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.ru,nners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:53:35.007  5614  5660 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunn,er: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.,ParentRunner$3.run(ParentRunner.java:290)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:35.008  5614  5660 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-17 05:53:35.011  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG UnitTest_app: 'Running unit tests'
11-17 05:53:35.011  5614  5660 I jxcore-log: 
11-17 05:53:35.011  5614  5660 I jxcore-log: *Native tests were executed*
11-17 05:53:35.011  5614  5660 I jxcore-log: 
11-17 05:53:35.011  5614  5660 I jxcore-log: Total number of executed tests:  82
11-17 05:53:35.011  5614  5660 I jxcore-log: 
11-17 05:53:35.011  5614  5660 I jxcore-log: Number of passed tests:  79
11-17 05:53:35.011  5614  5660 I jxcore-log: 
11-17 05:53:35.011  5614  5660 I jxcore-log: Number of failed tests:  3
11-17 05:53:35.011  5614  5660 I jxcore-log: 
11-17 05:53:35.011  5614  5660 I jxcore-log: Number of ignored tests:  0
11-17 05:53:35.011  5614  5660 I jxcore-log: 
11-17 05:53:35.012  5614  5660 I jxcore-log: Total duration:  38324
11-17 05:53:35.012  5614  5660 I jxcore-log: 
11-17 05:53:35.012  5614  5660 I jxcore-log: Failed to execute UT.
11-17 05:53:35.012  5614  5660 I jxcore-log: 
11-17 05:53:35.013  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-17 05:53:35.013  5614  5660 I jxcore-log: 
11-17 05:53:35.014  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-17 05:53:35.014  5614  5660 I jxcore-log: 
11-17 05:53:35.017  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:,53:35.017  5614  5660 I jxcore-log: 
11-17 05:53:35.017  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:53:35.017  5614  5660 I jxcore-log: 
11-17 05:53:35.018  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:53:35.018  5614  5660 I jxcore-log: 
11-17 05:53:35.019  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:53:35.019  5614  5660 I jxcore-log: 
11-17 05:53:35.019  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:53:35.019  5614  5660 I jxcore-log: 
11-17 05:53:35.020  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:53:35.020  5614  5660 I jxcore-log: 
11-17 05:53:35.020  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.020  5614  5660 I jxcore-log: 
11-17 05:53:35.020  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:53:35.020  5614  5660 I jxcore-log: 
11-17 05:53:35.021  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:53:35.021  5614  5660 I jxcore-log: 
11-17 05:53:35.021  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.021  5614  5660 I jxcore-log: 
11-17 05:53:35.021  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:53:35.021  5614  5660 I jxcore-log: 
11-17 05:53:35.021  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:53:35.021  5614  5660 I jxcore-log: 
11-17 05:53:35.021  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.021  5614  5660 I jxcore-log: 
11-17 05:53:35.022  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 05:53:35.022  5614  5660 I jxcore-log: 
11-17 05:53:35.022  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.022  5614  5660 I jxcore-log: 
11-17 05:53:35.022  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:53:35.022  5614  5660 I jxcore-log: 
11-17 05:53:35.022  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:53:35.022  5614  5660 I jxcore-log: 
11-17 05:53:35.023  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 05:53:35.023  5614  5660 I jxcore-log: 
11-17 05:53:35.023  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.023  5614  5660 I jxcore-log: 
11-17 05:53:35.023  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:53:35.023  5614  5660 I jxcore-log: 
11-17 05:53:35.023  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:53:35.023  5614  5660 I jxcore-log: 
11-17 05:53:35.023  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 05:53:35.023  5614  5660 I jxcore-log: 
11-17 05:53:35.024  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:53:35.024  5614  5660 I jxcore-log: 
11-17 05:53:35.024  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-17 05:53:35.024  5614  5660 I jxcore-log: 
11-17 05:53:35.024  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:53:35.024  5614  5660 I jxcore-log: 
11-17 05:53:35.024  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-17 05:53:35.024  5614  5660 I jxcore-log: 
11-17 05:53:35.024  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-17 05:53:35.024  5614  5660 I jxcore-log: 
11-17 05:53:35.025  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-17 05:53:35.025  5614  5660 I jxcore-log: 
11-17 05:53:35.026  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:53:35.026  5614  5660 I jxcore-log: 
11-17 05:53:35.026  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.026  5614  5660 I jxcore-log: 
11-17 05:53:35.027  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-17 05:53:35.027  5614  5660 I jxcore-log: 
11-17 05:53:35.027  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:53:35.027  5614  5660 I jxcore-log: 
11-17 05:53:35.027  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.027  5614  5660 I jxcore-log: 
11-17 05:53:35.027  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"A8:81:95:E9:5F:6F-6","peerAvailable":true,"pleaseConnect":false}]'
11-17 05:53:35.027  5614  5660 I jxcore-log: 
11-17 05:53:35.028  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8:81:95:E9:5F:6F-6","peerAvailable":true,"pleaseConnect":false}'
11-17 05:53:35.028  5614  5660 I jxcore-log: 
11-17 05:53:35.028  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
11-17 05:53:35.028  5614  5660 I jxcore-log: 
11-17 05:53:35.028  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}]'
11-17 05:53:35.028  5614  5660 I jxcore-log: 
11-17 05:53:35.028  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}'
11-17 05:53:35.028  5614  5660 I jxcore-log: 
11-17 05:53:35.029  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
11-17 05:53:35.029  5614  5660 I jxcore-log: 
11-17 05:53:35.029  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-17 05:53:35.029  5614  5660 I jxcore-log: 
11-17 05:53:35.029  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-17 05:53:35.029  5614  5660 I jxcore-log: 
11-17 05:53:35.029  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.029  5614  5660 I jxcore-log: 
11-17 05:53:35.029  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 05:53:35.029  5614  5660 I jxcore-log: 
11-17 05:53:35.030  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 05:53:35.030  5614  5660 I jxcore-log: 
11-17 05:53:35.034  5614  5614 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-17 05:53:35.035  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-17 05:53:35.035  5614  5660 I jxcore-log: 
11-17 05:53:35.035  5614  5660 I jxcore-log: 2016-11-17 10:53:35 - WARN testUtils: 'myNameCallback not set!'
11-17 05:53:35.035  5614  5660 I jxcore-log: 
,11-17 05:53:37.145  5614  5660 I jxcore-log: 2016-11-17 10:53:37 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-17 05:53:37.145  5614  5660 I jxcore-log: 
,11-17 05:53:37.147  5614  5660 I jxcore-log: 2016-11-17 10:53:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-17 05:53:37.147  5614  5660 I jxcore-log: 
,11-17 05:53:37.497  5614  5660 I jxcore-log: 2016-11-17 10:53:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-17 05:53:37.497  5614  5660 I jxcore-log: 
,11-17 05:53:37.511  5614  5660 I jxcore-log: 2016-11-17 10:53:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-17 05:53:37.511  5614  5660 I jxcore-log: 
,11-17 05:53:38.331   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:38.635  5614  5660 I jxcore-log: 2016-11-17 10:53:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-17 05:53:38.635  5614  5660 I jxcore-log: 
,11-17 05:53:38.805  5614  5660 I jxcore-log: 2016-11-17 10:53:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-17 05:53:38.805  5614  5660 I jxcore-log: 
,11-17 05:53:38.811  5614  5660 I jxcore-log: 2016-11-17 10:53:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-17 05:53:38.811  5614  5660 I jxcore-log: 
,11-17 05:53:38.823  5614  5660 I jxcore-log: 2016-11-17 10:53:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-17 05:53:38.823  5614  5660 I jxcore-log: 
,11-17 05:53:39.316  5614  5660 I jxcore-log: 2016-11-17 10:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-17 05:53:39.316  5614  5660 I jxcore-log: 
,11-17 05:53:39.332   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:39.360  5614  5660 I jxcore-log: 2016-11-17 10:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-17 05:53:39.360  5614  5660 I jxcore-log: 
,11-17 05:53:39.373  5614  5660 I jxcore-log: 2016-11-17 10:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-17 05:53:39.373  5614  5660 I jxcore-log: 
,11-17 05:53:39.378  5614  5660 I jxcore-log: 2016-11-17 10:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-17 05:53:39.378  5614  5660 I jxcore-log: 
,11-17 05:53:39.659  5614  5660 I jxcore-log: 2016-11-17 10:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-17 05:53:39.659  5614  5660 I jxcore-log: 
,11-17 05:53:39.786  5614  5660 I jxcore-log: 2016-11-17 10:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-17 05:53:39.786  5614  5660 I jxcore-log: 
,11-17 05:53:40.177  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-17 05:53:40.177  5614  5660 I jxcore-log: 
,11-17 05:53:40.184  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-17 05:53:40.184  5614  5660 I jxcore-log: 
,11-17 05:53:40.188  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-17 05:53:40.188  5614  5660 I jxcore-log: 
,11-17 05:53:40.192  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-17 05:53:40.192  5614  5660 I jxcore-log: 
,11-17 05:53:40.197  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-17 05:53:40.197  5614  5660 I jxcore-log: 
,11-17 05:53:40.235  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-17 05:53:40.235  5614  5660 I jxcore-log: 
,11-17 05:53:40.242  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-17 05:53:40.242  5614  5660 I jxcore-log: 
,11-17 05:53:40.271  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-17 05:53:40.271  5614  5660 I jxcore-log: 
,11-17 05:53:40.309  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-17 05:53:40.309  5614  5660 I jxcore-log: 
,11-17 05:53:40.316  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-17 05:53:40.316  5614  5660 I jxcore-log: 
,11-17 05:53:40.323  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-17 05:53:40.323  5614  5660 I jxcore-log: 
,11-17 05:53:40.333   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:40.339  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-17 05:53:40.339  5614  5660 I jxcore-log: 
,11-17 05:53:40.354  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-17 05:53:40.354  5614  5660 I jxcore-log: 
,11-17 05:53:40.360  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-17 05:53:40.360  5614  5660 I jxcore-log: 
,11-17 05:53:40.365  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-17 05:53:40.365  5614  5660 I jxcore-log: 
,11-17 05:53:40.379  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-17 05:53:40.379  5614  5660 I jxcore-log: 
,11-17 05:53:40.396  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-17 05:53:40.396  5614  5660 I jxcore-log: 
,11-17 05:53:40.411  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-17 05:53:40.411  5614  5660 I jxcore-log: 
,11-17 05:53:40.421  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-17 05:53:40.421  5614  5660 I jxcore-log: 
,11-17 05:53:40.434  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-17 05:53:40.434  5614  5660 I jxcore-log: 
,11-17 05:53:40.444  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-17 05:53:40.444  5614  5660 I jxcore-log: 
,11-17 05:53:40.458  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-17 05:53:40.458  5614  5660 I jxcore-log: 
,11-17 05:53:40.468  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-17 05:53:40.468  5614  5660 I jxcore-log: 
,11-17 05:53:40.475  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-17 05:53:40.475  5614  5660 I jxcore-log: 
,11-17 05:53:40.496  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-17 05:53:40.496  5614  5660 I jxcore-log: 
,11-17 05:53:40.502  5614  5660 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-17 05:53:40.503  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - INFO testUtils: 'BLE multiple advertisement supported'
11-17 05:53:40.503  5614  5660 I jxcore-log: 
,11-17 05:53:40.583  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:40.583  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:40.583  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:40.583  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:40.583  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:40.583  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:40.583  5614  5660 I jxcore-log: 
,11-17 05:53:40.914  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:40.914  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:40.914  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:40.914  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:40.914  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:40.914  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:40.914  5614  5660 I jxcore-log: 
,11-17 05:53:40.917  5614  5660 I jxcore-log: 2016-11-17 10:53:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:40.917  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:40.917  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:40.917  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:40.917  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:40.917  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:40.917  5614  5660 I jxcore-log: 
,11-17 05:53:41.002   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:53:41.315  5614  5660 I jxcore-log: 2016-11-17 10:53:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:41.315  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:41.315  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:41.315  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:41.315  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:41.315  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:41.315  5614  5660 I jxcore-log: 
,11-17 05:53:41.319  5614  5660 I jxcore-log: 2016-11-17 10:53:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:41.319  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:41.319  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:41.319  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:41.319  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:41.319  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:41.319  5614  5660 I jxcore-log: 
,11-17 05:53:41.333   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:42.334   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 05:53:42.350  5614  5660 I jxcore-log: 2016-11-17 10:53:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:42.350  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:42.350  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:42.350  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:42.350  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:42.350  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:42.350  5614  5660 I jxcore-log: 
,11-17 05:53:42.353  5614  5660 I jxcore-log: 2016-11-17 10:53:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:42.353  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:42.353  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:42.353  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:42.353  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:42.353  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:42.353  5614  5660 I jxcore-log: 
,11-17 05:53:43.335   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-17 05:53:43.388  5614  5660 I jxcore-log: 2016-11-17 10:53:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:43.388  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:43.388  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:43.388  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:43.388  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:43.388  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:43.388  5614  5660 I jxcore-log: 
,11-17 05:53:43.392  5614  5660 I jxcore-log: 2016-11-17 10:53:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:43.392  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:43.392  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:43.392  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:43.392  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:43.392  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:43.392  5614  5660 I jxcore-log: 
,11-17 05:53:43.861   928  5829 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170363, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-17 05:53:44.026   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:53:44.432  5614  5660 I jxcore-log: 2016-11-17 10:53:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:44.432  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:44.432  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:44.432  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:44.432  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:44.432  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:44.432  5614  5660 I jxcore-log: 
,11-17 05:53:44.436  5614  5660 I jxcore-log: 2016-11-17 10:53:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:44.436  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:44.436  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:44.436  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:44.436  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:44.436  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:44.436  5614  5660 I jxcore-log: 
,11-17 05:53:45.467  5614  5660 I jxcore-log: 2016-11-17 10:53:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:45.467  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:45.467  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:45.467  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:45.467  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:45.467  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:45.467  5614  5660 I jxcore-log: 
,11-17 05:53:45.471  5614  5660 I jxcore-log: 2016-11-17 10:53:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:45.471  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:45.471  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:45.471  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:45.471  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:45.471  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:45.471  5614  5660 I jxcore-log: 
,11-17 05:53:46.504  5614  5660 I jxcore-log: 2016-11-17 10:53:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:46.504  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:46.504  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:46.504  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:46.504  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:46.504  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:46.504  5614  5660 I jxcore-log: 
,11-17 05:53:46.508  5614  5660 I jxcore-log: 2016-11-17 10:53:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:46.508  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:46.508  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:46.508  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:46.508  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:46.508  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:46.508  5614  5660 I jxcore-log: 
,11-17 05:53:47.556  5614  5660 I jxcore-log: 2016-11-17 10:53:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:47.556  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:47.556  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:47.556  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:47.556  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:47.556  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:47.556  5614  5660 I jxcore-log: 
,11-17 05:53:47.561  5614  5660 I jxcore-log: 2016-11-17 10:53:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:47.561  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:47.561  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:47.561  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:47.561  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:47.561  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:47.561  5614  5660 I jxcore-log: 
,11-17 05:53:48.594  5614  5660 I jxcore-log: 2016-11-17 10:53:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:48.594  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:48.594  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:48.594  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:48.594  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:48.594  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:48.594  5614  5660 I jxcore-log: 
,11-17 05:53:48.598  5614  5660 I jxcore-log: 2016-11-17 10:53:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:48.598  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:48.598  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:48.598  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:48.598  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:48.598  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:48.598  5614  5660 I jxcore-log: 
,11-17 05:53:49.415   928  5829 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-17 05:53:49.659  5614  5660 I jxcore-log: 2016-11-17 10:53:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:49.659  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:49.659  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:49.659  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:49.659  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:49.659  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:49.659  5614  5660 I jxcore-log: 
,11-17 05:53:49.663  5614  5660 I jxcore-log: 2016-11-17 10:53:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:49.663  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:49.663  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:49.663  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:49.663  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:49.663  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:49.663  5614  5660 I jxcore-log: 
,11-17 05:53:50.082   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:53:50.690  5614  5660 I jxcore-log: 2016-11-17 10:53:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:50.690  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:50.690  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:50.690  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:50.690  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:50.690  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:50.690  5614  5660 I jxcore-log: 
,11-17 05:53:50.695  5614  5660 I jxcore-log: 2016-11-17 10:53:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:50.695  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:50.695  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:50.695  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:50.695  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:50.695  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:50.695  5614  5660 I jxcore-log: 
,11-17 05:53:50.983   928  2889 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-17 05:53:51.725  5614  5660 I jxcore-log: 2016-11-17 10:53:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:51.725  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:51.725  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:51.725  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:51.725  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:51.725  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:51.725  5614  5660 I jxcore-log: 
,11-17 05:53:51.729  5614  5660 I jxcore-log: 2016-11-17 10:53:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:51.729  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:51.729  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:51.729  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:51.729  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:51.729  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:51.729  5614  5660 I jxcore-log: 
,11-17 05:53:52.722  3655  5863 I EventLogService: Aggregate from 1479378232608 (log), 1479378232608 (data)
,11-17 05:53:52.743  5614  5660 I jxcore-log: 2016-11-17 10:53:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:52.743  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:52.743  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:52.743  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:52.743  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:52.743  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:52.743  5614  5660 I jxcore-log: 
,11-17 05:53:52.746  5614  5660 I jxcore-log: 2016-11-17 10:53:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:52.746  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:52.746  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:52.746  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:52.746  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:52.746  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:52.746  5614  5660 I jxcore-log: 
,11-17 05:53:52.804  3539  5866 I VacuumService: Vacuum at: now=1479380032804 tag=VacuumService
,11-17 05:53:52.835  3539  5869 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-17 05:53:52.866  3539  5867 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-17 05:53:52.869  3539  5867 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-17 05:53:52.911  3539  5867 W Uploader:  no longer exists, so no auth token.
,11-17 05:53:52.925  3539  5869 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 05:53:53.248  3539  5872 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 05:53:53.347  3539  5869 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 05:53:53.598  3539  5872 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 05:53:53.686  3539  5867 W Uploader:  no longer exists, so no auth token.
,11-17 05:53:53.697  3539  5869 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 05:53:53.769  5614  5660 I jxcore-log: 2016-11-17 10:53:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:53.769  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:53.769  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:53.769  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:53.769  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:53.769  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:53.769  5614  5660 I jxcore-log: 
,11-17 05:53:53.773  5614  5660 I jxcore-log: 2016-11-17 10:53:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:53.773  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:53.773  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:53.773  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:53.773  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:53.773  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:53.773  5614  5660 I jxcore-log: 
,11-17 05:53:53.788  3539  5872 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 05:53:54.819  5614  5660 I jxcore-log: 2016-11-17 10:53:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 05:53:54.819  5614  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 05:53:54.819  5614  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 05:53:54.819  5614  5660 I jxcore-log: emit@events.js:82:1
11-17 05:53:54.819  5614  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 05:53:54.819  5614  5660 I jxcore-log: emit@events.js:82:1'
11-17 05:53:54.819  5614  5660 I jxcore-log: 
,11-17 05:53:54.830  5614  5660 E jxcore  : Error!: error is undefined
11-17 05:53:54.830  5614  5660 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-17 05:53:54.836  5614  5660 I jxcore-log: 2016-11-17 10:53:54 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-17 05:53:54.836  5614  5660 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-17 05:53:54.836  5614  5660 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-17 05:53:54.836  5614  5660 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-17 05:53:54.836  5614  5660 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-17 05:53:54.836  5614  5660 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-17 05:53:54.836  5614  5660 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-17 05:53:54.836  5614  5660 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-17 05:53:54.838  5614  5660 I jxcore-log: 2016-11-17 10:53:54 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-17 05:53:54.838  5614  5660 I jxcore-log: 
,11-17 05:53:54.840  5614  5660 E jxcore-log: TypeError: 
11-17 05:53:54.840  5614  5660 E jxcore-log: error is undefined
11-17 05:53:54.840  5614  5660 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-17 05:53:54.840  5614  5660 E jxcore-log: 
,11-17 05:53:55.322  5877  5877 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-17 05:53:55.328  5877  5877 D AndroidRuntime: CheckJNI is OFF
,11-17 05:53:55.361  5877  5877 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-17 05:53:55.398  5877  5877 I Radio-JNI: register_android_hardware_Radio DONE
,11-17 05:53:55.415  5877  5877 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 05:53:55.425   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-17 05:53:55.425   928   941 I ActivityManager: Killing 5614:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-17 05:53:55.536   928  3376 I WindowState: WIN DEATH: Window{c372af9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-17 05:53:55.536   928  2897 D WifiService: Client connection lost with reason: 4
11-17 05:53:55.537   928  3797 D GraphicsStats: Buffer count: 2
,11-17 05:53:55.580   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-17 05:53:55.581   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-17 05:53:55.581   928   951 I art     : Starting a blocking GC Explicit
,11-17 05:53:55.581   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-17 05:53:55.581   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-17 05:53:55.581   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:55.581   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:55.581   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:53:55.581   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-17 05:53:55.582   928   941 I ActivityManager:   Force finishing activity ActivityRecord{8407192 u0 com.test.thalitest/.MainActivity t6}
,11-17 05:53:55.591   928  3375 W ActivityManager: Spurious death for ProcessRecord{84c0acf 0:com.test.thalitest/u0a77}, curProc for 5614: null
,11-17 05:53:55.595   928   946 W WindowManager: Attempted to add application window with unknown token Token{ef70763 ActivityRecord{8407192 u0 com.test.thalitest/.MainActivity t6 f}}.  Aborting.
,11-17 05:53:55.595   928   946 W WindowManager: Token{ef70763 ActivityRecord{8407192 u0 com.test.thalitest/.MainActivity t6 f}} already running, starting window not displayed. Unable to add window -- token Token{ef70763 ActivityRecord{8407192 u0 com.test.thalitest/.MainActivity t6 f}} is not valid; is your activity running?
11-17 05:53:55.595   928   946 W WindowManager: view not successfully added to wm, removing view
11-17 05:53:55.595   928   946 W WindowManager: Exception when adding starting window
11-17 05:53:55.595   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{185b606 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-17 05:53:55.595   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-17 05:53:55.595   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-17 05:53:55.595   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-17 05:53:55.595   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-17 05:53:55.595   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-17 05:53:55.595   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:55.595   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:55.595   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:53:55.595   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-17 05:53:55.667   928   951 I art     : Explicit concurrent mark sweep GC freed 73082(4MB) AllocSpace objects, 21(696KB) LOS objects, 33% free, 28MB/43MB, paused 1.552ms total 85.250ms
,11-17 05:53:55.686   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-17 05:53:55.690  5877  5877 I art     : System.exit called, status: 0
,11-17 05:53:55.690  5877  5877 I AndroidRuntime: VM exiting with result code 0.
,11-17 05:53:55.693   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-17 05:53:55.702   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-17 05:53:55.708  5718  5718 D BluetoothMapAppObserver: onReceive
11-17 05:53:55.708  5718  5718 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-17 05:53:55.710  4012  4125 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-17 05:53:55.710   928  2848 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-17 05:53:55.713  3624  3624 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-17 05:53:55.747  3624  5888 I Keyboard.Facilitator.DecoderInitializer: run()
,11-17 05:53:55.749  3360  5890 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-17 05:53:55.762  3742  3742 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-17 05:53:55.767   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 05:53:55.769  3624  5888 I Decoder : createOrResetDecoder
,11-17 05:53:55.774  3539  3539 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-17 05:53:55.774  3539  3539 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 05:53:55.788  3655  5894 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-17 05:53:55.789  3655  5894 D AccountUtils: Clearing selected account for com.test.thalitest
,11-17 05:53:55.819  3539  3539 I ConfigService: onCreate
,11-17 05:53:55.838    21    21 W kworker/3:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:53:55.847  3655  5894 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-17 05:53:55.844    21    21 W kworker/3:0: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:53:55.855  3624  5888 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-17 05:53:55.851    21    21 W kworker/3:0: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 05:53:55.867  3360  3384 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj956817978) - 
,11-17 05:53:55.883  3655  5894 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:55.883  3655  5894 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:55.883  3655  5894 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 05:53:55.884  3655  5894 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-17 05:53:55.920  3360  5890 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
11-17 05:53:55.921  3360  5890 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-17 05:53:55.921  3360  5890 E AndroidRuntime: Process: android.process.acore, PID: 3360
11-17 05:53:55.921  3360  5890 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-17 05:53:55.921  3360  5890 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 05:53:55.926   928  5902 E DropBoxManagerService: Can't write: system_app_crash
11-17 05:53:55.926   928  5902 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-17 05:53:55.926   928  5902 E DropBoxManagerService: 	... 5 more
,11-17 05:53:55.930  3655  3655 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 05:53:55.930  3655  3655 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 05:53:55.938  3655  3655 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 05:53:55.942  3655  3655 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 05:53:55.926  3360  5890 I Process : Sending signal. PID: 3360 SIG: 9
,11-17 05:53:55.966   381   381 E lowmemorykiller: Error writing /proc/3360/oom_score_adj; errno=22
11-17 05:53:55.966   381   381 E lowmemorykiller: Error writing /proc/3360/oom_score_adj; errno=22
,11-17 05:53:55.967  4911  5904 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-17 05:53:55.998  4911  5904 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 05:53:56.001   928  3782 I ActivityManager: Start proc 5908:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-17 05:53:56.015   928  3807 I ActivityManager: Start proc 5913:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-17 05:53:56.035  3655  5903 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 05:53:56.044  3655  5903 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 05:53:56.053  3655  3655 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-17 05:53:56.059   928  3376 I ActivityManager: Process android.process.acore (pid 3360) has died
,11-17 05:53:56.059   928  3376 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-17 05:53:56.068  3655  5919 I GMPM-SVC: App measurement is starting up
,11-17 05:53:56.072  3655  5919 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-17 05:53:56.073  3655  5919 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-17 05:53:56.109   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 05:53:56.254   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
