#### Test 863731520a9f9e4_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-26 11:23:09.416  5542  5587 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
09-26 11:23:09.462  3828  4910 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
09-26 11:23:09.466  3828  3828 I ConfigFetchService: fetch service done; releasing wakelock
09-26 11:23:09.467  3828  3828 I ConfigFetchService: stopping self
09-26 11:23:09.533   544   544 I ServiceManager: Waiting for service AtCmdFwd...
09-26 11:23:09.549  3828  4910 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
09-26 11:23:09.561  5542  5587 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
09-26 11:23:09.592  5542  5587 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-26 11:23:10.535   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:11.492   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
09-26 11:23:11.520  5599  5599 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 11:23:11.525  5599  5599 D AndroidRuntime: CheckJNI is OFF
09-26 11:23:11.536   544   544 I ServiceManager: Waiting for service AtCmdFwd...
09-26 11:23:11.553  5599  5599 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 11:23:11.598  5599  5599 I Radio-JNI: register_android_hardware_Radio DONE
09-26 11:23:11.613  5599  5599 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-26 11:23:11.627   929  3536 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-26 11:23:11.680   929  3536 I ActivityManager: Start proc 5608:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-26 11:23:11.699  5599  5599 D AndroidRuntime: Shutting down VM
,09-26 11:23:12.026   929   939 I WindowManager: Screenshot max retries 4 of Token{948d459 ActivityRecord{37220a0 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{35f63b8 u0 Starting com.test.thalitest} drawState=4
,09-26 11:23:12.088  5608  5608 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-26 11:23:12.111  5608  5608 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-26 11:23:12.189  5608  5608 I LibraryLoader: Time to load native libraries: 74 ms (timestamps 1774-1848)
,09-26 11:23:12.189  5608  5608 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-26 11:23:12.223  5608  5608 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b4d5650}
09-26 11:23:12.223  5608  5608 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-26 11:23:12.223  5608  5608 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-26 11:23:12.226  5608  5608 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-26 11:23:12.227  5608  5608 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-26 11:23:12.273  5608  5608 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-26 11:23:12.284  5608  5608 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 11:23:12.284  5608  5608 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 11:23:12.284  5608  5608 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-26 11:23:12.284  5608  5608 I Adreno  : Build Date                       : 12/06/15
09-26 11:23:12.284  5608  5608 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-26 11:23:12.284  5608  5608 I Adreno  : Local Branch                     : mybranch17112971
09-26 11:23:12.284  5608  5608 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-26 11:23:12.284  5608  5608 I Adreno  : Remote Branch                    : NONE
09-26 11:23:12.284  5608  5608 I Adreno  : Reconstruct Branch               : NOTHING
,09-26 11:23:12.329   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21ef1d0:true
,09-26 11:23:12.366   763   763 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23310]" dev="sockfs" ino=23310 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 11:23:12.366   763   763 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[23310]" dev="sockfs" ino=23310 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 11:23:12.379  5608  5608 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-26 11:23:12.387  5608  5608 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-26 11:23:12.410   764   764 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 11:23:12.410   764   764 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-26 11:23:12.413  5608  5645 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-26 11:23:12.416  3120  3120 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[23321]" dev="sockfs" ino=23321 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-26 11:23:12.416  3120  3120 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[23321]" dev="sockfs" ino=23321 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-26 11:23:12.421  5608  5632 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-26 11:23:12.442  5608  5645 I OpenGLRenderer: Initialized EGL, version 1.4
,09-26 11:23:12.510   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +482ms (total +860ms)
,09-26 11:23:12.537   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:12.559  5608  5608 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5608
,09-26 11:23:12.668  5608  5608 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-26 11:23:12.961  5608  5647 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -580912848
,09-26 11:23:12.993  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-26 11:23:12.993  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-26 11:23:12.993  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-26 11:23:12.993  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-26 11:23:12.993  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-26 11:23:12.993  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8385541 added. We now have 1 listener(s)
,09-26 11:23:13.005  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-26 11:23:13.007  5608  5647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 11:23:13.008  5608  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 11:23:13.009  5608  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-26 11:23:13.017  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4047d added. We now have 1 listener(s)
09-26 11:23:13.018  5608  5647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:23:13.025   929  2944 D WifiService: New client listening to asynchronous messages
,09-26 11:23:13.027  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 11:23:13.027  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-26 11:23:13.028  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-26 11:23:13.028  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-26 11:23:13.028  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-26 11:23:13.032  5608  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:23:13.033  5608  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-26 11:23:13.043  5608  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:13.043  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:13.043  5608  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-26 11:23:13.043  5608  5647 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:23:13.044  5608  5647 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-26 11:23:13.210  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:13.215  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:13.218  5608  5608 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-26 11:23:13.386  5608  5654 W jxcore-log: Initializing JXcore engine
09-26 11:23:13.386  5608  5654 W jxcore-log: JXcore engine is ready
,09-26 11:23:13.405  5608  5617 I art     : Background sticky concurrent mark sweep GC freed 85313(8MB) AllocSpace objects, 18(1892KB) LOS objects, 25% free, 24MB/32MB, paused 1.963ms total 106.532ms
,09-26 11:23:13.410  5654  5654 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12629 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-26 11:23:13.410  5654  5654 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13644]" dev="sockfs" ino=13644 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-26 11:23:13.410  5654  5654 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-26 11:23:13.410  5654  5654 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33285]" dev="sockfs" ino=33285 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-26 11:23:13.419  5608  5654 W jxcore-log: Starting JXcore engine
,09-26 11:23:13.469  5608  5654 W jxcore-log: Platform android
09-26 11:23:13.469  5608  5654 W jxcore-log: 
,09-26 11:23:13.469  5608  5654 W jxcore-log: Process ARCH arm
09-26 11:23:13.469  5608  5654 W jxcore-log: 
,09-26 11:23:13.537   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:23:13.566  5608  5654 I jxcore-log: JXcore Cordova bridge is ready!
09-26 11:23:13.566  5608  5654 I jxcore-log: 
,09-26 11:23:13.567  5608  5654 W jxcore-log: JXcore engine is started
,09-26 11:23:13.576  5608  5647 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-26 11:23:13.582  5608  5608 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-26 11:23:14.476  3541  3541 I ConfigService: onDestroy
,09-26 11:23:16.069   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:18.538   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:19.095   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:19.539   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:20.540   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:21.541   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:22.542   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:22.912  5423  5455 D Finsky  : [248] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-26 11:23:22.913  5423  5423 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,09-26 11:23:23.347  5608  5654 I jxcore-log: 2016-09-26 15:23:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-26 11:23:23.347  5608  5654 I jxcore-log: 
,09-26 11:23:23.349  5608  5654 I jxcore-log: 2016-09-26 15:23:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-26 11:23:23.349  5608  5654 I jxcore-log: 
,09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:23.354  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:23:23.355  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 11:23:23.357  5608  5654 I jxcore-log: 2016-09-26 15:23:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-26 11:23:23.357  5608  5654 I jxcore-log: 
,09-26 11:23:23.358  5608  5654 I jxcore-log: 2016-09-26 15:23:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-26 11:23:23.358  5608  5654 I jxcore-log: 
,09-26 11:23:23.543   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:23:23.617  5608  5654 I jxcore-log: 2016-09-26 15:23:23 - DEBUG UnitTest_app: 'Running unit tests'
09-26 11:23:23.617  5608  5654 I jxcore-log: 
,09-26 11:23:23.617  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 11:23:23.617  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad648b added. We now have 2 listener(s)
09-26 11:23:23.618  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 11:23:23.618  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-26 11:23:23.618  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 11:23:23.618  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 11:23:23.618  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f85968 added. We now have 2 listener(s)
09-26 11:23:23.619  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 11:23:23.619  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 11:23:23.621  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:23.624  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:23:23.625  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:23.625  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:23:23.625  5608  5654 D executeNativeTests: Running unit tests
09-26 11:23:23.631  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:23.636  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:23.662  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 11:23:23.662  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 added. We now have 3 listener(s)
,09-26 11:23:23.663  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 11:23:23.663  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 11:23:23.663  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 11:23:23.663  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 11:23:23.663  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 added. We now have 3 listener(s)
09-26 11:23:23.663  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 11:23:23.663  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 11:23:23.665  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:23.667  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:23:23.668  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:23.668  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:23:23.669  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-26 11:23:23.669  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-26 11:23:23.669  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 11:23:23.669  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 11:23:23.670  5608  5654 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-26 11:23:23.670  5608  5654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-26 11:23:23.670  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-26 11:23:23.670  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 11:23:23.670  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 11:23:23.670  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 11:23:23.671  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:23.671  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 11:23:23.671  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:23.671  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 11:23:23.671  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.671  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:23.671  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-26 11:23:23.672  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 removed from the list
09-26 11:23:23.672  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:23.672  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 removed from the list
09-26 11:23:23.673  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:23.673  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 11:23:23.673  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.674  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.674  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.682  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 11:23:23.684  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:23.683  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:23.684  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:23.684  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:23.685  5608  5654 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-26 11:23:23.685  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:23.685  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:23.685  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:23.686  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:23.686  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.686  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.686  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:23.686  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:23.686  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:23.686  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:23.686  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.686  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.686  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.686  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.686  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 11:23:23.686  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:23.686  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:23.686  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 11:23:23.689  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 11:23:23.690  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 11:23:23.690  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-26 11:23:23.690  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 11:23:23.690  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 11:23:23.690  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-26 11:23:23.690  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:23.690  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:23.690  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:23.690  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:23.690  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.690  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.690  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:23.690  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:23.690  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:23.690  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:23.690  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.690  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.690  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:23.690  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:23.691  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:23.691  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:23.691  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:23.691  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:23.691  5608  5654 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 11:23:23.692  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:23.694  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:23.695  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:23.695  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 11:23:23.695  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:23:23.695  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 11:23:23.695  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 11:23:23.695  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:23.695  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:23.699  5608  5654 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:23:23.699  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 11:23:23.700  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:23.704  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:23.704  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:23:23.705  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 11:23:23.705  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:23:23.706  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-26 11:23:23.707  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-26 11:23:23.708  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 11:23:23.708  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 11:23:23.708  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 11:23:23.709  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:23.710  4556  4571 D BtGatt.GattService: registerClient() - UUID=fa68d7ea-091d-4e13-9db7-d48b6f91d6bd
09-26 11:23:23.711  4556  4643 D BtGatt.GattService: onClientRegistered() - UUID=fa68d7ea-091d-4e13-9db7-d48b6f91d6bd, clientIf=5
09-26 11:23:23.712  5608  5619 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 11:23:23.713  4556  4802 D BtGatt.GattService: start scan with filters
09-26 11:23:23.717  4556  4647 D BtGatt.ScanManager: handling starting scan
09-26 11:23:23.717  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 11:23:23.717  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 11:23:23.717  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 11:23:23.717  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 11:23:23.718  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 11:23:23.718  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 11:23:23.719  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 11:23:23.719  4556  4647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:23:23.719  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 11:23:23.720  5608  5654 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 11:23:23.727  4556  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 11:23:23.727  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:23.728  4556  4647 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 11:23:23.734  4556  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 11:23:23.734  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:23.735  4556  4647 D BtGatt.ScanManager: Starting BLE batch scan
09-26 11:23:23.735  4556  4647 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-26 11:23:23.746  4556  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 11:23:23.746  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:23.753  4556  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 11:23:23.753  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:23:24.221  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 11:23:24.221  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:23:24.221  5608  5608 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 11:23:25.273   929  5319 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134931, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:23:28.184   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:28.724  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:28.724  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-26 11:23:28.725  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 11:23:28.725  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:28.725  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 11:23:28.725  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 11:23:28.725  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 11:23:28.725  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 11:23:28.725  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 11:23:28.726  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 11:23:28.726  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 11:23:28.727  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:28.728  4556  4802 D BtGatt.GattService: stopScan() - queue size =1
09-26 11:23:28.729  4556  4570 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 11:23:28.729  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:28.729  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 11:23:28.730  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 11:23:28.730  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 11:23:28.730  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-26 11:23:28.731  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 11:23:28.732  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:28.732  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 11:23:28.732  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 11:23:28.733  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:28.734  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:28.734  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:28.735  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 11:23:28.735  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:23:28.735  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:28.735  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:28.735  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:28.735  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:28.735  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:28.735  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:28.735  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:28.739  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:23:28.739  5608  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 11:23:28.741  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:23:28.742  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 11:23:28.742  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 11:23:28.742  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:28.748  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:28.749  4556  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 11:23:28.749  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:28.749  4556  4647 D BtGatt.ScanManager: stopping BLe Batch
,09-26 11:23:28.753  4556  4556 D BtGatt.ScanManager: awakened up at time 138412
,09-26 11:23:28.754  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:23:28.754  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:28.755  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 11:23:28.759  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:23:28.759  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:28.760  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:28.761  4556  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 11:23:28.761  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:28.761  4556  4647 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 11:23:28.763  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 11:23:28.775  4556  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-26 11:23:28.775  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:28.775  4556  4643 D BtGatt.GattService: current time is 138434783521
09-26 11:23:28.776  4556  4643 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -74, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -72, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 11:23:28.777  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 11:23:28.778  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 11:23:28.778  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-26 11:23:28.779  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 11:23:28.779  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 11:23:28.779  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-26 11:23:29.265  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 11:23:31.216   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:31.492   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:23:33.544   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:33.738  5608  5654 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-26 11:23:33.741  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:33.747  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:23:33.753  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 11:23:33.753  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:23:33.754  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-26 11:23:33.754  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-26 11:23:33.754  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 11:23:33.754  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:33.755  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 11:23:33.759  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:33.761  5608  5654 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:23:33.765  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:33.769  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 11:23:33.769  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 11:23:33.769  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-26 11:23:33.771  5608  5654 D BluetoothAdapter: STATE_ON
,09-26 11:23:33.775  4556  4781 D BtGatt.GattService: registerClient() - UUID=0ac0b5d8-e7d5-4500-9096-31ea2a7ad3ea
,09-26 11:23:33.776  4556  4643 D BtGatt.GattService: onClientRegistered() - UUID=0ac0b5d8-e7d5-4500-9096-31ea2a7ad3ea, clientIf=5
,09-26 11:23:33.777  5608  5619 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 11:23:33.778  4556  4571 D BtGatt.GattService: start scan with filters
,09-26 11:23:33.782  4556  4647 D BtGatt.ScanManager: handling starting scan
09-26 11:23:33.783  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-26 11:23:33.783  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 11:23:33.783  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 11:23:33.783  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 11:23:33.790  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 11:23:33.790  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 11:23:33.790  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 11:23:33.793  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 11:23:33.793   929  3850 I ActivityManager: Killing 5362:com.android.chrome/u0a39 (adj 15): empty #17
,09-26 11:23:33.794  4556  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-26 11:23:33.794  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.795  4556  4647 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 11:23:33.799  5608  5654 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 11:23:33.802  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:33.802  5608  5654 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-26 11:23:33.803  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:33.803  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 11:23:33.803  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:33.803  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 11:23:33.803  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 11:23:33.803  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 11:23:33.803  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 11:23:33.803  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 11:23:33.803  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 11:23:33.803  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 11:23:33.805  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:33.806  4556  4781 D BtGatt.GattService: stopScan() - queue size =1
09-26 11:23:33.807  4556  4571 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 11:23:33.808  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:33.808  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 11:23:33.808  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 11:23:33.808  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 11:23:33.808  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 11:23:33.810  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:23:33.810  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 11:23:33.810  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 11:23:33.810  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 11:23:33.821  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:33.822  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:23:33.822  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:33.822  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:23:33.823  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:33.823  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:33.823  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 11:23:33.823  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:33.823  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:33.823  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:33.823  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:33.823  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:33.826  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:23:33.826  5608  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 11:23:33.826  4556  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 11:23:33.826  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.826  4556  4647 D BtGatt.ScanManager: Starting BLE batch scan
09-26 11:23:33.827  4556  4647 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-26 11:23:33.831  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:23:33.832  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 11:23:33.832  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:23:33.832  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:33.833  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:33.835  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:23:33.835  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:33.835  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:33.839  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:23:33.839  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:33.839  4556  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 11:23:33.839  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.839  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:33.841  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:33.841  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:23:33.841  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:33.843  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 11:23:33.843  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:33.843  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:33.843  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:33.843  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:33.844  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:33.844  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:33.844  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:33.844  5608  5654 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 11:23:33.845  4556  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 11:23:33.845  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.846  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:33.850  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:33.852  4556  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-26 11:23:33.852  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.852  4556  4647 D BtGatt.ScanManager: stopping BLe Batch
09-26 11:23:33.853  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:33.853  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:23:33.853  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:23:33.853  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 11:23:33.853  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 11:23:33.853  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:33.853  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:33.856  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:33.857  5608  5654 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:23:33.859  4556  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 11:23:33.859  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.859  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 11:23:33.859  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:33.859  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 11:23:33.859  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 11:23:33.860  4556  4647 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 11:23:33.860  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:33.864  4556  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-26 11:23:33.864  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.866  4556  4802 D BtGatt.GattService: registerClient() - UUID=f6637980-b3ef-4935-b5c2-e8c6a8ba6332
09-26 11:23:33.866  4556  4643 D BtGatt.GattService: onClientRegistered() - UUID=f6637980-b3ef-4935-b5c2-e8c6a8ba6332, clientIf=5
09-26 11:23:33.866  5608  5619 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 11:23:33.867  4556  4781 D BtGatt.GattService: start scan with filters
,09-26 11:23:33.869  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 11:23:33.869  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 11:23:33.869  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 11:23:33.869  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 11:23:33.869  4556  4647 D BtGatt.ScanManager: handling starting scan
,09-26 11:23:33.874  4556  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 11:23:33.875  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.875  4556  4647 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 11:23:33.875  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 11:23:33.875  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 11:23:33.875  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 11:23:33.876  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 11:23:33.878  5608  5654 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 11:23:33.880  4556  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 11:23:33.880  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:33.880  4556  4647 D BtGatt.ScanManager: Starting BLE batch scan
09-26 11:23:33.880  4556  4647 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 11:23:33.889  4556  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-26 11:23:33.889  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:23:33.894  4556  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 11:23:33.894  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:23:34.239   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:34.376  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 11:23:34.377  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:23:34.377  5608  5608 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 11:23:34.545   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:35.546   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:36.547   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:37.262   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:37.548   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:38.549   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:23:38.879  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:23:38.879  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:38.879  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 11:23:38.880  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:38.880  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-26 11:23:38.880  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 11:23:38.880  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 11:23:38.880  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-26 11:23:38.880  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 11:23:38.881  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 11:23:38.881  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 11:23:38.883  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:38.885  4556  4571 D BtGatt.GattService: stopScan() - queue size =1
09-26 11:23:38.887  4556  4802 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 11:23:38.888  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 11:23:38.888  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 11:23:38.888  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 11:23:38.889  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 11:23:38.889  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-26 11:23:38.892  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 11:23:38.892  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 11:23:38.892  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 11:23:38.893  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:38.893  4556  4556 D BtGatt.ScanManager: awakened up at time 148552
09-26 11:23:38.894  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:38.896  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:23:38.896  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:23:38.896  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:38.899  4556  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 11:23:38.899  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:23:38.900  4556  4647 D BtGatt.ScanManager: stopping BLe Batch
,09-26 11:23:38.902  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:23:38.902  5608  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 11:23:38.906  4556  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 11:23:38.906  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:38.906  4556  4647 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 11:23:38.906  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:23:38.907  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 11:23:38.907  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:23:38.908  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:38.908  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 11:23:38.911  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:23:38.911  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:38.911  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:38.915  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:23:38.915  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:38.915  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:38.918  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 11:23:38.924  4556  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-26 11:23:38.924  4556  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:23:38.924  4556  4643 D BtGatt.GattService: current time is 148583768385
09-26 11:23:38.924  4556  4643 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -88, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -71, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -74, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 11:23:38.925  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 11:23:38.925  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 11:23:38.925  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 11:23:38.925  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 11:23:38.925  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-26 11:23:38.925  4556  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-26 11:23:39.419  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 11:23:39.419  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:39.420  5608  5608 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 11:23:43.898  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:23:43.898  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.898  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.899  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.899  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.899  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:43.899  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.899  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:43.899  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.899  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.900  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.901  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.901  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.904  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.904  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.905  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:23:43.906  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.907  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.907  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.907  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.907  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.909  5608  5654 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-26 11:23:43.911  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:23:43.911  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.911  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.911  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 11:23:43.912  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.912  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.912  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.912  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.912  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.912  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.913  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.913  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:43.913  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.913  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.916  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.916  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.916  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:23:43.917  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.917  5608  5654 D BluetoothLeScanner: could not find callback wrapper
,09-26 11:23:43.917  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.917  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.917  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.919  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-26 11:23:43.919  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:43.919  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.919  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.919  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.919  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.919  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.919  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.919  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.919  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
,09-26 11:23:43.920  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.920  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.920  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.920  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.920  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.921  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.921  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.921  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:23:43.922  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.922  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.922  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.922  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.922  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.923  5608  5654 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-26 11:23:43.923  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:43.923  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 11:23:43.924  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.924  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.924  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.924  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.924  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.924  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.924  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.924  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.924  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.924  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.924  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.924  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:43.926  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.926  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.926  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:23:43.927  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.927  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.927  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.927  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:43.928  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.928  5608  5654 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-26 11:23:43.928  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:43.929  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.929  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.929  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.929  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:43.929  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.929  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.929  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.929  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.929  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.929  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.929  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.929  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:43.929  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.931  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.931  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.931  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:43.932  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.932  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.932  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.932  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.933  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.933  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 11:23:43.934  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 11:23:43.934  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 11:23:43.934  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 11:23:43.934  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 11:23:43.934  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 11:23:43.934  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 11:23:43.934  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 11:23:43.934  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 11:23:43.934  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:43.935  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.935  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.935  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.935  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.935  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.935  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.935  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.935  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.935  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.935  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list ,- probably already removed
09-26 11:23:43.935  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.935  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.935  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:43.937  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.937  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.937  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:43.938  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.938  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.938  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.938  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.938  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.939  5608  5654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-26 11:23:43.939  5608  5654 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 11:23:43.939  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 11:23:43.942  5608  5654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 11:23:43.942  5608  5654 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 11:23:43.942  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 11:23:43.943  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-26 11:23:43.944  5608  5654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-26 11:23:43.944  5608  5654 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 11:23:43.944  5608  5654 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-26 11:23:43.944  5608  5654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 11:23:43.944  5608  5654 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 11:23:43.944  5608  5654 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-26 11:23:43.945  5608  5654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 11:23:43.945  5608  5654 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 11:23:43.945  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-26 11:23:43.948  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-26 11:23:43.949  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-26 11:23:43.949  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-26 11:23:43.951  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-26 11:23:43.951  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-26 11:23:43.951  5608  5654 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-26 11:23:43.951  5608  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-26 11:23:43.951  5608  5654 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 11:23:43.952  5608  5654 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-26 11:23:43.953  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:43.953  5608  5659 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 11:23:43.953  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.953  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 11:23:43.953  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.953  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.953  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.954  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-26 11:23:43.954  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
,09-26 11:23:43.955  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.955  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.955  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.955  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.955  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.955  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.955  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.955  5608  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-26 11:23:43.955  5608  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-26 11:23:43.955  5608  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-26 11:23:43.953  4802  4802 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30629]" dev="sockfs" ino=30629 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 11:23:43.953  4802  4802 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30629]" dev="sockfs" ino=30629 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-26 11:23:43.956  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 11:23:43.956  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.956  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:43.957  5608  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-26 11:23:43.958  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.958  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.958  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.958  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.958  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.959  5608  5654 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-26 11:23:43.959  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:43.959  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.959  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.960  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.960  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.960  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:43.960  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.960  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.960  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.960  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.960  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.960  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.960  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.960  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.961  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.961  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.961  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:43.962  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.962  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.962  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.962  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:43.962  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.963  5608  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-26 11:23:43.963  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:43.963  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.963  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.963  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.963  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.963  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.963  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.963  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.963  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.963  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.963  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.963  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.963  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.963  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.965  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.965  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.965  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:23:43.965  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:43.965  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.965  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.965  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.965  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.966  5608  5654 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-26 11:23:43.966  5608  5654 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-26 11:23:43.966  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 11:23:43.966  5608  5654 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-26 11:23:43.966  5608  5654 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 11:23:43.966  5608  5654 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-26 11:23:43.967  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 11:23:43.967  5608  5654 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-26 11:23:43.967  5608  5654 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 11:23:43.967  5608  5654 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 11:23:43.967  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 11:23:43.967  5608  5654 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-26 11:23:43.967  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:23:43.967  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:43.967  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:43.967  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.967  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.967  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.967  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.967  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:43.967  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.967  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.968  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.968  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.968  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.968  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:43.969  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:43.969  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:43.969  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:43.969  5608  5654 D BluetoothAdapter: STATE_ON
,09-26 11:23:43.969  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:43.969  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:43.969  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.969  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.970  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:43.970  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.970  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:43.970  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:43.970  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:43.970  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:43.971  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:43.971  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:43.971  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:46.353   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:48.439  3541  5662 I VacuumService: Vacuum at: now=1474903428439 tag=VacuumService
,09-26 11:23:48.477  3541  5665 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,09-26 11:23:48.510  3541  5663 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-26 11:23:48.513  3541  5663 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-26 11:23:48.553  3541  5663 W Uploader:  no longer exists, so no auth token.
,09-26 11:23:48.558  3541  5665 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 11:23:48.973  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:48.973  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:48.973  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:48.973  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:48.973  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:48.974  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:48.974  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:48.974  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 11:23:48.974  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:48.975  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 11:23:48.975  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:48.975  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:48.975  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
,09-26 11:23:48.975  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:48.975  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:48.975  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 11:23:48.976  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:48.976  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:48.976  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:48.976  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:48.980  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:48.980  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:48.980  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:48.982  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:48.983  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:48.983  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:48.983  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:48.983  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
,09-26 11:23:48.987  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-26 11:23:48.988  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:48.990  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-26 11:23:48.994  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-26 11:23:48.994  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-26 11:23:48.995  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-26 11:23:48.995  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 11:23:48.995  5608  5608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-26 11:23:48.995  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:48.995  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 11:23:48.995  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-26 11:23:48.995  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-26 11:23:48.995  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:48.995  5608  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 11:23:48.996  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 11:23:48.996  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
,09-26 11:23:48.996  5608  5608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-26 11:23:48.996  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:48.996  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 11:23:48.996  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 11:23:48.996  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 11:23:48.996  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 11:23:48.997  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:48.997  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:48.997  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:48.997  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:48.997  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 11:23:48.997  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:48.997  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:48.996  4570  4570 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30647]" dev="sockfs" ino=30647 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 11:23:48.996  4570  4570 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30647]" dev="sockfs" ino=30647 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 11:23:48.999  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:23:48.999  5608  5669 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-26 11:23:48.999  5608  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-26 11:23:48.999  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:48.999  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:23:48.999  5608  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 11:23:48.999  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:23:48.999  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:23:48.999  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:48.999  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:48.999  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:48.999  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:48.999  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:48.999  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:48.999  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:48.999  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:48.999  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:49.000  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:49.000  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:49.000  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:49.003  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:23:49.003  5608  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 11:23:49.008  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:23:49.009  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 11:23:49.009  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:23:49.009  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:49.009  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:49.012  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:49.012  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.014  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 11:23:49.014  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:49.014  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:49.015  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:49.015  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:49.015  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:49.015  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:49.015  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 11:23:49.015  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:49.015  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:49.015  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:23:49.017  5608  5654 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-26 11:23:49.017  5608  5654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-26 11:23:49.017  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 11:23:49.017  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 11:23:49.017  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 11:23:49.018  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:23:49.018  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:49.018  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:49.018  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:49.018  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:49.018  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:23:49.018  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:49.018  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:49.018  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:49.018  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:49.018  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:49.018  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 11:23:49.020  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:23:49.020  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:23:49.021  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.025  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:23:49.024  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:49.025  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.025  5608  5608 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-26 11:23:49.026  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:49.026  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:49.026  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:23:49.028  5608  5654 D BluetoothAdapter: STATE_ON
,09-26 11:23:49.028  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:49.028  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:49.028  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:49.028  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
,09-26 11:23:49.032  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:23:49.032  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:49.032  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:49.032  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:49.032  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:49.032  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.032  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:49.032  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:49.033  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:49.033  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:49.033  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:49.033  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.033  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:49.033  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.034  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:49.034  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:49.034  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:23:49.035  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:49.035  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:49.035  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:49.035  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:49.035  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:49.036  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:23:49.036  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:23:49.036  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:23:49.036  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:23:49.036  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:49.036  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.036  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a890d6 not in the list
09-26 11:23:49.036  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:49.036  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:49.036  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:23:49.036  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:49.036  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.037  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:23:49.037  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:23:49.038  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:23:49.038  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:23:49.038  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:23:49.039  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:23:49.039  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:23:49.039  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:23:49.039  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:49.039  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b0f57 not in the list
09-26 11:23:49.040  5608  5654 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-26 11:23:49.040  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 11:23:49.040  5608  5654 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-26 11:23:49.040  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 11:23:49.040  5608  5654 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-26 11:23:49.040  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-26 11:23:49.043  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-26 11:23:49.043  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-26 11:23:49.043  5608  5654 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-26 11:23:49.043  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 11:23:49.043  5608  5654 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-26 11:23:49.043  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 11:23:49.044  5608  5654 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-26 11:23:49.044  5608  5654 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-26 11:23:49.044  5608  5654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-26 11:23:49.044  5608  5654 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-26 11:23:49.045  5608  5654 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-26 11:23:49.045  5608  5654 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-26 11:23:49.045  5608  5654 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-26 11:23:49.045  5608  5654 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-26 11:23:49.046  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 11:23:49.047  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebb0b55 added. We now have 3 listener(s)
09-26 11:23:49.047  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:23:49.049  5608  5654 D BluetoothAdapter: enable(): BT is already enabled..!
09-26 11:23:49.049   929  3120 D WifiService: setWifiEnabled: true pid=5608, uid=10077
09-26 11:23:49.049   929  3120 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 11:23:49.081  4556  4761 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-26 11:23:49.082  4556  4779 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-26 11:23:49.366   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:49.399  3541  5673 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 11:23:49.523  3541  5675 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 11:23:49.526  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 11:23:49.596  3541  5663 W Uploader:  no longer exists, so no auth token.
,09-26 11:23:49.609  3541  5673 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 11:23:49.706  3541  5675 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 11:23:53.550   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:53.578   929  5319 D NetlinkSocketObserver: NeighborEvent{elapsedMs=163237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 11:23:54.055  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 11:23:54.055  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd5e96a added. We now have 4 listener(s)
,09-26 11:23:54.056  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:23:54.069  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:23:54.069  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd5e96a removed from the list
09-26 11:23:54.070  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 11:23:54.070  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:54.070  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:54.073  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 11:23:54.073  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92ede5b added. We now have 4 listener(s)
09-26 11:23:54.073  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 11:23:54.075  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:23:54.076  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92ede5b removed from the list
09-26 11:23:54.076  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 11:23:54.076  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:23:54.076  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:23:54.077  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 11:23:54.078  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61696f8 added. We now have 4 listener(s)
09-26 11:23:54.078  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:23:54.081   929  3788 D WifiService: setWifiEnabled: false pid=5608, uid=10077
09-26 11:23:54.081   929  3788 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 11:23:54.084   929  2943 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-26 11:23:54.085   929  2943 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 11:23:54.085   929  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 11:23:54.085   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 11:23:54.092  4556  4635 D BluetoothAdapterState: Current state: ON, message: 23
,09-26 11:23:54.092  4556  4635 D BluetoothAdapterProperties: Setting state to 13
09-26 11:23:54.092  4556  4635 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-26 11:23:54.093  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:23:54.093  4556  4635 D BluetoothAdapterProperties: onBluetoothDisable()
09-26 11:23:54.094  4556  4635 I BluetoothAdapterState: Entering PendingCommandState
,09-26 11:23:54.096  4556  4556 D BluetoothMapService: onReceive
,09-26 11:23:54.096  4556  4556 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 11:23:54.097  4556  4556 D BluetoothMapService: STATE_TURNING_OFF
09-26 11:23:54.097  4556  4556 D BluetoothMapService: MAP Service closeService in
09-26 11:23:54.097  4556  4556 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 11:23:54.097  4556  4556 D ObexServerSockets0: shutdown(block = true)
09-26 11:23:54.098  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 11:23:54.098  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 11:23:54.098  4556  4779 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-26 11:23:54.098  4556  4815 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-26 11:23:54.100  4556  4814 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-26 11:23:54.102  4556  4556 I BtOppRfcommListener: stopping Accept Thread
09-26 11:23:54.102   929  5320 D DhcpClient: Clearing IP address
09-26 11:23:54.102  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.102  4556  5236 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:54.102  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:54.102  4556  5236 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-26 11:23:54.103   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-26 11:23:54.106  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.107  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:54.107  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:23:54.109   507   920 D CommandListener: Setting iface cfg
,09-26 11:23:54.113   929   942 I ActivityManager: Start proc 5679:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-26 11:23:54.113  4556  4643 D BluetoothAdapterProperties: Scan Mode:20
09-26 11:23:54.113  4556  4635 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-26 11:23:54.114  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.116  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.118  3541  5391 V NativeCrypto: Read error: ssl=0x7f6d507a80: I/O error during system call, Connection timed out
09-26 11:23:54.118   929  5321 D DhcpClient: Receive thread stopped
09-26 11:23:54.119  4556  4556 D HeadsetService: Received stop request...Stopping profile...
09-26 11:23:54.121  3745  4746 D BluetoothHeadset: Proxy object disconnected
09-26 11:23:54.121   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 11:23:54.121  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:54.121  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:54.122  3099  3111 D BluetoothHeadset: Proxy object disconnected
09-26 11:23:54.122   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 11:23:54.122  4556  4556 D A2dpService: Received stop request...Stopping profile...
09-26 11:23:54.122  3541  5391 V NativeCrypto: SSL shutdown failed: ssl=0x7f6d507a80: I/O error during system call, Broken pipe
09-26 11:23:54.122   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 11:23:54.122  4556  4787 D A2dpStateMachine: Exit Disconnected: -1
,09-26 11:23:54.123  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.123  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:54.124   929   929 D BluetoothA2dp: Proxy object disconnected
09-26 11:23:54.126  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.126  4556  4556 D HidService: Received stop request...Stopping profile...
,09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:23:54.127  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:54.127  4556  4556 D HidService: Stopping Bluetooth HidService
09-26 11:23:54.128  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.128  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:23:54.128  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-26 11:23:54.128  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.128  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:23:54.128  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:23:54.129   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-26 11:23:54.130   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-26 11:23:54.130  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.132   542   542 E Parcel  : Reading a NULL string not supported here.
09-26 11:23:54.133  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 11:23:54.133  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.134  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:54.134  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-26 11:23:54.134  4556  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 11:23:54.134  4556  4761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:23:54.134  4556  4761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:23:54.134  4556  4761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:23:54.135  4556  4556 D HealthService: Received stop request...Stopping profile...
09-26 11:23:54.135  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.135  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:23:54.137  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-26 11:23:54.137  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.137  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:23:54.137  4556  4643 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-26 11:23:54.137  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 11:23:54.138  4556  4556 D PanService: Received stop request...Stopping profile...
,09-26 11:23:54.138  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.139  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:23:54.139   929   929 D RttService: SCAN_AVAILABLE : 1
,09-26 11:23:54.139   929  3052 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-26 11:23:54.140  3099  3099 D HeadsetProfile: Bluetooth service disconnected
,09-26 11:23:54.140   929  2945 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-26 11:23:54.140  3099  3099 D BluetoothA2dp: Proxy object disconnected
09-26 11:23:54.141  3099  3099 D BluetoothInputDevice: Proxy object disconnected
,09-26 11:23:54.141  3099  3099 D HidProfile: Bluetooth service disconnected
09-26 11:23:54.141  3099  3099 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 11:23:54.141  3099  3099 D PanProfile: Bluetooth service disconnected
09-26 11:23:54.141  4556  4556 D BluetoothMapService: Received stop request...Stopping profile...
09-26 11:23:54.141  4556  4556 D BluetoothMapService: stop()
09-26 11:23:54.141  3711  3877 W QCNEJ   : |CORE| network lost: 100
09-26 11:23:54.142  4556  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-26 11:23:54.142  4556  4761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:23:54.142  3711  3877 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-26 11:23:54.143  4556  4761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:23:54.143  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.143  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:23:54.143  4556  4761 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 11:23:54.143  4556  4761 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 11:23:54.143  4556  4556 D BluetoothMapAppObserver: deinitObservers()
09-26 11:23:54.143  4556  4761 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 11:23:54.143  4556  4556 D BluetoothMapAppObserver: removeReceiver()
09-26 11:23:54.143  4556  4761 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 11:23:54.145  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.146  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 11:23:54.146  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.146  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:23:54.149  4556  4556 D SapService: Received stop request...Stopping profile...
09-26 11:23:54.149  4556  4556 V SapService: stop()
,09-26 11:23:54.151  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-26 11:23:54.152  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.152  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:23:54.152  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:23:54.152  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-26 11:23:54.152  4556  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 11:23:54.152   929  2943 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-26 11:23:54.152  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 11:23:54.153  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-26 11:23:54.153  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.153  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:23:54.153  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:23:54.153  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 11:23:54.153  4556  4643 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 11:23:54.153  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 11:23:54.154  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-26 11:23:54.154  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.154  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:23:54.154  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:23:54.154  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 11:23:54.154  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-26 11:23:54.156  4556  4556 D BluetoothMapService: MAP Service closeService in
09-26 11:23:54.156  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-26 11:23:54.156  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.156  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:23:54.156  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:23:54.156  4556  4556 D BluetoothMapService: cleanup()
09-26 11:23:54.156  4556  4556 D BluetoothMapService: MAP Service closeService in
09-26 11:23:54.156  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-26 11:23:54.157  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.157  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:23:54.157  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:23:54.157  4556  4635 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-26 11:23:54.157  4556  4635 D BluetoothAdapterProperties: Setting state to 15
09-26 11:23:54.157  4556  4635 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-26 11:23:54.158  4556  4635 I BluetoothAdapterState: Entering BleOnState
09-26 11:23:54.158   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 11:23:54.158  3745  4000 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:23:54.159  3099  3110 D BluetoothMap: onBluetoothStateChange: up=false
09-26 11:23:54.159   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:23:54.160  3099  3947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:23:54.160  3099  3111 D BluetoothPan: onBluetoothStateChange on: false
,09-26 11:23:54.161  3099  3110 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 11:23:54.162   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-26 11:23:54.162   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:23:54.162  3099  3947 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-26 11:23:54.163  3099  3111 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 11:23:54.165   929  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 11:23:54.166  4556  4635 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-26 11:23:54.166  4556  4635 D BluetoothAdapterProperties: Setting state to 16
09-26 11:23:54.166  4556  4635 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 11:23:54.167  4556  4635 D BluetoothAdapterProperties: onBleDisable
09-26 11:23:54.167  4556  4635 I BluetoothAdapterState: Entering PendingCommandState
,09-26 11:23:54.167  4556  4636 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 11:23:54.168  4556  4643 D BluetoothAdapterProperties: Scan Mode:20
09-26 11:23:54.168  4556  4761 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 11:23:54.168  4556  4761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:23:54.170  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.170  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:54.172  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.172  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:54.174  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.176   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 11:23:54.181  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.183  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.184  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:54.196  5679  5679 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-26 11:23:54.198   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-26 11:23:54.199   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-26 11:23:54.199   507   920 D TetherController: Setting IP forward enable = 0
,09-26 11:23:54.200   929  2945 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-26 11:23:54.200   929  2945 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-26 11:23:54.201   929  2943 D DhcpClient: doQuit
09-26 11:23:54.202   929  2943 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-26 11:23:54.202   929  5320 D DhcpClient: onQuitting
09-26 11:23:54.203   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-26 11:23:54.204  3419  3419 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-26 11:23:54.204  5223  5223 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@401103c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-26 11:23:54.209  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.209  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:54.209  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.209  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:23:54.211  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.211  4990  5014 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.211  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:54.211  4990  5014 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 11:23:54.211  4990  5014 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-26 11:23:54.211  4990  5014 E SarControlService: no key has been found,reset the power
09-26 11:23:54.211  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 11:23:54.212  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.212  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 11:23:54.212  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:23:54.212  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 11:23:54.212  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 11:23:54.212  5015  5015 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 11:23:54.213  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:54.213  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:54.213  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:54.213  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 11:23:54.214  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:23:54.214  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 11:23:54.214  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 11:23:54.214  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 11:23:54.214  5015  5015 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 11:23:54.214  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.215  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.216  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.218  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000ea03000000000000ffffffff]
09-26 11:23:54.218  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 11:23:54.218  5015  5029 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-26 11:23:54.218  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:23:54.218  4990  5001 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-26 11:23:54.226  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000eb03000000000000ffffffff]
,09-26 11:23:54.226  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-26 11:23:54.226  5015  5029 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-26 11:23:54.226  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:23:54.227  4990  5000 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 11:23:54.229  3419  3419 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-26 11:23:54.229  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 11:23:54.234  3419  3419 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-26 11:23:54.235   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d727208:true
09-26 11:23:54.236  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 11:23:54.249   929  3555 I ActivityManager: Start proc 5708:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-26 11:23:54.250   507   920 E Netd    : netlink response contains error (No such file or directory)
,09-26 11:23:54.251   507   920 D TetherController: Setting IP forward enable = 0
09-26 11:23:54.253   929  2945 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-26 11:23:54.265  5679  5679 D LocalBluetoothProfileManager: Adding local MAP profile
,09-26 11:23:54.268  5679  5679 D BluetoothMap: Create BluetoothMap proxy object
,09-26 11:23:54.273  3419  3419 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-26 11:23:54.280  5679  5679 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-26 11:23:54.281  3419  3419 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-26 11:23:54.297  5708  5708 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-26 11:23:54.298  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,09-26 11:23:54.307   929  3778 I ActivityManager: Killing 4929:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-26 11:23:54.377  4556  4643 I bt_hci  : shut_down
,09-26 11:23:54.381  4556  4648 D bt_hwcfg: hw_epilog_process
,09-26 11:23:54.381  4556  4648 I bt_vendor: low_power_mode_cb
,09-26 11:23:54.384  4556  4648 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-26 11:23:54.384  4556  4648 I bt_vendor: epilog_cb
09-26 11:23:54.384  4556  4648 I bt_hci  : epilog_finished_callback
,09-26 11:23:54.386  4965  4965 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 11:23:54.386   929  2943 D wifi    : In wifi stop Hal
09-26 11:23:54.387   929  2943 D wifi    : halHandle = 0x7f6c01e680, mVM = 0x7f8864d140, mCls = 0x100a06
09-26 11:23:54.387   929  3417 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-26 11:23:54.387   929  3417 D WifiHAL : Got a signal to exit!!!
09-26 11:23:54.387   929  3417 I WifiHAL : Exit wifi_event_loop
09-26 11:23:54.389   929  2943 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-26 11:23:54.389   929  2943 E WifiHAL : Event processing terminated
09-26 11:23:54.389   929  2943 D wifi    : In wifi cleaned up handler
,09-26 11:23:54.389   929  2943 I WifiHAL : Internal cleanup completed
09-26 11:23:54.389  4556  4643 I bt_hci_h4: hal_close
09-26 11:23:54.389  4556  4643 I bt_userial_vendor: device fd = 54 close
09-26 11:23:54.389  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.390  4050  4189 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 11:23:54.391  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:54.393  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:54.407   929  3417 D wifi    : set interface wlan0 flags (DOWN)
,09-26 11:23:54.407   929  2943 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 11:23:54.496  5708  5708 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-26 11:23:54.496  5708  5708 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.496  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-26 11:23:54.497  5708  5708 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 11:23:54.497  5708  5708 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 11:23:54.497  570,8  5708 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 11:23:54.497  5708  5708 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.k.d(PG:583)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:2,3:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 11:23:54.497  5708  5708 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.497  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 11:23:54.498  4556  4636 D bt_stack_manager: event_shut_down_stack finished.
09-26 11:23:54.499  4556  4635 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-26 11:23:54.500  4556  4556 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 11:23:54.501  4556  4635 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-26 11:23:54.501  4556  4556 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 11:23:54.501  4556  4556 D BtGatt.GattService: stop()
09-26 11:23:54.501  4556  4556 D BtGatt.AdvertiseManager: advertise clients cleared
09-26 11:23:54.502  4556  4556 V BluetoothAdapterState: isTurningOff()=false
09-26 11:23:54.503  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-26 11:23:54.503  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:23:54.503  4556  4556 V BluetoothAdapterState: isBleTurningOff()=true
09-26 11:23:54.503  4556  4635 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-26 11:23:54.503  4556  4635 D BluetoothAdapterProperties: Setting state to 10
09-26 11:23:54.503  4556  4635 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-26 11:23:54.504  4556  4635 I BluetoothAdapterState: Entering OffState
09-26 11:23:54.504   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-26 11:23:54.510  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-26 11:23:54.510  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 11:23:54.510  4556  4556 I BluetoothServiceJni: cleanupNative: return from cleanup
09-26 11:23:54.511  4556  4636 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-26 11:23:54.515  4556  4556 I art     : System.exit called, status: 0
09-26 11:23:54.515  4556  4556 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-26 11:23:54.517  5708  5708 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.517  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 11:23:54.518  5708  5708 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 11:23:54.518  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-26 11:23:54.538  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 11:23:54.540   929  3165 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-26 11:23:54.541   929  3165 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-26 11:23:54.541   929  3165 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-26 11:23:54.541   929  3165 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-26 11:23:54.541   929  3165 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-26 11:23:54.551   544   544 I ServiceManager: Waiting for service AtCmdFwd...
09-26 11:23:54.557   929  3165 I ActivityManager: Start proc 5741:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-26 11:23:54.558  5679  5679 D DockEventReceiver: finishStartingService: stopping service
09-26 11:23:54.558   929  3788 W ActivityManager: Spurious death for ProcessRecord{3da6d86 5741:com.android.bluetooth/1002}, curProc for 4556: null
09-26 11:23:54.560   929  3850 I ActivityManager: Killing 5065:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-26 11:23:54.609   929   946 D Tethering: InitialState.processMessage what=4
,09-26 11:23:54.611   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 11:23:54.638  5741  5741 D AdapterServiceConfig: Adding HeadsetService
,09-26 11:23:54.639  5741  5741 D AdapterServiceConfig: Adding A2dpService
09-26 11:23:54.639  5741  5741 D AdapterServiceConfig: Adding HidService
,09-26 11:23:54.639  5741  5741 D AdapterServiceConfig: Adding HealthService
,09-26 11:23:54.639  5741  5741 D AdapterServiceConfig: Adding PanService
09-26 11:23:54.639  5741  5741 D AdapterServiceConfig: Adding GattService
09-26 11:23:54.639  5741  5741 D AdapterServiceConfig: Adding BluetoothMapService
09-26 11:23:54.639  5741  5741 D AdapterServiceConfig: Adding SapService
,09-26 11:23:54.642   929  3703 I ActivityManager: Killing 5393:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-26 11:23:54.669  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 11:23:54.676  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-26 11:23:54.679  3828  3828 D SystemUpdateService: onCreate
,09-26 11:23:54.683  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 11:23:54.691  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-26 11:23:54.695  3828  5347 I iu.UploadsManager: num queued entries: 0
,09-26 11:23:54.696  3828  5347 I iu.UploadsManager: num updated entries: 0
09-26 11:23:54.696  3828  5347 I iu.SyncManager: NEXT; no task
,09-26 11:23:54.698  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 11:23:54.699  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 11:23:54.702  3828  5754 I SystemUpdateService: active receiver: enabled
,09-26 11:23:54.711   929  3120 I ActivityManager: Start proc 5756:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-26 11:23:54.719  3828  5754 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 11:23:54.749  5756  5756 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-26 11:23:54.752  5756  5756 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 11:23:54.762  5756  5756 D SprintDMHelper: simOperator: 
,09-26 11:23:54.762  5756  5756 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 11:23:54.763  3828  5754 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-26 11:23:54.763  3828  5754 I SystemUpdateService: now status is 0 (complete)
09-26 11:23:54.763  3828  5754 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-26 11:23:54.763  3828  5754 I SystemUpdateService: file has been verified
09-26 11:23:54.763  3828  5754 I SystemUpdateService: OTA package size = 21989297
,09-26 11:23:54.770  3828  5754 I SystemUpdateService: showing system update notification
,09-26 11:23:54.774   929  3850 I ActivityManager: Start proc 5768:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-26 11:23:54.797  3828  3828 D SystemUpdateService: onDestroy
,09-26 11:23:54.799   929  3536 I ActivityManager: Killing 5377:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-26 11:23:54.876  4965  5782 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-26 11:23:54.884   929  3778 I ActivityManager: Start proc 5783:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-26 11:23:54.886   929  3778 I ActivityManager: Killing 5223:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-26 11:23:54.943  5783  5783 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-26 11:23:55.025  5708  5729 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-26 11:23:55.115   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0ab8b:true
,09-26 11:23:55.141   929   940 I ActivityManager: Killing 4654:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-26 11:23:55.180   929   939 I ActivityManager: Start proc 5797:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-26 11:23:55.209  5797  5797 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-26 11:23:55.216   929   939 I ActivityManager: Killing 5482:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-26 11:23:55.551   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:56.552   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:57.553   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:23:58.554   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:23:59.109   929  3703 D WifiService: setWifiEnabled: true pid=5608, uid=10077
,09-26 11:23:59.110   929  3703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 11:23:59.120   507   920 D SoftapController: Softap fwReload - Ok
,09-26 11:23:59.125   507   920 D CommandListener: Setting iface cfg
09-26 11:23:59.126   507   920 D CommandListener: Trying to bring down wlan0
09-26 11:23:59.127   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-26 11:23:59.135   929  2943 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 11:23:59.706   929  2943 D wifi    : set interface wlan0 flags (UP)
,09-26 11:23:59.710   929  2943 I WifiHAL : Initializing wifi
09-26 11:23:59.710   929  2943 I WifiHAL : Creating socket
,09-26 11:23:59.714   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-26 11:23:59.717   929  2943 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-26 11:23:59.717   929  2943 D wifi    : Did set static halHandle = 0x7f6c01e680
09-26 11:23:59.717   929  2943 D wifi    : halHandle = 0x7f6c01e680, mVM = 0x7f8864d140, mCls = 0x18da
09-26 11:23:59.718   929  2943 D wifi    : array field set
,09-26 11:23:59.718   929  2943 I WifiNative-HAL: interface[0] = wlan0
09-26 11:23:59.721   929  5815 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547272910464
09-26 11:23:59.721   929  5815 D wifi    : waitForHalEvents called, vm = 0x7f8864d140, obj = 0x18da, env = 0x7f6d6ff040
,09-26 11:23:59.794  5816  5816 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 11:23:59.817  5816  5816 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 11:23:59.822   929  2943 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 11:23:59.825  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:59.826  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:23:59.827  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:23:59.842  5816  5816 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 11:23:59.842  5816  5816 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-26 11:23:59.857   929  2943 D WifiConfigStore: Loading config and enabling all networks 
,09-26 11:23:59.858  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:59.858  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:59.858  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:59.858  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:23:59.859  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:59.859  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:59.859  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:59.859  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:23:59.860  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:23:59.860  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:23:59.860  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:23:59.860  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:23:59.866   929  2943 D WifiConfigStore: loaded 0 passpoint configs
09-26 11:23:59.866   929  2943 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-26 11:23:59.866   929  2943 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 11:23:59.867   929  2943 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-26 11:23:59.867   929  2943 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-26 11:23:59.868   929  2943 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-26 11:23:59.868   929  2943 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 11:23:59.868   929  2943 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-26 11:23:59.870   929  2943 D WifiNative-HAL: Setting external_sim to 1
,09-26 11:23:59.870  4965  4965 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 11:23:59.870   929  2943 D wifi    : setting dfs flag to true, 0x7f71df94a0
09-26 11:23:59.871   929  2943 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 11:23:59.871   929  2943 D wifi    : setting scan oui 0x7f71df94a0
09-26 11:23:59.871   929  2943 D WifiHAL : Sending mac address OUI
,09-26 11:23:59.874   929  2943 E native  : do suspend false
,09-26 11:23:59.881   929  2943 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-26 11:23:59.881   929   929 D RttService: SCAN_AVAILABLE : 3
09-26 11:23:59.882   929  3052 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-26 11:23:59.885   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-26 11:23:59.886   507   920 D CommandListener: Setting iface cfg
,09-26 11:23:59.889   929  2926 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
09-26 11:23:59.889   929  2926 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 11:23:59.894   929  2926 D WifiNative-HAL: p2pGetDeviceAddress
,09-26 11:23:59.899   929  2926 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 11:23:59.899   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=169558 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-26 11:24:03.053  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:03.060  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:03.064  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:03.068  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:03.121   929  2943 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-26 11:24:03.122   929  2943 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-26 11:24:03.122   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 11:24:03.134   929  2943 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 11:24:03.168   929  2943 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 11:24:03.170  5816  5816 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 11:24:03.592  5816  5816 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 11:24:03.640  5816  5816 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-26 11:24:03.642  5816  5816 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 11:24:03.651   929  2943 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 11:24:03.651   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-26 11:24:03.651   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 11:24:03.669   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 11:24:03.684   507   920 D CommandListener: Setting iface cfg
,09-26 11:24:03.690   929  2943 D WifiStateMachine: Start Dhcp Watchdog 2
,09-26 11:24:03.701   929  5822 D DhcpClient: Receive thread started
09-26 11:24:03.701   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-26 11:24:03.701   929  2943 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-26 11:24:03.701   929  2945 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-26 11:24:03.782   929  2943 E native  : do suspend false
,09-26 11:24:03.798   929  5821 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 11:24:03.822   929  5822 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172667, domain null
,09-26 11:24:03.823   929  5821 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172667 seconds
,09-26 11:24:03.825   929  5821 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 11:24:03.865   929  5822 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 11:24:03.865   929  5821 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-26 11:24:03.868   507   920 D CommandListener: Setting iface cfg
,09-26 11:24:03.875   929  2943 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 11:24:03.881   929  5821 D DhcpClient: Scheduling renewal in 86399s
,09-26 11:24:03.885   929  2943 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-26 11:24:03.885   929  2943 D WifiConfigStore: No blacklist allowed without epno enabled
,09-26 11:24:03.886   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-26 11:24:03.888   929  2945 D ConnectivityService: Adding iface wlan0 to network 101
09-26 11:24:03.890   929  2943 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-26 11:24:03.935   929  2945 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-26 11:24:03.935   929  2945 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-26 11:24:03.938   929  2945 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-26 11:24:03.947   929  2945 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-26 11:24:03.948   929  2945 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-26 11:24:03.955   929  2945 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 11:24:03.960   929  2945 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-26 11:24:03.960   929  2945 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-26 11:24:03.960   929  2945 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-26 11:24:03.960   929  2945 D ConnectivityService:    accepting network in place of null
09-26 11:24:03.960   929  2943 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 11:24:03.960   929  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 11:24:03.961   929  2945 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 11:24:03.970   929  5820 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173629, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 11:24:03.984   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 11:24:04.007   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 11:24:04.010   929  2945 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-26 11:24:04.011  3711  3877 W QCNEJ   : |CORE| network available: 101
,09-26 11:24:04.011   929  2945 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 11:24:04.012   929  2945 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-26 11:24:04.013   929   946 D Tethering: MasterInitialState.processMessage what=3
09-26 11:24:04.015  3711  3877 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-26 11:24:04.016  3711  3877 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-26 11:24:04.016  3711  3877 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-26 11:24:04.019  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:04.019  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:24:04.019  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.019  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:04.022  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:04.022  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:24:04.022  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.022  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:04.024  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 11:24:04.025  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:04.026  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:24:04.026  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.026  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:04.026  4990  5014 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 11:24:04.026  4990  5014 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 11:24:04.026  4990  5014 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 11:24:04.027  4990  5014 E SarControlService: no key has been found,reset the power
09-26 11:24:04.027  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 11:24:04.027  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 11:24:04.027  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-26 11:24:04.028  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-26 11:24:04.028  5015  5015 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 11:24:04.029  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 11:24:04.030  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 11:24:04.030  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 11:24:04.030  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 11:24:04.030  5015  5015 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 11:24:04.033  3828  3828 D SystemUpdateService: onCreate
,09-26 11:24:04.035  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000ec03000000000000ffffffff]
,09-26 11:24:04.035  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 11:24:04.035  5015  5029 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-26 11:24:04.035  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:24:04.035  4990  5001 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 11:24:04.036  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000ed03000000000000ffffffff]
09-26 11:24:04.036  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 11:24:04.036  5015  5029 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-26 11:24:04.036  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:24:04.036  4990  5000 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-26 11:24:04.038  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 11:24:04.040   929  5819 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-26 11:24:04.049  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-26 11:24:04.055  3828  5347 I iu.UploadsManager: num queued entries: 0
,09-26 11:24:04.055  3828  5347 I iu.UploadsManager: num updated entries: 0
,09-26 11:24:04.056  3828  5347 I iu.SyncManager: NEXT; no task
09-26 11:24:04.053  3828  5832 I SystemUpdateService: active receiver: enabled
,09-26 11:24:04.060  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 11:24:04.061  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 11:24:04.063  5756  5756 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 11:24:04.067  5756  5756 D SprintDMHelper: simOperator: 
09-26 11:24:04.067  5756  5756 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 11:24:04.088   929  5819 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 26 Sep 2016 15:24:04 GMT], X-Android-Received-Millis=[1474903444087], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474903444062]}
,09-26 11:24:04.079  3828  5832 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-26 11:24:04.088   929  2945 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-26 11:24:04.088   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-26 11:24:04.089   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 11:24:04.090   929  2945 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-26 11:24:04.098  3828  5832 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-26 11:24:04.098  3828  5832 I SystemUpdateService: now status is 0 (complete)
09-26 11:24:04.098  3828  5832 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 11:24:04.098  3828  5832 I SystemUpdateService: file has been verified
09-26 11:24:04.099  3828  5832 I SystemUpdateService: OTA package size = 21989297
,09-26 11:24:04.108  3828  5832 I SystemUpdateService: showing system update notification
,09-26 11:24:04.118   929   939 D WifiService: setWifiEnabled: false pid=5608, uid=10077
,09-26 11:24:04.118   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-26 11:24:04.118  3828  3828 D SystemUpdateService: onDestroy
,09-26 11:24:04.119   929  2943 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-26 11:24:04.119   929  2943 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 11:24:04.119   929  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 11:24:04.120   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 11:24:04.128   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-26 11:24:04.130   929  5821 D DhcpClient: Clearing IP address
09-26 11:24:04.131   507   920 D CommandListener: Setting iface cfg
,09-26 11:24:04.139   929   940 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,09-26 11:24:04.139   929  5819 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-26 11:24:04.140   929  5819 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-26 11:24:04.143   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-26 11:24:04.143   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-26 11:24:04.146   929   929 D RttService: SCAN_AVAILABLE : 1
09-26 11:24:04.148   929  2945 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-26 11:24:04.148   929  3052 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-26 11:24:04.148   542   542 E Parcel  : Reading a NULL string not supported here.
09-26 11:24:04.150  3711  3877 W QCNEJ   : |CORE| network lost: 101
09-26 11:24:04.152  3711  3877 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-26 11:24:04.154   929  2943 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-26 11:24:04.155   929  5819 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-26 11:24:04.155   929  5822 D DhcpClient: Receive thread stopped
,09-26 11:24:04.157   929  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-26 11:24:04.172   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 11:24:04.192   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 11:24:04.193   929  2945 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-26 11:24:04.193   929  2945 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-26 11:24:04.194   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-26 11:24:04.195   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-26 11:24:04.196  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:04.197  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:04.197  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.197  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:24:04.198  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:04.198  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:04.198  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.198  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:24:04.199  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:04.200  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:04.200  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.200  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:04.205  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 11:24:04.207  4990  5014 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 11:24:04.207  4990  5014 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 11:24:04.207  4990  5014 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-26 11:24:04.207  4990  5014 E SarControlService: no key has been found,reset the power
09-26 11:24:04.208  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 11:24:04.208  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 11:24:04.208  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 11:24:04.208  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 11:24:04.208  5015  5015 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 11:24:04.209  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 11:24:04.210  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 11:24:04.210  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 11:24:04.210  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 11:24:04.210  5015  5015 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 11:24:04.213  3828  3828 D SystemUpdateService: onCreate
09-26 11:24:04.216  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000ee03000000000000ffffffff]
09-26 11:24:04.216  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 11:24:04.216  5015  5029 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-26 11:24:04.216  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:24:04.216  4990  5000 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 11:24:04.217  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000ef03000000000000ffffffff]
09-26 11:24:04.217  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 11:24:04.218  5015  5029 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-26 11:24:04.219  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:24:04.219  4990  5001 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 11:24:04.217  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 11:24:04.223  3828  5850 I SystemUpdateService: active receiver: enabled
09-26 11:24:04.227  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-26 11:24:04.232  3828  5347 I iu.UploadsManager: num queued entries: 0
09-26 11:24:04.232  3828  5347 I iu.UploadsManager: num updated entries: 0
09-26 11:24:04.233  3828  5347 I iu.SyncManager: NEXT; no task
09-26 11:24:04.235  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 11:24:04.237  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-26 11:24:04.238  5756  5756 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 11:24:04.241  5756  5756 D SprintDMHelper: simOperator: 
09-26 11:24:04.242  5756  5756 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-26 11:24:04.244   507   920 E Netd    : netlink response contains error (No such file or directory)
09-26 11:24:04.245   929  2945 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-26 11:24:04.245   929  2945 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-26 11:24:04.246   929  2943 D DhcpClient: doQuit
09-26 11:24:04.246   929  2943 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-26 11:24:04.246   929  5821 D DhcpClient: onQuitting
09-26 11:24:04.247  3828  5850 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-26 11:24:04.247  5816  5816 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-26 11:24:04.249  3828  5850 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-26 11:24:04.249  3828  5850 I SystemUpdateService: now status is 0 (complete)
09-26 11:24:04.249  3828  5850 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 11:24:04.249  3828  5850 I SystemUpdateService: file has been verified
09-26 11:24:04.250  3828  5850 I SystemUpdateService: OTA package size = 21989297
09-26 11:24:04.251  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:04.251  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:04.251  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.251  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:04.252  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:04.252  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:04.252  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.253  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:04.253  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:04.253  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:04.253  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:04.253  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:04.259  3828  5850 I SystemUpdateService: showing system update notification
09-26 11:24:04.265  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-26 11:24:04.268  5816  5816 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-26 11:24:04.276  3828  3828 D SystemUpdateService: onDestroy
,09-26 11:24:04.295  5816  5816 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-26 11:24:04.301  5816  5816 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-26 11:24:04.406   929  2943 D wifi    : In wifi stop Hal
,09-26 11:24:04.406   929  2943 D wifi    : halHandle = 0x7f6c01e680, mVM = 0x7f8864d140, mCls = 0x18da
,09-26 11:24:04.411   929  5815 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-26 11:24:04.411   929  5815 D WifiHAL : Got a signal to exit!!!
09-26 11:24:04.411   929  5815 I WifiHAL : Exit wifi_event_loop
09-26 11:24:04.412  4965  4965 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 11:24:04.413  4050  4189 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 11:24:04.414   929  2943 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-26 11:24:04.414   929  2943 E WifiHAL : Event processing terminated
09-26 11:24:04.414   929  2943 D wifi    : In wifi cleaned up handler
09-26 11:24:04.414   929  2943 I WifiHAL : Internal cleanup completed
09-26 11:24:04.417  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:04.418  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:04.419  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:04.440   929  5815 D wifi    : set interface wlan0 flags (DOWN)
,09-26 11:24:04.440   929  2943 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 11:24:04.646   929   946 D Tethering: InitialState.processMessage what=4
,09-26 11:24:04.652   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 11:24:05.011   929  2945 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-26 11:24:09.099  4965  5837 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-26 11:24:09.099  4965  5837 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-26 11:24:09.103  4965  5837 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-26 11:24:09.154   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2eedbe:true
,09-26 11:24:09.155  5741  5741 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 11:24:09.160  5741  5741 I bt_bluedroid: init
,09-26 11:24:09.160  5741  5855 I BluetoothAdapterState: Entering OffState
,09-26 11:24:09.164  5741  5856 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-26 11:24:09.164  5741  5856 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 11:24:09.164  5741  5856 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-26 11:24:09.164  5741  5856 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-26 11:24:09.165  5741  5741 I bt_bluedroid: get_profile_interface socket
,09-26 11:24:09.168  5741  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 11:24:09.169  5741  5741 I bt_bluedroid: get_profile_interface sdp
09-26 11:24:09.171  5741  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 11:24:09.177  5741  5752 I bt_bluedroid: config_hci_snoop_log
09-26 11:24:09.179   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-26 11:24:09.185  5741  5855 D BluetoothAdapterState: Current state: OFF, message: 0
,09-26 11:24:09.186  5741  5855 D BluetoothAdapterProperties: Setting state to 14
09-26 11:24:09.186  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-26 11:24:09.188  5741  5855 D BluetoothBondStateMachine: make
,09-26 11:24:09.190  5741  5860 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 11:24:09.193  5741  5855 I BluetoothAdapterState: Entering PendingCommandState
,09-26 11:24:09.194  5741  5741 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 11:24:09.197  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:09.198  5741  5741 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 11:24:09.199  5741  5741 D BtGatt.GattService: Received start request. Starting profile...
,09-26 11:24:09.199  5741  5741 D BtGatt.GattService: start()
09-26 11:24:09.199  5741  5741 I bt_bluedroid: get_profile_interface gatt
,09-26 11:24:09.200  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:09.200  5741  5741 D BtGatt.AdvertiseManager: advertise manager created
,09-26 11:24:09.207  5741  5741 V BluetoothAdapterState: isTurningOff()=false
,09-26 11:24:09.207  5741  5741 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:09.207  5741  5741 V BluetoothAdapterState: isBleTurningOn()=true
09-26 11:24:09.207  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:09.207  5741  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-26 11:24:09.209  5741  5855 I bt_bluedroid: bt_bluedroid
,09-26 11:24:09.209  5741  5856 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-26 11:24:09.210  5741  5856 I bt_hci  : start_up
,09-26 11:24:09.217  5741  5856 I bt_vendor: alloc value 0xf41b8871
,09-26 11:24:09.217  5741  5856 I bt_vendor: init
09-26 11:24:09.217  5741  5856 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 11:24:09.217  5741  5856 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 11:24:09.327  5741  5856 D bt_hci  : start_up starting async portion
,09-26 11:24:09.328  5741  5863 I bt_hci  : event_finish_startup
09-26 11:24:09.328  5741  5863 I bt_hci_h4: hal_open
,09-26 11:24:09.328  5741  5863 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-26 11:24:09.326  5864  5864 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-26 11:24:09.331  5741  5863 I bt_userial_vendor: device fd = 54 open
,09-26 11:24:09.346  5741  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 11:24:09.348  5741  5863 D bt_hwcfg: Chipset BCM4358A3
,09-26 11:24:09.348  5741  5863 D bt_hwcfg: Target name = [BCM4358A3]
09-26 11:24:09.348  5741  5863 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 11:24:09.729  5741  5863 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-26 11:24:09.730  5741  5863 D bt_hwcfg: Settlement delay -- 100 ms
,09-26 11:24:09.730  5741  5863 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 11:24:09.865  5741  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 11:24:09.865  5741  5863 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-26 11:24:09.867  5741  5863 I bt_hwcfg: vendor lib fwcfg completed
09-26 11:24:09.867  5741  5863 I bt_vendor: firmware callback
09-26 11:24:09.867  5741  5863 I bt_hci  : firmware_config_callback
,09-26 11:24:09.877  5741  5866 I bt_btu  : btu_task pending for preload complete event
,09-26 11:24:09.877  5741  5866 I bt_btu_task: Bluetooth chip preload is complete
,09-26 11:24:09.877  5741  5866 I bt_btu  : btu_task received preload complete event
,09-26 11:24:09.885  5741  5866 I         : BTE_InitTraceLevels -- TRC_HCI
,09-26 11:24:09.885  5741  5866 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-26 11:24:09.885  5741  5866 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-26 11:24:09.885  5741  5866 I         : BTE_InitTraceLevels -- TRC_AVDT
09-26 11:24:09.885  5741  5866 I         : BTE_InitTraceLevels -- TRC_AVRC
09-26 11:24:09.885  5741  5866 I         : BTE_InitTraceLevels -- TRC_A2D
,09-26 11:24:09.885  5741  5866 I         : BTE_InitTraceLevels -- TRC_BNEP
09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_BTM
09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_GAP
,09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_PAN
09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_SDP
,09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_GATT
09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_SMP
09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 11:24:09.886  5741  5866 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 11:24:09.968  5741  5866 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4136549
09-26 11:24:09.968  5741  5866 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4136549 
,09-26 11:24:09.988  5741  5859 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-26 11:24:09.989  5741  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 11:24:09.990  5741  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-26 11:24:09.993  5741  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 11:24:09.996  5741  5859 D BluetoothAdapterProperties: Scan Mode:20
,09-26 11:24:09.997  5741  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 11:24:09.997  5741  5859 D bt_hci  : do_postload posting postload work item
09-26 11:24:09.997  5741  5863 I bt_hci  : event_postload
09-26 11:24:09.998  5741  5863 I bt_vendor: sco_config_cb
09-26 11:24:09.998  5741  5863 I bt_hci  : sco_config_callback postload finished.
,09-26 11:24:10.000  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:10.004  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:10.004  5741  5863 I bt_vendor: low_power_mode_cb
09-26 11:24:10.006  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:10.008  5741  5859 D bt_bte_conf: Device ID record 1 : primary
09-26 11:24:10.008  5741  5859 D bt_bte_conf:   vendorId            = 000f
,09-26 11:24:10.008  5741  5859 D bt_bte_conf:   vendorIdSource      = 0001
09-26 11:24:10.008  5741  5859 D bt_bte_conf:   product             = 1200
09-26 11:24:10.008  5741  5859 D bt_bte_conf:   version             = 1436
09-26 11:24:10.008  5741  5859 D bt_bte_conf:   clientExecutableURL = 
09-26 11:24:10.008  5741  5859 D bt_bte_conf:   serviceDescription  = 
09-26 11:24:10.008  5741  5859 D bt_bte_conf:   documentationURL    = 
09-26 11:24:10.008  5741  5859 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-26 11:24:10.010  5741  5856 D bt_stack_manager: event_start_up_stack finished
,09-26 11:24:10.010  5741  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-26 11:24:10.011  5741  5855 D BluetoothAdapterProperties: Setting state to 15
09-26 11:24:10.011  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-26 11:24:10.012  5741  5855 I BluetoothAdapterState: Entering BleOnState
,09-26 11:24:10.015  5741  5855 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-26 11:24:10.015  5741  5855 D BluetoothAdapterProperties: Setting state to 11
09-26 11:24:10.015  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-26 11:24:10.019  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:10.020  5741  5741 D HeadsetService: Received start request. Starting profile...
09-26 11:24:10.022  5741  5741 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-26 11:24:10.022  5741  5741 D HeadsetStateMachine: make
,09-26 11:24:10.025  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:10.026  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:10.028  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:10.037  5741  5855 I BluetoothAdapterState: Entering PendingCommandState
,09-26 11:24:10.039  5741  5741 D HeadsetStateMachine: max_hf_connections = 1
,09-26 11:24:10.039  5741  5741 I bt_bluedroid: get_profile_interface handsfree
09-26 11:24:10.040  5741  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-26 11:24:10.040  5741  5859 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-26 11:24:10.043  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:10.043  5741  5741 D A2dpService: Received start request. Starting profile...
,09-26 11:24:10.044  5741  5741 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-26 11:24:10.044  5741  5741 I bt_bluedroid: get_profile_interface avrcp
,09-26 11:24:10.050  5741  5741 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-26 11:24:10.051  5741  5741 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-26 11:24:10.051  5741  5741 D A2dpStateMachine: make
09-26 11:24:10.052  5741  5741 I bt_bluedroid: get_profile_interface a2dp
,09-26 11:24:10.053  5741  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-26 11:24:10.054  5741  5874 D A2dpStateMachine: Enter Disconnected: -2
,09-26 11:24:10.055  5741  5741 I BluetoothHidServiceJni: classInitNative: succeeds
,09-26 11:24:10.056  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 11:24:10.056  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:10.057  5741  5741 D HidService: Received start request. Starting profile...
09-26 11:24:10.058  5741  5741 I bt_bluedroid: get_profile_interface hidhost
09-26 11:24:10.058  5741  5741 D HidService: setHidService(): set to: null
,09-26 11:24:10.058  5741  5859 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf411756d
09-26 11:24:10.058  5741  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 11:24:10.059  5741  5741 I BluetoothHealthServiceJni: classInitNative: succeeds
09-26 11:24:10.060  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:10.061  5679  5679 D BluetoothInputDevice: Proxy object connected
09-26 11:24:10.061  5679  5679 D HidProfile: Bluetooth service connected
09-26 11:24:10.062  5741  5741 D HealthService: Received start request. Starting profile...
,09-26 11:24:10.063  5741  5741 I bt_bluedroid: get_profile_interface health
09-26 11:24:10.064  5741  5741 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-26 11:24:10.065  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:10.066  5741  5741 D PanService: Received start request. Starting profile...
09-26 11:24:10.066  5741  5741 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-26 11:24:10.066  5741  5741 I bt_bluedroid: get_profile_interface pan
09-26 11:24:10.067  5741  5859 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-26 11:24:10.069  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:10.070  5679  5679 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 11:24:10.070  5741  5741 D BluetoothMapService: Received start request. Starting profile...
09-26 11:24:10.070  5741  5741 D BluetoothMapService: start()
09-26 11:24:10.070  5679  5679 D PanProfile: Bluetooth service connected
09-26 11:24:10.071  5679  5679 D BluetoothMap: Proxy object connected
09-26 11:24:10.071  5679  5679 D MapProfile: Bluetooth service connected
09-26 11:24:10.072  5679  5679 D BluetoothMap: getConnectedDevices()
,09-26 11:24:10.072  5679  5679 D BluetoothMap: Bluetooth is Not enabled
09-26 11:24:10.072  5741  5741 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-26 11:24:10.073  5741  5741 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 11:24:10.073  5741  5741 D BluetoothMapAppObserver: createReceiver()
,09-26 11:24:10.075  5741  5741 D BluetoothMapAppObserver: initObservers()
09-26 11:24:10.075  5741  5741 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-26 11:24:10.080  5741  5741 V SapService: SapBinder()
09-26 11:24:10.080  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:10.080  5741  5741 D SapService: Received start request. Starting profile...
09-26 11:24:10.081  5741  5741 V SapService: start()
,09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isTurningOff()=false
,09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:10.083  5741  5871 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-26 11:24:10.083  5741  5741 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:10.084  5741  5741 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:10.085  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:10.085  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:10.085  5741  5741 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:10.085  5741  5741 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:10.085  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:10.085  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:10.086  5741  5741 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:10.086  5741  5741 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:10.086  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:10.086  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:10.086  5741  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 11:24:10.086  5741  5855 D BluetoothAdapterProperties: ScanMode =  20
09-26 11:24:10.086  5741  5855 D BluetoothAdapterProperties: State =  11
09-26 11:24:10.087  5741  5855 D BluetoothAdapterProperties: Setting state to 12
09-26 11:24:10.087  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-26 11:24:10.087  5741  5855 I BluetoothAdapterState: Entering OnState
09-26 11:24:10.087  5679  5690 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 11:24:10.087  5741  5859 D BluetoothAdapterProperties: Scan Mode:21
09-26 11:24:10.088  5741  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 11:24:10.089   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-26 11:24:10.089  3745  4746 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:10.090   929   929 D BluetoothA2dp: Proxy object connected
,09-26 11:24:10.090  3099  3947 D BluetoothMap: onBluetoothStateChange: up=true
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:10.092  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:10.092  3099  3099 D BluetoothMap: Proxy object connected
09-26 11:24:10.092  3099  3099 D MapProfile: Bluetooth service connected
09-26 11:24:10.092  5679  5693 D BluetoothPan: onBluetoothStateChange on: true
09-26 11:24:10.092  3099  3099 D BluetoothMap: getConnectedDevices()
09-26 11:24:10.092   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 11:24:10.093  5679  5690 D BluetoothMap: onBluetoothStateChange: up=true
09-26 11:24:10.093  3099  3111 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 11:24:10.094  3099  3947 D BluetoothPan: onBluetoothStateChange on: true
,09-26 11:24:10.094  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:10.095  3099  3099 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 11:24:10.095  3099  3099 D PanProfile: Bluetooth service connected
09-26 11:24:10.095  3099  3111 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 11:24:10.097   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:10.097   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:10.097  5679  5693 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 11:24:10.097  3099  3947 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:10.098  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 11:24:10.099  3099  3111 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 11:24:10.099  3099  3099 D BluetoothInputDevice: Proxy object connected
09-26 11:24:10.099  3099  3099 D HidProfile: Bluetooth service connected
09-26 11:24:10.099  5741  5741 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 11:24:10.099  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:10.100  5741  5741 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-26 11:24:10.101  3099  3099 D BluetoothA2dp: Proxy object connected
09-26 11:24:10.101  5741  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 11:24:10.105  5741  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 11:24:10.106  5679  5679 D LocalBluetoothProfileManager: Adding local A2DP profile
09-26 11:24:10.102   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-26 11:24:10.115  5741  5741 D ObexServerSockets: Succeed to create listening sockets ,
09-26 11:24:10.115  5741  5741 D ObexServerSockets0: startAccept()
09-26 11:24:10.115  5741  5741 D ObexServerSockets0: prepareForNewConnect()
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:10.115  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:10.117  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:10.117  5741  5741 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-26 11:24:10.117  5741  5741 D BluetoothSdpJni: SDP Create record success - handle: 0
09-26 11:24:10.117  5741  5882 D ObexServerSockets0: Accepting socket connection...
,09-26 11:24:10.117  5741  5741 D BluetoothMapService: onReceive
09-26 11:24:10.117  5741  5741 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 11:24:10.118  5741  5741 D BluetoothMapService: STATE_ON
,09-26 11:24:10.118  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:10.118  5741  5883 D ObexServerSockets0: Accepting socket connection...
09-26 11:24:10.120  5741  5884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 11:24:10.120  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:10.121  5741  5884 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 11:24:10.121  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:10.121  5741  5884 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-26 11:24:10.126  5679  5679 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-26 11:24:10.131  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 11:24:10.135  5679  5679 D BluetoothA2dp: Proxy object connected
,09-26 11:24:10.138  5741  5741 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 11:24:10.138  5741  5741 D ObexServerSockets0: prepareForNewConnect()
,09-26 11:24:10.139  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 11:24:10.140  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,09-26 11:24:10.147  3099  3099 D BluetoothPbap: Proxy object connected
,09-26 11:24:10.147  3099  3099 D PbapServerProfile: Bluetooth service connected
,09-26 11:24:10.149  5679  5679 D BluetoothPbap: Proxy object connected
,09-26 11:24:10.149  5679  5679 D PbapServerProfile: Bluetooth service connected
,09-26 11:24:10.154  5741  5888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 11:24:10.169  5741  5892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 11:24:10.171  5741  5892 I BtOppRfcommListener: Accept thread started.
,09-26 11:24:10.191  3745  3770 D BluetoothHeadset: Proxy object connected
,09-26 11:24:10.191   929   929 D BluetoothHeadset: Proxy object connected
09-26 11:24:10.192  3099  3947 D BluetoothHeadset: Proxy object connected
09-26 11:24:10.192  3099  3099 D HeadsetProfile: Bluetooth service connected
09-26 11:24:10.192   929   929 D BluetoothHeadset: Proxy object connected
09-26 11:24:10.192   929   929 D BluetoothHeadset: Proxy object connected
09-26 11:24:10.193   929   946 D BluetoothHeadset: Proxy object connected
09-26 11:24:10.194  3099  3111 D BluetoothHeadset: Proxy object connected
,09-26 11:24:10.194  3099  3099 D HeadsetProfile: Bluetooth service connected
,09-26 11:24:10.197   929   946 D BluetoothHeadset: Proxy object connected
09-26 11:24:10.197   929   946 D BluetoothHeadset: Proxy object connected
,09-26 11:24:10.229  5679  5690 D BluetoothHeadset: Proxy object connected
,09-26 11:24:10.230  5679  5679 D HeadsetProfile: Bluetooth service connected
,09-26 11:24:11.967   929  2945 D ConnectivityService: handlePromptUnvalidated 101
,09-26 11:24:14.136  5741  5855 D BluetoothAdapterState: Current state: ON, message: 23
,09-26 11:24:14.136  5741  5855 D BluetoothAdapterProperties: Setting state to 13
,09-26 11:24:14.136  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-26 11:24:14.138  5741  5855 D BluetoothAdapterProperties: onBluetoothDisable()
09-26 11:24:14.142  5741  5855 I BluetoothAdapterState: Entering PendingCommandState
09-26 11:24:14.144  5741  5741 D BluetoothMapService: onReceive
09-26 11:24:14.144  5741  5741 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 11:24:14.144  5741  5741 D BluetoothMapService: STATE_TURNING_OFF
,09-26 11:24:14.145  5741  5741 D BluetoothMapService: MAP Service closeService in
09-26 11:24:14.145  5741  5741 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 11:24:14.145  5741  5741 D ObexServerSockets0: shutdown(block = true)
09-26 11:24:14.146  5741  5741 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-26 11:24:14.147  5741  5741 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 11:24:14.147  5741  5868 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-26 11:24:14.148  5741  5883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-26 11:24:14.148  5741  5882 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-26 11:24:14.151  5741  5741 I BtOppRfcommListener: stopping Accept Thread
09-26 11:24:14.151  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:14.152  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:14.152  5741  5892 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 11:24:14.152  5741  5892 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-26 11:24:14.152  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:14.153  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:14.153  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 11:24:14.155  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:14.156  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:14.156  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:14.156  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:24:14.159  5741  5859 D BluetoothAdapterProperties: Scan Mode:20
09-26 11:24:14.159  5741  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-26 11:24:14.159  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:14.160  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:14.161  5608  5608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 11:24:14.161  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:24:14.164  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:14.164  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 11:24:14.166  3099  3099 D BluetoothPbap: Proxy object disconnected
09-26 11:24:14.166  3099  3099 D PbapServerProfile: Bluetooth service disconnected
09-26 11:24:14.166  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:14.167  5741  5741 D HeadsetService: Received stop request...Stopping profile...
09-26 11:24:14.170  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,09-26 11:24:14.171  5679  5679 D BluetoothPbap: Proxy object disconnected
09-26 11:24:14.171  5679  5679 D PbapServerProfile: Bluetooth service disconnected
09-26 11:24:14.172  5679  5690 D BluetoothHeadset: Proxy object disconnected
09-26 11:24:14.172  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:14.172  5741  5741 D A2dpService: Received stop request...Stopping profile...
09-26 11:24:14.172  5741  5874 D A2dpStateMachine: Exit Disconnected: -1
09-26 11:24:14.172  3745  3773 D BluetoothHeadset: Proxy object disconnected
,09-26 11:24:14.173   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 11:24:14.173  3099  3110 D BluetoothHeadset: Proxy object disconnected
09-26 11:24:14.173  3099  3099 D HeadsetProfile: Bluetooth service disconnected
09-26 11:24:14.173   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 11:24:14.173   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 11:24:14.174  5679  5679 D HeadsetProfile: Bluetooth service disconnected
09-26 11:24:14.174   929   929 D BluetoothA2dp: Proxy object disconnected
09-26 11:24:14.174  5679  5679 D BluetoothA2dp: Proxy object disconnected
09-26 11:24:14.174  3099  3099 D BluetoothA2dp: Proxy object disconnected
,09-26 11:24:14.175  5741  5741 D HidService: Received stop request...Stopping profile...
09-26 11:24:14.175  5741  5741 D HidService: Stopping Bluetooth HidService
09-26 11:24:14.176  5679  5679 D BluetoothInputDevice: Proxy object disconnected
09-26 11:24:14.176  5679  5679 D HidProfile: Bluetooth service disconnected
09-26 11:24:14.176  3099  3099 D BluetoothInputDevice: Proxy object disconnected
09-26 11:24:14.176  5741  5741 V BluetoothAdapterState: isTurningOff()=true
09-26 11:24:14.176  3099  3099 D HidProfile: Bluetooth service disconnected
09-26 11:24:14.176  5741  5741 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:14.176  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:14.176  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:14.177  5741  5741 D HealthService: Received stop request...Stopping profile...
09-26 11:24:14.179  5741  5741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 11:24:14.179  5741  5741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-26 11:24:14.179  5741  5741 V BluetoothAdapterState: isTurningOff()=true
09-26 11:24:14.179  5741  5741 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:14.179  5741  5866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-26 11:24:14.179  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:14.179  5741  5866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:24:14.179  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:14.179  5741  5866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:24:14.179  5741  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 11:24:14.180  5741  5859 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-26 11:24:14.180  5741  5741 D PanService: Received stop request...Stopping profile...
,09-26 11:24:14.183  3099  3099 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 11:24:14.183  3099  3099 D PanProfile: Bluetooth service disconnected
09-26 11:24:14.184  5741  5741 D BluetoothMapService: Received stop request...Stopping profile...
09-26 11:24:14.184  5741  5741 D BluetoothMapService: stop()
09-26 11:24:14.185  5741  5866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:24:14.185  5741  5741 D BluetoothMapAppObserver: deinitObservers()
09-26 11:24:14.185  5741  5866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:24:14.185  5741  5741 D BluetoothMapAppObserver: removeReceiver()
09-26 11:24:14.186  5741  5741 V BluetoothAdapterState: isTurningOff()=true
,09-26 11:24:14.186  5741  5741 V BluetoothAdapterState: isTurningOn()=false
,09-26 11:24:14.186  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:14.186  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:14.186  3099  3099 D BluetoothMap: Proxy object disconnected
09-26 11:24:14.186  3099  3099 D MapProfile: Bluetooth service disconnected
09-26 11:24:14.186  5741  5741 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-26 11:24:14.186  5741  5741 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 11:24:14.186  5741  5866 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 11:24:14.186  5741  5866 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 11:24:14.186  5741  5866 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 11:24:14.187  5741  5866 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 11:24:14.187  5741  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 11:24:14.187  5741  5741 D SapService: Received stop request...Stopping profile...
09-26 11:24:14.187  5741  5741 V SapService: stop()
09-26 11:24:14.187  5741  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 11:24:14.188  5741  5741 V BluetoothAdapterState: isTurningOff()=true
09-26 11:24:14.188  5679  5679 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 11:24:14.188  5741  5741 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:14.188  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:14.188  5679  5679 D PanProfile: Bluetooth service disconnected
09-26 11:24:14.188  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:14.188  5741  5741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 11:24:14.188  5679  5679 D BluetoothMap: Proxy object disconnected
09-26 11:24:14.188  5679  5679 D MapProfile: Bluetooth service disconnected
09-26 11:24:14.188  5741  5859 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 11:24:14.188  5741  5741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 11:24:14.188  5741  5741 V BluetoothAdapterState: isTurningOff()=true
09-26 11:24:14.189  5741  5741 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:14.189  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:14.189  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:14.189  5741  5741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 11:24:14.189  5741  5741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-26 11:24:14.189  5741  5741 D BluetoothMapService: MAP Service closeService in
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isTurningOff()=true
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:14.190  5741  5741 D BluetoothMapService: cleanup()
,09-26 11:24:14.190  5741  5741 D BluetoothMapService: MAP Service closeService in
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isTurningOff()=true
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:14.190  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:14.190  5741  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-26 11:24:14.190  5741  5855 D BluetoothAdapterProperties: Setting state to 15
09-26 11:24:14.190  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-26 11:24:14.191  5679  5690 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 11:24:14.191   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 11:24:14.192  3745  4000 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:24:14.192  3099  3110 D BluetoothMap: onBluetoothStateChange: up=false
09-26 11:24:14.192  5679  5693 D BluetoothPan: onBluetoothStateChange on: false
09-26 11:24:14.193  5679  5690 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 11:24:14.194  5741  5855 I BluetoothAdapterState: Entering BleOnState
09-26 11:24:14.194  5679  5693 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:24:14.194   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:24:14.194  5679  5690 D BluetoothMap: onBluetoothStateChange: up=false
,09-26 11:24:14.195  3099  3947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:24:14.195  3099  3111 D BluetoothPan: onBluetoothStateChange on: false
09-26 11:24:14.196  3099  3110 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 11:24:14.196   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:24:14.196   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 11:24:14.196  5679  5693 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-26 11:24:14.197  3099  3947 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-26 11:24:14.197  3099  3111 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 11:24:14.198  5741  5855 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-26 11:24:14.198  5741  5855 D BluetoothAdapterProperties: Setting state to 16
09-26 11:24:14.198  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 11:24:14.199  5741  5855 D BluetoothAdapterProperties: onBleDisable
09-26 11:24:14.199  5741  5855 I BluetoothAdapterState: Entering PendingCommandState
09-26 11:24:14.199  5741  5856 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 11:24:14.201  5741  5866 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 11:24:14.201  5741  5866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 11:24:14.201  5741  5859 D BluetoothAdapterProperties: Scan Mode:20
,09-26 11:24:14.201  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:14.202  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 11:24:14.203  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:14.206  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:14.208  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:14.209  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 11:24:14.210  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:14.211  5679  5679 D DockEventReceiver: finishStartingService: stopping service
09-26 11:24:14.211  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:14.407  5741  5859 I bt_hci  : shut_down
,09-26 11:24:14.413  5741  5863 D bt_hwcfg: hw_epilog_process
09-26 11:24:14.413  5741  5863 I bt_vendor: low_power_mode_cb
,09-26 11:24:14.416  5741  5863 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-26 11:24:14.416  5741  5863 I bt_vendor: epilog_cb
09-26 11:24:14.416  5741  5863 I bt_hci  : epilog_finished_callback
,09-26 11:24:14.420  5741  5859 I bt_hci_h4: hal_close
,09-26 11:24:14.421  5741  5859 I bt_userial_vendor: device fd = 54 close
,09-26 11:24:14.534  5741  5856 D bt_stack_manager: event_shut_down_stack finished.
,09-26 11:24:14.535  5741  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-26 11:24:14.540  5741  5855 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-26 11:24:14.540  5741  5741 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-26 11:24:14.541  5741  5741 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 11:24:14.542  5741  5741 D BtGatt.GattService: stop()
09-26 11:24:14.542  5741  5741 D BtGatt.AdvertiseManager: advertise clients cleared
,09-26 11:24:14.548  5741  5741 V BluetoothAdapterState: isTurningOff()=false
,09-26 11:24:14.548  5741  5741 V BluetoothAdapterState: isTurningOn()=false
,09-26 11:24:14.548  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:14.548  5741  5741 V BluetoothAdapterState: isBleTurningOff()=true
09-26 11:24:14.549  5741  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-26 11:24:14.549  5741  5855 D BluetoothAdapterProperties: Setting state to 10
09-26 11:24:14.549  5741  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-26 11:24:14.551  5741  5855 I BluetoothAdapterState: Entering OffState
09-26 11:24:14.553   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-26 11:24:14.570  5741  5741 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-26 11:24:14.570  5741  5741 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 11:24:14.570  5741  5741 I BluetoothServiceJni: cleanupNative: return from cleanup
09-26 11:24:14.572  5741  5856 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-26 11:24:14.579  5741  5741 I art     : System.exit called, status: 0
,09-26 11:24:14.580  5741  5741 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-26 11:24:14.609   929  3555 I ActivityManager: Process com.android.bluetooth (pid 5741) has died
,09-26 11:24:18.555   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:24:19.135  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 11:24:19.135  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:24:19.140  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:19.140  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61696f8 removed from the list
,09-26 11:24:19.141  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:24:19.141  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:19.141  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:24:19.145  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 11:24:19.146  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e13236 added. We now have 4 listener(s)
09-26 11:24:19.146  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:24:19.147  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:24:19.148  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e13236 removed from the list
09-26 11:24:19.148  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:24:19.148  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:19.149  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:19.151  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 11:24:19.151  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f30537 added. We now have 4 listener(s)
09-26 11:24:19.151  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:24:19.556   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:24:20.558   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:24:21.559   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:24:22.561   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:24:23.562   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:24:24.163  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:24.199   929   946 I ActivityManager: Start proc 5902:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-26 11:24:24.306  5902  5902 D AdapterServiceConfig: Adding HeadsetService
,09-26 11:24:24.306  5902  5902 D AdapterServiceConfig: Adding A2dpService
09-26 11:24:24.307  5902  5902 D AdapterServiceConfig: Adding HidService
,09-26 11:24:24.307  5902  5902 D AdapterServiceConfig: Adding HealthService
09-26 11:24:24.307  5902  5902 D AdapterServiceConfig: Adding PanService
09-26 11:24:24.307  5902  5902 D AdapterServiceConfig: Adding GattService
,09-26 11:24:24.307  5902  5902 D AdapterServiceConfig: Adding BluetoothMapService
09-26 11:24:24.307  5902  5902 D AdapterServiceConfig: Adding SapService
,09-26 11:24:24.322   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e7887e:true
09-26 11:24:24.322  5902  5902 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 11:24:24.325  5902  5902 I bt_bluedroid: init
,09-26 11:24:24.326  5902  5914 I BluetoothAdapterState: Entering OffState
,09-26 11:24:24.329  5902  5915 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-26 11:24:24.329  5902  5915 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 11:24:24.329  5902  5915 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-26 11:24:24.329  5902  5915 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-26 11:24:24.330  5902  5902 I bt_bluedroid: get_profile_interface socket
,09-26 11:24:24.331  5902  5918 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 11:24:24.332  5902  5902 I bt_bluedroid: get_profile_interface sdp
09-26 11:24:24.333  5902  5918 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 11:24:24.337  5902  5913 I bt_bluedroid: config_hci_snoop_log
09-26 11:24:24.338   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-26 11:24:24.343  5902  5914 D BluetoothAdapterState: Current state: OFF, message: 0
09-26 11:24:24.344  5902  5914 D BluetoothAdapterProperties: Setting state to 14
09-26 11:24:24.344  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-26 11:24:24.345  5902  5914 D BluetoothBondStateMachine: make
,09-26 11:24:24.348  5902  5919 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 11:24:24.350  5902  5914 I BluetoothAdapterState: Entering PendingCommandState
,09-26 11:24:24.352  5902  5902 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 11:24:24.354  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:24.355  5902  5902 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-26 11:24:24.356  5902  5902 D BtGatt.GattService: Received start request. Starting profile...
,09-26 11:24:24.356  5902  5902 D BtGatt.GattService: start()
09-26 11:24:24.356  5902  5902 I bt_bluedroid: get_profile_interface gatt
09-26 11:24:24.357  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:24.357  5902  5902 D BtGatt.AdvertiseManager: advertise manager created
,09-26 11:24:24.363  5902  5902 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:24.364  5902  5902 V BluetoothAdapterState: isTurningOn()=false
09-26 11:24:24.364  5902  5902 V BluetoothAdapterState: isBleTurningOn()=true
,09-26 11:24:24.364  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:24.364  5902  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-26 11:24:24.366  5902  5914 I bt_bluedroid: bt_bluedroid
,09-26 11:24:24.366  5902  5915 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-26 11:24:24.366  5902  5915 I bt_hci  : start_up
,09-26 11:24:24.372  5902  5915 I bt_vendor: alloc value 0xf420f871
09-26 11:24:24.372  5902  5915 I bt_vendor: init
09-26 11:24:24.372  5902  5915 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 11:24:24.372  5902  5915 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 11:24:24.482  5902  5915 D bt_hci  : start_up starting async portion
,09-26 11:24:24.483  5902  5922 I bt_hci  : event_finish_startup
,09-26 11:24:24.483  5902  5922 I bt_hci_h4: hal_open
,09-26 11:24:24.483  5902  5922 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-26 11:24:24.485  5902  5922 I bt_userial_vendor: device fd = 54 open
09-26 11:24:24.483  5923  5923 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-26 11:24:24.501  5902  5922 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 11:24:24.504  5902  5922 D bt_hwcfg: Chipset BCM4358A3
,09-26 11:24:24.505  5902  5922 D bt_hwcfg: Target name = [BCM4358A3]
09-26 11:24:24.505  5902  5922 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 11:24:25.005  5902  5922 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-26 11:24:25.006  5902  5922 D bt_hwcfg: Settlement delay -- 100 ms
,09-26 11:24:25.006  5902  5922 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 11:24:25.140  5902  5922 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-26 11:24:25.141  5902  5922 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-26 11:24:25.142  5902  5922 I bt_hwcfg: vendor lib fwcfg completed
09-26 11:24:25.143  5902  5922 I bt_vendor: firmware callback
,09-26 11:24:25.143  5902  5922 I bt_hci  : firmware_config_callback
,09-26 11:24:25.154  5902  5925 I bt_btu  : btu_task pending for preload complete event
,09-26 11:24:25.154  5902  5925 I bt_btu_task: Bluetooth chip preload is complete
09-26 11:24:25.154  5902  5925 I bt_btu  : btu_task received preload complete event
,09-26 11:24:25.162  5902  5925 I         : BTE_InitTraceLevels -- TRC_HCI
,09-26 11:24:25.162  5902  5925 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-26 11:24:25.162  5902  5925 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-26 11:24:25.163  5902  5925 I         : BTE_InitTraceLevels -- TRC_AVDT
09-26 11:24:25.163  5902  5925 I         : BTE_InitTraceLevels -- TRC_AVRC
09-26 11:24:25.163  5902  5925 I         : BTE_InitTraceLevels -- TRC_A2D
,09-26 11:24:25.163  5902  5925 I         : BTE_InitTraceLevels -- TRC_BNEP
09-26 11:24:25.163  5902  5925 I         : BTE_InitTraceLevels -- TRC_BTM
09-26 11:24:25.163  5902  5925 I         : BTE_InitTraceLevels -- TRC_GAP
09-26 11:24:25.163  5902  5925 I         : BTE_InitTraceLevels -- TRC_PAN
,09-26 11:24:25.164  5902  5925 I         : BTE_InitTraceLevels -- TRC_SDP
09-26 11:24:25.164  5902  5925 I         : BTE_InitTraceLevels -- TRC_GATT
09-26 11:24:25.164  5902  5925 I         : BTE_InitTraceLevels -- TRC_SMP
09-26 11:24:25.164  5902  5925 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 11:24:25.164  5902  5925 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 11:24:25.262  5902  5925 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf418d549
09-26 11:24:25.263  5902  5925 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf418d549 
,09-26 11:24:25.281  5902  5918 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-26 11:24:25.283  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-26 11:24:25.284  5902  5918 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 11:24:25.288  5902  5918 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 11:24:25.291  5902  5918 D BluetoothAdapterProperties: Scan Mode:20
,09-26 11:24:25.291  5902  5918 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 11:24:25.291  5902  5918 D bt_hci  : do_postload posting postload work item
09-26 11:24:25.292  5902  5922 I bt_hci  : event_postload
09-26 11:24:25.292  5902  5922 I bt_vendor: sco_config_cb
09-26 11:24:25.292  5902  5922 I bt_hci  : sco_config_callback postload finished.
09-26 11:24:25.295  5902  5918 D bt_bte_conf: Device ID record 1 : primary
09-26 11:24:25.295  5902  5918 D bt_bte_conf:   vendorId            = 000f
09-26 11:24:25.295  5902  5918 D bt_bte_conf:   vendorIdSource      = 0001
09-26 11:24:25.295  5902  5918 D bt_bte_conf:   product             = 1200
09-26 11:24:25.295  5902  5918 D bt_bte_conf:   version             = 1436
,09-26 11:24:25.296  5902  5918 D bt_bte_conf:   clientExecutableURL = 
09-26 11:24:25.296  5902  5918 D bt_bte_conf:   serviceDescription  = 
09-26 11:24:25.296  5902  5918 D bt_bte_conf:   documentationURL    = 
09-26 11:24:25.296  5902  5918 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-26 11:24:25.296  5902  5915 D bt_stack_manager: event_start_up_stack finished
09-26 11:24:25.297  5902  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-26 11:24:25.299  5902  5914 D BluetoothAdapterProperties: Setting state to 15
,09-26 11:24:25.299  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-26 11:24:25.299  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:25.301  5902  5914 I BluetoothAdapterState: Entering BleOnState
09-26 11:24:25.302  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:25.302  5902  5922 I bt_vendor: low_power_mode_cb
09-26 11:24:25.304  5902  5914 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-26 11:24:25.304  5902  5914 D BluetoothAdapterProperties: Setting state to 11
09-26 11:24:25.304  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-26 11:24:25.312  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:25.314  5902  5902 D HeadsetService: Received start request. Starting profile...
,09-26 11:24:25.318  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:25.319  5902  5902 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-26 11:24:25.320  5902  5902 D HeadsetStateMachine: make
09-26 11:24:25.322  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:25.332  5902  5914 I BluetoothAdapterState: Entering PendingCommandState
,09-26 11:24:25.333  5902  5902 D HeadsetStateMachine: max_hf_connections = 1
09-26 11:24:25.333  5902  5902 I bt_bluedroid: get_profile_interface handsfree
09-26 11:24:25.334  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-26 11:24:25.337  5902  5918 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-26 11:24:25.338  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:25.341  5902  5902 D A2dpService: Received start request. Starting profile...
09-26 11:24:25.341  5902  5902 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-26 11:24:25.342  5902  5902 I bt_bluedroid: get_profile_interface avrcp
09-26 11:24:25.348  5902  5902 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-26 11:24:25.348  5902  5902 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-26 11:24:25.348  5902  5902 D A2dpStateMachine: make
09-26 11:24:25.349  5902  5902 I bt_bluedroid: get_profile_interface a2dp
,09-26 11:24:25.350  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-26 11:24:25.355  5902  5933 D A2dpStateMachine: Enter Disconnected: -2
,09-26 11:24:25.355  5902  5902 I BluetoothHidServiceJni: classInitNative: succeeds
,09-26 11:24:25.356  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:25.358  5902  5902 D HidService: Received start request. Starting profile...
09-26 11:24:25.358  5902  5902 I bt_bluedroid: get_profile_interface hidhost
09-26 11:24:25.358  5902  5902 D HidService: setHidService(): set to: null
09-26 11:24:25.359  5902  5918 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf416e56d
09-26 11:24:25.359  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 11:24:25.360  5902  5902 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-26 11:24:25.361  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
,09-26 11:24:25.362  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 11:24:25.363  5902  5902 D HealthService: Received start request. Starting profile...
,09-26 11:24:25.365  5902  5902 I bt_bluedroid: get_profile_interface health
09-26 11:24:25.365  5902  5902 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-26 11:24:25.366  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:25.367  5902  5902 D PanService: Received start request. Starting profile...
09-26 11:24:25.367  5902  5902 D BluetoothPanServiceJni: initializeNative(L110): pan
09-26 11:24:25.367  5902  5902 I bt_bluedroid: get_profile_interface pan
09-26 11:24:25.367  5902  5918 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-26 11:24:25.369  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:25.370  5902  5902 D BluetoothMapService: Received start request. Starting profile...
09-26 11:24:25.370  5902  5902 D BluetoothMapService: start()
09-26 11:24:25.372  5902  5902 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-26 11:24:25.374  5902  5902 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 11:24:25.374  5902  5902 D BluetoothMapAppObserver: createReceiver()
,09-26 11:24:25.376  5902  5902 D BluetoothMapAppObserver: initObservers()
09-26 11:24:25.376  5902  5902 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-26 11:24:25.385  5902  5902 V SapService: SapBinder()
,09-26 11:24:25.385  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:25.385  5902  5902 D SapService: Received start request. Starting profile...
09-26 11:24:25.385  5902  5902 V SapService: start()
,09-26 11:24:25.387  5902  5902 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:25.387  5902  5902 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:25.387  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:25.387  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:25.388  5902  5931 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:25.388  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:25.389  5902  5902 V BluetoothAdapterState: isTurningOff()=false
,09-26 11:24:25.389  5902  5902 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:25.389  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 11:24:25.389  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:25.389  5902  5902 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:25.390  5902  5902 V BluetoothAdapterState: isTurningOn()=true
09-26 11:24:25.390  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:25.390  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 11:24:25.390  5902  5902 V BluetoothAdapterState: isTurningOff()=false
09-26 11:24:25.390  5902  5902 V BluetoothAdapterState: isTurningOn()=true
,09-26 11:24:25.390  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:25.390  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:25.391  5902  5902 V BluetoothAdapterState: isTurningOff()=false
,09-26 11:24:25.391  5902  5902 V BluetoothAdapterState: isTurningOn()=true
,09-26 11:24:25.391  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
09-26 11:24:25.391  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
09-26 11:24:25.392  5902  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 11:24:25.392  5902  5914 D BluetoothAdapterProperties: ScanMode =  20
09-26 11:24:25.392  5902  5914 D BluetoothAdapterProperties: State =  11
09-26 11:24:25.392  5902  5914 D BluetoothAdapterProperties: Setting state to 12
09-26 11:24:25.392  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-26 11:24:25.393  5902  5914 I BluetoothAdapterState: Entering OnState
09-26 11:24:25.393  5679  5690 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 11:24:25.394  5902  5918 D BluetoothAdapterProperties: Scan Mode:21
09-26 11:24:25.394  5902  5918 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 11:24:25.395   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 11:24:25.396  3745  4746 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:25.396   929   929 D BluetoothA2dp: Proxy object connected
09-26 11:24:25.397  3099  3110 D BluetoothMap: onBluetoothStateChange: up=true
,09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:25.398  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:25.398  5679  5693 D BluetoothPan: onBluetoothStateChange on: true
09-26 11:24:25.399  3099  3099 D BluetoothMap: Proxy object connected
09-26 11:24:25.399  3099  3099 D MapProfile: Bluetooth service connected
09-26 11:24:25.399  3099  3099 D BluetoothMap: getConnectedDevices()
09-26 11:24:25.400  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:25.400  5679  5690 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 11:24:25.402  5679  5693 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:25.403  5902  5902 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 11:24:25.403   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:25.403  5679  5690 D BluetoothMap: onBluetoothStateChange: up=true
09-26 11:24:25.403  5902  5902 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:25.404  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:25.405  3099  3947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:25.405  5902  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 11:24:25.405  3099  3110 D BluetoothPan: onBluetoothStateChange on: true
09-26 11:24:25.406  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:24:25.407  3099  3099 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 11:24:25.407  3099  3947 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 11:24:25.407  5902  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 11:24:25.407  3099  3099 D PanProfile: Bluetooth service connected
09-26 11:24:25.408  5902  5902 D ObexServerSockets: Succeed to create listening sockets 
09-26 11:24:25.408  5902  5902 D ObexServerSockets0: startAccept()
09-26 11:24:25.408  5902  5902 D ObexServerSockets0: prepareForNewConnect()
09-26 11:24:25.408   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:25.408   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 11:24:25.409  5679  5693 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 11:24:25.410  5902  5902 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-26 11:24:25.410  5902  5902 D BluetoothSdpJni: SDP Create record success - handle: 0
09-26 11:24:25.410  3099  3110 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 11:24:25.410  5902  5940 D ObexServerSockets0: Accepting socket connection...
09-26 11:24:25.411  5679  5679 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 11:24:25.411  5679  5679 D PanProfile: Bluetooth service connected
09-26 11:24:25.411  5902  5941 D ObexServerSockets0: Accepting socket connection...
,09-26 11:24:25.411  5679  5679 D BluetoothA2dp: Proxy object connected
09-26 11:24:25.412  3099  3099 D BluetoothInputDevice: Proxy object connected
09-26 11:24:25.412  3099  3099 D HidProfile: Bluetooth service connected
09-26 11:24:25.412  3099  3947 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 11:24:25.413  5679  5679 D BluetoothMap: Proxy object connected
09-26 11:24:25.413  5679  5679 D MapProfile: Bluetooth service connected
09-26 11:24:25.413  5679  5679 D BluetoothMap: getConnectedDevices()
09-26 11:24:25.414  3099  3099 D BluetoothA2dp: Proxy object connected
09-26 11:24:25.415  5679  5679 D BluetoothInputDevice: Proxy object connected
09-26 11:24:25.415  5679  5679 D HidProfile: Bluetooth service connected
09-26 11:24:25.415   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-26 11:24:25.416  5902  5902 D BluetoothMapService: onReceive
09-26 11:24:25.416  5902  5902 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-26 11:24:25.416  5902  5902 D BluetoothMapService: STATE_ON
09-26 11:24:25.419  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:25.419  5902  5944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 11:24:25.421  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:25.421  5902  5944 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 11:24:25.422  5902  5944 D BluetoothSdpJni: SDP Create record success - handle: 1
09-26 11:24:25.424  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 11:24:25.432  3541  3541 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 11:24:25.433  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,09-26 11:24:25.438  5679  5679 D BluetoothPbap: Proxy object connected
09-26 11:24:25.438  5679  5679 D PbapServerProfile: Bluetooth service connected
,09-26 11:24:25.444  5902  5902 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 11:24:25.444  5902  5902 D ObexServerSockets0: prepareForNewConnect()
,09-26 11:24:25.448  5902  5948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 11:24:25.453  3099  3099 D BluetoothPbap: Proxy object connected
,09-26 11:24:25.453  3099  3099 D PbapServerProfile: Bluetooth service connected
,09-26 11:24:25.466  5902  5952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 11:24:25.468  5902  5952 I BtOppRfcommListener: Accept thread started.
,09-26 11:24:25.499  5679  5690 D BluetoothHeadset: Proxy object connected
09-26 11:24:25.499  3745  3770 D BluetoothHeadset: Proxy object connected
09-26 11:24:25.499   929   929 D BluetoothHeadset: Proxy object connected
,09-26 11:24:25.499  3099  3110 D BluetoothHeadset: Proxy object connected
,09-26 11:24:25.500  3099  3099 D HeadsetProfile: Bluetooth service connected
09-26 11:24:25.500   929   929 D BluetoothHeadset: Proxy object connected
09-26 11:24:25.500   929   929 D BluetoothHeadset: Proxy object connected
09-26 11:24:25.501  5679  5679 D HeadsetProfile: Bluetooth service connected
,09-26 11:24:25.503  5679  5939 D BluetoothHeadset: Proxy object connected
09-26 11:24:25.504   929   946 D BluetoothHeadset: Proxy object connected
,09-26 11:24:25.504  5679  5679 D HeadsetProfile: Bluetooth service connected
09-26 11:24:25.505  3099  3947 D BluetoothHeadset: Proxy object connected
09-26 11:24:25.506  3099  3099 D HeadsetProfile: Bluetooth service connected
,09-26 11:24:25.508   929   946 D BluetoothHeadset: Proxy object connected
,09-26 11:24:25.509   929   946 D BluetoothHeadset: Proxy object connected
,09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:29.178  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 11:24:29.184  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:24:29.185  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:24:29.185  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f30537 removed from the list
,09-26 11:24:29.185  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:24:29.186  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:29.186  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:29.189  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 11:24:29.189  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9a2aa4 added. We now have 4 listener(s)
09-26 11:24:29.189  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:24:29.192   929  3850 D WifiService: setWifiEnabled: false pid=5608, uid=10077
09-26 11:24:29.192   929  3850 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 11:24:34.201  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:34.202   929  3788 D WifiService: setWifiEnabled: true pid=5608, uid=10077
,09-26 11:24:34.202   929  3788 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 11:24:34.215   507   920 D SoftapController: Softap fwReload - Ok
,09-26 11:24:34.221   507   920 D CommandListener: Setting iface cfg
09-26 11:24:34.221   507   920 D CommandListener: Trying to bring down wlan0
,09-26 11:24:34.223   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-26 11:24:34.229   929  2943 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 11:24:34.906   929  2943 D wifi    : set interface wlan0 flags (UP)
,09-26 11:24:34.908   929  2943 I WifiHAL : Initializing wifi
09-26 11:24:34.908   929  2943 I WifiHAL : Creating socket
09-26 11:24:34.912   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-26 11:24:34.916   929  2943 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-26 11:24:34.916   929  2943 D wifi    : Did set static halHandle = 0x7f6c01e680
,09-26 11:24:34.916   929  2943 D wifi    : halHandle = 0x7f6c01e680, mVM = 0x7f8864d140, mCls = 0x101466
09-26 11:24:34.916   929  2943 D wifi    : array field set
,09-26 11:24:34.917   929  2943 I WifiNative-HAL: interface[0] = wlan0
09-26 11:24:34.919   929  5957 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547272910464
09-26 11:24:34.919   929  5957 D wifi    : waitForHalEvents called, vm = 0x7f8864d140, obj = 0x101466, env = 0x7f6d6ff940
,09-26 11:24:34.968  5958  5958 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 11:24:34.989  5958  5958 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 11:24:34.999  5958  5958 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 11:24:34.999  5958  5958 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-26 11:24:35.020   929  2943 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:35.033  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 11:24:35.034   929  2943 D WifiConfigStore: Loading config and enabling all networks 
09-26 11:24:35.036  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 11:24:35.040  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 11:24:35.042  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 11:24:35.043  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:35.044  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:35.046   929  2943 D WifiConfigStore: loaded 0 passpoint configs
,09-26 11:24:35.047   929  2943 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-26 11:24:35.047   929  2943 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 11:24:35.048   929  2943 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-26 11:24:35.050   929  2943 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-26 11:24:35.050   929  2943 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-26 11:24:35.050   929  2943 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 11:24:35.050   929  2943 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-26 11:24:35.055   929  2943 D WifiNative-HAL: Setting external_sim to 1
09-26 11:24:35.055  4965  4965 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 11:24:35.056   929  2943 D wifi    : setting dfs flag to true, 0x7f719ae0e0
,09-26 11:24:35.057   929  2943 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 11:24:35.057   929  2943 D wifi    : setting scan oui 0x7f719ae0e0
09-26 11:24:35.057   929  2943 D WifiHAL : Sending mac address OUI
,09-26 11:24:35.061   929  2943 E native  : do suspend false
,09-26 11:24:35.070   929  2943 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-26 11:24:35.070   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-26 11:24:35.070   929   929 D RttService: SCAN_AVAILABLE : 3
09-26 11:24:35.071   929  3052 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-26 11:24:35.072   507   920 D CommandListener: Setting iface cfg
,09-26 11:24:35.074   929  2926 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-26 11:24:35.074   929  2926 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 11:24:35.085   929  2926 D WifiNative-HAL: p2pGetDeviceAddress
,09-26 11:24:35.085   929  2926 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 11:24:35.090   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=204749 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-26 11:24:38.280  5958  5958 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:38.289  5958  5958 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:38.294  5958  5958 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:38.301  5958  5958 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 11:24:38.333   929  2943 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-26 11:24:38.335   929  2943 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-26 11:24:38.335   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 11:24:38.345   929  2943 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 11:24:38.379   929  2943 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 11:24:38.382  5958  5958 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 11:24:38.798  5958  5958 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 11:24:38.848  5958  5958 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-26 11:24:38.850  5958  5958 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 11:24:38.861   929  2943 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 11:24:38.861   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 11:24:38.861   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 11:24:38.878   929  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 11:24:38.889   507   920 D CommandListener: Setting iface cfg
,09-26 11:24:38.895   929  2943 D WifiStateMachine: Start Dhcp Watchdog 3
,09-26 11:24:38.901   929  5963 D DhcpClient: Receive thread started
,09-26 11:24:38.906   929  2943 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-26 11:24:38.906   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:24:38.906   929  2945 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-26 11:24:38.989   929  2943 E native  : do suspend false
,09-26 11:24:39.003   929  5962 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 11:24:39.021   929  5963 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-26 11:24:39.022   929  5962 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-26 11:24:39.024   929  5962 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 11:24:39.036   929  5963 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 11:24:39.037   929  5962 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-26 11:24:39.041   507   920 D CommandListener: Setting iface cfg
,09-26 11:24:39.046   929  2943 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 11:24:39.052   929  5962 D DhcpClient: Scheduling renewal in 86399s
,09-26 11:24:39.061   929  2943 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-26 11:24:39.062   929  2943 D WifiConfigStore: No blacklist allowed without epno enabled
09-26 11:24:39.064   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-26 11:24:39.066   929  2945 D ConnectivityService: Adding iface wlan0 to network 102
,09-26 11:24:39.077   929  2943 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-26 11:24:39.118   929  2945 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-26 11:24:39.118   929  2945 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-26 11:24:39.120   929  2945 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-26 11:24:39.122   929  2945 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-26 11:24:39.124   929  2945 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-26 11:24:39.133   929  2945 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:24:39.137   929  2945 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-26 11:24:39.137   929  2945 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-26 11:24:39.137   929  2945 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-26 11:24:39.137   929  2943 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 11:24:39.137   929  2945 D ConnectivityService:    accepting network in place of null
09-26 11:24:39.137   929  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-26 11:24:39.138   929  2945 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 11:24:39.148   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208807, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 11:24:39.162   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 11:24:39.185   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 11:24:39.189   929  2945 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-26 11:24:39.189  3711  3877 W QCNEJ   : |CORE| network available: 102
09-26 11:24:39.189   929  2945 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 11:24:39.191   929  2945 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-26 11:24:39.191  3711  3877 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-26 11:24:39.192  3711  3877 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-26 11:24:39.192  3711  3877 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-26 11:24:39.193   929   946 D Tethering: MasterInitialState.processMessage what=3
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:39.199  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:24:39.203  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 11:24:39.205  4990  5014 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 11:24:39.206  4990  5014 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 11:24:39.206  4990  5014 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 11:24:39.206  4990  5014 E SarControlService: no key has been found,reset the power
09-26 11:24:39.206  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 11:24:39.206  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 11:24:39.206  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 11:24:39.207  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 11:24:39.207  5015  5015 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 11:24:39.207  4990  5027 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 11:24:39.208  4990  5027 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 11:24:39.208  4990  5027 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:39.208  5608  5608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:24:39.208  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-26 11:24:39.208  5015  5015 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 11:24:39.210  5608  5608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:39.213  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 11:24:39.214  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000f003000000000000ffffffff]
09-26 11:24:39.214  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 11:24:39.215  5015  5029 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-26 11:24:39.217  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:24:39.217  4990  5000 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-26 11:24:39.218  3828  3828 D SystemUpdateService: onCreate
,09-26 11:24:39.221  5015  5029 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dbc5302 HexData = [00000000f103000000000000ffffffff]
09-26 11:24:39.222  5015  5029 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 11:24:39.222   929  5960 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-26 11:24:39.222  5015  5029 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:39.222  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 11:24:39.222  5015  5015 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 11:24:39.222  4990  5001 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 11:24:39.223  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 11:24:39.224  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:39.225  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:39.225  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9a2aa4 removed from the list
09-26 11:24:39.225  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:24:39.225  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:39.225  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:39.227  5608  5974 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-26 11:24:39.227  5608  5974 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-26 11:24:39.236  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-26 11:24:39.240  3828  5347 I iu.UploadsManager: num queued entries: 0
,09-26 11:24:39.240  3828  5347 I iu.UploadsManager: num updated entries: 0
,09-26 11:24:39.243  3828  5973 I SystemUpdateService: active receiver: enabled
,09-26 11:24:39.246  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 11:24:39.248  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 11:24:39.249  5756  5756 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 11:24:39.253  5756  5756 D SprintDMHelper: simOperator: 
09-26 11:24:39.253  5756  5756 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 11:24:39.265  3828  5347 I iu.SyncManager: NEXT; no task
,09-26 11:24:39.271  3828  5973 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 11:24:39.284   929  5960 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 26 Sep 2016 15:24:39 GMT], X-Android-Received-Millis=[1474903479283], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474903479245]}
,09-26 11:24:39.285   929  2945 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-26 11:24:39.285   929  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-26 11:24:39.285   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-26 11:24:39.286  3828  5973 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-26 11:24:39.286  3828  5973 I SystemUpdateService: now status is 0 (complete)
,09-26 11:24:39.286  3828  5973 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 11:24:39.286   929  2945 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-26 11:24:39.286  3828  5973 I SystemUpdateService: file has been verified
,09-26 11:24:39.286  3828  5973 I SystemUpdateService: OTA package size = 21989297
,09-26 11:24:39.292  3828  5973 I SystemUpdateService: showing system update notification
,09-26 11:24:39.302  3828  3828 D SystemUpdateService: onDestroy
,09-26 11:24:39.421  4965  5979 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-26 11:24:42.238  5608  5986 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-26 11:24:42.238  5608  5974 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-26 11:24:42.239  5608  5974 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-26 11:24:42.239  5608  5986 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-26 11:24:42.240  5608  5986 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 11:24:42.240  5608  5974 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 11:24:42.243  5608  5974 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 11:24:42.243  5608  5986 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 11:24:42.245  5608  5989 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Sender)
09-26 11:24:42.245  5608  5988 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender)
,09-26 11:24:42.247  5608  5986 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-26 11:24:42.248  5608  5974 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-26 11:24:42.252  5608  5990 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver)
,09-26 11:24:42.254  5608  5991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Receiver)
,09-26 11:24:42.255  5608  5991 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: OutgoingSocketThread/Receiver)
,09-26 11:24:42.255  5608  5991 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-26 11:24:42.256  5608  5991 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-26 11:24:42.256  5608  5990 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver)
,09-26 11:24:42.256  5608  5990 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-26 11:24:42.256  5608  5990 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-26 11:24:45.236  5608  5654 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-26 11:24:45.238  5608  5654 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-26 11:24:45.245  5608  5654 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3af0826 Bundle[{}]
,09-26 11:24:45.246  5608  5654 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-26 11:24:45.247  5608  5654 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-26 11:24:45.248  5608  5654 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-26 11:24:45.249  5608  5654 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-26 11:24:45.250  5608  5654 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-26 11:24:45.252  5608  5654 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-26 11:24:45.263  5608  5654 I System.out: Running OutgoingSocketThread
,09-26 11:24:45.268  5608  5992 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-26 11:24:45.268  5608  5992 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-26 11:24:47.142   929  2945 D ConnectivityService: handlePromptUnvalidated 102
,09-26 11:24:48.277  5608  5993 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-26 11:24:48.277  5608  5993 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-26 11:24:48.277  5608  5992 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-26 11:24:48.277  5608  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 11:24:48.277  5608  5992 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-26 11:24:48.278  5608  5992 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 11:24:48.280  5608  5992 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 11:24:48.280  5608  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 11:24:48.283  5608  5995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Sender)
,09-26 11:24:48.284  5608  5993 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-26 11:24:48.284  5608  5992 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-26 11:24:48.287  5608  5996 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender)
,09-26 11:24:48.289  5608  5997 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Receiver)
,09-26 11:24:48.291  5608  5998 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver)
,09-26 11:24:48.291  5608  5997 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Receiver)
09-26 11:24:48.291  5608  5997 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-26 11:24:48.292  5608  5997 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-26 11:24:48.292  5608  5998 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver)
09-26 11:24:48.292  5608  5998 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-26 11:24:48.292  5608  5998 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-26 11:24:48.562   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:24:48.563   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:24:50.086   929  2943 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,09-26 11:24:51.276  5608  5654 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
,09-26 11:24:51.277  5608  5654 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-26 11:24:51.277  5608  5654 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
09-26 11:24:51.282  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 11:24:51.284  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a500d added. We now have 3 listener(s)
,09-26 11:24:51.289  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 11:24:51.289  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 11:24:51.289  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 11:24:51.289  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 11:24:51.290  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@863bc2 added. We now have 4 listener(s)
09-26 11:24:51.290  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 11:24:51.291  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 11:24:51.295  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:51.303  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:24:51.306  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 11:24:51.306  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 11:24:51.307  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:24:51.307  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:24:51.307  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 11:24:51.307  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:24:51.307  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:51.307  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:24:51.308  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 11:24:51.308  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a500d removed from the list
09-26 11:24:51.308  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:51.308  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@863bc2 removed from the list
,09-26 11:24:51.310  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:51.314  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:51.314  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:24:51.315  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:51.315  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:51.315  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:24:51.317  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:24:51.317  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:24:51.317  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:24:51.317  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@863bc2 not in the list
09-26 11:24:51.317  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:51.317  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:24:51.319  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:24:51.319  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:24:51.319  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:24:51.319  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@863bc2 not in the list
09-26 11:24:51.319  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:24:51.319  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:51.319  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:51.319  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a500d not in the list
09-26 11:24:51.320  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 11:24:51.320  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa14d10 added. We now have 3 listener(s)
09-26 11:24:51.322  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 11:24:51.322  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 11:24:51.322  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 11:24:51.322  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 11:24:51.322  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788e009 added. We now have 4 listener(s)
,09-26 11:24:51.322  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 11:24:51.323  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 11:24:51.326  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:51.330  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:24:51.332  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 11:24:51.332  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 11:24:51.332  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:24:51.332  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 11:24:51.333  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 11:24:51.333  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:24:51.333  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 11:24:51.336  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:51.339  5608  5654 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:24:51.339  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 11:24:51.339  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:51.343  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 11:24:51.343  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 11:24:51.343  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:24:51.346  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 11:24:51.346  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 11:24:51.346  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 11:24:51.347  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:24:51.349  5902  5938 D BtGatt.GattService: registerClient() - UUID=01758c41-2266-48b6-a2eb-3082395c87b5
09-26 11:24:51.350  5902  5918 D BtGatt.GattService: onClientRegistered() - UUID=01758c41-2266-48b6-a2eb-3082395c87b5, clientIf=5
09-26 11:24:51.351  5608  5619 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 11:24:51.352  5902  5929 D BtGatt.GattService: start scan with filters
,09-26 11:24:51.355  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 11:24:51.355  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 11:24:51.355  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-26 11:24:51.355  5902  5921 D BtGatt.ScanManager: handling starting scan
,09-26 11:24:51.356  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 11:24:51.357  5902  5921 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bc028b
09-26 11:24:51.358  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 11:24:51.359  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 11:24:51.359  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 11:24:51.360  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 11:24:51.362  5608  5654 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-26 11:24:51.363  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 11:24:51.363  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 11:24:51.363  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:51.363  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 11:24:51.363  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 11:24:51.363  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 11:24:51.363  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 11:24:51.363  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 11:24:51.363  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 11:24:51.363  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 11:24:51.364  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:24:51.364  5902  5918 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 11:24:51.364  5902  5938 D BtGatt.GattService: stopScan() - queue size =1
09-26 11:24:51.365  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:24:51.365  5902  5921 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 11:24:51.365  5902  5929 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 11:24:51.366  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:24:51.366  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 11:24:51.366  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 11:24:51.366  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 11:24:51.366  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 11:24:51.369  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:24:51.369  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:24:51.369  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 11:24:51.370  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 11:24:51.370  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:24:51.372  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:24:51.372  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:24:51.372  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 11:24:51.373  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 11:24:51.373  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:24:51.374  5902  5921 D BtGatt.ScanManager: Starting BLE batch scan
09-26 11:24:51.374  5902  5921 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 11:24:51.376  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:24:51.376  5608  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 11:24:51.381  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:24:51.381  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 11:24:51.381  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:24:51.381  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 11:24:51.382  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 11:24:51.384  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 11:24:51.384  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:24:51.384  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:24:51.384  5902  5918 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 11:24:51.384  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:24:51.387  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:24:51.387  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:24:51.388  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 11:24:51.390  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 11:24:51.391  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 11:24:51.391  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:24:51.398  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-26 11:24:51.398  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:24:51.398  5902  5921 D BtGatt.ScanManager: stopping BLe Batch
,09-26 11:24:51.404  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 11:24:51.405  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:24:51.405  5902  5921 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 11:24:51.410  5902  5918 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-26 11:24:51.410  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:24:51.891  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-26 11:24:51.892  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 11:24:51.892  5608  5608 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 11:24:54.372  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:24:54.372  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 11:24:54.372  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 11:24:54.373  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:24:54.373  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:24:54.373  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 11:24:54.373  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-26 11:24:54.373  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa14d10 removed from the list
,09-26 11:24:54.373  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 11:24:54.374  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788e009 removed from the list
09-26 11:24:54.374  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 11:24:54.374  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:54.376  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:24:54.376  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:54.380  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 11:24:54.380  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:24:54.380  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:24:54.382  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:24:54.382  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:24:54.382  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:24:54.382  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:54.383  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788e009 not in the list
09-26 11:24:54.383  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:54.383  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:54.385  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:24:54.387  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:24:54.387  5608  5654 D BluetoothLeScanner: could not find callback wrapper
,09-26 11:24:54.387  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:24:54.388  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:24:54.388  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:24:54.388  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:54.388  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788e009 not in the list
,09-26 11:24:54.388  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:24:54.388  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:54.388  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:54.389  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa14d10 not in the list
09-26 11:24:54.390  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 11:24:54.390  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63894e6 added. We now have 3 listener(s)
09-26 11:24:54.393  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 11:24:54.393  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 11:24:54.393  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 11:24:54.393  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 11:24:54.393  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359aa27 added. We now have 4 listener(s)
09-26 11:24:54.393  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 11:24:54.394  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 11:24:54.397  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:54.402  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:24:54.404  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 11:24:54.404  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 11:24:54.404  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 11:24:54.405  5608  5654 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-26 11:24:54.405  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-26 11:24:54.406  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 11:24:54.406  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-26 11:24:54.406  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-26 11:24:54.406  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:24:54.407  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-26 11:24:54.408  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-26 11:24:54.408  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-26 11:24:54.408  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-26 11:24:54.408  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-26 11:24:54.408  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:24:54.408  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:24:54.409  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:54.409  5608  5999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 11:24:54.410  5912  5912 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34839]" dev="sockfs" ino=34839 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-26 11:24:54.410  5912  5912 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34839]" dev="sockfs" ino=34839 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 11:24:54.412  5608  5654 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:24:54.413  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 11:24:54.413  5608  5999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-26 11:24:54.414  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:24:54.414  5608  5608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-26 11:24:54.418  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 11:24:54.419  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 11:24:54.419  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:24:54.421  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-26 11:24:54.421  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 11:24:54.422  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-26 11:24:54.423  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-26 11:24:54.423  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-26 11:24:54.423  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-26 11:24:54.424  5608  5654 D BluetoothAdapter: STATE_ON
,09-26 11:24:54.429  5902  5912 D BtGatt.GattService: registerClient() - UUID=47c27e03-075a-457e-a54a-1b67a4c61945
,09-26 11:24:54.430  5902  5918 D BtGatt.GattService: onClientRegistered() - UUID=47c27e03-075a-457e-a54a-1b67a4c61945, clientIf=5
09-26 11:24:54.430  5608  5619 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-26 11:24:54.432  5902  5920 D BtGatt.AdvertiseManager: message : 0
,09-26 11:24:54.434  5902  5920 D BtGatt.AdvertiseManager: starting multi advertising
,09-26 11:24:54.444  5902  5918 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-26 11:24:54.450  5902  5918 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-26 11:24:54.451  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-26 11:24:54.451  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-26 11:24:54.452  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 11:24:54.454  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 11:24:54.454  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-26 11:24:54.454  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-26 11:24:54.454  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-26 11:24:54.454  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-26 11:24:54.454  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-26 11:24:54.455  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 11:24:54.457  5608  5608 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-26 11:24:54.457  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-26 11:24:54.958  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-26 11:24:54.958  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 11:24:54.959  5608  5608 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 11:24:55.478   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=225137, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:24:57.457  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:24:57.457  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-26 11:24:57.457  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 11:24:57.457  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 11:24:57.458  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-26 11:24:57.458  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-26 11:24:57.458  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 11:24:57.458  5608  5999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-26 11:24:57.458  5608  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 11:24:57.458  5608  5999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-26 11:24:57.459  5608  5999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 11:24:57.459  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 11:24:57.459  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 11:24:57.459  5608  5608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-26 11:24:57.459  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 11:24:57.459  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 11:24:57.459  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 11:24:57.462  5608  5654 D BluetoothAdapter: STATE_ON
,09-26 11:24:57.462  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:24:57.462  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:24:57.462  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-26 11:24:57.464  5902  5920 D BtGatt.AdvertiseManager: message : 1
09-26 11:24:57.465  5902  5920 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-26 11:24:57.480  5902  5918 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-26 11:24:57.480  5902  5918 D BtGatt.GattService: Client app is not null!
09-26 11:24:57.482  5902  5913 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 11:24:57.483  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:24:57.483  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-26 11:24:57.483  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-26 11:24:57.483  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-26 11:24:57.483  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-26 11:24:57.485  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:24:57.486  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 11:24:57.486  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:24:57.486  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 11:24:57.488  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 11:24:57.489  5608  5608 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-26 11:24:57.489  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:57.489  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:24:57.489  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 11:24:57.489  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:24:57.489  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63894e6 removed from the list
09-26 11:24:57.489  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:24:57.489  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:57.489  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:24:57.489  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359aa27 removed from the list
09-26 11:24:57.489  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:24:57.490  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:24:57.495  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:24:57.496  5608  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 11:24:57.501  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:24:57.502  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 11:24:57.502  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:24:57.502  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:24:57.503  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:57.506  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:24:57.506  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:24:57.508  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:24:57.508  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 11:24:57.508  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:24:57.509  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:24:57.509  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:24:57.509  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:24:57.509  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:57.509  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:24:57.509  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359aa27 not in the list
,09-26 11:24:57.509  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:24:57.509  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 11:24:57.514  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 11:24:57.514  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:24:57.515  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:24:57.518  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:24:57.518  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:24:57.518  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:57.520  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 11:24:57.521  5608  5654 D BluetoothAdapter: STATE_ON
,09-26 11:24:57.521  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:24:57.521  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:24:57.521  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:24:57.521  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:24:57.521  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:24:57.522  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359aa27 not in the list
,09-26 11:24:57.522  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:24:57.522  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:24:57.522  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:24:57.522  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63894e6 not in the list
09-26 11:24:57.523  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 11:24:57.523  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef69a6c added. We now have 3 listener(s)
09-26 11:24:57.525  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 11:24:57.525  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 11:24:57.525  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 11:24:57.525  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 11:24:57.526  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94d835 added. We now have 4 listener(s)
09-26 11:24:57.526  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 11:24:57.527  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 11:24:57.531  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:24:57.536  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:24:57.539  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:24:57.539  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:24:57.539  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:24:57.539  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 11:24:57.539  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 11:24:57.539  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 11:24:57.539  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:24:57.542  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:57.543  5608  5654 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:24:57.543  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 11:24:57.545  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 11:24:57.548  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 11:24:57.549  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 11:24:57.549  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 11:24:57.553  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-26 11:24:57.553  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 11:24:57.553  5608  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 11:24:57.554  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:24:57.556  5902  5913 D BtGatt.GattService: registerClient() - UUID=d4d4850f-5735-42d5-8714-9c95b79203a1
09-26 11:24:57.556  5902  5918 D BtGatt.GattService: onClientRegistered() - UUID=d4d4850f-5735-42d5-8714-9c95b79203a1, clientIf=5
09-26 11:24:57.557  5608  5619 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 11:24:57.557  5902  5938 D BtGatt.GattService: start scan with filters
,09-26 11:24:57.560  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-26 11:24:57.560  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 11:24:57.560  5902  5921 D BtGatt.ScanManager: handling starting scan
09-26 11:24:57.560  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 11:24:57.561  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 11:24:57.563  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 11:24:57.563  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 11:24:57.563  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 11:24:57.565  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 11:24:57.568  5902  5918 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 11:24:57.568  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:24:57.568  5902  5921 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 11:24:57.575  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-26 11:24:57.575  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:24:57.575  5902  5921 D BtGatt.ScanManager: Starting BLE batch scan
09-26 11:24:57.575  5902  5921 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 11:24:57.585  5902  5918 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-26 11:24:57.585  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:24:57.590  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-26 11:24:57.590  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 11:24:58.018  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 11:24:58.064  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 11:24:58.065  5608  5608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:24:58.065  5608  5608 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 11:24:58.564   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:24:59.565   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:00.048   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:25:00.566   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:00.575  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 11:25:00.575  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 11:25:00.575  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 11:25:00.575  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:25:00.575  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 11:25:00.576  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 11:25:00.576  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 11:25:00.576  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 11:25:00.576  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 11:25:00.576  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 11:25:00.576  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 11:25:00.578  5608  5654 D BluetoothAdapter: STATE_ON
,09-26 11:25:00.580  5902  5943 D BtGatt.GattService: stopScan() - queue size =1
,09-26 11:25:00.582  5902  5929 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 11:25:00.583  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:25:00.583  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 11:25:00.583  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 11:25:00.583  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-26 11:25:00.584  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 11:25:00.588  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:25:00.588  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:25:00.588  5608  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 11:25:00.589  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:25:00.590  5902  5902 D BtGatt.ScanManager: awakened up at time 230249
09-26 11:25:00.591  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:25:00.595  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:25:00.595  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:25:00.595  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:25:00.595  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 11:25:00.595  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:25:00.595  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 11:25:00.596  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 11:25:00.596  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef69a6c removed from the list
09-26 11:25:00.596  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:25:00.596  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94d835 removed from the list
,09-26 11:25:00.596  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:25:00.596  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:25:00.597  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 11:25:00.597  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:25:00.598  5902  5921 D BtGatt.ScanManager: stopping BLe Batch
09-26 11:25:00.600  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:25:00.600  5608  5608 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 11:25:00.607  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 11:25:00.607  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:25:00.608  5902  5921 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 11:25:00.609  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 11:25:00.610  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 11:25:00.610  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 11:25:00.610  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 11:25:00.611  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:25:00.614  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:25:00.614  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:25:00.615  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:25:00.616  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:25:00.616  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:25:00.616  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:25:00.617  5608  5654 D BluetoothLeScanner: could not find callback wrapper
09-26 11:25:00.617  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:25:00.617  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:25:00.617  5608  5608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 11:25:00.617  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94d835 not in the list
09-26 11:25:00.617  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:25:00.617  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 11:25:00.622  5608  5608 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 11:25:00.622  5608  5608 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 11:25:00.623  5608  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:25:00.626  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:25:00.626  5608  5608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 11:25:00.626  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:25:00.627  5902  5918 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-26 11:25:00.627  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 11:25:00.628  5902  5918 D BtGatt.GattService: current time is 230287288140
09-26 11:25:00.628  5902  5918 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -83, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 11:25:00.629  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:25:00.630  5902  5918 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 11:25:00.630  5608  5654 D BluetoothAdapter: STATE_ON
09-26 11:25:00.630  5608  5654 D BluetoothLeScanner: could not find callback wrapper
,09-26 11:25:00.630  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 11:25:00.630  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:25:00.630  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 11:25:00.630  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:25:00.630  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94d835 not in the list
09-26 11:25:00.630  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:25:00.630  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:25:00.630  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:25:00.630  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef69a6c not in the list
09-26 11:25:00.630  5902  5918 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-26 11:25:00.631  5902  5918 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 11:25:00.631  5902  5918 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 11:25:00.631  5902  5918 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 11:25:00.631  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 11:25:00.631  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@756c322 added. We now have 3 listener(s)
09-26 11:25:00.631  5902  5918 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-26 11:25:00.634  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 11:25:00.634  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 11:25:00.634  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 11:25:00.634  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 11:25:00.635  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db1a1b3 added. We now have 4 listener(s)
09-26 11:25:00.635  5608  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 11:25:00.637  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 11:25:00.641  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 11:25:00.645  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 11:25:00.647  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 11:25:00.648  5608  5654 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 11:25:00.648  5608  5654 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 11:25:00.648  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 11:25:00.648  5608  5654 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 11:25:00.648  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:25:00.648  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:25:00.648  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 11:25:00.648  5608  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 11:25:00.648  5608  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@756c322 removed from the list
09-26 11:25:00.648  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:25:00.648  5608  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db1a1b3 removed from the list
,09-26 11:25:00.650  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:25:00.650  5608  5654 D io.jxcore.node.ConnectivityMonitor: stop
09-26 11:25:00.650  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 11:25:00.651  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 11:25:00.651  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:25:00.652  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 11:25:00.652  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:25:00.652  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:25:00.652  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db1a1b3 not in the list
09-26 11:25:00.652  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:25:00.652  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:25:00.653  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 11:25:00.653  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 11:25:00.653  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 11:25:00.653  5608  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 11:25:00.653  5608  5654 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db1a1b3 not in the list
09-26 11:25:00.653  5608  5654 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 11:25:00.653  5608  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 11:25:00.653  5608  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 11:25:00.653  5608  5654 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@756c322 not in the list
,09-26 11:25:00.654  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-26 11:25:00.655  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 11:25:00.655  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-26 11:25:00.655  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 11:25:00.655  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-26 11:25:00.655  5608  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-26 11:25:01.127  5608  5608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 11:25:01.567   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:02.568   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:02.666  5608  6000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: My test thread name)
,09-26 11:25:03.069   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:25:03.568   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:25:04.665  5608  5654 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 190
,09-26 11:25:04.665  5608  5654 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 190, name: My test thread name)
,09-26 11:25:04.670  5608  6001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-26 11:25:04.670  5608  6001 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: My test thread name)
09-26 11:25:04.671  5608  6001 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-26 11:25:04.676  5608  5654 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 11:25:04.677  5608  6000 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-26 11:25:04.682  5608  6002 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name)
09-26 11:25:04.682  5608  6002 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 195, thread name: My test thread name): Test exception.
09-26 11:25:04.682  5608  6002 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-26 11:25:04.693  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-26 11:25:04.693  5608  5654 I jxcore-log: 
,09-26 11:25:04.695  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-26 11:25:04.695  5608  5654 I jxcore-log: 
,09-26 11:25:04.696  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-26 11:25:04.696  5608  5654 I jxcore-log: 
09-26 11:25:04.698  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-26 11:25:04.698  5608  5654 I jxcore-log: 
09-26 11:25:04.700  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'Total duration:  101023'
09-26 11:25:04.700  5608  5654 I jxcore-log: 
,09-26 11:25:04.709  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-26 11:25:04.709  5608  5654 I jxcore-log: 
,09-26 11:25:04.721  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.721  5608  5654 I jxcore-log: 
,09-26 11:25:04.724  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.724  5608  5654 I jxcore-log: 
,09-26 11:25:04.725  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.725  5608  5654 I jxcore-log: 
,09-26 11:25:04.727  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.727  5608  5654 I jxcore-log: 
,09-26 11:25:04.728  5608  5608 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-26 11:25:04.728  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 11:25:04.728  5608  5654 I jxcore-log: 
,09-26 11:25:04.730  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 11:25:04.730  5608  5654 I jxcore-log: 
,09-26 11:25:04.732  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.732  5608  5654 I jxcore-log: 
09-26 11:25:04.732  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.732  5608  5654 I jxcore-log: 
09-26 11:25:04.733  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 11:25:04.733  5608  5654 I jxcore-log: 
09-26 11:25:04.733  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 11:25:04.733  5608  5654 I jxcore-log: 
09-26 11:25:04.734  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 11:25:04.734  5608  5654 I jxcore-log: 
,09-26 11:25:04.735  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.735  5608  5654 I jxcore-log: 
,09-26 11:25:04.736  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.736  5608  5654 I jxcore-log: 
,09-26 11:25:04.737  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.737  5608  5654 I jxcore-log: 
,09-26 11:25:04.739  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.739  5608  5654 I jxcore-log: 
,09-26 11:25:04.740  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.740  5608  5654 I jxcore-log: 
,09-26 11:25:04.741  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.741  5608  5654 I jxcore-log: 
,09-26 11:25:04.742  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.742  5608  5654 I jxcore-log: 
09-26 11:25:04.743  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.743  5608  5654 I jxcore-log: 
09-26 11:25:04.744  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.744  5608  5654 I jxcore-log: 
,09-26 11:25:04.745  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.745  5608  5654 I jxcore-log: 
,09-26 11:25:04.746  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.746  5608  5654 I jxcore-log: 
,09-26 11:25:04.747  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.747  5608  5654 I jxcore-log: 
,09-26 11:25:04.751  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.751  5608  5654 I jxcore-log: 
,09-26 11:25:04.752  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.752  5608  5654 I jxcore-log: 
,09-26 11:25:04.753  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.753  5608  5654 I jxcore-log: 
,09-26 11:25:04.754  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.754  5608  5654 I jxcore-log: 
,09-26 11:25:04.755  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.755  5608  5654 I jxcore-log: 
09-26 11:25:04.756  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.756  5608  5654 I jxcore-log: 
09-26 11:25:04.756  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.756  5608  5654 I jxcore-log: 
09-26 11:25:04.756  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.756  5608  5654 I jxcore-log: 
09-26 11:25:04.757  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.757  5608  5654 I jxcore-log: 
09-26 11:25:04.757  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.757  5608  5654 I jxcore-log: 
,09-26 11:25:04.758  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.758  5608  5654 I jxcore-log: 
,09-26 11:25:04.759  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.759  5608  5654 I jxcore-log: 
09-26 11:25:04.760  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.760  5608  5654 I jxcore-log: 
,09-26 11:25:04.761  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.761  5608  5654 I jxcore-log: 
,09-26 11:25:04.762  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.762  5608  5654 I jxcore-log: 
,09-26 11:25:04.762  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.762  5608  5654 I jxcore-log: 
,09-26 11:25:04.763  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.763  5608  5654 I jxcore-log: 
,09-26 11:25:04.764  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 11:25:04.764  5608  5654 I jxcore-log: 
,09-26 11:25:04.765  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.765  5608  5654 I jxcore-log: 
09-26 11:25:04.765  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 11:25:04.765  5608  5654 I jxcore-log: 
,09-26 11:25:04.766  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.766  5608  5654 I jxcore-log: 
,09-26 11:25:04.766  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.766  5608  5654 I jxcore-log: 
09-26 11:25:04.767  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.767  5608  5654 I jxcore-log: 
,09-26 11:25:04.768  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.768  5608  5654 I jxcore-log: 
09-26 11:25:04.769  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.769  5608  5654 I jxcore-log: 
,09-26 11:25:04.769  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 11:25:04.769  5608  5654 I jxcore-log: 
09-26 11:25:04.770  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.770  5608  5654 I jxcore-log: 
09-26 11:25:04.771  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-26 11:25:04.771  5608  5654 I jxcore-log: 
09-26 11:25:04.771  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.771  5608  5654 I jxcore-log: 
09-26 11:25:04.772  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 11:25:04.772  5608  5654 I jxcore-log: 
09-26 11:25:04.773  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 11:25:04.773  5608  5654 I jxcore-log: 
09-26 11:25:04.773  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 11:25:04.773  5608  5654 I jxcore-log: 
09-26 11:25:04.774  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 11:25:04.774  5608  5654 I jxcore-log: 
09-26 11:25:04.777  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-26 11:25:04.777  5608  5654 I jxcore-log: 
09-26 11:25:04.778  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - WARN testUtils: 'myNameCallback not set!'
09-26 11:25:04.778  5608  5654 I jxcore-log: 
09-26 11:25:04.779  5608  5654 I jxcore-log: 2016-09-26 15:25:04 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-26 11:25:04.779  5608  5654 I jxcore-log: 
,09-26 11:25:06.832  5608  5654 I jxcore-log: 2016-09-26 15:25:06 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-26 11:25:06.832  5608  5654 I jxcore-log: 
,09-26 11:25:07.161  5608  5654 I jxcore-log: 2016-09-26 15:25:07 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-26 11:25:07.161  5608  5654 I jxcore-log: 
,09-26 11:25:07.175  5608  5654 I jxcore-log: 2016-09-26 15:25:07 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-26 11:25:07.175  5608  5654 I jxcore-log: 
,09-26 11:25:08.300  5608  5654 I jxcore-log: 2016-09-26 15:25:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-26 11:25:08.300  5608  5654 I jxcore-log: 
,09-26 11:25:08.452  5608  5654 I jxcore-log: 2016-09-26 15:25:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-26 11:25:08.452  5608  5654 I jxcore-log: 
,09-26 11:25:08.458  5608  5654 I jxcore-log: 2016-09-26 15:25:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-26 11:25:08.458  5608  5654 I jxcore-log: 
,09-26 11:25:08.462  5608  5654 I jxcore-log: 2016-09-26 15:25:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-26 11:25:08.462  5608  5654 I jxcore-log: 
,09-26 11:25:08.569   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:08.999  5608  5654 I jxcore-log: 2016-09-26 15:25:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-26 11:25:08.999  5608  5654 I jxcore-log: 
,09-26 11:25:09.051  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-26 11:25:09.051  5608  5654 I jxcore-log: 
,09-26 11:25:09.063  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-26 11:25:09.063  5608  5654 I jxcore-log: 
,09-26 11:25:09.075  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-26 11:25:09.075  5608  5654 I jxcore-log: 
,09-26 11:25:09.337  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-26 11:25:09.337  5608  5654 I jxcore-log: 
,09-26 11:25:09.460  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-26 11:25:09.460  5608  5654 I jxcore-log: 
,09-26 11:25:09.570   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:09.691  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-26 11:25:09.691  5608  5654 I jxcore-log: 
,09-26 11:25:09.702  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-26 11:25:09.702  5608  5654 I jxcore-log: 
,09-26 11:25:09.708  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-26 11:25:09.708  5608  5654 I jxcore-log: 
,09-26 11:25:09.714  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-26 11:25:09.714  5608  5654 I jxcore-log: 
,09-26 11:25:09.744  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-26 11:25:09.744  5608  5654 I jxcore-log: 
,09-26 11:25:09.781  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-26 11:25:09.781  5608  5654 I jxcore-log: 
,09-26 11:25:09.789  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-26 11:25:09.789  5608  5654 I jxcore-log: 
,09-26 11:25:09.795  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-26 11:25:09.795  5608  5654 I jxcore-log: 
,09-26 11:25:09.811  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-26 11:25:09.811  5608  5654 I jxcore-log: 
,09-26 11:25:09.815  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-26 11:25:09.815  5608  5654 I jxcore-log: 
,09-26 11:25:09.821  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-26 11:25:09.821  5608  5654 I jxcore-log: 
,09-26 11:25:09.835  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-26 11:25:09.835  5608  5654 I jxcore-log: 
,09-26 11:25:09.856  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-26 11:25:09.856  5608  5654 I jxcore-log: 
,09-26 11:25:09.865  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-26 11:25:09.865  5608  5654 I jxcore-log: 
,09-26 11:25:09.876  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-26 11:25:09.876  5608  5654 I jxcore-log: 
,09-26 11:25:09.885  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-26 11:25:09.885  5608  5654 I jxcore-log: 
,09-26 11:25:09.897  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-26 11:25:09.897  5608  5654 I jxcore-log: 
,09-26 11:25:09.907  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-26 11:25:09.907  5608  5654 I jxcore-log: 
,09-26 11:25:09.912  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-26 11:25:09.912  5608  5654 I jxcore-log: 
,09-26 11:25:09.932  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js'
09-26 11:25:09.932  5608  5654 I jxcore-log: 
,09-26 11:25:09.940  5608  5654 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-26 11:25:09.941  5608  5654 I jxcore-log: 2016-09-26 15:25:09 - INFO testUtils: 'BLE multiple advertisement supported'
09-26 11:25:09.941  5608  5654 I jxcore-log: 
,09-26 11:25:10.027  5608  5654 I jxcore-log: 2016-09-26 15:25:10 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:10.027  5608  5654 I jxcore-log: 
,09-26 11:25:10.251  5608  5654 I jxcore-log: 2016-09-26 15:25:10 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:10.251  5608  5654 I jxcore-log: 
,09-26 11:25:10.259  5608  5654 I jxcore-log: 2016-09-26 15:25:10 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:10.259  5608  5654 I jxcore-log: 
,09-26 11:25:10.571   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:10.576  5608  5654 I jxcore-log: 2016-09-26 15:25:10 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:10.576  5608  5654 I jxcore-log: 
,09-26 11:25:10.583  5608  5654 I jxcore-log: 2016-09-26 15:25:10 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:10.583  5608  5654 I jxcore-log: 
,09-26 11:25:11.321  5608  5654 I jxcore-log: 2016-09-26 15:25:11 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:11.321  5608  5654 I jxcore-log: 
,09-26 11:25:11.333  5608  5654 I jxcore-log: 2016-09-26 15:25:11 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:11.333  5608  5654 I jxcore-log: 
,09-26 11:25:11.572   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:12.375  5608  5654 I jxcore-log: 2016-09-26 15:25:12 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:12.375  5608  5654 I jxcore-log: 
,09-26 11:25:12.382  5608  5654 I jxcore-log: 2016-09-26 15:25:12 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:12.382  5608  5654 I jxcore-log: 
,09-26 11:25:12.573   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:13.423  5608  5654 I jxcore-log: 2016-09-26 15:25:13 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:13.423  5608  5654 I jxcore-log: 
,09-26 11:25:13.429  5608  5654 I jxcore-log: 2016-09-26 15:25:13 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:13.429  5608  5654 I jxcore-log: 
,09-26 11:25:13.574   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:25:14.473  5608  5654 I jxcore-log: 2016-09-26 15:25:14 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:14.473  5608  5654 I jxcore-log: 
,09-26 11:25:14.482  5608  5654 I jxcore-log: 2016-09-26 15:25:14 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:14.482  5608  5654 I jxcore-log: 
,09-26 11:25:15.004   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:25:15.528  5608  5654 I jxcore-log: 2016-09-26 15:25:15 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:15.528  5608  5654 I jxcore-log: 
,09-26 11:25:15.536  5608  5654 I jxcore-log: 2016-09-26 15:25:15 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:15.536  5608  5654 I jxcore-log: 
,09-26 11:25:16.573  5608  5654 I jxcore-log: 2016-09-26 15:25:16 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:16.573  5608  5654 I jxcore-log: 
,09-26 11:25:16.581  5608  5654 I jxcore-log: 2016-09-26 15:25:16 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:16.581  5608  5654 I jxcore-log: 
,09-26 11:25:17.640  5608  5654 I jxcore-log: 2016-09-26 15:25:17 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:17.640  5608  5654 I jxcore-log: 
,09-26 11:25:17.648  5608  5654 I jxcore-log: 2016-09-26 15:25:17 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:17.648  5608  5654 I jxcore-log: 
,09-26 11:25:18.719  5608  5654 I jxcore-log: 2016-09-26 15:25:18 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:18.719  5608  5654 I jxcore-log: 
,09-26 11:25:18.727  5608  5654 I jxcore-log: 2016-09-26 15:25:18 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:18.727  5608  5654 I jxcore-log: 
,09-26 11:25:19.123   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:25:19.771  5608  5654 I jxcore-log: 2016-09-26 15:25:19 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:19.771  5608  5654 I jxcore-log: 
,09-26 11:25:19.780  5608  5654 I jxcore-log: 2016-09-26 15:25:19 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:19.780  5608  5654 I jxcore-log: 
,09-26 11:25:20.813  5608  5654 I jxcore-log: 2016-09-26 15:25:20 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:20.813  5608  5654 I jxcore-log: 
,09-26 11:25:20.821  5608  5654 I jxcore-log: 2016-09-26 15:25:20 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:20.821  5608  5654 I jxcore-log: 
,09-26 11:25:21.999  5608  5654 I jxcore-log: 2016-09-26 15:25:21 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:21.999  5608  5654 I jxcore-log: 
,09-26 11:25:22.010  5608  5654 I jxcore-log: 2016-09-26 15:25:22 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:22.010  5608  5654 I jxcore-log: 
,09-26 11:25:23.046  5608  5654 I jxcore-log: 2016-09-26 15:25:23 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:23.046  5608  5654 I jxcore-log: 
,09-26 11:25:23.052  5608  5654 I jxcore-log: 2016-09-26 15:25:23 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:23.052  5608  5654 I jxcore-log: 
,09-26 11:25:23.575   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:24.102  5608  5654 I jxcore-log: 2016-09-26 15:25:24 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 11:25:24.102  5608  5654 I jxcore-log: 
,09-26 11:25:24.112  5608  5654 I jxcore-log: 2016-09-26 15:25:24 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 11:25:24.112  5608  5654 I jxcore-log: 
,09-26 11:25:24.576   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:25.577   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:26.578   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:27.579   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:28.580   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:25:30.089  5608  5654 I jxcore-log: 2016-09-26 15:25:30 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.089  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:30.089  5608  5654 I jxcore-log: ''
09-26 11:25:30.089  5608  5654 I jxcore-log: 
,09-26 11:25:30.106  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.106  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:30.106  5608  5654 W jxcore-log:  color: red
09-26 11:25:30.106  5608  5654 W jxcore-log: 
,09-26 11:25:30.281  5608  5654 I jxcore-log: 2016-09-26 15:25:30 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.281  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:30.281  5608  5654 I jxcore-log: ''
09-26 11:25:30.281  5608  5654 I jxcore-log: 
,09-26 11:25:30.286  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.286  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:30.286  5608  5654 W jxcore-log:  color: red
09-26 11:25:30.286  5608  5654 W jxcore-log: 
,09-26 11:25:30.293  5608  5654 I jxcore-log: 2016-09-26 15:25:30 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.293  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:30.293  5608  5654 I jxcore-log: ''
09-26 11:25:30.293  5608  5654 I jxcore-log: 
,09-26 11:25:30.301  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.301  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:30.301  5608  5654 W jxcore-log:  color: red
09-26 11:25:30.301  5608  5654 W jxcore-log: 
,09-26 11:25:30.620  5608  5654 I jxcore-log: 2016-09-26 15:25:30 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.620  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:30.620  5608  5654 I jxcore-log: ''
09-26 11:25:30.620  5608  5654 I jxcore-log: 
,09-26 11:25:30.626  5608  5654 I jxcore-log: 2016-09-26 15:25:30 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.626  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:30.626  5608  5654 I jxcore-log: ''
09-26 11:25:30.626  5608  5654 I jxcore-log: 
,09-26 11:25:30.644  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.644  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:30.644  5608  5654 W jxcore-log:  color: red
09-26 11:25:30.644  5608  5654 W jxcore-log: 
,09-26 11:25:30.644  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:30.644  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:30.644  5608  5654 W jxcore-log:  color: red
09-26 11:25:30.644  5608  5654 W jxcore-log: 
,09-26 11:25:30.817   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=260476, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:25:31.348  5608  5654 I jxcore-log: 2016-09-26 15:25:31 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:31.348  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:31.348  5608  5654 I jxcore-log: ''
09-26 11:25:31.348  5608  5654 I jxcore-log: 
,09-26 11:25:31.358  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:31.358  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:31.358  5608  5654 W jxcore-log:  color: red
09-26 11:25:31.358  5608  5654 W jxcore-log: 
,09-26 11:25:31.376  5608  5654 I jxcore-log: 2016-09-26 15:25:31 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:31.376  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:31.376  5608  5654 I jxcore-log: ''
09-26 11:25:31.376  5608  5654 I jxcore-log: 
,09-26 11:25:31.383  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:31.383  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:31.383  5608  5654 W jxcore-log:  color: red
09-26 11:25:31.383  5608  5654 W jxcore-log: 
,09-26 11:25:32.398  5608  5654 I jxcore-log: 2016-09-26 15:25:32 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:32.398  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:32.398  5608  5654 I jxcore-log: ''
09-26 11:25:32.398  5608  5654 I jxcore-log: 
,09-26 11:25:32.404  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:32.404  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:32.404  5608  5654 W jxcore-log:  color: red
09-26 11:25:32.404  5608  5654 W jxcore-log: 
,09-26 11:25:32.422  5608  5654 I jxcore-log: 2016-09-26 15:25:32 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:32.422  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:32.422  5608  5654 I jxcore-log: ''
09-26 11:25:32.422  5608  5654 I jxcore-log: 
,09-26 11:25:32.427  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:32.427  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:32.427  5608  5654 W jxcore-log:  color: red
09-26 11:25:32.427  5608  5654 W jxcore-log: 
,09-26 11:25:33.445  5608  5654 I jxcore-log: 2016-09-26 15:25:33 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:33.445  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:33.445  5608  5654 I jxcore-log: ''
09-26 11:25:33.445  5608  5654 I jxcore-log: 
,09-26 11:25:33.452  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:33.452  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:33.452  5608  5654 W jxcore-log:  color: red
09-26 11:25:33.452  5608  5654 W jxcore-log: 
,09-26 11:25:33.470  5608  5654 I jxcore-log: 2016-09-26 15:25:33 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:33.470  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:33.470  5608  5654 I jxcore-log: ''
09-26 11:25:33.470  5608  5654 I jxcore-log: 
,09-26 11:25:33.483  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:33.483  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:33.483  5608  5654 W jxcore-log:  color: red
09-26 11:25:33.483  5608  5654 W jxcore-log: 
,09-26 11:25:34.492  5608  5654 I jxcore-log: 2016-09-26 15:25:34 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:34.492  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:34.492  5608  5654 I jxcore-log: ''
09-26 11:25:34.492  5608  5654 I jxcore-log: 
,09-26 11:25:34.501  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:34.501  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:34.501  5608  5654 W jxcore-log:  color: red
09-26 11:25:34.501  5608  5654 W jxcore-log: 
,09-26 11:25:34.515  5608  5654 I jxcore-log: 2016-09-26 15:25:34 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:34.515  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:34.515  5608  5654 I jxcore-log: ''
09-26 11:25:34.515  5608  5654 I jxcore-log: 
,09-26 11:25:34.522  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:34.522  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:34.522  5608  5654 W jxcore-log:  color: red
09-26 11:25:34.522  5608  5654 W jxcore-log: 
,09-26 11:25:35.545  5608  5654 I jxcore-log: 2016-09-26 15:25:35 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:35.545  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:35.545  5608  5654 I jxcore-log: ''
09-26 11:25:35.545  5608  5654 I jxcore-log: 
,09-26 11:25:35.553  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:35.553  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:35.553  5608  5654 W jxcore-log:  color: red
09-26 11:25:35.553  5608  5654 W jxcore-log: 
,09-26 11:25:35.570  5608  5654 I jxcore-log: 2016-09-26 15:25:35 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:35.570  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:35.570  5608  5654 I jxcore-log: ''
09-26 11:25:35.570  5608  5654 I jxcore-log: 
,09-26 11:25:35.576  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:35.576  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:35.576  5608  5654 W jxcore-log:  color: red
09-26 11:25:35.576  5608  5654 W jxcore-log: 
,09-26 11:25:36.593  5608  5654 I jxcore-log: 2016-09-26 15:25:36 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:36.593  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:36.593  5608  5654 I jxcore-log: ''
09-26 11:25:36.593  5608  5654 I jxcore-log: 
,09-26 11:25:36.600  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:36.600  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:36.600  5608  5654 W jxcore-log:  color: red
09-26 11:25:36.600  5608  5654 W jxcore-log: 
,09-26 11:25:36.619  5608  5654 I jxcore-log: 2016-09-26 15:25:36 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:36.619  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:36.619  5608  5654 I jxcore-log: ''
09-26 11:25:36.619  5608  5654 I jxcore-log: 
,09-26 11:25:36.623  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:36.623  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:36.623  5608  5654 W jxcore-log:  color: red
09-26 11:25:36.623  5608  5654 W jxcore-log: 
,09-26 11:25:37.667  5608  5654 I jxcore-log: 2016-09-26 15:25:37 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:37.667  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:37.667  5608  5654 I jxcore-log: ''
09-26 11:25:37.667  5608  5654 I jxcore-log: 
09-26 11:25:37.671  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:37.671  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:37.671  5608  5654 W jxcore-log:  color: red
09-26 11:25:37.671  5608  5654 W jxcore-log: 
,09-26 11:25:37.728  5608  5654 I jxcore-log: 2016-09-26 15:25:37 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:37.728  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:37.728  5608  5654 I jxcore-log: ''
09-26 11:25:37.728  5608  5654 I jxcore-log: 
,09-26 11:25:37.731  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:37.731  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:37.731  5608  5654 W jxcore-log:  color: red
09-26 11:25:37.731  5608  5654 W jxcore-log: 
,09-26 11:25:38.752  5608  5654 I jxcore-log: 2016-09-26 15:25:38 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:38.752  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:38.752  5608  5654 I jxcore-log: ''
09-26 11:25:38.752  5608  5654 I jxcore-log: 
,09-26 11:25:38.761  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:38.761  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:38.761  5608  5654 W jxcore-log:  color: red
09-26 11:25:38.761  5608  5654 W jxcore-log: 
,09-26 11:25:38.767  5608  5654 I jxcore-log: 2016-09-26 15:25:38 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:38.767  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:38.767  5608  5654 I jxcore-log: ''
09-26 11:25:38.767  5608  5654 I jxcore-log: 
,09-26 11:25:38.770  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:38.770  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:38.770  5608  5654 W jxcore-log:  color: red
09-26 11:25:38.770  5608  5654 W jxcore-log: 
,09-26 11:25:39.789  5608  5654 I jxcore-log: 2016-09-26 15:25:39 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:39.789  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:39.789  5608  5654 I jxcore-log: ''
09-26 11:25:39.789  5608  5654 I jxcore-log: 
,09-26 11:25:39.802  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:39.802  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:39.802  5608  5654 W jxcore-log:  color: red
09-26 11:25:39.802  5608  5654 W jxcore-log: 
,09-26 11:25:39.813  5608  5654 I jxcore-log: 2016-09-26 15:25:39 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:39.813  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:39.813  5608  5654 I jxcore-log: ''
09-26 11:25:39.813  5608  5654 I jxcore-log: 
,09-26 11:25:39.820  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:39.820  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:39.820  5608  5654 W jxcore-log:  color: red
09-26 11:25:39.820  5608  5654 W jxcore-log: 
,09-26 11:25:40.830  5608  5654 I jxcore-log: 2016-09-26 15:25:40 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:40.830  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:40.830  5608  5654 I jxcore-log: ''
09-26 11:25:40.830  5608  5654 I jxcore-log: 
,09-26 11:25:40.842  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:40.842  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:40.842  5608  5654 W jxcore-log:  color: red
09-26 11:25:40.842  5608  5654 W jxcore-log: 
,09-26 11:25:40.851  5608  5654 I jxcore-log: 2016-09-26 15:25:40 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:40.851  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:40.851  5608  5654 I jxcore-log: ''
09-26 11:25:40.851  5608  5654 I jxcore-log: 
09-26 11:25:40.854  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:40.854  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:40.854  5608  5654 W jxcore-log:  color: red
09-26 11:25:40.854  5608  5654 W jxcore-log: 
,09-26 11:25:42.018  5608  5654 I jxcore-log: 2016-09-26 15:25:42 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:42.018  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:42.018  5608  5654 I jxcore-log: ''
09-26 11:25:42.018  5608  5654 I jxcore-log: 
,09-26 11:25:42.029  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:42.029  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:42.029  5608  5654 W jxcore-log:  color: red
09-26 11:25:42.029  5608  5654 W jxcore-log: 
,09-26 11:25:42.046  5608  5654 I jxcore-log: 2016-09-26 15:25:42 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:42.046  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:42.046  5608  5654 I jxcore-log: ''
09-26 11:25:42.046  5608  5654 I jxcore-log: 
,09-26 11:25:42.050  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:42.050  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:42.050  5608  5654 W jxcore-log:  color: red
09-26 11:25:42.050  5608  5654 W jxcore-log: 
,09-26 11:25:43.067  5608  5654 I jxcore-log: 2016-09-26 15:25:43 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:43.067  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:43.067  5608  5654 I jxcore-log: ''
09-26 11:25:43.067  5608  5654 I jxcore-log: 
,09-26 11:25:43.072  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:43.072  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:43.072  5608  5654 W jxcore-log:  color: red
09-26 11:25:43.072  5608  5654 W jxcore-log: 
,09-26 11:25:43.091  5608  5654 I jxcore-log: 2016-09-26 15:25:43 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:43.091  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:43.091  5608  5654 I jxcore-log: ''
09-26 11:25:43.091  5608  5654 I jxcore-log: 
,09-26 11:25:43.094  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:43.094  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:43.094  5608  5654 W jxcore-log:  color: red
09-26 11:25:43.094  5608  5654 W jxcore-log: 
,09-26 11:25:43.582   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:44.125  5608  5654 I jxcore-log: 2016-09-26 15:25:44 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:44.125  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:44.125  5608  5654 I jxcore-log: ''
09-26 11:25:44.125  5608  5654 I jxcore-log: 
09-26 11:25:44.133  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:44.133  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:44.133  5608  5654 W jxcore-log:  color: red
09-26 11:25:44.133  5608  5654 W jxcore-log: 
09-26 11:25:44.140  5608  5654 I jxcore-log: 2016-09-26 15:25:44 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:44.140  5608  5654 I jxcore-log: $9@timers.js:120:1
09-26 11:25:44.140  5608  5654 I jxcore-log: ''
09-26 11:25:44.140  5608  5654 I jxcore-log: 
09-26 11:25:44.145  5608  5654 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 11:25:44.145  5608  5654 W jxcore-log: $9@timers.js:120:1
09-26 11:25:44.145  5608  5654 W jxcore-log:  color: red
09-26 11:25:44.145  5608  5654 W jxcore-log: 
,09-26 11:25:44.583   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:45.585   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:46.587   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:47.589   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:25:48.589   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:25:56.725   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:25:59.130   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:26:08.591   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:09.593   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:09.603   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:26:10.594   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:11.596   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:12.578   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:26:12.597   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:12.635   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:26:13.598   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:26:19.131   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:26:21.731   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:26:24.761   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:26:38.599   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:26:38.600   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:26:48.947   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:26:51.981   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:26:53.601   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:54.602   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:55.604   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:56.605   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:57.607   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:26:58.608   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:26:59.136   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:27:03.610   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:04.611   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:05.613   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:06.615   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:07.616   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:08.617   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:27:14.553   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=364211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:27:18.619   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:19.141   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:27:19.620   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:20.622   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:21.623   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:22.625   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:23.626   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:27:30.392   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:27:38.628   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:39.141   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:27:39.629   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:40.632   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:41.633   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:42.635   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:27:43.636   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:27:54.805   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=404464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:27:55.516   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:01.552   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:03.637   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:04.639   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:05.642   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:06.644   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:07.645   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:08.646   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:28:10.649   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:10.658   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=420317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:28:16.702   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:19.146   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:28:33.647   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:28:33.647   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:28:39.148   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:28:40.925   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:43.947   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:44.325   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=453984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:28:53.034   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:53.648   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:54.649   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:55.651   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:56.067   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:28:56.653   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:57.655   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:28:58.656   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:28:59.149   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:29:00.151   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=469810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:29:03.657   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:04.659   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:05.662   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:06.663   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:07.665   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:08.666   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:29:18.668   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:19.151   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:29:19.669   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:20.670   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:21.671   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:22.673   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:23.674   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:29:26.371   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:29:29.407   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:29:38.676   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:39.152   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:29:39.678   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:40.679   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:41.680   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:42.681   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:29:43.682   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:29:44.299   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=513957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:30:00.098   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=529757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:30:01.037   929   942 I ActivityManager: Start proc 6004:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-26 11:30:01.095  6004  6004 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,09-26 11:30:01.119  6004  6004 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-26 11:30:01.119  6004  6004 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-26 11:30:01.119  6004  6004 I GAv4    :   adb logcat -s GAv4
,09-26 11:30:01.136  6004  6004 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-26 11:30:01.141  6004  6004 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-26 11:30:01.156  6004  6019 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-26 11:30:03.683   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:30:04.685   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:30:05.686   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:30:06.687   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:30:07.688   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:30:08.689   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:30:12.525   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=542184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:30:17.850   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:30:19.158   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:30:20.876   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:30:28.365   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=558024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:30:33.690   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:30:33.690   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:30:39.160   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:30:40.739   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=570397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 11:30:56.579   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=586237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:30:58.776   544  1255 E QC-QMI  : qmi_client [544] a: failed to locate client data
,09-26 11:30:58.781   519   519 E QC-QMI  : qmuxd: RX on fd=19 returned error=0 errno[2:No such file or directory]
,09-26 11:30:58.782   519   519 E QC-QMI  : QMUX qmux_client_id=a not found in qmux client list, unable to remove
09-26 11:30:58.783   544   544 I Atfwd_Daemon: Stop the daemon....
,09-26 11:30:58.813  6026  6026 W ATFWD-daemon: type=1400 audit(0.0:118): avc: denied { read write } for name="diag" dev="tmpfs" ino=12569 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-26 11:30:58.816  6026  6026 I libmdmdetect: ESOC framework not supported
09-26 11:30:58.816  6026  6026 I libmdmdetect: Found internal modem: modem
09-26 11:30:58.817  6026  6026 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-26 11:30:58.822  6026  6026 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-26 11:30:58.822  6026  6026 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-26 11:30:58.823  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:30:59.162   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:30:59.827  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:00.828  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:01.829  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:02.830  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:03.831  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:31:08.832  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:09.834  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:10.835  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:11.837  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:12.838  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:13.839  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:31:19.164   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:31:23.841  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:24.842  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:25.843  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:26.845  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:27.847  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:28.848  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:31:39.168   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:31:43.849  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:44.850  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:45.851  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:46.853  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:47.854  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:31:48.855  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:31:59.169   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:32:03.833   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:32:06.859   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:32:08.856  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:09.858  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:10.859  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:11.861  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:12.863  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:13.864  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:32:19.170   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:32:38.865  6026  6026 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:32:38.865  6026  6026 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:32:43.866  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:44.867  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:45.869  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:46.870  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:47.872  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:48.873  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:32:53.875  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:54.876  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:55.878  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:56.879  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:57.880  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:32:58.882  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:32:59.174   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:33:08.883  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:09.885  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:10.887  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:11.888  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:12.889  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:13.890  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:33:19.178   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:33:28.891  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:29.893  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:30.895  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:31.896  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:32.897  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:33.898  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:33:39.180   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:33:49.827   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:33:53.899  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:54.900  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:55.879   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:33:55.901  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:56.903  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:57.904  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:33:58.906  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:33:59.181   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:34:19.184   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:34:23.906  6026  6026 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:34:23.906  6026  6026 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:34:26.186   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:34:29.214   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:34:33.908  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:34.909  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:35.911  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:36.913  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:37.914  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:38.915  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:34:39.186   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:34:41.346   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:34:43.917  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:44.918  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:45.920  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:46.921  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:47.403   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:34:47.922  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:48.923  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:34:56.482   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:34:58.925  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:34:59.192   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:34:59.927  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:00.928  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:01.929  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:02.930  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:03.931  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:35:05.554   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:35:14.646   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:35:17.676   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:35:18.932  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:19.193   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:35:19.934  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:20.936  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:21.937  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:22.938  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:23.939  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:35:29.800   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:35:38.888   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:35:39.195   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:35:43.940  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:44.941  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:44.956   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:35:45.943  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:46.945  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:47.946  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:35:48.947  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:35:51.038   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:35:59.199   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:36:03.146   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:36:12.246   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:36:13.948  6026  6026 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:36:13.949  6026  6026 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:36:19.200   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:36:28.950  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:29.952  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:30.953  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:31.955  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:32.956  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:33.458   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:36:33.956  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:36:38.958  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:39.513   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:36:39.960  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:40.961  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:41.963  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:42.964  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:43.965  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:36:51.624   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:36:53.966  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:54.968  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:55.969  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:56.971  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:57.686   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:36:57.973  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:36:58.974  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:36:59.207   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:37:06.779   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:37:12.838   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:37:13.975  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:14.976  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:15.978  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:16.979  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:17.982  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:18.983  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:37:19.209   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:37:24.961   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:37:34.052   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:37:37.088   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:37:38.984  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:39.211   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:37:39.985  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:40.987  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:41.989  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:42.990  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:37:43.991  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:37:46.171   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:37:58.302   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:37:59.213   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:38:04.356   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:38:08.992  6026  6026 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-26 11:38:08.993  6026  6026 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:38:13.446   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:38:19.215   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:38:19.495   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:38:28.995  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:29.996  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:30.997  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:31.621   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:38:31.999  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:33.000  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:34.001  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:38:39.002  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:39.216   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:38:40.005  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:40.718   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:38:41.007  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:42.009  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:43.010  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:44.011  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:38:46.790   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:38:52.851   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:38:54.013  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:55.014  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:56.016  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:57.018  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:58.020  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:38:59.021  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:38:59.217   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:39:04.972   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:08.000   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:14.022  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:15.025  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:16.027  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:17.028  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:18.030  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:19.030  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:39:19.221   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:39:20.119   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:23.155   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:29.216   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:32.256   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:38.317   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:39.032  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:39.223   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:39:39.667  3828  6038 I EventLogService: Aggregate from 1474902282641 (log), 1474902282641 (data)
,09-26 11:39:40.034  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:41.035  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:41.357   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:42.037  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:43.039  6026  6026 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:39:44.039  6026  6026 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:39:44.658   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1114317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 11:39:53.471   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:39:55.512   929  5961 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1125170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 11:39:59.226   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:39:59.510   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:05.567   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:09.040  6026  6026 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:40:09.041  6026  6026 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:40:14.650   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:17.682   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:19.226   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:40:20.713   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:26.770   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:29.792   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:34.055  6026  6028 E QC-QMI  : qmi_client [6026] 1d: failed to locate client data
,09-26 11:40:34.058   519   519 E QC-QMI  : qmuxd: RX on fd=19 returned error=0 errno[2:No such file or directory]
,09-26 11:40:34.059   519   519 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
09-26 11:40:34.061  6026  6026 I Atfwd_Daemon: Stop the daemon....
,09-26 11:40:34.183  6046  6046 W ATFWD-daemon: type=1400 audit(0.0:119): avc: denied { read write } for name="diag" dev="tmpfs" ino=12569 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-26 11:40:34.184  6046  6046 I libmdmdetect: ESOC framework not supported
09-26 11:40:34.184  6046  6046 I libmdmdetect: Found internal modem: modem
09-26 11:40:34.185  6046  6046 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-26 11:40:34.193  6046  6046 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-26 11:40:34.194  6046  6046 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-26 11:40:34.194  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:35.198  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:36.199  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:37.201  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:38.203  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:39.204  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:40:39.227   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:40:41.916   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:44.205  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:45.206  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:46.208  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:47.209  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:47.973   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:48.210  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:49.211  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:40:54.025   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:57.057   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:40:59.213  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:40:59.230   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:41:00.214  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:01.215  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:02.217  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:03.219  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:04.220  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:41:15.234   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:41:18.266   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:41:19.221  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:19.231   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:41:20.223  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:21.224  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:22.225  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:23.226  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:24.227  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:41:28.882   929   941 I UsageStatsService: User[0] Flushing usage stats to disk
,09-26 11:41:39.235   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:41:44.228  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:45.230  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:46.231  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:47.233  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:48.234  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:41:49.235  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:41:59.236   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:42:03.689   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:42:06.727   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:42:12.789   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:42:14.236  6046  6046 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:42:14.236  6046  6046 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:42:15.825   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:42:19.238  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:19.240   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:42:20.239  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:21.241  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:22.242  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:23.243  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:24.245  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:42:29.246  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:30.248  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:31.249  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:32.251  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:33.252  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:34.253  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:42:44.255  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:45.256  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:46.258  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:47.259  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:48.261  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:42:49.261  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:42:59.244   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:43:04.262  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:05.265  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:06.266  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:07.268  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:08.269  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:09.270  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:43:19.245   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:43:28.482   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:43:29.271  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:30.273  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:31.274  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:31.523   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:43:32.276  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:33.277  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:43:34.278  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:43:39.248   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:43:59.249   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:43:59.279  6046  6046 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:43:59.280  6046  6046 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:44:04.832   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:44:07.869   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:44:09.281  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:10.283  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:11.284  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:12.286  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:13.288  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:14.289  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:44:19.252   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:44:19.291  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:20.292  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:21.294  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:22.296  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:23.298  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:24.299  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:44:34.301  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:35.302  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:36.304  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:37.306  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:38.308  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:39.254   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:44:39.309  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:44:47.248   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:44:50.281   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:44:54.310  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:55.312  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:56.313  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:57.315  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:58.317  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:44:59.258   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:44:59.318  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 11:45:19.262   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:45:19.319  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:45:20.320  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:45:21.321  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:45:22.323  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:45:23.325  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:45:24.325  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 11:45:32.677   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:45:35.716   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:45:39.262   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:45:49.327  6046  6046 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 11:45:49.327  6046  6046 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 11:45:59.266   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:45:59.954   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:46:02.985   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 11:46:04.328  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:05.330  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:06.332  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:07.333  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:08.335  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:09.336  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 11:46:14.338  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:15.339  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:16.341  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:17.343  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:18.344  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:19.267   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 11:46:19.345  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 11:46:29.347  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:30.349  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:31.351  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:32.352  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:33.354  6046  6046 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 11:46:34.355  6046  6046 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 11:46:39.272   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,TIME-OUT KILL (timeout was 1400000ms)
```
