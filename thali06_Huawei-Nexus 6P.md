#### Test 950065924e01fb7_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 11:16:47.176  5585  5625 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
11-23 11:16:47.338   932  3668 I ActivityManager: Killing 5296:org.codeaurora.ims/1001 (adj 15): empty #17
11-23 11:16:47.545  5585  5633 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-23 11:16:47.567  3897  4933 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-23 11:16:47.574  3897  3897 I ConfigFetchService: fetch service done; releasing wakelock
11-23 11:16:47.575  3897  3897 I ConfigFetchService: stopping self
11-23 11:16:47.635  5634  5634 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 11:16:47.639  5634  5634 D AndroidRuntime: CheckJNI is OFF
11-23 11:16:47.650  3897  4933 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-23 11:16:47.661  5634  5634 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 11:16:47.680  5585  5633 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-23 11:16:47.687  5634  5634 I Radio-JNI: register_android_hardware_Radio DONE
11-23 11:16:47.702  5634  5634 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-23 11:16:47.705   932  3394 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 11:16:47.709  5585  5633 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-23 11:16:47.728   932  3394 I ActivityManager: Start proc 5650:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 11:16:47.750  5634  5634 D AndroidRuntime: Shutting down VM
,11-23 11:16:48.060   932   942 I WindowManager: Screenshot max retries 4 of Token{efa19b9 ActivityRecord{f719f80 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{633de98 u0 Starting com.test.thalitest} drawState=2
,11-23 11:16:48.145  5650  5650 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-23 11:16:48.175  5650  5650 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-23 11:16:48.236  5650  5650 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 9907-9963)
,11-23 11:16:48.236  5650  5650 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 11:16:48.273  5650  5650 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {383208a}
11-23 11:16:48.274  5650  5650 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 11:16:48.274  5650  5650 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 11:16:48.278  5650  5650 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 11:16:48.279  5650  5650 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 11:16:48.326  5650  5650 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 11:16:48.335  5650  5650 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 11:16:48.335  5650  5650 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 11:16:48.335  5650  5650 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 11:16:48.335  5650  5650 I Adreno  : Build Date                       : 12/06/15
11-23 11:16:48.335  5650  5650 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 11:16:48.335  5650  5650 I Adreno  : Local Branch                     : mybranch17112971
11-23 11:16:48.335  5650  5650 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 11:16:48.335  5650  5650 I Adreno  : Remote Branch                    : NONE
11-23 11:16:48.335  5650  5650 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 11:16:48.382   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@277e329:true
,11-23 11:16:48.416   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[17915]" dev="sockfs" ino=17915 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 11:16:48.416   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[17915]" dev="sockfs" ino=17915 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 11:16:48.430  5650  5650 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 11:16:48.438  5650  5650 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 11:16:48.466   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34176]" dev="sockfs" ino=34176 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 11:16:48.472  5650  5687 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-23 11:16:48.466   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34176]" dev="sockfs" ino=34176 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 11:16:48.472  3146  3146 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14936]" dev="sockfs" ino=14936 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 11:16:48.472  3146  3146 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14936]" dev="sockfs" ino=14936 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 11:16:48.480  5650  5674 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 11:16:48.506  5650  5687 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 11:16:48.584   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +518ms (total +865ms)
,11-23 11:16:48.613  5650  5650 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5650
,11-23 11:16:48.710  5650  5650 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-23 11:16:48.968  5650  5690 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -578025168
,11-23 11:16:48.973  5650  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 11:16:48.973  5650  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 11:16:48.973  5650  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 11:16:48.973  5650  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 11:16:48.973  5650  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-23 11:16:48.973  5650  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68e4233 added. We now have 1 listener(s)
,11-23 11:16:48.975  5650  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-23 11:16:48.976  5650  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 11:16:48.976  5650  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:16:48.976  5650  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-23 11:16:48.979  5650  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51d69ee added. We now have 1 listener(s)
11-23 11:16:48.979  5650  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 11:16:48.984  5650  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 11:16:48.984  5650  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 11:16:48.984   932  2961 D WifiService: New client listening to asynchronous messages
11-23 11:16:48.984  5650  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 11:16:48.984  5650  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 11:16:48.984  5650  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 11:16:48.985  5650  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 11:16:48.985  5650  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-23 11:16:48.987  5650  5690 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 11:16:49.100   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:16:49.134  5650  5650 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-23 11:16:49.408  5650  5659 I art     : Background sticky concurrent mark sweep GC freed 75213(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.217ms total 207.053ms
,11-23 11:16:50.632  5650  5659 I art     : Background partial concurrent mark sweep GC freed 57579(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.310ms total 133.201ms
,11-23 11:16:50.782  5650  5696 W jxcore-log: Initializing JXcore engine
11-23 11:16:50.782  5650  5696 W jxcore-log: JXcore engine is ready
,11-23 11:16:50.802  5696  5696 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11980 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 11:16:50.802  5696  5696 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[17486]" dev="sockfs" ino=17486 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-23 11:16:50.802  5696  5696 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 11:16:50.802  5696  5696 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34142]" dev="sockfs" ino=34142 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 11:16:50.815  5650  5696 W jxcore-log: Starting JXcore engine
,11-23 11:16:50.865  5650  5696 W jxcore-log: Platform android
11-23 11:16:50.865  5650  5696 W jxcore-log: 
,11-23 11:16:50.865  5650  5696 W jxcore-log: Process ARCH arm
11-23 11:16:50.865  5650  5696 W jxcore-log: 
,11-23 11:16:51.047  5650  5696 I jxcore-log: JXcore Cordova bridge is ready!
11-23 11:16:51.047  5650  5696 I jxcore-log: 
,11-23 11:16:51.047  5650  5696 W jxcore-log: JXcore engine is started
,11-23 11:16:51.059  5650  5690 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 11:16:51.065  5650  5650 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 11:16:52.356   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:16:52.583  3568  3568 I ConfigService: onDestroy
,11-23 11:16:53.356   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:16:54.357   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:16:55.358   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:16:56.359   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:16:57.360   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 11:16:59.513   932   932 I ActivityManager: Killing 5309:com.android.settings/1000 (adj 15): empty #17
,11-23 11:17:00.786  5650  5696 I jxcore-log: 2016-11-23 16:17:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 11:17:00.786  5650  5696 I jxcore-log: 
,11-23 11:17:00.788  5650  5696 I jxcore-log: 2016-11-23 16:17:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 11:17:00.788  5650  5696 I jxcore-log: 
,11-23 11:17:00.794  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 11:17:00.794  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 11:17:00.796  5650  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 11:17:00.798  5650  5696 I jxcore-log: 2016-11-23 16:17:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 11:17:00.798  5650  5696 I jxcore-log: 
,11-23 11:17:00.800  5650  5696 I jxcore-log: 2016-11-23 16:17:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 11:17:00.800  5650  5696 I jxcore-log: 
,11-23 11:17:01.038  5650  5696 I jxcore-log: 2016-11-23 16:17:01 - DEBUG UnitTest_app: 'Running unit tests'
11-23 11:17:01.038  5650  5696 I jxcore-log: 
,11-23 11:17:01.038  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:17:01.038  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eba27b8 added. We now have 2 listener(s)
11-23 11:17:01.039  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:17:01.039  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:17:01.039  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:17:01.039  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:17:01.039  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad2991 added. We now have 2 listener(s)
11-23 11:17:01.039  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 11:17:01.040  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 11:17:01.041  5650  5696 D executeNativeTests: Running unit tests
,11-23 11:17:01.044  4823  4857 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-23 11:17:01.046  4823  4823 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-23 11:17:01.077  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:17:01.077  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 added. We now have 3 listener(s)
,11-23 11:17:01.078  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:17:01.078  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:17:01.078  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:17:01.078  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:17:01.078  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 added. We now have 3 listener(s)
,11-23 11:17:01.078  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:17:01.078  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 11:17:01.080  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 11:17:01.080  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 11:17:01.080  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 11:17:01.080  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 11:17:01.081  5650  5696 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 11:17:01.081  5650  5696 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-23 11:17:01.082  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-23 11:17:01.082  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 11:17:01.082  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 11:17:01.082  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 11:17:01.082  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:01.082  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 11:17:01.082  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:01.083  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:01.083  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:01.083  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:17:01.083  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 removed from the list
11-23 11:17:01.083  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:01.083  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 removed from the list
11-23 11:17:01.083  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:01.083  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:01.083  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.084  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.084  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.084  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.084  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:01.084  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:01.084  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:01.084  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:01.085  5650  5696 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 11:17:01.085  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 11:17:01.085  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:01.085  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:01.085  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:01.085  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:01.085  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:01.085  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:01.085  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:01.085  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:01.085  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.085  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.086  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:01.086  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.086  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.086  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:01.086  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:01.086  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:01.086  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:01.088  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 11:17:01.088  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 11:17:01.088  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 11:17:01.088  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 11:17:01.089  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 11:17:01.089  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:01.089  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:01.089  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:01.089  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:01.089  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:01.090  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:01.090  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:01.090  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:01.090  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:01.090  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.090  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.090  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.090  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.090  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.090  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:01.090  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:01.090  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:01.090  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:01.091  5650  5696 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 11:17:01.092  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 11:17:01.092  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 11:17:01.095  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 11:17:01.096  5650  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 11:17:01.096  5650  5696 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 11:17:01.096  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:17:01.096  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 11:17:01.096  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 11:17:01.096  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 11:17:01.096  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 11:17:01.098  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:01.101  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:01.101  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 11:17:01.102  5650  5696 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 11:17:01.102  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 11:17:01.105  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:01.105  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 11:17:01.106  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 11:17:01.106  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 11:17:01.106  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 11:17:01.107  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-23 11:17:01.108  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 11:17:01.108  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.108  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 11:17:01.108  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-23 11:17:01.108  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 11:17:01.108  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 11:17:01.108  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.109  5650  5696 D BluetoothAdapter: STATE_ON
,11-23 11:17:01.111  4604  4835 D BtGatt.GattService: registerClient() - UUID=d190c4c4-6b01-4744-8308-5030acfd1b89
,11-23 11:17:01.112  4604  4666 D BtGatt.GattService: onClientRegistered() - UUID=d190c4c4-6b01-4744-8308-5030acfd1b89, clientIf=5
,11-23 11:17:01.112  5650  5661 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 11:17:01.114  4604  4815 D BtGatt.GattService: start scan with filters
,11-23 11:17:01.117  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 11:17:01.117  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.118  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 11:17:01.118  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.118  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 11:17:01.118  4604  4671 D BtGatt.ScanManager: handling starting scan
11-23 11:17:01.118  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 11:17:01.118  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:17:01.118  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-23 11:17:01.118  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 11:17:01.118  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:17:01.118  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 11:17:01.118  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 11:17:01.119  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.119  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:17:01.119  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 11:17:01.119  4604  4671 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:17:01.120  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.120  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:17:01.120  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:01.120  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:01.120  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:17:01.120  5650  5696 I io.jxcore.node.ConnectionHelper: start: OK
,11-23 11:17:01.122  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 11:17:01.122  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:01.122  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:01.122  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 11:17:01.128  4604  4666 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 11:17:01.128  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:01.128  4604  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 11:17:01.134  4604  4666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 11:17:01.134  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:01.135  4604  4671 D BtGatt.ScanManager: Starting BLE batch scan
11-23 11:17:01.135  4604  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 11:17:01.144  4604  4666 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 11:17:01.144  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:01.149  4604  4666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 11:17:01.149  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:01.623  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 11:17:01.624  5650  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 11:17:01.624  5650  5650 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 11:17:03.292   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 11:17:06.124  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 11:17:06.125  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:06.125  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 11:17:06.125  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:17:06.125  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 11:17:06.125  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:06.125  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 11:17:06.125  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 11:17:06.126  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.126  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 11:17:06.126  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 11:17:06.127  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.127  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.127  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.127  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 11:17:06.127  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.128  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:17:06.129  4604  4835 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-23 11:17:06.129  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 11:17:06.130  4604  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 11:17:06.131  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:17:06.132  4604  4617 D BtGatt.GattService: stopScan() - queue size =1
11-23 11:17:06.132  4604  4835 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 11:17:06.133  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 11:17:06.133  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.133  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-23 11:17:06.133  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.133  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.134  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:06.134  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.134  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 11:17:06.134  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.135  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.135  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.135  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 11:17:06.135  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 11:17:06.136  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:17:06.136  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.138  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.138  4604  4604 D BtGatt.ScanManager: awakened up at time 97865
11-23 11:17:06.138  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:06.138  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.138  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:06.138  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:06.138  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:17:06.138  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:17:06.138  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:17:06.139  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 11:17:06.139  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:06.139  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:06.139  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:17:06.139  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:06.139  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:06.139  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 11:17:06.139  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-23 11:17:06.140  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:17:06.140  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 11:17:06.140  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 11:17:06.140  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:17:06.140  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-23 11:17:06.141  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:17:06.141  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:06.141  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 11:17:06.141  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:17:06.144  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:17:06.145  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:06.145  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 11:17:06.163  4604  4666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-23 11:17:06.164  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:06.164  4604  4666 D BtGatt.GattService: current time is 97891929948
11-23 11:17:06.164  4604  4666 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -81, 75, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -91, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 86, -31, -99, 30, -52, -57, 1, 0, -97, 78, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -105, -8, 94, 3, 2, -29, 20, 62, -63, -59, -37, 28, 6, 8, 116, 105, 115, 54, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, 57, 25, -57, 101, -38, 1, 0, -94, 76, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, 48, -41, 94, 3, 3, -12, 24, 62, 87, -39, 121, 28, 6, 8, 116, 105, 115, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 11:17:06.166  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 11:17:06.167  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-23 11:17:06.167  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
11-23 11:17:06.167  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -105, -8, 94, 3, 2, -29, 20, 62, -63, -59, -37, 6, 8, 116, 105, 115, 54, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 11:17:06.168  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, 48, -41, 94, 3, 3, -12, 24, 62, 87, -39, 121, 6, 8, 116, 105, 115, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,11-23 11:17:06.175  4604  4666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 11:17:06.175  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:06.175  4604  4671 D BtGatt.ScanManager: stopping BLe Batch
,11-23 11:17:06.182  4604  4666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 11:17:06.182  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:06.182  4604  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:17:06.189  4604  4666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 11:17:06.189  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:06.314   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 11:17:06.642  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 11:17:11.143  5650  5696 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 11:17:11.148  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 11:17:11.148  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 11:17:11.162  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 11:17:11.167  5650  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 11:17:11.167  5650  5696 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 11:17:11.167  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:17:11.168  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 11:17:11.168  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-23 11:17:11.168  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 11:17:11.168  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 11:17:11.175  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 11:17:11.175  5650  5696 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-23 11:17:11.175  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 11:17:11.176  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:11.184  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:11.185  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.185  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 11:17:11.186  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 11:17:11.186  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 11:17:11.186  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 11:17:11.190  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.190  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 11:17:11.190  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 11:17:11.190  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 11:17:11.190  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-23 11:17:11.190  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.191  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:17:11.194  4604  4815 D BtGatt.GattService: registerClient() - UUID=2ea6eea9-93ac-4a62-820f-6090ff0522e9
11-23 11:17:11.194  4604  4666 D BtGatt.GattService: onClientRegistered() - UUID=2ea6eea9-93ac-4a62-820f-6090ff0522e9, clientIf=5
11-23 11:17:11.195  5650  5660 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 11:17:11.195  4604  4835 D BtGatt.GattService: start scan with filters
,11-23 11:17:11.200  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 11:17:11.200  4604  4671 D BtGatt.ScanManager: handling starting scan
11-23 11:17:11.200  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.200  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 11:17:11.200  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:11.200  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 11:17:11.200  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 11:17:11.200  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.200  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-23 11:17:11.201  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 11:17:11.201  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.201  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.201  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.201  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.202  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-23 11:17:11.202  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:11.205  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.205  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:17:11.206  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.206  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.206  5650  5696 I io.jxcore.node.ConnectionHelper: start: OK
11-23 11:17:11.206  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 11:17:11.209  4604  4666 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 11:17:11.209  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:11.209  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:11.209  5650  5696 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 11:17:11.209  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:11.209  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 11:17:11.209  4604  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 11:17:11.209  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:17:11.209  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-23 11:17:11.209  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:11.210  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 11:17:11.213  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.213  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.213  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.213  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 11:17:11.213  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 11:17:11.213  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.213  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 11:17:11.213  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 11:17:11.214  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:11.214  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.214  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.214  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-23 11:17:11.214  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.215  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:17:11.215  4604  4815 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 11:17:11.215  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 11:17:11.216  5650  5696 D BluetoothAdapter: STATE_ON
,11-23 11:17:11.217  4604  4619 D BtGatt.GattService: stopScan() - queue size =1
11-23 11:17:11.217  4604  4666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-23 11:17:11.217  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.218  4604  4671 D BtGatt.ScanManager: Starting BLE batch scan
11-23 11:17:11.218  4604  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 11:17:11.218  4604  4815 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-23 11:17:11.219  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.220  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.220  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.220  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 11:17:11.220  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 11:17:11.220  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:17:11.220  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.221  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.222  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:11.222  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:11.222  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.223  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:11.223  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:17:11.223  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 11:17:11.223  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:17:11.223  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:11.223  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:17:11.223  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:11.223  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:11.223  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 11:17:11.223  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:11.223  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.223  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:11.223  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 11:17:11.223  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 11:17:11.223  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 11:17:11.223  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.223  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.223  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.223  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:11.224  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.224  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 11:17:11.226  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.226  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.226  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.226  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.226  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.227  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.227  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.227  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.227  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:11.227  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:11.228  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:11.228  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:11.228  5650  5696 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 11:17:11.229  4604  4666 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 11:17:11.229  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.232  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 11:17:11.232  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 11:17:11.234  4604  4666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 11:17:11.234  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:11.236  4604  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 11:17:11.238  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 11:17:11.240  5650  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 11:17:11.240  5650  5696 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 11:17:11.241  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:17:11.241  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 11:17:11.241  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 11:17:11.241  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 11:17:11.241  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 11:17:11.241  4604  4666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 11:17:11.241  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.242  4604  4666 E BtGatt.ContextMap: Context not found for ID 5
11-23 11:17:11.243  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:11.245  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 11:17:11.245  5650  5696 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 11:17:11.245  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 11:17:11.246  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:11.248  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:11.248  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 11:17:11.249  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 11:17:11.249  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 11:17:11.249  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 11:17:11.249  4604  4666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 11:17:11.249  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.249  4604  4671 D BtGatt.ScanManager: stopping BLe Batch
11-23 11:17:11.251  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.251  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 11:17:11.251  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 11:17:11.252  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 11:17:11.252  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 11:17:11.252  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.252  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:17:11.254  4604  4666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 11:17:11.254  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.254  4604  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 11:17:11.255  4604  4835 D BtGatt.GattService: registerClient() - UUID=e203b14e-f3a8-48f8-a5df-9e5bf1741031
,11-23 11:17:11.259  4604  4666 D BtGatt.GattService: onClientRegistered() - UUID=e203b14e-f3a8-48f8-a5df-9e5bf1741031, clientIf=5
11-23 11:17:11.259  5650  5660 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 11:17:11.259  4604  4815 D BtGatt.GattService: start scan with filters
11-23 11:17:11.259  4604  4666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 11:17:11.260  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.262  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 11:17:11.262  4604  4671 D BtGatt.ScanManager: handling starting scan
11-23 11:17:11.262  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.262  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 11:17:11.262  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.262  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 11:17:11.262  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 11:17:11.262  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.262  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 11:17:11.262  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 11:17:11.262  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.262  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.262  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.263  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 11:17:11.263  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-23 11:17:11.263  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.266  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.266  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:17:11.266  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.266  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:11.266  5650  5696 I io.jxcore.node.ConnectionHelper: start: OK
11-23 11:17:11.266  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.268  4604  4666 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 11:17:11.268  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.268  4604  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 11:17:11.268  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.268  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.268  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:11.268  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 11:17:11.273  4604  4666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-23 11:17:11.273  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:11.273  4604  4671 D BtGatt.ScanManager: Starting BLE batch scan
11-23 11:17:11.273  4604  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 11:17:11.281  4604  4666 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 11:17:11.281  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:11.286  4604  4666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 11:17:11.286  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:11.770  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 11:17:11.770  5650  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 11:17:11.770  5650  5650 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 11:17:12.348   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 11:17:12.351   932  2962 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-23 11:17:15.376   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 11:17:15.382   932  2962 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-23 11:17:16.266  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:16.267  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 11:17:16.267  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 11:17:16.267  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:17:16.267  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 11:17:16.267  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:16.268  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 11:17:16.268  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 11:17:16.268  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:16.268  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 11:17:16.268  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 11:17:16.269  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.269  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:16.269  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.269  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 11:17:16.270  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.271  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:17:16.272  4604  4617 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 11:17:16.272  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 11:17:16.273  4604  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 11:17:16.274  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:17:16.276  4604  4835 D BtGatt.GattService: stopScan() - queue size =1
11-23 11:17:16.278  4604  4815 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 11:17:16.280  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-23 11:17:16.280  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.280  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 11:17:16.281  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.281  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.281  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.281  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.281  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 11:17:16.281  4604  4604 D BtGatt.ScanManager: awakened up at time 108009
11-23 11:17:16.282  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.282  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.282  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:16.283  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 11:17:16.283  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 11:17:16.284   932  3140 I ActivityManager: Killing 5084:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-23 11:17:16.314  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 11:17:16.315  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:16.316  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.316  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:16.316  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.316  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:16.316  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 11:17:16.316  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:17:16.317  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 11:17:16.317  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.317  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 11:17:16.317  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 11:17:16.317  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.317  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.317  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.317  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:16.317  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.317  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.319  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.319  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:17:16.319  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 11:17:16.323  4604  4666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-23 11:17:16.323  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:16.323  4604  4666 D BtGatt.GattService: current time is 108051299408
11-23 11:17:16.323  4604  4666 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -80, -54, -100, -120, -128, -10, 1, -128, -97, 96, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, -114, -43, 94, 3, 1, -29, 24, 62, -19, 26, -64, 0, 85, -113, -37, 31, -33, 8, 0, 4, -78, 3, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -77, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 11:17:16.324  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 11:17:16.325  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, -114, -43, 94, 3, 1, -29, 24, 62, -19, 26, -64]
11-23 11:17:16.326  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-23 11:17:16.326  4604  4666 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-23 11:17:16.330  4604  4666 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 11:17:16.331  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:16.331  4604  4671 D BtGatt.ScanManager: stopping BLe Batch
,11-23 11:17:16.336  4604  4666 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 11:17:16.336  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:17:16.336  4604  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:17:16.341  4604  4666 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 11:17:16.341  4604  4666 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:17:16.818  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 11:17:16.819  5650  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 11:17:16.819  5650  5650 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 11:17:21.318  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 11:17:21.318  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.318  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.318  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.319  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 11:17:21.319  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:17:21.319  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.319  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
,11-23 11:17:21.319  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.320  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.320  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.320  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 11:17:21.324  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.324  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.328  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.328  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.329  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.329  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 11:17:21.329  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.329  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.330  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
,11-23 11:17:21.331  5650  5696 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-23 11:17:21.333  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:21.333  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.333  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.334  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.334  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 11:17:21.334  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.334  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.334  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.334  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.335  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.335  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.337  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.337  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.338  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.338  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.338  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.338  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.338  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.340  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-23 11:17:21.340  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:21.340  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.340  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.341  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.341  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 11:17:21.341  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.341  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.341  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.341  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.341  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.342  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.344  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.345  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.345  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.345  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 11:17:21.345  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.345  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.345  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
,11-23 11:17:21.346  5650  5696 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-23 11:17:21.347  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 11:17:21.347  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.347  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.347  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.347  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.347  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.348  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:21.348  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.348  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.348  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.348  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.352  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.352  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.352  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.352  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.352  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.352  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.353  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
,11-23 11:17:21.354  5650  5696 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-23 11:17:21.354  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:21.354  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.354  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.354  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.354  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.354  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.355  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.355  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.355  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 11:17:21.355  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.355  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.357  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.357  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.357  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.357  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.357  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.357  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.357  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.358  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-23 11:17:21.358  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 11:17:21.358  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 11:17:21.358  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 11:17:21.359  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 11:17:21.359  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 11:17:21.359  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 11:17:21.359  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 11:17:21.359  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 11:17:21.359  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:21.359  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.359  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 11:17:21.359  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.359  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.359  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.360  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.360  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.360  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.360  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.360  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.363  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.363  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.363  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.363  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.363  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.363  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.363  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.364  5650  5696 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-23 11:17:21.364  5650  5696 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 11:17:21.365  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-23 11:17:21.369  5650  5696 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 11:17:21.369  5650  5696 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 11:17:21.369  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-23 11:17:21.369  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 11:17:21.369  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 11:17:21.369  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 11:17:21.369  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 11:17:21.370  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 11:17:21.371  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 11:17:21.371  5650  5696 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,11-23 11:17:21.372  5650  5696 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 11:17:21.372  5650  5696 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 11:17:21.372  5650  5696 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 11:17:21.372  5650  5696 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 11:17:21.372  5650  5696 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 11:17:21.372  5650  5696 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 11:17:21.372  5650  5696 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-23 11:17:21.372  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-23 11:17:21.378  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-23 11:17:21.379  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,11-23 11:17:21.379  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-23 11:17:21.381  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 11:17:21.381  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 11:17:21.381  5650  5696 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 11:17:21.381  5650  5696 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-23 11:17:21.382  5650  5696 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,11-23 11:17:21.383  5650  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-23 11:17:21.383  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:21.383  5650  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-23 11:17:21.383  5650  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 11:17:21.383  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.383  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.383  5650  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-23 11:17:21.384  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.384  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.384  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 11:17:21.385  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.386  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:21.386  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.386  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.386  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.386  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.386  5650  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-23 11:17:21.386  5650  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-23 11:17:21.386  5650  5700 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 11:17:21.387  5650  5700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:17:21.386  4619  4619 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28392]" dev="sockfs" ino=28392 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 11:17:21.386  4619  4619 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28392]" dev="sockfs" ino=28392 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 11:17:21.389  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.389  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.389  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.389  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.389  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.389  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.389  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.390  5650  5696 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-23 11:17:21.391  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 11:17:21.391  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.391  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.391  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.391  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.391  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.391  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.391  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.392  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 11:17:21.392  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.392  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.393  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.393  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.393  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.393  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.393  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.393  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.393  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.394  5650  5696 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 11:17:21.394  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 11:17:21.395  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.395  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.395  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.395  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.395  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.395  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.395  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
,11-23 11:17:21.395  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.395  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.395  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.396  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.396  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.397  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:21.397  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.397  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.397  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.397  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.397  5650  5696 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 11:17:21.398  5650  5696 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 11:17:21.398  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 11:17:21.398  5650  5696 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-23 11:17:21.398  5650  5696 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 11:17:21.398  5650  5696 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 11:17:21.398  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 11:17:21.398  5650  5696 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 11:17:21.398  5650  5696 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 11:17:21.398  5650  5696 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 11:17:21.398  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 11:17:21.398  5650  5696 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-23 11:17:21.398  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:21.398  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:21.398  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:21.399  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.399  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.399  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.399  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.399  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
,11-23 11:17:21.399  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:21.399  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.399  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.400  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.400  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.400  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:21.400  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:21.400  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:21.400  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:21.401  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.401  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:21.401  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:21.401  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:21.401  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:21.401  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:21.401  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 11:17:22.361   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-23 11:17:22.361   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 11:17:26.402  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:26.403  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.403  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:26.403  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:26.403  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
,11-23 11:17:26.403  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:26.404  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:26.404  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:26.404  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 11:17:26.404  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:26.404  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:26.405  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.405  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
,11-23 11:17:26.405  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:26.405  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.405  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:26.408  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:17:26.409  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.409  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.409  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:26.409  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 11:17:26.409  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.410  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.413  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-23 11:17:26.414  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 11:17:26.415  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 11:17:26.420  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-23 11:17:26.421  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-23 11:17:26.421  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 11:17:26.422  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-23 11:17:26.422  5650  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-23 11:17:26.422  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 11:17:26.422  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 11:17:26.422  5650  5650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-23 11:17:26.423  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:26.423  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 11:17:26.423  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 11:17:26.423  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 11:17:26.423  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 11:17:26.423  5650  5702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:17:26.425  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-23 11:17:26.425  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-23 11:17:26.425  5650  5650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 11:17:26.425  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:26.425  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:26.425  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 11:17:26.426  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.426  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 11:17:26.426  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 11:17:26.422  4815  4815 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34225]" dev="sockfs" ino=34225 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 11:17:26.422  4815  4815 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34225]" dev="sockfs" ino=34225 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 11:17:26.426  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.427  5650  5702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 11:17:26.427  5650  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 11:17:26.427  5650  5702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 11:17:26.428  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.428  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:26.428  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.428  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.428  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.428  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:17:26.428  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:26.429  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:17:26.429  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:26.429  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:26.429  5650  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 11:17:26.429  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:26.429  5650  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:26.429  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:17:26.429  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:26.429  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:26.429  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.430  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.430  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:26.430  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.430  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread,-61,5,main], id: 61
11-23 11:17:26.432  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.432  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.432  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.432  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:26.432  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:26.432  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.432  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.434  5650  5696 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 11:17:26.434  5650  5696 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 11:17:26.435  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 11:17:26.435  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 11:17:26.435  5650  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 11:17:26.435  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:26.435  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:26.435  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:26.436  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:26.436  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:26.436  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:26.436  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.436  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.436  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:26.436  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.436  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.439  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.439  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.439  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.439  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:26.440  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:26.440  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.440  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.447  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:26.447  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:26.447  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:26.447  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:26.447  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:26.447  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:26.447  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.447  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.447  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:26.447  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.448  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.449  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.449  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.449  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.450  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:26.450  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:26.450  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.450  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.452  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:17:26.452  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:17:26.452  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:17:26.452  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:17:26.452  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:17:26.452  5650  5696 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77a3a6 not in the list
11-23 11:17:26.452  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.452  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.452  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:26.452  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.453  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.454  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.454  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.454  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:17:26.454  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:17:26.454  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:17:26.454  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:17:26.454  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3171e7 not in the list
11-23 11:17:26.455  5650  5696 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 11:17:26.456  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 11:17:26.456  5650  5696 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-23 11:17:26.456  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 11:17:26.456  5650  5696 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 11:17:26.456  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 11:17:26.458  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 11:17:26.458  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 11:17:26.459  5650  5696 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 11:17:26.459  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 11:17:26.459  5650  5696 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 11:17:26.459  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 11:17:26.460  5650  5696 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 11:17:26.460  5650  5696 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-23 11:17:26.460  5650  5696 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-23 11:17:26.460  5650  5696 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 11:17:26.461  5650  5696 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 11:17:26.461  5650  5696 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 11:17:26.461  5650  5696 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-23 11:17:26.461  5650  5696 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-23 11:17:26.463  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:17:26.463  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88107c4 added. We now have 3 listener(s)
11-23 11:17:26.463  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:17:26.465  5650  5696 D BluetoothAdapter: enable(): BT is already enabled..!
11-23 11:17:26.465   932  3669 D WifiService: setWifiEnabled: true pid=5650, uid=10077
11-23 11:17:26.465   932  3669 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 11:17:26.516  4604  4808 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-23 11:17:26.516  4604  4813 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-23 11:17:26.516  5650  5700 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-23 11:17:26.516  5650  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 11:17:26.516  5650  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-23 11:17:26.930  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 11:17:27.362   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:28.363   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:28.963   932  5413 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 11:17:29.106   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:17:29.364   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:30.365   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:31.366   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:31.470  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 11:17:31.471  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e636ad added. We now have 4 listener(s)
11-23 11:17:31.471  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 11:17:31.483  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:31.484  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e636ad removed from the list
11-23 11:17:31.484  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:31.487  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:17:31.487  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17c2de2 added. We now have 4 listener(s)
,11-23 11:17:31.487  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 11:17:31.490  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:31.490  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17c2de2 removed from the list
11-23 11:17:31.491  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 11:17:31.492  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:17:31.492  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a69573 added. We now have 4 listener(s)
11-23 11:17:31.492  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:17:31.497   932  3146 D WifiService: setWifiEnabled: false pid=5650, uid=10077
,11-23 11:17:31.497   932  3146 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 11:17:31.502   932  2960 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-23 11:17:31.503   932  2960 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-23 11:17:31.503   932  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 11:17:31.503   932  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 11:17:31.511  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 11:17:31.511  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 11:17:31.512  4604  4662 D BluetoothAdapterState: Current state: ON, message: 23
11-23 11:17:31.512  4604  4662 D BluetoothAdapterProperties: Setting state to 13
11-23 11:17:31.512  4604  4662 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 11:17:31.513  4604  4662 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 11:17:31.515  4604  4662 I BluetoothAdapterState: Entering PendingCommandState
11-23 11:17:31.516  4604  4666 D BluetoothAdapterProperties: Scan Mode:20
11-23 11:17:31.517  4604  4662 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 11:17:31.522  4604  4604 D HeadsetService: Received stop request...Stopping profile...
,11-23 11:17:31.524  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:31.524   932  5414 D DhcpClient: Clearing IP address
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 11:17:31.524  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 11:17:31.524   508   926 D CommandListener: Clearing all IP addresses on wlan0
11-23 11:17:31.525  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:31.525  5650  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 11:17:31.526  5650  5696 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 11:17:31.530  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:31.533   508   926 D CommandListener: Setting iface cfg
11-23 11:17:31.533  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 11:17:31.534  3568  5470 V NativeCrypto: Read error: ssl=0x7f6f432700: I/O error during system call, Connection timed out
11-23 11:17:31.535   932  5415 D DhcpClient: Receive thread stopped
11-23 11:17:31.536  3568  5470 V NativeCrypto: SSL shutdown failed: ssl=0x7f6f432700: I/O error during system call, Broken pipe
11-23 11:17:31.537  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:31.538   932  3140 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-23 11:17:31.539   932  5410 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-23 11:17:31.544   932  5410 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-23 11:17:31.545   932  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-23 11:17:31.545   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 11:17:31.546   932  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 11:17:31.550   932   945 I ActivityManager: Start proc 5707:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-23 11:17:31.552   932   932 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:31.552  3767  4119 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:31.552   932   932 D BluetoothHeadset: Proxy object disconnected
,11-23 11:17:31.552   932   932 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:31.553  3127  5649 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:31.553  3127  3127 D HeadsetProfile: Bluetooth service disconnected
11-23 11:17:31.553   932  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 11:17:31.553   932  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 11:17:31.554  4604  4604 D BluetoothMapService: onReceive
11-23 11:17:31.554  4604  4604 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 11:17:31.555  4604  4604 D BluetoothMapService: STATE_TURNING_OFF
11-23 11:17:31.555  4604  4604 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:31.555  4604  4604 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:31.555  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:31.555  4604  4604 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:31.556  4604  4604 D A2dpService: Received stop request...Stopping profile...
11-23 11:17:31.557  4604  4818 D A2dpStateMachine: Exit Disconnected: -1
11-23 11:17:31.558   534   534 E Parcel  : Reading a NULL string not supported here.
,11-23 11:17:31.562   932   932 D RttService: SCAN_AVAILABLE : 1
,11-23 11:17:31.562   932  3069 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 11:17:31.563   932  2962 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-23 11:17:31.564  3722  3858 W QCNEJ   : |CORE| network lost: 100
11-23 11:17:31.564  3722  3858 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 11:17:31.565  4604  4604 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 11:17:31.565  4604  4604 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 11:17:31.565  4604  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:31.565  4604  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:31.565  4604  4604 D BluetoothMapService: MAP Service closeService in
11-23 11:17:31.565  4604  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 11:17:31.565  4604  4604 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 11:17:31.566  4604  4604 D ObexServerSockets0: shutdown(block = true)
,11-23 11:17:31.566  4604  4666 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 11:17:31.566  4604  4666 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 11:17:31.566  4604  4604 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 11:17:31.566  4604  4837 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-23 11:17:31.566   932   932 D BluetoothA2dp: Proxy object disconnected
11-23 11:17:31.566  4604  4604 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 11:17:31.566  4604  4813 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 11:17:31.567  4604  4838 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 11:17:31.568  4604  4604 I BtOppRfcommListener: stopping Accept Thread
,11-23 11:17:31.568  4604  5353 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 11:17:31.568  4604  5353 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 11:17:31.572  3127  3127 D BluetoothA2dp: Proxy object disconnected
11-23 11:17:31.575  4604  4604 D HidService: Received stop request...Stopping profile...
11-23 11:17:31.575  4604  4604 D HidService: Stopping Bluetooth HidService
11-23 11:17:31.576  4604  4604 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:31.576  4604  4604 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:31.576  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:31.576  4604  4604 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:31.577  4604  4604 D HealthService: Received stop request...Stopping profile...
11-23 11:17:31.579  4604  4666 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 11:17:31.579  4604  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:31.579  4604  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:31.579  4604  4808 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 11:17:31.579  4604  4808 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 11:17:31.579  4604  4808 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 11:17:31.579  4604  4808 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 11:17:31.582  4604  4604 D PanService: Received stop request...Stopping profile...
,11-23 11:17:31.584  4604  4604 D BluetoothMapService: Received stop request...Stopping profile...
11-23 11:17:31.584  4604  4604 D BluetoothMapService: stop()
11-23 11:17:31.584   932  2960 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 11:17:31.584  4604  4604 D BluetoothMapAppObserver: deinitObservers()
11-23 11:17:31.584  4604  4604 D BluetoothMapAppObserver: removeReceiver()
,11-23 11:17:31.588  4604  4604 D SapService: Received stop request...Stopping profile...
,11-23 11:17:31.588  4604  4604 V SapService: stop()
,11-23 11:17:31.590  4604  4604 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:31.590  4604  4604 V BluetoothAdapterState: isTurningOn()=false
,11-23 11:17:31.590  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 11:17:31.590  4604  4604 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:31.590  4604  4604 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 11:17:31.590  4604  4604 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 11:17:31.591  4604  4604 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:31.591  4604  4666 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 11:17:31.591  4604  4604 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:31.591  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:31.591  4604  4604 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:31.591  4604  4604 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 11:17:31.591  4604  4666 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 11:17:31.591  4604  4604 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 11:17:31.591  4604  4604 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:31.591  4604  4604 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:31.591  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:31.592  4604  4604 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:31.592  4604  4604 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 11:17:31.592  4604  4604 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 11:17:31.593  4604  4604 D BluetoothMapService: MAP Service closeService in
11-23 11:17:31.593  4604  4604 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:31.593  4604  4604 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:31.593  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:31.593  4604  4604 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:31.593  4604  4604 D BluetoothMapService: cleanup()
11-23 11:17:31.593  4604  4604 D BluetoothMapService: MAP Service closeService in
11-23 11:17:31.593  4604  4604 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:31.594  4604  4604 V BluetoothAdapterState: isTurningOn()=false
,11-23 11:17:31.594  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:31.594  4604  4604 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:31.594   932  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 11:17:31.594  4604  4662 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 11:17:31.595  4604  4662 D BluetoothAdapterProperties: Setting state to 15
11-23 11:17:31.595  4604  4662 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 11:17:31.595  4604  4662 I BluetoothAdapterState: Entering BleOnState
11-23 11:17:31.595   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:31.595  3767  3985 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:31.596   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 11:17:31.596  3127  3139 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:31.596  3127  3141 D BluetoothMap: onBluetoothStateChange: up=false
,11-23 11:17:31.597   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 11:17:31.598  3127  3925 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 11:17:31.599  3127  5649 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 11:17:31.601  3127  3139 D BluetoothPan: onBluetoothStateChange on: false
11-23 11:17:31.602  3127  3141 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 11:17:31.605   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:31.606  4604  4662 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 11:17:31.606  4604  4662 D BluetoothAdapterProperties: Setting state to 16
11-23 11:17:31.607  4604  4662 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 11:17:31.607  4604  4662 D BluetoothAdapterProperties: onBleDisable
11-23 11:17:31.607  4604  4662 I BluetoothAdapterState: Entering PendingCommandState
,11-23 11:17:31.608  4604  4663 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-23 11:17:31.610  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 11:17:31.610  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 11:17:31.612  4604  4808 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 11:17:31.612  4604  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 11:17:31.613  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 11:17:31.613  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 11:17:31.613   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 11:17:31.614  4604  4666 D BluetoothAdapterProperties: Scan Mode:20
11-23 11:17:31.616  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:31.630  5707  5707 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 11:17:31.641  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 11:17:31.642   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 11:17:31.642   508   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 11:17:31.642   508   926 D TetherController: Setting IP forward enable = 0
,11-23 11:17:31.643   932  2962 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-23 11:17:31.643   932  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 11:17:31.644   932   949 D Tethering: MasterInitialState.processMessage what=3
,11-23 11:17:31.646   932  2960 D DhcpClient: doQuit
11-23 11:17:31.646   932  2960 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 11:17:31.647   932  5414 D DhcpClient: onQuitting
11-23 11:17:31.647  3437  3437 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 11:17:31.647  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:31.652  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:17:31.652  4939  4939 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 11:17:31.654  5072  5095 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 11:17:31.654  5072  5095 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 11:17:31.654  5072  5095 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-23 11:17:31.654  5072  5095 E SarControlService: no key has been found,reset the power
,11-23 11:17:31.655  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 11:17:31.655  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 11:17:31.655  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 11:17:31.655  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 11:17:31.656  5097  5097 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 11:17:31.656  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 11:17:31.656  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 11:17:31.656  5323  5323 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@286ae16 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-23 11:17:31.657  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 11:17:31.657  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:31.657  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 11:17:31.657  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 11:17:31.657  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 11:17:31.658  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 11:17:31.658  5097  5097 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 11:17:31.661  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a80802c HexData = [00000000ea03000000000000ffffffff]
,11-23 11:17:31.661  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 11:17:31.661  5097  5111 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 11:17:31.661  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 11:17:31.661  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 11:17:31.666   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@591c570:true
,11-23 11:17:31.668   932   943 I ActivityManager: Start proc 5731:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-23 11:17:31.669  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a80802c HexData = [00000000eb03000000000000ffffffff]
11-23 11:17:31.669  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 11:17:31.669  5097  5111 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-23 11:17:31.670  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 11:17:31.670  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 11:17:31.672  3437  3437 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 11:17:31.676  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 11:17:31.680   508   919 W SocketClient: write error (Broken pipe)
11-23 11:17:31.681   508   919 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
,11-23 11:17:31.681   508   919 W SocketListener: Error sending broadcast (Broken pipe)
,11-23 11:17:31.684  5707  5707 D LocalBluetoothProfileManager: Adding local MAP profile
,11-23 11:17:31.687  5707  5707 D BluetoothMap: Create BluetoothMap proxy object
,11-23 11:17:31.694  3437  3437 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 11:17:31.696   508   926 E Netd    : netlink response contains error (No such file or directory)
,11-23 11:17:31.697   508   926 D TetherController: Setting IP forward enable = 0
11-23 11:17:31.697   932  2962 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-23 11:17:31.697   932  2962 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 11:17:31.706  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 11:17:31.706  5707  5707 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-23 11:17:31.711   932  2960 D wifi    : In wifi stop Hal
11-23 11:17:31.711   932  2960 D wifi    : halHandle = 0x7f58ee0180, mVM = 0x7f7554d140, mCls = 0x100a02
11-23 11:17:31.711   932  3436 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 11:17:31.711   932  3436 D WifiHAL : Got a signal to exit!!!
11-23 11:17:31.712   932  3436 I WifiHAL : Exit wifi_event_loop
11-23 11:17:31.712  5046  5046 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 11:17:31.712   932  2960 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 11:17:31.712   932  2960 E WifiHAL : Event processing terminated
11-23 11:17:31.712   932  2960 D wifi    : In wifi cleaned up handler
11-23 11:17:31.712   932  2960 I WifiHAL : Internal cleanup completed
11-23 11:17:31.713  4105  4213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 11:17:31.713  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:31.724  5707  5707 D DockEventReceiver: finishStartingService: stopping service
,11-23 11:17:31.726  5731  5731 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
11-23 11:17:31.728   932  3395 I ActivityManager: Killing 4979:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-23 11:17:31.731   932  3436 D wifi    : set interface wlan0 flags (DOWN)
11-23 11:17:31.731   932  2960 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 11:17:31.821  4604  4666 I bt_hci  : shut_down
,11-23 11:17:31.823  4604  4672 D bt_hwcfg: hw_epilog_process
11-23 11:17:31.824  4604  4672 I bt_vendor: low_power_mode_cb
,11-23 11:17:31.826  4604  4672 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 11:17:31.826  4604  4672 I bt_vendor: epilog_cb
,11-23 11:17:31.826  4604  4672 I bt_hci  : epilog_finished_callback
11-23 11:17:31.828  4604  4666 I bt_hci_h4: hal_close
,11-23 11:17:31.828  4604  4666 I bt_userial_vendor: device fd = 54 close
,11-23 11:17:31.934   932   949 D Tethering: InitialState.processMessage what=4
,11-23 11:17:31.935  5731  5731 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:17:31.935  5731  5731 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:17:31.935  5731  5731 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:17:31.935  5731  5731 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:17:31.936   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-23 11:17:31.939  4604  4663 D bt_stack_manager: event_shut_down_stack finished.
11-23 11:17:31.939  4604  4662 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-23 11:17:31.941  4604  4662 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 11:17:31.941  4604  4604 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 11:17:31.942  4604  4604 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 11:17:31.942  4604  4604 D BtGatt.GattService: stop()
11-23 11:17:31.942  4604  4604 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 11:17:31.935  5731  5731 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.k.d(PG:583)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.935  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 11:17:31.945  4604  4604 V BluetoothAdapterState: isTurningOff()=false
11-23 11:17:31.945  4604  4604 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:31.945  4604  4604 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:31.945  4604  4604 V BluetoothAdapterState: isBleTurningOff()=true
11-23 11:17:31.945  4604  4662 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 11:17:31.945  4604  4662 D BluetoothAdapterProperties: Setting state to 10
11-23 11:17:31.945  4604  4662 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 11:17:31.946  4604  4662 I BluetoothAdapterState: Entering OffState
11-23 11:17:31.946  5731  5731 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.946  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:17:31.947   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-23 11:17:31.953  4604  4604 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 11:17:31.953  4604  4604 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 11:17:31.953  4604  4604 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 11:17:31.954  4604  4663 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 11:17:31.958  4604  4604 I art     : System.exit called, status: 0
,11-23 11:17:31.958  4604  4604 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 11:17:31.960  5731  5731 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.960  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:17:31.961  5731  5731 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:17:31.961  5731  5731 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:17:31.988  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 11:17:31.990   932  3842 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-23 11:17:31.991   932  3842 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
11-23 11:17:31.991   932  3842 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
11-23 11:17:31.991   932  3842 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
11-23 11:17:31.991   932  3842 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,11-23 11:17:32.007   932  3842 I ActivityManager: Start proc 5770:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,11-23 11:17:32.008   932  3146 W ActivityManager: Spurious death for ProcessRecord{98b288d 5770:com.android.bluetooth/1002}, curProc for 4604: null
,11-23 11:17:32.009  5707  5707 D DockEventReceiver: finishStartingService: stopping service
,11-23 11:17:32.010   932   943 I ActivityManager: Killing 5444:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-23 11:17:32.084  5770  5770 D AdapterServiceConfig: Adding HeadsetService
,11-23 11:17:32.084  5770  5770 D AdapterServiceConfig: Adding A2dpService
11-23 11:17:32.084  5770  5770 D AdapterServiceConfig: Adding HidService
11-23 11:17:32.084  5770  5770 D AdapterServiceConfig: Adding HealthService
11-23 11:17:32.085  5770  5770 D AdapterServiceConfig: Adding PanService
11-23 11:17:32.085  5770  5770 D AdapterServiceConfig: Adding GattService
,11-23 11:17:32.085  5770  5770 D AdapterServiceConfig: Adding BluetoothMapService
11-23 11:17:32.085  5770  5770 D AdapterServiceConfig: Adding SapService
,11-23 11:17:32.091   932  3140 I ActivityManager: Killing 5457:com.android.chrome/u0a39 (adj 15): empty #17
,11-23 11:17:32.119  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:17:32.128  3897  3897 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 11:17:32.131  3897  3897 D SystemUpdateService: onCreate
,11-23 11:17:32.137  3897  3897 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 11:17:32.145  3897  3897 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 11:17:32.152  3897  3897 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 11:17:32.153  3897  3897 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 11:17:32.160  3897  5440 I iu.UploadsManager: num queued entries: 0
,11-23 11:17:32.161  3897  5782 I SystemUpdateService: active receiver: enabled
,11-23 11:17:32.162  3897  5440 I iu.UploadsManager: num updated entries: 0
,11-23 11:17:32.167   932   942 I ActivityManager: Start proc 5785:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 11:17:32.170  3897  5782 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 11:17:32.171  3897  5440 I iu.SyncManager: NEXT; no task
,11-23 11:17:32.180  3897  5782 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 11:17:32.181  3897  5782 I SystemUpdateService: now status is 0 (complete)
11-23 11:17:32.181  3897  5782 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 11:17:32.181  3897  5782 I SystemUpdateService: file has been verified
11-23 11:17:32.181  3897  5782 I SystemUpdateService: OTA package size = 21989297
,11-23 11:17:32.199  5785  5785 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 11:17:32.207  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 11:17:32.214  5785  5785 D SprintDMHelper: simOperator: 
11-23 11:17:32.214  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 11:17:32.216  3897  5782 I SystemUpdateService: showing system update notification
,11-23 11:17:32.226   932  3820 I ActivityManager: Start proc 5797:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-23 11:17:32.248  3897  3897 D SystemUpdateService: onDestroy
,11-23 11:17:32.250   932  3669 I ActivityManager: Killing 5474:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-23 11:17:32.327  5046  5811 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 11:17:32.332   932   943 I ActivityManager: Start proc 5812:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-23 11:17:32.334   932   942 I ActivityManager: Killing 5323:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 11:17:32.367   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 11:17:32.371  5731  5761 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-23 11:17:32.393  5812  5812 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-23 11:17:32.552   932  3669 I ActivityManager: Killing 4676:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 11:17:32.572   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d5af93:true
,11-23 11:17:32.588   932  3395 I ActivityManager: Start proc 5826:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 11:17:32.622  5826  5826 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 11:17:32.631   932   942 I ActivityManager: Killing 5522:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-23 11:17:36.528   932  3842 D WifiService: setWifiEnabled: true pid=5650, uid=10077
11-23 11:17:36.528   932  3842 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 11:17:36.540   508   926 D SoftapController: Softap fwReload - Ok
,11-23 11:17:36.545   508   926 D CommandListener: Setting iface cfg
11-23 11:17:36.546   508   926 D CommandListener: Trying to bring down wlan0
11-23 11:17:36.547   508   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 11:17:36.555   932  2960 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 11:17:37.130   932  2960 D wifi    : set interface wlan0 flags (UP)
11-23 11:17:37.133   932  2960 I WifiHAL : Initializing wifi
11-23 11:17:37.134   932  2960 I WifiHAL : Creating socket
11-23 11:17:37.139   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 11:17:37.140   932  2960 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 11:17:37.140   932  2960 D wifi    : Did set static halHandle = 0x7f58ee0180
,11-23 11:17:37.140   932  2960 D wifi    : halHandle = 0x7f58ee0180, mVM = 0x7f7554d140, mCls = 0x1018ba
,11-23 11:17:37.141   932  2960 D wifi    : array field set
,11-23 11:17:37.141   932  2960 I WifiNative-HAL: interface[0] = wlan0
11-23 11:17:37.144   932  5846 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546952839552
,11-23 11:17:37.145   932  5846 D wifi    : waitForHalEvents called, vm = 0x7f7554d140, obj = 0x1018ba, env = 0x7f59e3b300
,11-23 11:17:37.148   932  2960 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 11:17:37.150   932  2960 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
11-23 11:17:37.152  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:37.225  5847  5847 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 11:17:37.245  5847  5847 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 11:17:37.285  5847  5847 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 11:17:37.285  5847  5847 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 11:17:37.368   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:38.165  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 11:17:38.165  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 11:17:38.166  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:38.166  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 11:17:38.168   932  2960 D WifiConfigStore: Loading config and enabling all networks 
,11-23 11:17:38.191   932  2960 D WifiConfigStore: loaded 0 passpoint configs
,11-23 11:17:38.192   932  2960 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-23 11:17:38.193   932  2960 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 11:17:38.195   932  2960 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 11:17:38.197   932  2960 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 11:17:38.198   932  2960 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 11:17:38.198   932  2960 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 11:17:38.198   932  2960 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 11:17:38.203   932  2960 D WifiNative-HAL: Setting external_sim to 1
,11-23 11:17:38.203  5046  5046 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 11:17:38.204   932  2960 D wifi    : setting dfs flag to true, 0x7f5cbbf8e0
,11-23 11:17:38.205   932  2960 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 11:17:38.205   932  2960 D wifi    : setting scan oui 0x7f5cbbf8e0
11-23 11:17:38.205   932  2960 D WifiHAL : Sending mac address OUI
,11-23 11:17:38.211   932  2960 E native  : do suspend false
,11-23 11:17:38.221   932  2960 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 11:17:38.221   508   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 11:17:38.222   932   932 D RttService: SCAN_AVAILABLE : 3
11-23 11:17:38.222   932  3069 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 11:17:38.223   508   926 D CommandListener: Setting iface cfg
,11-23 11:17:38.226   932  2947 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-23 11:17:38.226   932  2947 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 11:17:38.237   932  2947 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 11:17:38.242   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129970 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
11-23 11:17:38.243   932  2947 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-23 11:17:38.369   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:39.370   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:40.371   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:41.310  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 11:17:41.319  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 11:17:41.324  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 11:17:41.349   932  2960 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 11:17:41.350   932  2960 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 11:17:41.350   932  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 11:17:41.360   932  2960 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 11:17:41.371   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:41.391   932  2960 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 11:17:41.393  5847  5847 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 11:17:41.541   932  3840 D WifiService: setWifiEnabled: false pid=5650, uid=10077
,11-23 11:17:41.541   932  3840 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 11:17:41.549   932   932 D RttService: SCAN_AVAILABLE : 1
,11-23 11:17:41.549   932  3069 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 11:17:41.561   932  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 11:17:41.562   508   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 11:17:41.571   932  2960 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 11:17:41.573  5847  5847 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-23 11:17:41.579  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 11:17:41.579  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 11:17:41.579  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:41.579  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 11:17:41.590  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 11:17:41.594  5847  5847 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-23 11:17:41.615  5847  5847 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 11:17:41.626  5847  5847 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 11:17:41.735   932  2960 D wifi    : In wifi stop Hal
11-23 11:17:41.737   932  2960 D wifi    : halHandle = 0x7f58ee0180, mVM = 0x7f7554d140, mCls = 0x1018ba
11-23 11:17:41.738   932  5846 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 11:17:41.738   932  5846 D WifiHAL : Got a signal to exit!!!
,11-23 11:17:41.738   932  5846 I WifiHAL : Exit wifi_event_loop
11-23 11:17:41.741   932  2960 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 11:17:41.741   932  2960 E WifiHAL : Event processing terminated
11-23 11:17:41.742  4105  4213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 11:17:41.742   932  2960 D wifi    : In wifi cleaned up handler
11-23 11:17:41.742  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 11:17:41.743   932  2960 I WifiHAL : Internal cleanup completed
,11-23 11:17:41.745  5046  5046 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 11:17:41.771   932  5846 D wifi    : set interface wlan0 flags (DOWN)
,11-23 11:17:41.772   932  2960 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 11:17:41.978   932   949 D Tethering: InitialState.processMessage what=4
,11-23 11:17:41.986   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 11:17:42.372   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 11:17:46.583   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a2f539:true
,11-23 11:17:46.584  5770  5770 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 11:17:46.590  5770  5770 I bt_bluedroid: init
,11-23 11:17:46.591  5770  5851 I BluetoothAdapterState: Entering OffState
,11-23 11:17:46.594  5770  5852 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 11:17:46.595  5770  5852 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 11:17:46.595  5770  5852 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-23 11:17:46.595  5770  5852 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 11:17:46.595  5770  5770 I bt_bluedroid: get_profile_interface socket
,11-23 11:17:46.597  5770  5855 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-23 11:17:46.597  5770  5770 I bt_bluedroid: get_profile_interface sdp
,11-23 11:17:46.599  5770  5855 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 11:17:46.604  5770  5780 I bt_bluedroid: config_hci_snoop_log
,11-23 11:17:46.605   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 11:17:46.611  5770  5851 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 11:17:46.611  5770  5851 D BluetoothAdapterProperties: Setting state to 14
11-23 11:17:46.611  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 11:17:46.613  5770  5851 D BluetoothBondStateMachine: make
,11-23 11:17:46.615  5770  5856 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 11:17:46.619  5770  5851 I BluetoothAdapterState: Entering PendingCommandState
,11-23 11:17:46.620  5770  5770 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 11:17:46.622  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:17:46.623  5770  5770 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 11:17:46.623  5770  5770 D BtGatt.GattService: Received start request. Starting profile...
11-23 11:17:46.623  5770  5770 D BtGatt.GattService: start()
11-23 11:17:46.623  5770  5770 I bt_bluedroid: get_profile_interface gatt
,11-23 11:17:46.625  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:17:46.625  5770  5770 D BtGatt.AdvertiseManager: advertise manager created
,11-23 11:17:46.630  5770  5770 V BluetoothAdapterState: isTurningOff()=false
,11-23 11:17:46.630  5770  5770 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:46.630  5770  5770 V BluetoothAdapterState: isBleTurningOn()=true
11-23 11:17:46.630  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:46.630  5770  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 11:17:46.631  5770  5851 I bt_bluedroid: bt_bluedroid
,11-23 11:17:46.631  5770  5852 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 11:17:46.632  5770  5852 I bt_hci  : start_up
,11-23 11:17:46.637  5770  5852 I bt_vendor: alloc value 0xf41f8871,
11-23 11:17:46.637  5770  5852 I bt_vendor: init
11-23 11:17:46.637  5770  5852 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 11:17:46.637  5770  5852 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 11:17:46.749  5770  5852 D bt_hci  : start_up starting async portion
,11-23 11:17:46.749  5770  5859 I bt_hci  : event_finish_startup
11-23 11:17:46.749  5770  5859 I bt_hci_h4: hal_open
11-23 11:17:46.750  5770  5859 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 11:17:46.753  5770  5859 I bt_userial_vendor: device fd = 54 open
,11-23 11:17:46.746  5860  5860 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 11:17:46.767  5770  5859 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 11:17:46.770  5770  5859 D bt_hwcfg: Chipset BCM4358A3
,11-23 11:17:46.770  5770  5859 D bt_hwcfg: Target name = [BCM4358A3]
11-23 11:17:46.770  5770  5859 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 11:17:47.156  5770  5859 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 11:17:47.156  5770  5859 D bt_hwcfg: Settlement delay -- 100 ms
11-23 11:17:47.156  5770  5859 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 11:17:47.292  5770  5859 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-23 11:17:47.292  5770  5859 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-23 11:17:47.294  5770  5859 I bt_hwcfg: vendor lib fwcfg completed
,11-23 11:17:47.294  5770  5859 I bt_vendor: firmware callback
11-23 11:17:47.294  5770  5859 I bt_hci  : firmware_config_callback
11-23 11:17:47.302  5770  5862 I bt_btu  : btu_task pending for preload complete event
11-23 11:17:47.303  5770  5862 I bt_btu_task: Bluetooth chip preload is complete
,11-23 11:17:47.303  5770  5862 I bt_btu  : btu_task received preload complete event
,11-23 11:17:47.310  5770  5862 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 11:17:47.310  5770  5862 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 11:17:47.310  5770  5862 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 11:17:47.310  5770  5862 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 11:17:47.310  5770  5862 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-23 11:17:47.310  5770  5862 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_PAN
,11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_SMP
,11-23 11:17:47.311  5770  5862 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 11:17:47.312  5770  5862 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 11:17:47.396  5770  5862 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4176549
,11-23 11:17:47.397  5770  5862 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4176549 
,11-23 11:17:47.421  5770  5855 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 11:17:47.422  5770  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 11:17:47.423  5770  5855 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 11:17:47.425  5770  5855 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 11:17:47.428  5770  5855 D BluetoothAdapterProperties: Scan Mode:20
11-23 11:17:47.429  5770  5855 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 11:17:47.429  5770  5855 D bt_hci  : do_postload posting postload work item
11-23 11:17:47.429  5770  5859 I bt_hci  : event_postload
11-23 11:17:47.429  5770  5859 I bt_vendor: sco_config_cb
,11-23 11:17:47.429  5770  5859 I bt_hci  : sco_config_callback postload finished.
,11-23 11:17:47.433  5770  5855 D bt_bte_conf: Device ID record 1 : primary
,11-23 11:17:47.433  5770  5855 D bt_bte_conf:   vendorId            = 000f
11-23 11:17:47.433  5770  5855 D bt_bte_conf:   vendorIdSource      = 0001
11-23 11:17:47.433  5770  5855 D bt_bte_conf:   product             = 1200
11-23 11:17:47.433  5770  5855 D bt_bte_conf:   version             = 1436
11-23 11:17:47.433  5770  5855 D bt_bte_conf:   clientExecutableURL = 
11-23 11:17:47.433  5770  5855 D bt_bte_conf:   serviceDescription  = 
11-23 11:17:47.433  5770  5855 D bt_bte_conf:   documentationURL    = 
11-23 11:17:47.434  5770  5855 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 11:17:47.434  5770  5852 D bt_stack_manager: event_start_up_stack finished
11-23 11:17:47.435  5770  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 11:17:47.435  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 11:17:47.435  5770  5851 D BluetoothAdapterProperties: Setting state to 15
11-23 11:17:47.436  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 11:17:47.437  5770  5851 I BluetoothAdapterState: Entering BleOnState
,11-23 11:17:47.440  5770  5859 I bt_vendor: low_power_mode_cb
11-23 11:17:47.442  5770  5851 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 11:17:47.442  5770  5851 D BluetoothAdapterProperties: Setting state to 11
,11-23 11:17:47.442  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 11:17:47.448  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:47.451  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:17:47.452  5770  5770 D HeadsetService: Received start request. Starting profile...
,11-23 11:17:47.454  5770  5770 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-23 11:17:47.455  5770  5770 D HeadsetStateMachine: make
,11-23 11:17:47.463  5770  5851 I BluetoothAdapterState: Entering PendingCommandState
,11-23 11:17:47.463  5770  5770 D HeadsetStateMachine: max_hf_connections = 1
11-23 11:17:47.463  5770  5770 I bt_bluedroid: get_profile_interface handsfree
11-23 11:17:47.464  5770  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 11:17:47.464  5770  5855 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 11:17:47.468  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:17:47.468  5770  5770 D A2dpService: Received start request. Starting profile...
,11-23 11:17:47.469  5770  5770 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 11:17:47.469  5770  5770 I bt_bluedroid: get_profile_interface avrcp
,11-23 11:17:47.474  5770  5770 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 11:17:47.474  5770  5770 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 11:17:47.474  5770  5770 D A2dpStateMachine: make
11-23 11:17:47.475  5770  5770 I bt_bluedroid: get_profile_interface a2dp
,11-23 11:17:47.476  5770  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 11:17:47.479  5770  5870 D A2dpStateMachine: Enter Disconnected: -2
,11-23 11:17:47.479  5770  5770 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 11:17:47.480  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:17:47.480  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:17:47.482  5770  5770 D HidService: Received start request. Starting profile...
,11-23 11:17:47.482  5707  5707 D BluetoothInputDevice: Proxy object connected
11-23 11:17:47.482  5770  5770 I bt_bluedroid: get_profile_interface hidhost
11-23 11:17:47.483  5770  5770 D HidService: setHidService(): set to: null
11-23 11:17:47.483  5770  5855 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf415756d
11-23 11:17:47.483  5770  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 11:17:47.483  5770  5770 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 11:17:47.483  5707  5707 D HidProfile: Bluetooth service connected
11-23 11:17:47.484  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:17:47.484  5770  5770 D HealthService: Received start request. Starting profile...
,11-23 11:17:47.486  5770  5770 I bt_bluedroid: get_profile_interface health
11-23 11:17:47.486  5770  5770 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 11:17:47.487  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:17:47.488  5770  5770 D PanService: Received start request. Starting profile...
11-23 11:17:47.488  5770  5770 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-23 11:17:47.488  5707  5707 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 11:17:47.488  5770  5770 I bt_bluedroid: get_profile_interface pan
11-23 11:17:47.489  5770  5855 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 11:17:47.490  5707  5707 D PanProfile: Bluetooth service connected
11-23 11:17:47.490  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:17:47.492  5707  5707 D BluetoothMap: Proxy object connected
,11-23 11:17:47.492  5707  5707 D MapProfile: Bluetooth service connected
,11-23 11:17:47.493  5707  5707 D BluetoothMap: getConnectedDevices()
11-23 11:17:47.493  5770  5770 D BluetoothMapService: Received start request. Starting profile...
11-23 11:17:47.493  5770  5770 D BluetoothMapService: start()
11-23 11:17:47.493  5707  5707 D BluetoothMap: Bluetooth is Not enabled
,11-23 11:17:47.495  5770  5770 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 11:17:47.496  5770  5770 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-23 11:17:47.496  5770  5770 D BluetoothMapAppObserver: createReceiver()
11-23 11:17:47.497  5770  5770 D BluetoothMapAppObserver: initObservers()
11-23 11:17:47.498  5770  5770 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 11:17:47.505  5770  5770 V SapService: SapBinder()
,11-23 11:17:47.505  5770  5770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:17:47.506  5770  5770 D SapService: Received start request. Starting profile...
,11-23 11:17:47.506  5770  5770 V SapService: start()
,11-23 11:17:47.507  5770  5770 V BluetoothAdapterState: isTurningOff()=false
,11-23 11:17:47.507  5770  5770 V BluetoothAdapterState: isTurningOn()=true
11-23 11:17:47.508  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:47.508  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 11:17:47.508  5770  5770 V BluetoothAdapterState: isTurningOff()=false
11-23 11:17:47.508  5770  5770 V BluetoothAdapterState: isTurningOn()=true
11-23 11:17:47.508  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:47.508  5770  5867 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 11:17:47.508  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isTurningOff()=false
11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isTurningOn()=true
11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isTurningOff()=false
11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isTurningOn()=true
11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:47.509  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isTurningOff()=false
11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isTurningOn()=true
,11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isTurningOff()=false
11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isTurningOn()=true
11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:47.510  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 11:17:47.511  5770  5770 V BluetoothAdapterState: isTurningOff()=false
11-23 11:17:47.511  5770  5770 V BluetoothAdapterState: isTurningOn()=true
11-23 11:17:47.511  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 11:17:47.511  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:47.511  5770  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 11:17:47.512  5770  5851 D BluetoothAdapterProperties: ScanMode =  20
11-23 11:17:47.512  5770  5851 D BluetoothAdapterProperties: State =  11
11-23 11:17:47.514  5770  5855 D BluetoothAdapterProperties: Scan Mode:21
11-23 11:17:47.514  5770  5851 D BluetoothAdapterProperties: Setting state to 12
11-23 11:17:47.514  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 11:17:47.514  5770  5855 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 11:17:47.514  5770  5851 I BluetoothAdapterState: Entering OnState
,11-23 11:17:47.514  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 11:17:47.515  5707  5721 D BluetoothPan: onBluetoothStateChange on: true
11-23 11:17:47.516   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 11:17:47.516  5707  5718 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 11:17:47.518  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 11:17:47.520  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 11:17:47.521  3767  3785 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 11:17:47.521   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 11:17:47.522  5707  5721 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 11:17:47.522  5770  5770 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 11:17:47.522  3127  3139 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 11:17:47.523  5770  5770 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 11:17:47.523  3127  3141 D BluetoothMap: onBluetoothStateChange: up=true
11-23 11:17:47.524  5770  5770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 11:17:47.524   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 11:17:47.524  3127  3127 D BluetoothMap: Proxy object connected
11-23 11:17:47.525  3127  3127 D MapProfile: Bluetooth service connected
11-23 11:17:47.525  3127  3127 D BluetoothMap: getConnectedDevices()
,11-23 11:17:47.525  3127  5649 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 11:17:47.526  5770  5770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 11:17:47.526  3127  3925 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 11:17:47.526  3127  3127 D BluetoothInputDevice: Proxy object connected
11-23 11:17:47.526  3127  3127 D HidProfile: Bluetooth service connected
,11-23 11:17:47.527  5770  5770 D ObexServerSockets: Succeed to create listening sockets 
11-23 11:17:47.528  5770  5770 D ObexServerSockets0: startAccept()
,11-23 11:17:47.528  5770  5770 D ObexServerSockets0: prepareForNewConnect()
11-23 11:17:47.528  5707  5718 D BluetoothMap: onBluetoothStateChange: up=true
11-23 11:17:47.528  3127  5649 D BluetoothPan: onBluetoothStateChange on: true
11-23 11:17:47.530  3127  3127 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 11:17:47.530  3127  3127 D PanProfile: Bluetooth service connected
11-23 11:17:47.530  5770  5770 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-23 11:17:47.530  5770  5770 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 11:17:47.530  5770  5875 D ObexServerSockets0: Accepting socket connection...
11-23 11:17:47.530  5770  5876 D ObexServerSockets0: Accepting socket connection...
,11-23 11:17:47.531   932   932 D BluetoothA2dp: Proxy object connected
11-23 11:17:47.531  3127  3127 D BluetoothA2dp: Proxy object connected
11-23 11:17:47.532  3127  3925 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 11:17:47.533   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 11:17:47.534  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 11:17:47.535   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 11:17:47.536  5770  5770 D BluetoothMapService: onReceive
11-23 11:17:47.536  5770  5770 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 11:17:47.536  5770  5770 D BluetoothMapService: STATE_ON
11-23 11:17:47.536  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 11:17:47.537  5707  5707 D LocalBluetoothProfileManager: Adding local A2DP profile
11-23 11:17:47.540  5770  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:17:47.541  5707  5707 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-23 11:17:47.541  5770  5879 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 11:17:47.541  5770  5879 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 11:17:47.547  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 11:17:47.549  5707  5707 D BluetoothA2dp: Proxy object connected
,11-23 11:17:47.553  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:17:47.561  5770  5770 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 11:17:47.561  5770  5770 D ObexServerSockets0: prepareForNewConnect()
11-23 11:17:47.562  5707  5707 D DockEventReceiver: finishStartingService: stopping service
11-23 11:17:47.563  5707  5707 D BluetoothPbap: Proxy object connected
11-23 11:17:47.563  5707  5707 D PbapServerProfile: Bluetooth service connected
,11-23 11:17:47.566  3127  3127 D BluetoothPbap: Proxy object connected
,11-23 11:17:47.566  3127  3127 D PbapServerProfile: Bluetooth service connected
,11-23 11:17:47.569  5770  5883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:17:47.583  5770  5887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:17:47.585  5770  5887 I BtOppRfcommListener: Accept thread started.
,11-23 11:17:47.616   932   932 D BluetoothHeadset: Proxy object connected
,11-23 11:17:47.616  3767  3780 D BluetoothHeadset: Proxy object connected
11-23 11:17:47.617   932   932 D BluetoothHeadset: Proxy object connected
11-23 11:17:47.617   932   932 D BluetoothHeadset: Proxy object connected
,11-23 11:17:47.617  3127  5649 D BluetoothHeadset: Proxy object connected
11-23 11:17:47.617  3127  3127 D HeadsetProfile: Bluetooth service connected
,11-23 11:17:47.622  3767  3985 D BluetoothHeadset: Proxy object connected
11-23 11:17:47.622  3127  3139 D BluetoothHeadset: Proxy object connected
,11-23 11:17:47.622  3127  3127 D HeadsetProfile: Bluetooth service connected
,11-23 11:17:47.625   932   949 D BluetoothHeadset: Proxy object connected
,11-23 11:17:47.634   932   949 D BluetoothHeadset: Proxy object connected
,11-23 11:17:47.643  5707  5721 D BluetoothHeadset: Proxy object connected
,11-23 11:17:47.644  5707  5707 D HeadsetProfile: Bluetooth service connected
,11-23 11:17:51.561  5770  5851 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 11:17:51.562  5770  5851 D BluetoothAdapterProperties: Setting state to 13
11-23 11:17:51.562  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 11:17:51.563  5770  5851 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 11:17:51.564  5770  5851 I BluetoothAdapterState: Entering PendingCommandState
,11-23 11:17:51.569  5770  5770 D BluetoothMapService: onReceive
,11-23 11:17:51.569  5770  5770 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-23 11:17:51.569  5770  5770 D BluetoothMapService: STATE_TURNING_OFF
11-23 11:17:51.570  5770  5770 D BluetoothMapService: MAP Service closeService in
11-23 11:17:51.570  5770  5770 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 11:17:51.570  5770  5770 D ObexServerSockets0: shutdown(block = true)
11-23 11:17:51.572  5770  5875 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 11:17:51.572  5770  5770 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 11:17:51.573  5770  5770 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 11:17:51.573  5770  5876 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 11:17:51.573  5770  5864 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 11:17:51.573  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 11:17:51.573  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 11:17:51.575  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 11:17:51.575  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 11:17:51.576  5770  5770 I BtOppRfcommListener: stopping Accept Thread
11-23 11:17:51.578  5770  5887 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 11:17:51.578  5770  5855 D BluetoothAdapterProperties: Scan Mode:20
11-23 11:17:51.579  5770  5887 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 11:17:51.579  5770  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 11:17:51.581  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 11:17:51.583  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:51.588  5770  5770 D HeadsetService: Received stop request...Stopping profile...
,11-23 11:17:51.590   932   932 D BluetoothHeadset: Proxy object disconnected
,11-23 11:17:51.591  3767  4119 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:51.591  5707  5707 D DockEventReceiver: finishStartingService: stopping service
11-23 11:17:51.591   932   932 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:51.591  5770  5770 D A2dpService: Received stop request...Stopping profile...
11-23 11:17:51.592  5770  5870 D A2dpStateMachine: Exit Disconnected: -1
11-23 11:17:51.592  5707  5721 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:51.592   932   932 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:51.592  3127  3141 D BluetoothHeadset: Proxy object disconnected
11-23 11:17:51.593   932   932 D BluetoothA2dp: Proxy object disconnected
,11-23 11:17:51.594  5707  5707 D HeadsetProfile: Bluetooth service disconnected
11-23 11:17:51.595  5770  5770 D HidService: Received stop request...Stopping profile...
11-23 11:17:51.595  5770  5770 D HidService: Stopping Bluetooth HidService
11-23 11:17:51.596  5707  5707 D BluetoothA2dp: Proxy object disconnected
11-23 11:17:51.596  5707  5707 D BluetoothInputDevice: Proxy object disconnected
11-23 11:17:51.596  5770  5770 D HealthService: Received stop request...Stopping profile...
11-23 11:17:51.596  5707  5707 D HidProfile: Bluetooth service disconnected
,11-23 11:17:51.600  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:17:51.601  5770  5770 D PanService: Received stop request...Stopping profile...
,11-23 11:17:51.602  5707  5707 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 11:17:51.602  5707  5707 D PanProfile: Bluetooth service disconnected
,11-23 11:17:51.603  5770  5770 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:51.603  5770  5770 V BluetoothAdapterState: isTurningOn()=false
,11-23 11:17:51.603  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:51.603  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:51.604  5770  5770 D BluetoothMapService: Received stop request...Stopping profile...
11-23 11:17:51.604  5770  5770 D BluetoothMapService: stop()
11-23 11:17:51.604  3127  3127 D HeadsetProfile: Bluetooth service disconnected
11-23 11:17:51.604  3127  3127 D BluetoothA2dp: Proxy object disconnected
11-23 11:17:51.605  3127  3127 D BluetoothInputDevice: Proxy object disconnected
,11-23 11:17:51.605  5770  5770 D BluetoothMapAppObserver: deinitObservers()
11-23 11:17:51.605  3127  3127 D HidProfile: Bluetooth service disconnected
11-23 11:17:51.605  5770  5770 D BluetoothMapAppObserver: removeReceiver()
11-23 11:17:51.605  3127  3127 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 11:17:51.605  3127  3127 D PanProfile: Bluetooth service disconnected
11-23 11:17:51.606  3127  3127 D BluetoothMap: Proxy object disconnected
11-23 11:17:51.606  3127  3127 D MapProfile: Bluetooth service disconnected
11-23 11:17:51.606  5707  5707 D BluetoothMap: Proxy object disconnected
11-23 11:17:51.606  5707  5707 D MapProfile: Bluetooth service disconnected
11-23 11:17:51.607  5770  5770 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 11:17:51.607  5770  5770 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 11:17:51.608  5770  5862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 11:17:51.608  5770  5862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:51.608  5770  5862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:51.608  5770  5770 D SapService: Received stop request...Stopping profile...
11-23 11:17:51.608  5770  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 11:17:51.608  5770  5770 V SapService: stop()
11-23 11:17:51.608  5770  5855 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 11:17:51.609  5770  5770 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:51.609  5770  5770 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:51.609  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 11:17:51.609  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:51.611  5770  5862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:51.611  5770  5862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:51.612  5770  5862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 11:17:51.612  5770  5862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 11:17:51.612  5770  5862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 11:17:51.612  5770  5862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 11:17:51.612  5770  5770 V BluetoothAdapterState: isTurningOff()=true
,11-23 11:17:51.612  5770  5770 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:51.612  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:51.612  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:51.613  5707  5707 D BluetoothPbap: Proxy object disconnected
11-23 11:17:51.613  5707  5707 D PbapServerProfile: Bluetooth service disconnected
11-23 11:17:51.613  5770  5770 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 11:17:51.613  5770  5770 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 11:17:51.613  5770  5770 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:51.613  5770  5770 V BluetoothAdapterState: isTurningOn()=false
,11-23 11:17:51.613  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:51.613  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:51.613  5770  5770 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 11:17:51.614  3127  3127 D BluetoothPbap: Proxy object disconnected
11-23 11:17:51.612  5770  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 11:17:51.614  3127  3127 D PbapServerProfile: Bluetooth service disconnected
11-23 11:17:51.614  5770  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 11:17:51.614  5770  5855 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-23 11:17:51.615  5770  5770 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 11:17:51.616  5770  5770 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:51.616  5770  5770 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:51.616  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:51.616  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:51.616  5770  5770 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 11:17:51.616  5770  5770 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 11:17:51.618  5770  5770 D BluetoothMapService: MAP Service closeService in
11-23 11:17:51.619  5770  5770 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:51.619  5770  5770 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:51.619  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:51.619  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:51.620  5770  5770 D BluetoothMapService: cleanup()
11-23 11:17:51.620  5770  5770 D BluetoothMapService: MAP Service closeService in
11-23 11:17:51.620  5770  5770 V BluetoothAdapterState: isTurningOff()=true
11-23 11:17:51.620  5770  5770 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:51.620  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:51.620  5770  5770 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:17:51.620  5770  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 11:17:51.620  5770  5851 D BluetoothAdapterProperties: Setting state to 15
11-23 11:17:51.620  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 11:17:51.621  5707  5718 D BluetoothPan: onBluetoothStateChange on: false
11-23 11:17:51.621  5770  5851 I BluetoothAdapterState: Entering BleOnState
11-23 11:17:51.622   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:51.622  5707  5891 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 11:17:51.622  5707  5721 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 11:17:51.623  3767  3785 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:51.623   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 11:17:51.623  5707  5718 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 11:17:51.624  3127  3139 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:51.624  3127  3925 D BluetoothMap: onBluetoothStateChange: up=false
11-23 11:17:51.625   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:51.625  3127  3141 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 11:17:51.625  5707  5891 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:51.626  3127  5649 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 11:17:51.626  5707  5721 D BluetoothMap: onBluetoothStateChange: up=false
11-23 11:17:51.627  3127  3139 D BluetoothPan: onBluetoothStateChange on: false
11-23 11:17:51.628  3127  3925 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 11:17:51.628   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 11:17:51.628  5770  5851 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 11:17:51.628  5770  5851 D BluetoothAdapterProperties: Setting state to 16
11-23 11:17:51.628  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 11:17:51.629  5770  5851 D BluetoothAdapterProperties: onBleDisable
11-23 11:17:51.629  5770  5852 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 11:17:51.629  5770  5851 I BluetoothAdapterState: Entering PendingCommandState
11-23 11:17:51.631  5770  5862 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 11:17:51.631  5770  5862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 11:17:51.631  5770  5855 D BluetoothAdapterProperties: Scan Mode:20
11-23 11:17:51.633  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 11:17:51.635  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 11:17:51.636  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:17:51.643  5707  5707 D DockEventReceiver: finishStartingService: stopping service
11-23 11:17:51.644  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:17:51.841  5770  5855 I bt_hci  : shut_down
,11-23 11:17:51.846  5770  5859 D bt_hwcfg: hw_epilog_process
11-23 11:17:51.847  5770  5859 I bt_vendor: low_power_mode_cb
,11-23 11:17:51.849  5770  5859 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 11:17:51.849  5770  5859 I bt_vendor: epilog_cb
11-23 11:17:51.849  5770  5859 I bt_hci  : epilog_finished_callback
,11-23 11:17:51.852  5770  5855 I bt_hci_h4: hal_close
,11-23 11:17:51.853  5770  5855 I bt_userial_vendor: device fd = 54 close
,11-23 11:17:51.966  5770  5852 D bt_stack_manager: event_shut_down_stack finished.
,11-23 11:17:51.968  5770  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 11:17:51.972  5770  5851 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 11:17:51.972  5770  5770 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 11:17:51.973  5770  5770 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 11:17:51.974  5770  5770 D BtGatt.GattService: stop()
11-23 11:17:51.974  5770  5770 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 11:17:51.977  5770  5770 V BluetoothAdapterState: isTurningOff()=false
,11-23 11:17:51.978  5770  5770 V BluetoothAdapterState: isTurningOn()=false
11-23 11:17:51.978  5770  5770 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:17:51.978  5770  5770 V BluetoothAdapterState: isBleTurningOff()=true
11-23 11:17:51.978  5770  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-23 11:17:51.979  5770  5851 D BluetoothAdapterProperties: Setting state to 10
,11-23 11:17:51.979  5770  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 11:17:51.980  5770  5851 I BluetoothAdapterState: Entering OffState
11-23 11:17:51.981   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 11:17:51.996  5770  5770 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 11:17:51.996  5770  5770 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 11:17:51.996  5770  5770 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 11:17:51.998  5770  5852 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 11:17:52.009  5770  5770 I art     : System.exit called, status: 0
,11-23 11:17:52.010  5770  5770 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 11:17:52.037   932  3825 I ActivityManager: Process com.android.bluetooth (pid 5770) has died
,11-23 11:17:52.373   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:53.374   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:54.375   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:55.376   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:56.377   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:17:56.559  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 11:17:56.559  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 11:17:56.565  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:56.565  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a69573 removed from the list
,11-23 11:17:56.591  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 11:17:56.594  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 11:17:56.594  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b3462e added. We now have 4 listener(s)
11-23 11:17:56.594  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 11:17:56.595  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:17:56.595  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b3462e removed from the list
11-23 11:17:56.595  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:17:56.597  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:17:56.597  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64b15cf added. We now have 4 listener(s)
,11-23 11:17:56.597  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 11:17:57.377   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 11:18:01.605  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 11:18:01.641   932   949 I ActivityManager: Start proc 5896:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 11:18:01.730  5896  5896 D AdapterServiceConfig: Adding HeadsetService
,11-23 11:18:01.731  5896  5896 D AdapterServiceConfig: Adding A2dpService
11-23 11:18:01.731  5896  5896 D AdapterServiceConfig: Adding HidService
11-23 11:18:01.731  5896  5896 D AdapterServiceConfig: Adding HealthService
11-23 11:18:01.731  5896  5896 D AdapterServiceConfig: Adding PanService
,11-23 11:18:01.731  5896  5896 D AdapterServiceConfig: Adding GattService
11-23 11:18:01.732  5896  5896 D AdapterServiceConfig: Adding BluetoothMapService
11-23 11:18:01.732  5896  5896 D AdapterServiceConfig: Adding SapService
,11-23 11:18:01.745   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@86d02f9:true
,11-23 11:18:01.745  5896  5896 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 11:18:01.748  5896  5896 I bt_bluedroid: init
,11-23 11:18:01.748  5896  5908 I BluetoothAdapterState: Entering OffState
,11-23 11:18:01.751  5896  5909 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-23 11:18:01.751  5896  5909 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 11:18:01.751  5896  5909 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 11:18:01.751  5896  5909 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 11:18:01.752  5896  5896 I bt_bluedroid: get_profile_interface socket
,11-23 11:18:01.754  5896  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 11:18:01.754  5896  5896 I bt_bluedroid: get_profile_interface sdp
,11-23 11:18:01.755  5896  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 11:18:01.759  5896  5907 I bt_bluedroid: config_hci_snoop_log
11-23 11:18:01.760   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 11:18:01.765  5896  5908 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 11:18:01.765  5896  5908 D BluetoothAdapterProperties: Setting state to 14
11-23 11:18:01.765  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 11:18:01.767  5896  5908 D BluetoothBondStateMachine: make
,11-23 11:18:01.770  5896  5913 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 11:18:01.772  5896  5908 I BluetoothAdapterState: Entering PendingCommandState
,11-23 11:18:01.774  5896  5896 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 11:18:01.777  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:18:01.778  5896  5896 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 11:18:01.778  5896  5896 D BtGatt.GattService: Received start request. Starting profile...
,11-23 11:18:01.779  5896  5896 D BtGatt.GattService: start()
11-23 11:18:01.779  5896  5896 I bt_bluedroid: get_profile_interface gatt
11-23 11:18:01.780  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:18:01.780  5896  5896 D BtGatt.AdvertiseManager: advertise manager created
,11-23 11:18:01.787  5896  5896 V BluetoothAdapterState: isTurningOff()=false
,11-23 11:18:01.787  5896  5896 V BluetoothAdapterState: isTurningOn()=false
11-23 11:18:01.787  5896  5896 V BluetoothAdapterState: isBleTurningOn()=true
11-23 11:18:01.787  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:18:01.788  5896  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 11:18:01.789  5896  5908 I bt_bluedroid: bt_bluedroid
,11-23 11:18:01.789  5896  5909 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 11:18:01.790  5896  5909 I bt_hci  : start_up
,11-23 11:18:01.795  5896  5909 I bt_vendor: alloc value 0xf4249871
,11-23 11:18:01.796  5896  5909 I bt_vendor: init
11-23 11:18:01.796  5896  5909 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 11:18:01.796  5896  5909 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 11:18:01.906  5896  5909 D bt_hci  : start_up starting async portion
,11-23 11:18:01.906  5896  5916 I bt_hci  : event_finish_startup
11-23 11:18:01.907  5896  5916 I bt_hci_h4: hal_open
11-23 11:18:01.907  5896  5916 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 11:18:01.906  5917  5917 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 11:18:01.911  5896  5916 I bt_userial_vendor: device fd = 54 open
,11-23 11:18:01.928  5896  5916 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 11:18:01.931  5896  5916 D bt_hwcfg: Chipset BCM4358A3
,11-23 11:18:01.932  5896  5916 D bt_hwcfg: Target name = [BCM4358A3]
11-23 11:18:01.932  5896  5916 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 11:18:02.453  5896  5916 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 11:18:02.453  5896  5916 D bt_hwcfg: Settlement delay -- 100 ms
11-23 11:18:02.454  5896  5916 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 11:18:02.587  5896  5916 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 11:18:02.588  5896  5916 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-23 11:18:02.590  5896  5916 I bt_hwcfg: vendor lib fwcfg completed
,11-23 11:18:02.590  5896  5916 I bt_vendor: firmware callback
11-23 11:18:02.590  5896  5916 I bt_hci  : firmware_config_callback
,11-23 11:18:02.599  5896  5919 I bt_btu  : btu_task pending for preload complete event
,11-23 11:18:02.600  5896  5919 I bt_btu_task: Bluetooth chip preload is complete
11-23 11:18:02.600  5896  5919 I bt_btu  : btu_task received preload complete event
,11-23 11:18:02.606  5896  5919 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 11:18:02.606  5896  5919 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 11:18:02.606  5896  5919 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 11:18:02.606  5896  5919 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-23 11:18:02.606  5896  5919 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 11:18:02.606  5896  5919 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 11:18:02.606  5896  5919 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_SDP
,11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_SMP
,11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 11:18:02.607  5896  5919 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 11:18:02.696  5896  5919 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41c7549
,11-23 11:18:02.696  5896  5919 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41c7549 
,11-23 11:18:02.710  5896  5912 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 11:18:02.712  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 11:18:02.712  5896  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 11:18:02.715  5896  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 11:18:02.717  5896  5912 D BluetoothAdapterProperties: Scan Mode:20
,11-23 11:18:02.718  5896  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 11:18:02.718  5896  5912 D bt_hci  : do_postload posting postload work item
11-23 11:18:02.718  5896  5916 I bt_hci  : event_postload
11-23 11:18:02.718  5896  5916 I bt_vendor: sco_config_cb
,11-23 11:18:02.718  5896  5916 I bt_hci  : sco_config_callback postload finished.
,11-23 11:18:02.721  5896  5912 D bt_bte_conf: Device ID record 1 : primary
11-23 11:18:02.721  5896  5912 D bt_bte_conf:   vendorId            = 000f
11-23 11:18:02.722  5896  5912 D bt_bte_conf:   vendorIdSource      = 0001
11-23 11:18:02.722  5896  5912 D bt_bte_conf:   product             = 1200
11-23 11:18:02.722  5896  5912 D bt_bte_conf:   version             = 1436
11-23 11:18:02.722  5896  5912 D bt_bte_conf:   clientExecutableURL = 
11-23 11:18:02.722  5896  5912 D bt_bte_conf:   serviceDescription  = 
,11-23 11:18:02.722  5896  5912 D bt_bte_conf:   documentationURL    = 
11-23 11:18:02.722  5896  5912 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 11:18:02.723  5896  5909 D bt_stack_manager: event_start_up_stack finished
11-23 11:18:02.723  5896  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 11:18:02.724  5896  5908 D BluetoothAdapterProperties: Setting state to 15
11-23 11:18:02.724  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-23 11:18:02.725  5896  5908 I BluetoothAdapterState: Entering BleOnState
,11-23 11:18:02.727  5896  5916 I bt_vendor: low_power_mode_cb
,11-23 11:18:02.730  5896  5908 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 11:18:02.730  5896  5908 D BluetoothAdapterProperties: Setting state to 11
11-23 11:18:02.730  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 11:18:02.741  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:18:02.742  5896  5896 D HeadsetService: Received start request. Starting profile...
11-23 11:18:02.746  5896  5896 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-23 11:18:02.747  5896  5896 D HeadsetStateMachine: make
,11-23 11:18:02.759  5896  5896 D HeadsetStateMachine: max_hf_connections = 1
,11-23 11:18:02.759  5896  5896 I bt_bluedroid: get_profile_interface handsfree
11-23 11:18:02.760  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 11:18:02.760  5896  5908 I BluetoothAdapterState: Entering PendingCommandState
11-23 11:18:02.760  5896  5912 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 11:18:02.763  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:18:02.764  5896  5896 D A2dpService: Received start request. Starting profile...
11-23 11:18:02.765  5896  5896 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 11:18:02.765  5896  5896 I bt_bluedroid: get_profile_interface avrcp
,11-23 11:18:02.771  5896  5896 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 11:18:02.772  5896  5896 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 11:18:02.772  5896  5896 D A2dpStateMachine: make
,11-23 11:18:02.773  5896  5896 I bt_bluedroid: get_profile_interface a2dp
,11-23 11:18:02.774  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 11:18:02.776  5896  5926 D A2dpStateMachine: Enter Disconnected: -2
11-23 11:18:02.778  5896  5896 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 11:18:02.778  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:18:02.779  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:18:02.780  5896  5896 D HidService: Received start request. Starting profile...
11-23 11:18:02.780  5896  5896 I bt_bluedroid: get_profile_interface hidhost
,11-23 11:18:02.780  5896  5896 D HidService: setHidService(): set to: null
11-23 11:18:02.780  5896  5912 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41a856d
,11-23 11:18:02.781  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 11:18:02.781  5896  5896 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 11:18:02.782  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
,11-23 11:18:02.783  5896  5896 D HealthService: Received start request. Starting profile...
,11-23 11:18:02.784  5896  5896 I bt_bluedroid: get_profile_interface health
,11-23 11:18:02.786  5896  5896 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-23 11:18:02.787  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:18:02.787  5896  5896 D PanService: Received start request. Starting profile...
,11-23 11:18:02.788  5896  5896 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 11:18:02.788  5896  5896 I bt_bluedroid: get_profile_interface pan
11-23 11:18:02.788  5896  5912 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-23 11:18:02.790  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:18:02.790  5896  5896 D BluetoothMapService: Received start request. Starting profile...
11-23 11:18:02.790  5896  5896 D BluetoothMapService: start()
,11-23 11:18:02.793  5896  5896 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 11:18:02.794  5896  5896 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-23 11:18:02.794  5896  5896 D BluetoothMapAppObserver: createReceiver()
11-23 11:18:02.796  5896  5896 D BluetoothMapAppObserver: initObservers()
11-23 11:18:02.796  5896  5896 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 11:18:02.803  5896  5896 V SapService: SapBinder()
,11-23 11:18:02.803  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:18:02.804  5896  5896 D SapService: Received start request. Starting profile...
11-23 11:18:02.804  5896  5896 V SapService: start()
,11-23 11:18:02.805  5896  5924 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 11:18:02.805  5896  5896 V BluetoothAdapterState: isTurningOff()=false
,11-23 11:18:02.805  5896  5896 V BluetoothAdapterState: isTurningOn()=true
11-23 11:18:02.805  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:18:02.806  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:18:02.806  5896  5896 V BluetoothAdapterState: isTurningOff()=false
11-23 11:18:02.806  5896  5896 V BluetoothAdapterState: isTurningOn()=true
11-23 11:18:02.806  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:18:02.806  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isTurningOff()=false
,11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isTurningOn()=true
11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isTurningOff()=false
11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isTurningOn()=true
11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:18:02.807  5896  5896 V BluetoothAdapterState: isTurningOff()=false
11-23 11:18:02.808  5896  5896 V BluetoothAdapterState: isTurningOn()=true
,11-23 11:18:02.808  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:18:02.808  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:18:02.808  5896  5896 V BluetoothAdapterState: isTurningOff()=false
11-23 11:18:02.808  5896  5896 V BluetoothAdapterState: isTurningOn()=true
11-23 11:18:02.808  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:18:02.808  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:18:02.809  5896  5896 V BluetoothAdapterState: isTurningOff()=false
11-23 11:18:02.809  5896  5896 V BluetoothAdapterState: isTurningOn()=true
11-23 11:18:02.809  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
11-23 11:18:02.809  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
11-23 11:18:02.809  5896  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 11:18:02.809  5896  5908 D BluetoothAdapterProperties: ScanMode =  20
11-23 11:18:02.809  5896  5908 D BluetoothAdapterProperties: State =  11
11-23 11:18:02.810  5896  5908 D BluetoothAdapterProperties: Setting state to 12
11-23 11:18:02.810  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 11:18:02.810  5896  5908 I BluetoothAdapterState: Entering OnState
11-23 11:18:02.811  5896  5912 D BluetoothAdapterProperties: Scan Mode:21
,11-23 11:18:02.811  5707  5718 D BluetoothPan: onBluetoothStateChange on: true
11-23 11:18:02.811  5896  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 11:18:02.813   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 11:18:02.813  5707  5891 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 11:18:02.816  5707  5721 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 11:18:02.817  3767  3785 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 11:18:02.818   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 11:18:02.818   932   932 D BluetoothA2dp: Proxy object connected
,11-23 11:18:02.818  5707  5718 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 11:18:02.820  3127  3139 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 11:18:02.821  5707  5707 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 11:18:02.821  5896  5896 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 11:18:02.821  3127  3925 D BluetoothMap: onBluetoothStateChange: up=true
11-23 11:18:02.821  5707  5707 D PanProfile: Bluetooth service connected
11-23 11:18:02.821  5707  5707 D BluetoothA2dp: Proxy object connected
11-23 11:18:02.822  5896  5896 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 11:18:02.823   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 11:18:02.823  3127  3141 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 11:18:02.824  5896  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 11:18:02.824  5707  5707 D BluetoothInputDevice: Proxy object connected
11-23 11:18:02.824  5707  5707 D HidProfile: Bluetooth service connected
,11-23 11:18:02.825  3127  3127 D BluetoothInputDevice: Proxy object connected
11-23 11:18:02.825  3127  3127 D HidProfile: Bluetooth service connected
,11-23 11:18:02.825  5707  5721 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 11:18:02.826  3127  5649 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 11:18:02.828  3127  3127 D BluetoothA2dp: Proxy object connected
11-23 11:18:02.828  5707  5718 D BluetoothMap: onBluetoothStateChange: up=true
11-23 11:18:02.830  3127  3925 D BluetoothPan: onBluetoothStateChange on: true
11-23 11:18:02.830  5896  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 11:18:02.831  3127  5649 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 11:18:02.831  3127  3127 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 11:18:02.831  3127  3127 D PanProfile: Bluetooth service connected
11-23 11:18:02.832  5896  5896 D ObexServerSockets: Succeed to create listening sockets 
11-23 11:18:02.832  5896  5896 D ObexServerSockets0: startAccept()
11-23 11:18:02.832  5896  5896 D ObexServerSockets0: prepareForNewConnect()
,11-23 11:18:02.833   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 11:18:02.834  5896  5896 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 11:18:02.834  5896  5896 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 11:18:02.835   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 11:18:02.835  5896  5896 D BluetoothMapService: onReceive
11-23 11:18:02.835  5896  5896 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 11:18:02.835  5896  5896 D BluetoothMapService: STATE_ON
,11-23 11:18:02.835  3127  3127 D BluetoothMap: Proxy object connected
11-23 11:18:02.836  3127  3127 D MapProfile: Bluetooth service connected
11-23 11:18:02.836  3127  3127 D BluetoothMap: getConnectedDevices()
11-23 11:18:02.836  5896  5933 D ObexServerSockets0: Accepting socket connection...
11-23 11:18:02.836  5896  5934 D ObexServerSockets0: Accepting socket connection...
11-23 11:18:02.838  5896  5935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:18:02.840  5896  5935 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-23 11:18:02.840  5896  5935 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 11:18:02.843  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 11:18:02.846  5707  5707 D BluetoothMap: Proxy object connected
11-23 11:18:02.846  5707  5707 D MapProfile: Bluetooth service connected
11-23 11:18:02.846  5707  5707 D BluetoothMap: getConnectedDevices()
,11-23 11:18:02.851  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 11:18:02.852  5707  5707 D DockEventReceiver: finishStartingService: stopping service
,11-23 11:18:02.860  3127  3127 D BluetoothPbap: Proxy object connected
11-23 11:18:02.861  3127  3127 D PbapServerProfile: Bluetooth service connected
,11-23 11:18:02.863  5707  5707 D BluetoothPbap: Proxy object connected
11-23 11:18:02.863  5707  5707 D PbapServerProfile: Bluetooth service connected
,11-23 11:18:02.866  5896  5896 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 11:18:02.866  5896  5896 D ObexServerSockets0: prepareForNewConnect()
,11-23 11:18:02.869  5896  5940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:18:02.886  5896  5944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 11:18:02.887  5896  5944 I BtOppRfcommListener: Accept thread started.
,11-23 11:18:02.916   932   932 D BluetoothHeadset: Proxy object connected
,11-23 11:18:02.916  3767  3780 D BluetoothHeadset: Proxy object connected
11-23 11:18:02.917   932   932 D BluetoothHeadset: Proxy object connected
11-23 11:18:02.917  5707  5721 D BluetoothHeadset: Proxy object connected
11-23 11:18:02.917  5707  5707 D HeadsetProfile: Bluetooth service connected
,11-23 11:18:02.918   932   932 D BluetoothHeadset: Proxy object connected
,11-23 11:18:02.918  3767  3985 D BluetoothHeadset: Proxy object connected
,11-23 11:18:02.918  3127  3925 D BluetoothHeadset: Proxy object connected
11-23 11:18:02.919  3127  3127 D HeadsetProfile: Bluetooth service connected
,11-23 11:18:02.922  3127  3141 D BluetoothHeadset: Proxy object connected
,11-23 11:18:02.922  3127  3127 D HeadsetProfile: Bluetooth service connected
,11-23 11:18:02.923   932   949 D BluetoothHeadset: Proxy object connected
,11-23 11:18:02.926  5707  5718 D BluetoothHeadset: Proxy object connected
11-23 11:18:02.926  5707  5707 D HeadsetProfile: Bluetooth service connected
,11-23 11:18:02.933   932   949 D BluetoothHeadset: Proxy object connected
,11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 11:18:06.623  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 11:18:06.630  5650  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 11:18:06.631  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:06.631  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64b15cf removed from the list
11-23 11:18:06.632  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:18:06.634  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:06.634  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb78b5c added. We now have 4 listener(s)
11-23 11:18:06.634  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:06.637   932  3840 D WifiService: setWifiEnabled: false pid=5650, uid=10077
,11-23 11:18:06.638   932  3840 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 11:18:11.649  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 11:18:11.650   932  3820 D WifiService: setWifiEnabled: true pid=5650, uid=10077
11-23 11:18:11.650   932  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 11:18:11.661   508   926 D SoftapController: Softap fwReload - Ok
,11-23 11:18:11.667   508   926 D CommandListener: Setting iface cfg
,11-23 11:18:11.667   508   926 D CommandListener: Trying to bring down wlan0
,11-23 11:18:11.670   508   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 11:18:11.674   932  2960 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 11:18:12.370   932  2960 D wifi    : set interface wlan0 flags (UP)
,11-23 11:18:12.371   932  2960 I WifiHAL : Initializing wifi
11-23 11:18:12.371   932  2960 I WifiHAL : Creating socket
11-23 11:18:12.377   932  2960 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 11:18:12.377   932  2960 D wifi    : Did set static halHandle = 0x7f58ee0180
,11-23 11:18:12.378   932  2960 D wifi    : halHandle = 0x7f58ee0180, mVM = 0x7f7554d140, mCls = 0x2019b6
,11-23 11:18:12.378   932  2960 D wifi    : array field set
,11-23 11:18:12.378   536   536 I ServiceManager: Waiting for service AtCmdFwd...
11-23 11:18:12.378   932  2960 I WifiNative-HAL: interface[0] = wlan0
,11-23 11:18:12.382   932  5949 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546952839552
11-23 11:18:12.382   932  5949 D wifi    : waitForHalEvents called, vm = 0x7f7554d140, obj = 0x2019b6, env = 0x7f59e3c980
11-23 11:18:12.384   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 11:18:12.432  5950  5950 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 11:18:12.454  5950  5950 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 11:18:12.483   932  2960 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 11:18:12.512  5950  5950 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 11:18:12.513  5950  5950 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 11:18:12.536   932  2960 D WifiConfigStore: Loading config and enabling all networks 
,11-23 11:18:12.552   932  2960 D WifiConfigStore: loaded 0 passpoint configs
,11-23 11:18:12.553   932  2960 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 11:18:12.553   932  2960 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 11:18:12.554   932  2960 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 11:18:12.556   932  2960 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 11:18:12.556   932  2960 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 11:18:12.556   932  2960 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 11:18:12.556   932  2960 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 11:18:12.558   932  2960 D WifiNative-HAL: Setting external_sim to 1
,11-23 11:18:12.559   932  2960 D wifi    : setting dfs flag to true, 0x7f5a53f540
,11-23 11:18:12.559  5046  5046 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 11:18:12.559   932  2960 D WifiStateMachine: Setting OUI to DA-A1-19
,11-23 11:18:12.559   932  2960 D wifi    : setting scan oui 0x7f5a53f540
11-23 11:18:12.559   932  2960 D WifiHAL : Sending mac address OUI
,11-23 11:18:12.563   932  2960 E native  : do suspend false
,11-23 11:18:12.574   932  2960 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 11:18:12.574   932   932 D RttService: SCAN_AVAILABLE : 3
,11-23 11:18:12.574   932  3069 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 11:18:12.574   508   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 11:18:12.576   508   926 D CommandListener: Setting iface cfg
,11-23 11:18:12.581   932  2947 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '140 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 140 Failed to set address (No such device)'
,11-23 11:18:12.582   932  2947 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 11:18:12.587   932  2947 D WifiNative-HAL: p2pGetDeviceAddress
11-23 11:18:12.587   932  2947 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-23 11:18:12.601   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164329 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-23 11:18:13.379   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:14.381   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:15.381   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:15.710   932  2960 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-23 11:18:15.711   932  2960 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-23 11:18:15.712   932  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 11:18:15.723   932  2960 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 11:18:15.757   932  2960 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 11:18:15.759  5950  5950 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 11:18:16.177  5950  5950 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 11:18:16.212  5950  5950 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 11:18:16.214  5950  5950 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 11:18:16.226   932  2960 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-23 11:18:16.226   932  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 11:18:16.226   932  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 11:18:16.241   932  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 11:18:16.253   508   926 D CommandListener: Setting iface cfg
,11-23 11:18:16.259   932  2960 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 11:18:16.265   932  5955 D DhcpClient: Receive thread started
,11-23 11:18:16.270   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 11:18:16.270   932  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 11:18:16.270   932  2962 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 11:18:16.351   932  2960 E native  : do suspend false
,11-23 11:18:16.363   932  5954 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 11:18:16.382   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:16.391   932  5955 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172673, domain null
,11-23 11:18:16.391   932  5954 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172673 seconds
,11-23 11:18:16.394   932  5954 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-23 11:18:16.408   932  5955 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 11:18:16.409   932  5954 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 11:18:16.413   508   926 D CommandListener: Setting iface cfg
,11-23 11:18:16.418   932  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 11:18:16.421   932  5954 D DhcpClient: Scheduling renewal in 86399s
,11-23 11:18:16.428   932  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 11:18:16.429   932  2960 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 11:18:16.430   932  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 11:18:16.431   932  2960 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 11:18:16.438   932  2962 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 11:18:16.479   932  2962 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 11:18:16.479   932  2962 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-23 11:18:16.481   932  2962 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 11:18:16.485   932  2962 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 11:18:16.487   932  2962 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 11:18:16.495   932  2962 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 11:18:16.500   932  2962 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-23 11:18:16.500   932  2962 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-23 11:18:16.500   932  2962 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-23 11:18:16.500   932  2960 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-23 11:18:16.500   932  2962 D ConnectivityService:    accepting network in place of null
11-23 11:18:16.501   932  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 11:18:16.501   932  2962 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 11:18:16.505   932  5953 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168233, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 11:18:16.525   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 11:18:16.546   508   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 11:18:16.549   932  2962 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 11:18:16.550   932  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 11:18:16.550  3722  3858 W QCNEJ   : |CORE| network available: 101
11-23 11:18:16.551   932  2962 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-23 11:18:16.551   932   949 D Tethering: MasterInitialState.processMessage what=3
11-23 11:18:16.554  3722  3858 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 11:18:16.555  3722  3858 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-23 11:18:16.556  3722  3858 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 11:18:16.570  5072  5095 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 11:18:16.570  5072  5095 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 11:18:16.570  5072  5095 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 11:18:16.570  5072  5095 E SarControlService: no key has been found,reset the power
11-23 11:18:16.571  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 11:18:16.571  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 11:18:16.571  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-23 11:18:16.571  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 11:18:16.571  5097  5097 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 11:18:16.574   932  5952 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
11-23 11:18:16.574  4939  4939 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 11:18:16.575  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 11:18:16.575  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 11:18:16.575  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-23 11:18:16.577  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 11:18:16.577  5097  5097 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 11:18:16.579  3897  3897 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 11:18:16.582  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a80802c HexData = [00000000ec03000000000000ffffffff]
11-23 11:18:16.582  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 11:18:16.582  5097  5111 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 11:18:16.582  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 11:18:16.583  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 11:18:16.583  3897  3897 D SystemUpdateService: onCreate
,11-23 11:18:16.587  3897  3897 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 11:18:16.589  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a80802c HexData = [00000000ed03000000000000ffffffff]
11-23 11:18:16.589  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 11:18:16.589  5097  5111 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-23 11:18:16.590  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 11:18:16.590  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 11:18:16.601  3897  3897 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 11:18:16.626  3897  3897 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 11:18:16.627  3897  3897 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 11:18:16.622  3897  5966 I SystemUpdateService: active receiver: enabled
,11-23 11:18:16.629  3897  5440 I iu.UploadsManager: num queued entries: 0
,11-23 11:18:16.629  3897  5440 I iu.UploadsManager: num updated entries: 0
11-23 11:18:16.631  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 11:18:16.635   932  5952 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 16:18:16 GMT], X-Android-Received-Millis=[1479917896635], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479917896599]}
,11-23 11:18:16.636   932  2962 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 11:18:16.636   932  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-23 11:18:16.636   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 11:18:16.638   932  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 11:18:16.639  3897  5440 I iu.SyncManager: NEXT; no task
,11-23 11:18:16.641  5785  5785 D SprintDMHelper: simOperator: 
,11-23 11:18:16.641  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 11:18:16.647  3897  5966 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 11:18:16.664  3897  5966 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 11:18:16.668  3897  5966 I SystemUpdateService: now status is 0 (complete)
11-23 11:18:16.668  3897  5966 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 11:18:16.668  3897  5966 I SystemUpdateService: file has been verified
11-23 11:18:16.668  3897  5966 I SystemUpdateService: OTA package size = 21989297
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 11:18:16.670  5650  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 11:18:16.671  5650  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 11:18:16.672  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 11:18:16.672  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb78b5c removed from the list
11-23 11:18:16.672  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 11:18:16.675  5650  5696 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-23 11:18:16.676  5650  5696 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-23 11:18:16.679  5650  5696 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d118d30 Bundle[{}]
,11-23 11:18:16.679  5650  5696 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 11:18:16.680  5650  5696 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 11:18:16.680  5650  5696 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-23 11:18:16.681  5650  5696 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 11:18:16.681  5650  5696 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 11:18:16.682  5650  5696 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-23 11:18:16.688  3897  5966 I SystemUpdateService: showing system update notification
11-23 11:18:16.688  5650  5696 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-23 11:18:16.689  5650  5696 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-23 11:18:16.689  5650  5696 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-23 11:18:16.691  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.691  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec48e65 added. We now have 3 listener(s)
11-23 11:18:16.692  3568  5977 I VacuumService: Vacuum at: now=1479917896692 tag=VacuumService
11-23 11:18:16.693  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:18:16.693  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.693  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 11:18:16.693  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:16.693  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@431973a added. We now have 4 listener(s)
11-23 11:18:16.693  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 11:18:16.694  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 11:18:16.695  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.695  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d3feb added. We now have 4 listener(s)
,11-23 11:18:16.697  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 11:18:16.697  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.697  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.697  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:16.697  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e00148 added. We now have 5 listener(s)
11-23 11:18:16.697  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.698  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:18:16.698  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:18:16.698  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:18:16.698  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.698  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.698  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.698  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec48e65 removed from the list
,11-23 11:18:16.698  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.698  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@431973a removed from the list
,11-23 11:18:16.698  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:18:16.699  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.699  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.700  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.700  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.700  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.700  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.700  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:18:16.701  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.701  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@431973a not in the list
11-23 11:18:16.701  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.701  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.701  3897  3897 D SystemUpdateService: onDestroy
,11-23 11:18:16.703  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.703  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.704  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.704  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 11:18:16.704  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.704  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.704  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e00148 removed from the list
11-23 11:18:16.704  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.704  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.704  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.704  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d3feb removed from the list
11-23 11:18:16.705  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.705  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74abe1 added. We now have 3 listener(s)
11-23 11:18:16.706  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 11:18:16.706  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.706  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.706  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:16.706  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f11ed06 added. We now have 4 listener(s)
11-23 11:18:16.707  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.707  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 11:18:16.708  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.708  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97defc7 added. We now have 4 listener(s)
11-23 11:18:16.709  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:18:16.709  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.709  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.709  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:16.709  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@497e9f4 added. We now have 5 listener(s)
11-23 11:18:16.709  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.709  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:18:16.709  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 11:18:16.709  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 11:18:16.709  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 11:18:16.710  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 11:18:16.711  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 11:18:16.716  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 11:18:16.716  5650  5696 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 11:18:16.716  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 11:18:16.719  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.719  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 11:18:16.720  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 11:18:16.720  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 11:18:16.720  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 11:18:16.724  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.724  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 11:18:16.724  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 11:18:16.724  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 11:18:16.724  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 11:18:16.724  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.725  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:18:16.728  5896  5936 D BtGatt.GattService: registerClient() - UUID=84bea8e9-44d8-4bd6-8342-789bd768664a
11-23 11:18:16.728  5896  5912 D BtGatt.GattService: onClientRegistered() - UUID=84bea8e9-44d8-4bd6-8342-789bd768664a, clientIf=5
11-23 11:18:16.729  5650  5660 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 11:18:16.730  3568  5980 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-23 11:18:16.730  5896  5932 D BtGatt.GattService: start scan with filters
,11-23 11:18:16.733  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 11:18:16.733  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.733  5896  5915 D BtGatt.ScanManager: handling starting scan
11-23 11:18:16.733  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 11:18:16.733  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.734  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 11:18:16.734  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 11:18:16.734  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.734  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 11:18:16.734  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 11:18:16.734  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.734  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.735  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.735  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-23 11:18:16.735  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.735  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.737  5896  5915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e5bc3ad
11-23 11:18:16.740  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.740  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:18:16.740  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.740  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.740  5650  5696 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 11:18:16.740  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.740  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 11:18:16.740  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 11:18:16.740  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.740  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 11:18:16.740  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.740  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 11:18:16.743  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.743  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.743  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.743  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 11:18:16.743  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 11:18:16.743  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.743  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 11:18:16.744  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 11:18:16.744  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.744  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.744  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.744  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 11:18:16.744  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.745  5896  5912 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 11:18:16.745  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.745  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:18:16.745  5896  5915 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 11:18:16.746  5896  5936 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 11:18:16.746  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 11:18:16.747  5650  5696 D BluetoothAdapter: STATE_ON
,11-23 11:18:16.748  5896  5907 D BtGatt.GattService: stopScan() - queue size =1
11-23 11:18:16.749  5896  5931 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 11:18:16.749  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.750  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.751  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.751  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 11:18:16.751  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 11:18:16.751  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 11:18:16.751  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.751  5896  5915 D BtGatt.ScanManager: Starting BLE batch scan
11-23 11:18:16.751  5896  5915 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 11:18:16.751  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 11:18:16.752  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.753  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.754  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:18:16.754  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.754  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.754  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:18:16.754  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:18:16.754  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 11:18:16.754  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.754  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 11:18:16.754  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 11:18:16.754  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.754  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.754  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.754  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:18:16.755  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.755  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.757  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 11:18:16.757  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:18:16.757  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:18:16.757  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.757  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.757  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 11:18:16.757  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74abe1 removed from the list
11-23 11:18:16.758  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.758  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.758  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.758  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f11ed06 removed from the list
11-23 11:18:16.758  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:18:16.758  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.758  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.758  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.759  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.759  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.759  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.759  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.759  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:18:16.759  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.759  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f11ed06 not in the list
11-23 11:18:16.759  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.759  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.760  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.760  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.760  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.760  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:18:16.760  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.760  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.760  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@497e9f4 removed from the list
11-23 11:18:16.760  5896  5912 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 11:18:16.760  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 11:18:16.760  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.760  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.761  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.761  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97defc7 removed from the list
11-23 11:18:16.761  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.761  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1df619 added. We now have 3 listener(s)
11-23 11:18:16.762  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:18:16.763  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.763  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.763  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 11:18:16.763  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41396de added. We now have 4 listener(s)
11-23 11:18:16.763  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.764  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 11:18:16.764  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.765  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20310bf added. We now have 4 listener(s)
11-23 11:18:16.766  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:18:16.766  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.766  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.766  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:16.766  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d22838c added. We now have 5 listener(s)
11-23 11:18:16.766  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.766  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:18:16.767  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:18:16.767  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 11:18:16.767  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 11:18:16.767  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.767  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 11:18:16.767  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 11:18:16.767  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 11:18:16.768  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 11:18:16.769  5896  5915 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:18:16.772  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 11:18:16.772  5650  5696 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 11:18:16.772  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 11:18:16.774  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 11:18:16.774  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.775  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.775  5896  5912 E BtGatt.ContextMap: Context not found for ID 5
11-23 11:18:16.776  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 11:18:16.776  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 11:18:16.776  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 11:18:16.776  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 11:18:16.781  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 11:18:16.781  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.781  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 11:18:16.781  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.781  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 11:18:16.781  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 11:18:16.781  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 11:18:16.781  5896  5915 D BtGatt.ScanManager: stopping BLe Batch
11-23 11:18:16.781  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.782  5650  5696 D BluetoothAdapter: STATE_ON
,11-23 11:18:16.784  3568  5978 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-23 11:18:16.786  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 11:18:16.786  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.786  5896  5915 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 11:18:16.786  3568  5978 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-23 11:18:16.790  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 11:18:16.791  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:18:16.793  5896  5907 D BtGatt.GattService: registerClient() - UUID=f185da19-7d93-405c-8334-ca88c1aba0eb
,11-23 11:18:16.793  5896  5912 D BtGatt.GattService: onClientRegistered() - UUID=f185da19-7d93-405c-8334-ca88c1aba0eb, clientIf=5
11-23 11:18:16.793  5650  5661 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 11:18:16.793  5896  5936 D BtGatt.GattService: start scan with filters
,11-23 11:18:16.795  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 11:18:16.795  5896  5915 D BtGatt.ScanManager: handling starting scan
11-23 11:18:16.796  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.796  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 11:18:16.796  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.796  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 11:18:16.796  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 11:18:16.796  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.796  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 11:18:16.796  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 11:18:16.796  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.796  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.796  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.796  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.797  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 11:18:16.797  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.799  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.799  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:18:16.799  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.799  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.799  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.799  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:18:16.799  5650  5696 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 11:18:16.799  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:18:16.800  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:18:16.800  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 11:18:16.800  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.800  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.800  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:18:16.800  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.800  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.800  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1df619 removed from the list
11-23 11:18:16.800  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.800  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41396de removed from the list
,11-23 11:18:16.800  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:18:16.800  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.800  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:18:16.800  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.800  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.800  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 11:18:16.800  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.800  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 11:18:16.800  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.800  5896  5912 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 11:18:16.801  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.801  5896  5915 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 11:18:16.801  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.801  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.801  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.801  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.801  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.801  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.801  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.801  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:18:16.801  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:18:16.801  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.801  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41396de not in the list
11-23 11:18:16.801  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 11:18:16.801  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.802  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 11:18:16.802  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 11:18:16.802  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.802  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.802  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.802  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 11:18:16.802  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.802  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:18:16.803  5896  5906 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-23 11:18:16.803  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 11:18:16.804  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:18:16.805  5896  5931 D BtGatt.GattService: stopScan() - queue size =1
11-23 11:18:16.806  5896  5907 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 11:18:16.806  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 11:18:16.806  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.806  5896  5915 D BtGatt.ScanManager: Starting BLE batch scan
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.806  5896  5915 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.806  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 11:18:16.807  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 11:18:16.809  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 11:18:16.809  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.812  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.812  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 11:18:16.812  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.812  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.813  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:18:16.813  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.813  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.813  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d22838c removed from the list
11-23 11:18:16.813  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.813  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.813  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.813  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20310bf removed from the list
11-23 11:18:16.813  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:18:16.813  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:18:16.813  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 11:18:16.813  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.813  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 11:18:16.813  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef4f51 added. We now have 3 listener(s)
11-23 11:18:16.813  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 11:18:16.814  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 11:18:16.814  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.814  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.814  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.814  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:18:16.814  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.814  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.814  3568  5980 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-23 11:18:16.815  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 11:18:16.815  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.815  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.815  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:16.815  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b5a3b6 added. We now have 4 listener(s)
11-23 11:18:16.815  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.815  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 11:18:16.816  5896  5912 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 11:18:16.816  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.817  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.817  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.817  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.819  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.819  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc58b7 added. We now have 4 listener(s)
11-23 11:18:16.821  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:18:16.821  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.821  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.821  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 11:18:16.821  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@303b824 added. We now have 5 listener(s)
,11-23 11:18:16.821  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.821  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:18:16.821  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 11:18:16.822  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.822  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 11:18:16.822  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 11:18:16.822  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 11:18:16.822  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 11:18:16.824  5896  5915 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:18:16.824  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 11:18:16.828  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 11:18:16.828  5650  5696 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 11:18:16.828  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 11:18:16.829  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 11:18:16.829  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:18:16.829  5896  5912 E BtGatt.ContextMap: Context not found for ID 5
,11-23 11:18:16.832  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.833  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 11:18:16.833  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 11:18:16.833  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 11:18:16.833  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 11:18:16.835  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 11:18:16.835  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.835  5896  5915 D BtGatt.ScanManager: stopping BLe Batch
,11-23 11:18:16.836  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.836  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 11:18:16.837  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 11:18:16.837  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 11:18:16.837  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 11:18:16.837  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.837  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:18:16.839  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 11:18:16.839  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.839  5896  5915 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:18:16.840  5896  5907 D BtGatt.GattService: registerClient() - UUID=f55cbd64-cf8b-431f-a61f-f2fa2a1edac1
,11-23 11:18:16.841  5896  5912 D BtGatt.GattService: onClientRegistered() - UUID=f55cbd64-cf8b-431f-a61f-f2fa2a1edac1, clientIf=5
11-23 11:18:16.841  5650  5784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 11:18:16.841  5896  5932 D BtGatt.GattService: start scan with filters
,11-23 11:18:16.842  5046  5973 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-23 11:18:16.843  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 11:18:16.844  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:18:16.845  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 11:18:16.845  5896  5915 D BtGatt.ScanManager: handling starting scan
11-23 11:18:16.845  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.845  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 11:18:16.845  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.845  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 11:18:16.845  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 11:18:16.845  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.845  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 11:18:16.845  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 11:18:16.845  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.845  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.845  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.845  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.846  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 11:18:16.846  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.848  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.848  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:18:16.848  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.848  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.848  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.850  5896  5912 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 11:18:16.850  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.850  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:18:16.850  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:18:16.850  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:18:16.850  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.850  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.850  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:18:16.850  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 11:18:16.850  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.850  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef4f51 removed from the list
11-23 11:18:16.851  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.851  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b5a3b6 removed from the list
11-23 11:18:16.851  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:18:16.851  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.851  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:18:16.851  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.851  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-23 11:18:16.851  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 11:18:16.851  5650  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 11:18:16.851  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 11:18:16.851  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.851  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.851  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.851  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.851  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 11:18:16.851  5896  5915 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.852  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.852  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:18:16.852  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.852  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b5a3b6 not in the list
11-23 11:18:16.852  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.852  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.853  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.853  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 11:18:16.853  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.853  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:18:16.853  5896  5931 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 11:18:16.853  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 11:18:16.854  5650  5696 D BluetoothAdapter: STATE_ON
11-23 11:18:16.854  5896  5936 D BtGatt.GattService: stopScan() - queue size =1
11-23 11:18:16.855  5896  5906 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 11:18:16.855  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-23 11:18:16.855  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.855  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 11:18:16.855  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.856  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 11:18:16.856  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 11:18:16.856  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 11:18:16.856  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 11:18:16.856  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.857  5896  5915 D BtGatt.ScanManager: Starting BLE batch scan
11-23 11:18:16.857  5896  5915 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 11:18:16.857  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.857  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.857  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:18:16.858  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.858  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.858  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 11:18:16.858  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.858  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.858  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:18:16.858  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@303b824 removed from the list
11-23 11:18:16.858  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.858  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 11:18:16.858  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.858  5650  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 11:18:16.858  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 11:18:16.858  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.858  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc58b7 removed from the list
11-23 11:18:16.858  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 11:18:16.858  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 11:18:16.858  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.858  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.858  5650  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.858  5650  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 11:18:16.858  5650  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.858  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 11:18:16.858  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.859  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfb9789 added. We now have 3 listener(s)
11-23 11:18:16.860  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.860  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:18:16.860  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.860  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.860  5650  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 11:18:16.860  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.860  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 11:18:16.860  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f41738e added. We now have 4 listener(s)
11-23 11:18:16.860  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.860  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 11:18:16.861  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 11:18:16.861  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de7a7af added. We now have 4 listener(s)
11-23 11:18:16.862  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 11:18:16.862  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 11:18:16.862  5650  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 11:18:16.863  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 11:18:16.863  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113e7bc added. We now have 5 listener(s)
11-23 11:18:16.863  5650  5696 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 11:18:16.863  5650  5696 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 11:18:16.863  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:18:16.863  5650  5696 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 11:18:16.863  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.863  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.863  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.863  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfb9789 removed from the list
,11-23 11:18:16.864  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.864  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f41738e removed from the list
11-23 11:18:16.864  5650  5696 D io.jxcore.node.ConnectivityMonitor: stop
11-23 11:18:16.864  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.864  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.864  5896  5912 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 11:18:16.864  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.865  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.865  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.865  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.865  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.866  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 11:18:16.866  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.866  5650  5696 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f41738e not in the list
11-23 11:18:16.866  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.866  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.867  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.867  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.867  5650  5696 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 11:18:16.867  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 11:18:16.867  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 11:18:16.868  5650  5696 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 11:18:16.868  5650  5696 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113e7bc removed from the list
11-23 11:18:16.868  5650  5696 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 11:18:16.868  5650  5696 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 11:18:16.868  5650  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 11:18:16.868  5650  5696 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de7a7af removed from the list
11-23 11:18:16.869  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 11:18:16.869  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 11:18:16.869  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-23 11:18:16.869  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 11:18:16.869  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 11:18:16.870  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 11:18:16.870  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 11:18:16.870  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.871  5896  5915 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:18:16.876  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 11:18:16.876  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.876  5896  5912 E BtGatt.ContextMap: Context not found for ID 5
,11-23 11:18:16.883  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 11:18:16.883  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.884  5896  5915 D BtGatt.ScanManager: stopping BLe Batch
,11-23 11:18:16.888  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 11:18:16.888  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 11:18:16.888  5896  5915 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 11:18:16.892  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 11:18:16.892  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 11:18:17.188  3568  5978 W Uploader:  no longer exists, so no auth token.
,11-23 11:18:17.196  3568  5982 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 11:18:17.255  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 11:18:17.315  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 11:18:17.359  5650  5650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 11:18:17.383   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 11:18:17.419  3568  5980 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 11:18:17.507  3568  5978 W Uploader:  no longer exists, so no auth token.
,11-23 11:18:17.519  3568  5982 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 11:18:17.550   932  2962 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 11:18:17.613  3568  5980 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 11:18:19.027  5650  5989 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 11:18:19.027  5650  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:19.291   932  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 11:18:19.832  5650  5989 W !!      : call onHalfStreamCopied
,11-23 11:18:19.832  5650  5989 I testCopyDataAndClose: closing input stream
,11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 11:18:20.604  5650  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 11:18:24.431  5650  5990 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:24.431  5650  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:24.507   932  2962 D ConnectivityService: handlePromptUnvalidated 101
,11-23 11:18:26.430  5650  5696 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-23 11:18:26.430  5650  5696 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:26.431  5650  5696 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-23 11:18:26.437  5650  5990 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 11:18:26.437  5650  5990 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:26.437  5650  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,11-23 11:18:26.606  5650  5991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 11:18:26.606  5650  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:27.604   932  2960 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 11:18:28.230  5650  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 11:18:31.965  5650  5992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:31.965  5650  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 11:18:31.965  5650  5992 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:31.965  5650  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:31.966  5650  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 11:18:31.968  5650  5696 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-23 11:18:31.971  5650  5993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:31.971  5650  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 11:18:31.971  5650  5993 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-23 11:18:31.972  5650  5993 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:31.972  5650  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 11:18:31.972  5650  5993 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-23 11:18:31.972  5650  5993 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 11:18:31.972  5650  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 11:18:31.977  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 11:18:31.977  5650  5696 I jxcore-log: 
,11-23 11:18:31.978  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 11:18:31.978  5650  5696 I jxcore-log: 
11-23 11:18:31.978  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 11:18:31.978  5650  5696 I jxcore-log: 
11-23 11:18:31.978  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 11:18:31.978  5650  5696 I jxcore-log: 
11-23 11:18:31.979  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG UnitTest_app: 'Total duration:  90898'
11-23 11:18:31.979  5650  5696 I jxcore-log: 
11-23 11:18:31.981  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 11:18:31.981  5650  5696 I jxcore-log: 
,11-23 11:18:31.985  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 11:18:31.985  5650  5696 I jxcore-log: 
,11-23 11:18:31.986  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 11:18:31.986  5650  5696 I jxcore-log: 
11-23 11:18:31.987  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 11:18:31.987  5650  5696 I jxcore-log: 
11-23 11:18:31.987  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 11:18:31.987  5650  5696 I jxcore-log: 
11-23 11:18:31.987  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.987  5650  5696 I jxcore-log: 
11-23 11:18:31.987  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 11:18:31.987  5650  5696 I jxcore-log: 
,11-23 11:18:31.988  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.988  5650  5696 I jxcore-log: 
11-23 11:18:31.988  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 11:18:31.988  5650  5696 I jxcore-log: 
11-23 11:18:31.989  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 11:18:31.989  5650  5696 I jxcore-log: 
,11-23 11:18:31.989  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 11:18:31.989  5650  5696 I jxcore-log: 
11-23 11:18:31.989  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 11:18:31.989  5650  5696 I jxcore-log: 
11-23 11:18:31.989  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.989  5650  5696 I jxcore-log: 
11-23 11:18:31.989  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 11:18:31.989  5650  5696 I jxcore-log: 
11-23 11:18:31.990  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.990  5650  5696 I jxcore-log: 
11-23 11:18:31.990  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 11:18:31.990  5650  5696 I jxcore-log: 
11-23 11:18:31.990  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.990  5650  5696 I jxcore-log: 
,11-23 11:18:31.990  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 11:18:31.990  5650  5696 I jxcore-log: 
11-23 11:18:31.990  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 11:18:31.990  5650  5696 I jxcore-log: 
11-23 11:18:31.991  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 11:18:31.991  5650  5696 I jxcore-log: 
11-23 11:18:31.991  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 11:18:31.991  5650  5696 I jxcore-log: 
11-23 11:18:31.991  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 11:18:31.991  5650  5696 I jxcore-log: 
,11-23 11:18:31.992  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 11:18:31.992  5650  5696 I jxcore-log: 
11-23 11:18:31.992  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 11:18:31.992  5650  5696 I jxcore-log: 
11-23 11:18:31.992  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 11:18:31.992  5650  5696 I jxcore-log: 
11-23 11:18:31.994  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 11:18:31.994  5650  5696 I jxcore-log: 
11-23 11:18:31.994  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 11:18:31.994  5650  5696 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-23 11:18:31.994  5650  5696 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 11:18:31.994  5650  5696 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 11:18:31.994  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 11:18:31.994  5650  5696 I jxcore-log: 
11-23 11:18:31.995  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.995  5650  5696 I jxcore-log: 
11-23 11:18:31.995  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 11:18:31.995  5650  5696 I jxcore-log: 
11-23 11:18:31.995  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.995  5650  5696 I jxcore-log: 
11-23 11:18:31.995  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 11:18:31.995  5650  5696 I jxcore-log: 
,11-23 11:18:31.995  5650  5696 I jxcore-log: 2016-11-23 16:18:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 11:18:31.995  5650  5696 I jxcore-log: 
,11-23 11:18:32.001  5650  5696 I jxcore-log: 2016-11-23 16:18:32 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 11:18:32.001  5650  5696 I jxcore-log: 
,11-23 11:18:32.001  5650  5696 I jxcore-log: 2016-11-23 16:18:32 - WARN testUtils: 'myNameCallback not set!'
11-23 11:18:32.001  5650  5696 I jxcore-log: 
,11-23 11:18:32.009  5650  5650 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 11:18:34.085  5650  5696 I jxcore-log: 2016-11-23 16:18:34 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 11:18:34.085  5650  5696 I jxcore-log: 
,11-23 11:18:34.086  5650  5696 I jxcore-log: 2016-11-23 16:18:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 11:18:34.086  5650  5696 I jxcore-log: 
,11-23 11:18:34.442  5650  5696 I jxcore-log: 2016-11-23 16:18:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 11:18:34.442  5650  5696 I jxcore-log: 
,11-23 11:18:34.453  5650  5696 I jxcore-log: 2016-11-23 16:18:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 11:18:34.453  5650  5696 I jxcore-log: 
,11-23 11:18:35.560  5650  5696 I jxcore-log: 2016-11-23 16:18:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 11:18:35.560  5650  5696 I jxcore-log: 
,11-23 11:18:35.748  5650  5696 I jxcore-log: 2016-11-23 16:18:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 11:18:35.748  5650  5696 I jxcore-log: 
,11-23 11:18:35.753  5650  5696 I jxcore-log: 2016-11-23 16:18:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 11:18:35.753  5650  5696 I jxcore-log: 
,11-23 11:18:35.758  5650  5696 I jxcore-log: 2016-11-23 16:18:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 11:18:35.758  5650  5696 I jxcore-log: 
,11-23 11:18:36.241  5650  5696 I jxcore-log: 2016-11-23 16:18:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 11:18:36.241  5650  5696 I jxcore-log: 
,11-23 11:18:36.286  5650  5696 I jxcore-log: 2016-11-23 16:18:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 11:18:36.286  5650  5696 I jxcore-log: 
,11-23 11:18:36.299  5650  5696 I jxcore-log: 2016-11-23 16:18:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 11:18:36.299  5650  5696 I jxcore-log: 
,11-23 11:18:36.303  5650  5696 I jxcore-log: 2016-11-23 16:18:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 11:18:36.303  5650  5696 I jxcore-log: 
,11-23 11:18:36.577  5650  5696 I jxcore-log: 2016-11-23 16:18:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 11:18:36.577  5650  5696 I jxcore-log: 
,11-23 11:18:36.703  5650  5696 I jxcore-log: 2016-11-23 16:18:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 11:18:36.703  5650  5696 I jxcore-log: 
,11-23 11:18:37.078  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 11:18:37.078  5650  5696 I jxcore-log: 
,11-23 11:18:37.086  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 11:18:37.086  5650  5696 I jxcore-log: 
,11-23 11:18:37.090  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 11:18:37.090  5650  5696 I jxcore-log: 
,11-23 11:18:37.096  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 11:18:37.096  5650  5696 I jxcore-log: 
,11-23 11:18:37.101  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 11:18:37.101  5650  5696 I jxcore-log: 
,11-23 11:18:37.130  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 11:18:37.130  5650  5696 I jxcore-log: 
,11-23 11:18:37.164  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 11:18:37.164  5650  5696 I jxcore-log: 
,11-23 11:18:37.171  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 11:18:37.171  5650  5696 I jxcore-log: 
,11-23 11:18:37.178  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 11:18:37.178  5650  5696 I jxcore-log: 
,11-23 11:18:37.193  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 11:18:37.193  5650  5696 I jxcore-log: 
,11-23 11:18:37.209  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 11:18:37.209  5650  5696 I jxcore-log: 
,11-23 11:18:37.215  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 11:18:37.215  5650  5696 I jxcore-log: 
,11-23 11:18:37.220  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 11:18:37.220  5650  5696 I jxcore-log: 
,11-23 11:18:37.233  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 11:18:37.233  5650  5696 I jxcore-log: 
,11-23 11:18:37.250  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 11:18:37.250  5650  5696 I jxcore-log: 
,11-23 11:18:37.265  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 11:18:37.265  5650  5696 I jxcore-log: 
,11-23 11:18:37.275  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 11:18:37.275  5650  5696 I jxcore-log: 
,11-23 11:18:37.288  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 11:18:37.288  5650  5696 I jxcore-log: 
,11-23 11:18:37.298  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 11:18:37.298  5650  5696 I jxcore-log: 
,11-23 11:18:37.311  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 11:18:37.311  5650  5696 I jxcore-log: 
,11-23 11:18:37.321  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 11:18:37.321  5650  5696 I jxcore-log: 
,11-23 11:18:37.328  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 11:18:37.328  5650  5696 I jxcore-log: 
,11-23 11:18:37.350  5650  5696 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 11:18:37.351  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 11:18:37.351  5650  5696 I jxcore-log: 
,11-23 11:18:37.383  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 11:18:37.383  5650  5696 I jxcore-log: 
,11-23 11:18:37.383   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:37.646  5650  5696 I jxcore-log: 2016-11-23 16:18:37 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 11:18:37.646  5650  5696 I jxcore-log: 
,11-23 11:18:38.384   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:39.386   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:40.165  5950  5950 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 11:18:40.387   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:41.388   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:18:42.388   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 11:18:56.438   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:19:07.389   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 11:19:07.390   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 11:19:17.391   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:18.393   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:19.394   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:20.395   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:21.396   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:22.397   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 11:19:27.398   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:28.400   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:29.402   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:30.403   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:31.404   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:32.405   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 11:19:36.443   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:19:42.407   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:43.408   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:44.410   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:45.411   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:46.412   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:19:47.413   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 11:19:56.444   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:20:02.415   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:03.416   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:04.417   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:05.419   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:06.420   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:07.420   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 11:20:27.422   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:28.423   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:29.424   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:30.425   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:31.426   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:20:32.427   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 11:20:36.449   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:20:56.450   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:20:57.427   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 11:20:57.428   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 11:21:12.429   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:13.430   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:14.431   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:15.433   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:16.434   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:16.452   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:21:17.434   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 11:21:22.436   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:23.437   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:24.439   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:25.440   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:26.442   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:27.442   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 11:21:37.444   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:38.445   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:39.447   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:40.448   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:41.449   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:42.450   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 11:21:56.453   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:21:57.451   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:58.452   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:21:59.453   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:00.454   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:01.455   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:02.456   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 11:22:16.456   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:22:22.458   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:23.459   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:24.461   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:25.462   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:26.463   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:22:27.464   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 11:22:36.460   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:22:52.465   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 11:22:52.465   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 11:22:56.462   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:23:12.466   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:23:13.468   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:23:14.469   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:23:15.470   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:23:16.464   932  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 11:23:16.471   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 11:23:17.472   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 11:23:19.288  5650  5696 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 11:23:19.288  5650  5696 I jxcore-log: 
,11-23 11:23:19.461  5650  5696 I jxcore-log: 2016-11-23 16:23:19 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 11:23:19.461  5650  5696 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 11:23:19.461  5650  5696 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 11:23:19.461  5650  5696 I jxcore-log: emit@events.js:82:1
11-23 11:23:19.461  5650  5696 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 11:23:19.461  5650  5696 I jxcore-log: emit@events.js:82:1''
11-23 11:23:19.461  5650  5696 I jxcore-log: 
,11-23 11:23:19.462  5650  5696 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedClient: 'test client failed'
11-23 11:23:19.462  5650  5696 I jxcore-log: 
,11-23 11:23:19.474  5650  5696 I jxcore-log: 2016-11-23 16:23:19 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 11:23:19.474  5650  5696 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 11:23:19.474  5650  5696 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 11:23:19.474  5650  5696 I jxcore-log: emit@events.js:82:1
11-23 11:23:19.474  5650  5696 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 11:23:19.474  5650  5696 I jxcore-log: emit@events.js:82:1''
11-23 11:23:19.474  5650  5696 I jxcore-log: 
,11-23 11:23:19.475  5650  5696 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedClient: 'test client failed'
11-23 11:23:19.475  5650  5696 I jxcore-log: 
,11-23 11:23:19.479  5650  5696 I jxcore-log: 2016-11-23 16:23:19 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 11:23:19.479  5650  5696 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 11:23:19.479  5650  5696 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 11:23:19.479  5650  5696 I jxcore-log: emit@events.js:82:1
11-23 11:23:19.479  5650  5696 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 11:23:19.479  5650  5696 I jxcore-log: emit@events.js:82:1''
11-23 11:23:19.479  5650  5696 I jxcore-log: 
,11-23 11:23:19.480  5650  5696 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 11:23:19.480  5650  5696 I jxcore-log: 
,11-23 11:23:20.091  6005  6005 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 11:23:20.114  6005  6005 D AndroidRuntime: CheckJNI is OFF
,11-23 11:23:20.142  6005  6005 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 11:23:20.172  6005  6005 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 11:23:20.187  6005  6005 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 11:23:20.195   932   945 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 11:23:20.195   932   945 I ActivityManager: Killing 5650:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 11:23:20.298   932   943 D GraphicsStats: Buffer count: 2
,11-23 11:23:20.298   932   943 I WindowState: WIN DEATH: Window{9c7f80c u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-23 11:23:20.299   932  2961 D WifiService: Client connection lost with reason: 4
,11-23 11:23:20.331   932   945 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-23 11:23:20.333   932   945 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-23 11:23:20.334   932   945 E ActivityManager: Failure starting process com.test.thalitest
11-23 11:23:20.334   932   945 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-23 11:23:20.334   932   945 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:23:20.334   932   945 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.334   932   945 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 11:23:20.334   932   945 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-23 11:23:20.335   932   955 I art     : Starting a blocking GC Explicit
,11-23 11:23:20.336   932   945 I ActivityManager:   Force finishing activity ActivityRecord{f719f80 u0 com.test.thalitest/.MainActivity t10}
,11-23 11:23:20.341   932  3825 W ActivityManager: Spurious death for ProcessRecord{ed59107 0:com.test.thalitest/u0a77}, curProc for 5650: null
,11-23 11:23:20.347   932   950 W WindowManager: Attempted to add application window with unknown token Token{efa19b9 ActivityRecord{f719f80 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-23 11:23:20.347   932   950 W WindowManager: Token{efa19b9 ActivityRecord{f719f80 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{efa19b9 ActivityRecord{f719f80 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-23 11:23:20.347   932   950 W WindowManager: view not successfully added to wm, removing view
11-23 11:23:20.348   932   950 W WindowManager: Exception when adding starting window
11-23 11:23:20.348   932   950 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a517d1e V.E...... R.....ID 0,0-0,0} not attached to window manager
11-23 11:23:20.348   932   950 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-23 11:23:20.348   932   950 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-23 11:23:20.348   932   950 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-23 11:23:20.348   932   950 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-23 11:23:20.348   932   950 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-23 11:23:20.348   932   950 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:23:20.348   932   950 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.348   932   950 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 11:23:20.348   932   950 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-23 11:23:20.436   932   955 I art     : Explicit concurrent mark sweep GC freed 134455(9MB) AllocSpace objects, 90(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.620ms total 101.188ms
,11-23 11:23:20.460   932   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 11:23:20.463  6005  6005 I art     : System.exit called, status: 0
11-23 11:23:20.463  6005  6005 I AndroidRuntime: VM exiting with result code 0.
,11-23 11:23:20.477   932   955 I ActivityManager: Start proc 6016:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-23 11:23:20.477   932   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 11:23:20.482   932   945 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-23 11:23:20.485  5896  5896 D BluetoothMapAppObserver: onReceive
,11-23 11:23:20.485  5896  5896 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-23 11:23:20.488  4105  4183 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-23 11:23:20.492  3654  3654 I Keyboard.Facilitator: resetDictionaries() : en_US
11-23 11:23:20.497   932  2926 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-23 11:23:20.511  3654  6028 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 11:23:20.526  3654  6028 I Decoder : createOrResetDecoder
,11-23 11:23:20.541  3767  3767 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 11:23:20.559  3380  6031 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 11:23:20.570  3568  3568 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-23 11:23:20.570  3568  3568 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-23 11:23:20.576   446   446 W kworker/7:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 11:23:20.579   446   446 W kworker/7:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 11:23:20.589   446   446 W kworker/7:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 11:23:20.585   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-23 11:23:20.588   932   944 E PackageManager: Failed to write settings, restoring backup
11-23 11:23:20.588   932   944 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-23 11:23:20.588   932   944 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-23 11:23:20.588   932   944 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-23 11:23:20.588   932   944 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-23 11:23:20.588   932   944 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
11-23 11:23:20.588   932   944 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
11-23 11:23:20.588   932   944 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:236)
11-23 11:23:20.588   932   944 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:468)
11-23 11:23:20.588   932   944 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4644)
11-23 11:23:20.588   932   944 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-23 11:23:20.588   932   944 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-23 11:23:20.588   932   944 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:23:20.588   932   944 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.588   932   944 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 11:23:20.588   932   944 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-23 11:23:20.588   932   944 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-23 11:23:20.588   932   944 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-23 11:23:20.588   932   944 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-23 11:23:20.588   932   944 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-23 11:23:20.588   932   944 E PackageManager: 	... 12 more
11-23 11:23:20.590  3782  3936 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-23 11:23:20.594  3568  3568 I ConfigService: onCreate
11-23 11:23:20.600  3897  6036 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-23 11:23:20.600  3897  6036 D AccountUtils: Clearing selected account for com.test.thalitest
,11-23 11:23:20.607   932  3669 I ActivityManager: Start proc 6039:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-23 11:23:20.608  3782  3936 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-23 11:23:20.608  3782  3936 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3782
11-23 11:23:20.608  3782  3936 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.608  3782  3936 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 11:23:20.615   932  6050 E DropBoxManagerService: Can't write: system_app_crash
11-23 11:23:20.615   932  6050 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 11:23:20.615   932  6050 E DropBoxManagerService: 	... 5 more
,11-23 11:23:20.617   932  3140 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 11:23:20.621  3782  3936 I Process : Sending signal. PID: 3782 SIG: 9
,11-23 11:23:20.627  3654  6028 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-23 11:23:20.654  3897  6036 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-23 11:23:20.746   932  3840 I WindowState: WIN DEATH: Window{8e4b1c2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-23 11:23:20.746   932  3825 D GraphicsStats: Buffer count: 1
,11-23 11:23:20.752   932  3146 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3782) has died
,11-23 11:23:20.759   932  3146 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-23 11:23:20.762   932  3146 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-23 11:23:20.778   932   945 I ActivityManager: Start proc 6057:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 11:23:20.825  6057  6057 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:23:20.825  6057  6057 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 11:23:20.826  6057  6057 D AndroidRuntime: Shutting down VM
,11-23 11:23:20.832  6057  6057 E AndroidRuntime: FATAL EXCEPTION: main
11-23 11:23:20.832  6057  6057 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6057
11-23 11:23:20.832  6057  6057 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-23 11:23:20.832  6057  6057 E AndroidRuntime: 	... 10 more
11-23 11:23:20.835   932   942 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 11:23:20.835  6057  6057 I Process : Sending signal. PID: 6057 SIG: 9
,11-23 11:23:20.850   932  3146 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6057) has died
,11-23 11:23:20.852   932  3146 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-23 11:23:20.866   932   945 I ActivityManager: Start proc 6071:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 11:23:20.918  6071  6071 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:23:20.918  6071  6071 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 11:23:20.918  6071  6071 D AndroidRuntime: Shutting down VM
,11-23 11:23:20.926  6071  6071 E AndroidRuntime: FATAL EXCEPTION: main
11-23 11:23:20.926  6071  6071 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6071
11-23 11:23:20.926  6071  6071 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-23 11:23:20.926  6071  6071 E AndroidRuntime: 	... 10 more
11-23 11:23:20.928   932  3669 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-23 11:23:20.929  6071  6071 I Process : Sending signal. PID: 6071 SIG: 9
,11-23 11:23:20.945   932  3395 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6071) has died
,11-23 11:23:20.947   932  3395 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-23 11:23:20.964   932   945 I ActivityManager: Start proc 6084:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 11:23:20.965   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
