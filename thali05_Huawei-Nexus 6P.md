#### Test 93986313a169e88_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-16 11:10:06.222   927  3136 I ActivityManager: Killing 5394:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
--------- beginning of main
11-16 11:10:06.357  5553  5602 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-16 11:10:06.405  5553  5602 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-16 11:10:06.433  5553  5602 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-16 11:10:06.501  3846  4922 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-16 11:10:06.585  3846  4922 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,11-16 11:10:07.577  5610  5610 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-16 11:10:07.583  5610  5610 D AndroidRuntime: CheckJNI is OFF
11-16 11:10:07.610  5610  5610 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-16 11:10:07.646  5610  5610 I Radio-JNI: register_android_hardware_Radio DONE
11-16 11:10:07.663  5610  5610 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-16 11:10:07.669   927   937 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-16 11:10:07.708   927   937 I ActivityManager: Start proc 5619:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-16 11:10:07.718  5610  5610 D AndroidRuntime: Shutting down VM
,11-16 11:10:08.049   927  3825 I WindowManager: Screenshot max retries 4 of Token{40c70fa ActivityRecord{1bfb725 u0 com.test.thalitest/.MainActivity t6}} appWin=Window{d4ea5dd u0 Starting com.test.thalitest} drawState=2
,11-16 11:10:08.142  5619  5619 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-16 11:10:08.178  5619  5619 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-16 11:10:08.248  5619  5619 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 1403-1466)
11-16 11:10:08.248  5619  5619 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-16 11:10:08.282  5619  5619 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f6b2e4}
11-16 11:10:08.282  5619  5619 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-16 11:10:08.282  5619  5619 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-16 11:10:08.287  5619  5619 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-16 11:10:08.288  5619  5619 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-16 11:10:08.331  5619  5619 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-16 11:10:08.348  5619  5619 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-16 11:10:08.348  5619  5619 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-16 11:10:08.348  5619  5619 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-16 11:10:08.348  5619  5619 I Adreno  : Build Date                       : 12/06/15
11-16 11:10:08.348  5619  5619 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-16 11:10:08.348  5619  5619 I Adreno  : Local Branch                     : mybranch17112971
11-16 11:10:08.348  5619  5619 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-16 11:10:08.348  5619  5619 I Adreno  : Remote Branch                    : NONE
11-16 11:10:08.348  5619  5619 I Adreno  : Reconstruct Branch               : NOTHING
,11-16 11:10:08.394   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22e8c38:true
,11-16 11:10:08.425   405   405 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21398]" dev="sockfs" ino=21398 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-16 11:10:08.425   405   405 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[21398]" dev="sockfs" ino=21398 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-16 11:10:08.440  5619  5619 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-16 11:10:08.450  5619  5619 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-16 11:10:08.471   405   405 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32396]" dev="sockfs" ino=32396 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-16 11:10:08.471   405   405 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32396]" dev="sockfs" ino=32396 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:08.475  5619  5656 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-16 11:10:08.475  3825  3825 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21409]" dev="sockfs" ino=21409 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:08.475  3825  3825 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[21409]" dev="sockfs" ino=21409 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-16 11:10:08.482  5619  5643 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-16 11:10:08.519  5619  5656 I OpenGLRenderer: Initialized EGL, version 1.4
,11-16 11:10:08.605   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +552ms (total +921ms)
,11-16 11:10:08.629  5619  5619 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5619
,11-16 11:10:08.702  5619  5619 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-16 11:10:08.842  5619  5659 D jxcore_app_log: JniHelper::setJavaVM(0xf4fbc000), pthread_self() = -584316624
,11-16 11:10:08.846  5619  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-16 11:10:08.846  5619  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-16 11:10:08.846  5619  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-16 11:10:08.846  5619  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-16 11:10:08.846  5619  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-16 11:10:08.846  5619  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63d821a added. We now have 1 listener(s)
,11-16 11:10:08.849  5619  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-16 11:10:08.849  5619  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:08.850  5619  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-16 11:10:08.850  5619  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-16 11:10:08.853  5619  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be3c41 added. We now have 1 listener(s)
11-16 11:10:08.853  5619  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-16 11:10:08.858   927  2937 D WifiService: New client listening to asynchronous messages
,11-16 11:10:08.859  5619  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-16 11:10:08.859  5619  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-16 11:10:08.859  5619  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-16 11:10:08.859  5619  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-16 11:10:08.859  5619  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-16 11:10:08.859  5619  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-16 11:10:08.859  5619  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-16 11:10:08.861  5619  5659 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-16 11:10:08.961  5619  5619 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-16 11:10:09.368  5619  5666 W jxcore-log: Initializing JXcore engine
11-16 11:10:09.368  5619  5666 W jxcore-log: JXcore engine is ready
,11-16 11:10:09.388  5666  5666 W Thread-62: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11610 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-16 11:10:09.388  5666  5666 W Thread-62: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15390]" dev="sockfs" ino=15390 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-16 11:10:09.388  5666  5666 W Thread-62: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-16 11:10:09.388  5666  5666 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32371]" dev="sockfs" ino=32371 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-16 11:10:09.399  5619  5666 W jxcore-log: Starting JXcore engine
,11-16 11:10:09.449  5619  5666 W jxcore-log: Platform android
11-16 11:10:09.449  5619  5666 W jxcore-log: 
,11-16 11:10:09.449  5619  5666 W jxcore-log: Process ARCH arm
11-16 11:10:09.449  5619  5666 W jxcore-log: 
,11-16 11:10:09.585  5619  5666 I jxcore-log: JXcore Cordova bridge is ready!
11-16 11:10:09.585  5619  5666 I jxcore-log: 
,11-16 11:10:09.585  5619  5666 W jxcore-log: JXcore engine is started
,11-16 11:10:09.592  5619  5659 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-16 11:10:09.595  5619  5619 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-16 11:10:10.864  3556  3556 I ConfigService: onDestroy
,11-16 11:10:19.449  5619  5666 I jxcore-log: 2016-11-16 16:10:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-16 11:10:19.449  5619  5666 I jxcore-log: 
,11-16 11:10:19.451  5619  5666 I jxcore-log: 2016-11-16 16:10:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-16 11:10:19.451  5619  5666 I jxcore-log: 
,11-16 11:10:19.456  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-16 11:10:19.456  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-16 11:10:19.460  5619  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-16 11:10:19.464  5619  5666 I jxcore-log: 2016-11-16 16:10:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-16 11:10:19.464  5619  5666 I jxcore-log: 
11-16 11:10:19.466  5619  5666 I jxcore-log: 2016-11-16 16:10:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-16 11:10:19.466  5619  5666 I jxcore-log: 
,11-16 11:10:19.713  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-16 11:10:19.713  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a419e7 added. We now have 2 listener(s)
11-16 11:10:19.714  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:19.714  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-16 11:10:19.714  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-16 11:10:19.714  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-16 11:10:19.714  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96d9994 added. We now have 2 listener(s)
11-16 11:10:19.714  5619  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-16 11:10:19.715  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-16 11:10:19.716  5619  5666 D ExecuteNativeTests: Running unit tests
11-16 11:10:19.716  5619  5666 D BluetoothAdapter: enable(): BT is already enabled..!
11-16 11:10:19.717   927  3136 D WifiService: setWifiEnabled: true pid=5619, uid=10077
,11-16 11:10:19.717   927  3136 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-16 11:10:19.990  4822  4852 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-16 11:10:19.992  4822  4822 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-16 11:10:21.032   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-16 11:10:21.033   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-16 11:10:21.339   927  5364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=114557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-16 11:10:26.034   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:27.036   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:28.002   927  2930 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-16 11:10:28.037   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:29.039   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:29.723  5619  5666 I com.test.thalitest.ThaliTestRunner: Running UT
,11-16 11:10:29.788  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-16 11:10:29.788  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c113e1 added. We now have 3 listener(s)
11-16 11:10:29.789  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:29.789  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-16 11:10:29.789  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-16 11:10:29.789  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-16 11:10:29.789  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14a3506 added. We now have 3 listener(s)
11-16 11:10:29.789  5619  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-16 11:10:29.790  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-16 11:10:29.794  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-16 11:10:29.794  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-16 11:10:29.794  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-16 11:10:29.795  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-16 11:10:29.795  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-16 11:10:29.795  5619  5666 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-16 11:10:29.796  5619  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-16 11:10:29.796  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-16 11:10:29.796  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:29.796  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:29.796  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:29.797  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,11-16 11:10:29.798  5619  5666 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-16 11:10:29.799  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-16 11:10:29.801  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,11-16 11:10:29.801  5619  5666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-16 11:10:29.803  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-16 11:10:29.803  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-16 11:10:29.807  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-16 11:10:29.808  5619  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-16 11:10:29.808  5619  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-16 11:10:29.808  5619  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-16 11:10:29.809  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-16 11:10:29.809  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.809  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:29.809  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.809  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-16 11:10:29.809  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-16 11:10:29.809  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-16 11:10:29.809  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:29.809  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-16 11:10:29.810  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-16 11:10:29.810  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-16 11:10:29.810  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-16 11:10:29.811  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-16 11:10:29.811  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-16 11:10:29.811  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:29.811  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-16 11:10:29.811  5619  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-16 11:10:29.812  5619  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-16 11:10:29.814  5619  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-16 11:10:29.815  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-16 11:10:29.815  5619  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-16 11:10:29.815  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-16 11:10:29.816  5619  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-16 11:10:29.816  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-16 11:10:29.815  4610  4610 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33954]" dev="sockfs" ino=33954 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:29.820  5619  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-16 11:10:29.815  4610  4610 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33954]" dev="sockfs" ino=33954 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:29.824  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.824  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-16 11:10:29.825  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-16 11:10:29.825  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-16 11:10:29.825  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-16 11:10:29.826  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.826  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.826  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-16 11:10:29.826  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-16 11:10:29.826  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:29.826  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-16 11:10:29.827  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:29.827  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:29.827  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:29.827  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-16 11:10:29.827  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:29.827  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:29.827  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.827  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.828  5619  5666 D BluetoothAdapter: STATE_ON
,11-16 11:10:29.831  4598  4612 D BtGatt.GattService: registerClient() - UUID=f4f91286-f24a-4fa5-8d8c-ab7575dc7da5
,11-16 11:10:29.832  4598  4660 D BtGatt.GattService: onClientRegistered() - UUID=f4f91286-f24a-4fa5-8d8c-ab7575dc7da5, clientIf=5
,11-16 11:10:29.833  5619  5629 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-16 11:10:29.835  4598  4664 D BtGatt.AdvertiseManager: message : 0
,11-16 11:10:29.837  4598  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-16 11:10:29.854  4598  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-16 11:10:29.863  4598  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-16 11:10:29.864  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.864  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:29.864  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-16 11:10:29.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.865  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-16 11:10:29.865  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-16 11:10:29.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:29.866  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.866  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.866  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:29.866  5619  5666 I io.jxcore.node.ConnectionHelper: start: OK
,11-16 11:10:29.866  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-16 11:10:29.867  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.867  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:29.867  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-16 11:10:29.868  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.868  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.868  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:29.869  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.869  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-16 11:10:29.869  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-16 11:10:29.869  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.869  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.869  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-16 11:10:29.869  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-16 11:10:29.873  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.873  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-16 11:10:29.873  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.873  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.874  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:29.874  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-16 11:10:30.040   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:30.369  5619  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-16 11:10:30.370  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-16 11:10:30.371  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-16 11:10:30.372  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-16 11:10:30.373  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-16 11:10:30.373  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-16 11:10:30.373  5619  5666 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-16 11:10:30.373  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-16 11:10:30.373  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-16 11:10:30.373  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-16 11:10:30.373  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-16 11:10:30.373  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-16 11:10:30.374  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-16 11:10:30.374  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-16 11:10:30.374  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-16 11:10:30.374  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-16 11:10:30.374  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-16 11:10:30.374  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-16 11:10:30.375  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-16 11:10:30.375  5619  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-16 11:10:30.375  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-16 11:10:30.375  5619  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-16 11:10:30.375  5619  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-16 11:10:30.375  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.375  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.376  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.376  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.377  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:30.378  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-16 11:10:30.379  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:30.379  5619  5666 D BluetoothLeScanner: could not find callback wrapper
11-16 11:10:30.379  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-16 11:10:30.379  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.379  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.379  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.379  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-16 11:10:30.379  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.381  4598  4664 D BtGatt.AdvertiseManager: message : 1
11-16 11:10:30.382  4598  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
11-16 11:10:30.397  4598  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-16 11:10:30.397  4598  4660 D BtGatt.GattService: Client app is not null!
11-16 11:10:30.399  4598  4810 D BtGatt.GattService: unregisterClient() - clientIf=5
11-16 11:10:30.400  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-16 11:10:30.400  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.400  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:30.400  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.400  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.401  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.401  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-16 11:10:30.401  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager,: release: No more listeners, de-initializing...
11-16 11:10:30.403  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-16 11:10:30.403  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.405  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.406  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:30.406  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.406  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.407  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-16 11:10:30.407  5619  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-16 11:10:30.409  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-16 11:10:30.409  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-16 11:10:30.409  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:30.409  5619  5666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-16 11:10:30.409  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-16 11:10:30.409  5619  5666 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-16 11:10:30.409  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-16 11:10:30.409  5619  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-16 11:10:30.409  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-16 11:10:30.410  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-16 11:10:30.410  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.410  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.410  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-16 11:10:30.410  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-16 11:10:30.410  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.410  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.410  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.410  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.410  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:30.410  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-16 11:10:30.410  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-16 11:10:30.411  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-16 11:10:30.411  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.411  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:30.415  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-16 11:10:30.415  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.415  4810  4810 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33962]" dev="sockfs" ino=33962 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:30.418  4810  4810 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33962]" dev="sockfs" ino=33962 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-16 11:10:30.415  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.416  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-16 11:10:30.416  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.416  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-16 11:10:30.416  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:30.416  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-16 11:10:30.416  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-16 11:10:30.416  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-16 11:10:30.416  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-16 11:10:30.416  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:30.416  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-16 11:10:30.416  5619  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-16 11:10:30.417  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-16 11:10:30.419  5619  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-16 11:10:30.421  5619  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-16 11:10:30.422  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-16 11:10:30.422  5619  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-16 11:10:30.422  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-16 11:10:30.427  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.427  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-16 11:10:30.428  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-16 11:10:30.428  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-16 11:10:30.428  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-16 11:10:30.430  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.430  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.430  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-16 11:10:30.431  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-16 11:10:30.431  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:30.431  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-16 11:10:30.431  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:30.431  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:30.431  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.431  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-16 11:10:30.431  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-16 11:10:30.431  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.432  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.432  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.432  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:30.434  4598  4612 D BtGatt.GattService: registerClient() - UUID=e8463b6b-df59-4d55-bdc6-1a8d985c9e5d
11-16 11:10:30.435  4598  4660 D BtGatt.GattService: onClientRegistered() - UUID=e8463b6b-df59-4d55-bdc6-1a8d985c9e5d, clientIf=5
11-16 11:10:30.435  5619  5630 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-16 11:10:30.436  4598  4664 D BtGatt.AdvertiseManager: message : 0
,11-16 11:10:30.438  4598  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-16 11:10:30.448  4598  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-16 11:10:30.454  4598  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-16 11:10:30.455  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.455  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.455  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-16 11:10:30.455  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.455  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.455  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.455  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.455  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.455  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-16 11:10:30.457  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-16 11:10:30.457  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.458  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.458  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.458  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.458  5619  5666 I io.jxcore.node.ConnectionHelper: start: OK
,11-16 11:10:30.458  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:30.458  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.458  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:30.458  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-16 11:10:30.458  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-16 11:10:30.459  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-16 11:10:30.459  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:30.459  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.459  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-16 11:10:30.459  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-16 11:10:30.459  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.459  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.459  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-16 11:10:30.459  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-16 11:10:30.462  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.462  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-16 11:10:30.462  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.462  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.462  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:30.462  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-16 11:10:30.963  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-16 11:10:30.963  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-16 11:10:30.964  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-16 11:10:30.964  5619  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-16 11:10:30.964  5619  5666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-16 11:10:30.964  5619  5666 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-16 11:10:30.964  5619  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-16 11:10:30.964  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-16 11:10:30.965  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.965  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.966  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-16 11:10:30.967  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.969  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-16 11:10:30.971  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.971  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.971  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.977  4598  4664 D BtGatt.AdvertiseManager: message : 1
,11-16 11:10:30.980  4598  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-16 11:10:30.992  4598  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-16 11:10:30.993  4598  4660 D BtGatt.GattService: Client app is not null!
,11-16 11:10:30.994  4598  4810 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-16 11:10:30.995  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-16 11:10:30.995  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.995  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:30.995  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.996  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.996  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.996  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-16 11:10:30.996  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.996  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.996  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.996  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-16 11:10:30.997  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-16 11:10:30.997  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-16 11:10:30.997  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
11-16 11:10:30.997  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-16 11:10:30.998  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:30.998  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:30.998  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-16 11:10:30.999  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:30.999  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.999  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:30.999  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.001  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:31.005  4598  4810 D BtGatt.GattService: registerClient() - UUID=feda93c1-1668-4265-8e69-45a3cdf2af20
11-16 11:10:31.006  4598  4660 D BtGatt.GattService: onClientRegistered() - UUID=feda93c1-1668-4265-8e69-45a3cdf2af20, clientIf=5
11-16 11:10:31.006  5619  5629 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-16 11:10:31.008  4598  4664 D BtGatt.AdvertiseManager: message : 0
,11-16 11:10:31.013  4598  4664 D BtGatt.AdvertiseManager: starting multi advertising
,11-16 11:10:31.030  4598  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-16 11:10:31.040   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-16 11:10:31.040  4598  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-16 11:10:31.042  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.042  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.042  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.042  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-16 11:10:31.042  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.042  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.042  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.042  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.043  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.043  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-16 11:10:31.043  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-16 11:10:31.043  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.043  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-16 11:10:31.043  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-16 11:10:31.043  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.043  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.043  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-16 11:10:31.043  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-16 11:10:31.043  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-16 11:10:31.043  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.044  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-16 11:10:31.044  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-16 11:10:31.044  5619  5666 I io.jxcore.node.ConnectionHelper: start: OK
11-16 11:10:31.044  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-16 11:10:31.044  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.044  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.045  5619  5666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-16 11:10:31.046  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-16 11:10:31.046  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-16 11:10:31.046  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-16 11:10:31.046  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-16 11:10:31.046  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-16 11:10:31.046  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-16 11:10:31.046  5619  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-16 11:10:31.046  5619  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-16 11:10:31.046  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-16 11:10:31.047  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-16 11:10:31.047  5619  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-16 11:10:31.047  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-16 11:10:31.047  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-16 11:10:31.047  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-16 11:10:31.047  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-16 11:10:31.047  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-16 11:10:31.047  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.047  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.047  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.048  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.049  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:31.049  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-16 11:10:31.050  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:31.050  5619  5666 D BluetoothLeScanner: could not find callback wrapper
11-16 11:10:31.050  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-16 11:10:31.050  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.051  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.051  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.051  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-16 11:10:31.051  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.052  4598  4664 D BtGatt.AdvertiseManager: message : 1
11-16 11:10:31.053  4598  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
11-16 11:10:31.063  4598  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - cl,ientIf=5, status=0
11-16 11:10:31.063  4598  4660 D BtGatt.GattService: Client app is not null!
11-16 11:10:31.064  4598  4610 D BtGatt.GattService: unregisterClient() - clientIf=5
11-16 11:10:31.066  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-16 11:10:31.066  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.066  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:31.066  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.066  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.066  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.066  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-16 11:10:31.066  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-16 11:10:31.067  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-16 11:10:31.067  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.069  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.069  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:31.069  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.069  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.069  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-16 11:10:31.069  5619  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-16 11:10:31.069  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-16 11:10:31.070  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-16 11:10:31.070  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:31.070  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:31.070  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:31.071  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.071  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-16 11:10:31.071  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-16 11:10:31.071  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.072  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.072  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-16 11:10:31.072  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-16 11:10:31.072  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.072  5619  5666 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-16 11:10:31.073  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.074  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.074  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.074  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.074  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:31.076  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-16 11:10:31.077  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-16 11:10:31.078  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-16 11:10:31.078  5619  5666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-16 11:10:31.080  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-16 11:10:31.080  5619  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-16 11:10:31.081  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-16 11:10:31.081  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-16 11:10:31.081  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-16 11:10:31.081  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-16 11:10:31.081  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-16 11:10:31.081  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-16 11:10:31.082  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:31.082  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:31.082  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:31.082  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-16 11:10:31.082  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-16 11:10:31.082  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-16 11:10:31.082  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-16 11:10:31.083  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-16 11:10:31.083  5619  5666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-16 11:10:31.084  5619  5666 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-16 11:10:31.087  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-16 11:10:31.087  5619  5666 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-16 11:10:31.089  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-16 11:10:31.089  5619  5666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-16 11:10:31.090  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-16 11:10:31.090  5619  5666 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-16 11:10:31.090  5619  5666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-16 11:10:31.090  5619  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-16 11:10:31.090  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-16 11:10:31.090  5619  5666 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-16 11:10:31.090  5619  5666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-16 11:10:31.090  5619  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-16 11:10:31.090  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-16 11:10:31.090  5619  5666 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-16 11:10:31.090  5619  5666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-16 11:10:31.091  5619  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-16 11:10:31.091  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-16 11:10:31.091  5619  5666 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-16 11:10:31.091  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-16 11:10:31.092  5619  5666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-16 11:10:31.092  5619  5666 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-16 11:10:31.092  5619  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-16 11:10:31.092  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-16 11:10:31.092  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.092  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.092  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.092  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:31.092  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-16 11:10:31.092  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-16 11:10:31.092  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:31.093  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-16 11:10:31.094  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-16 11:10:31.094  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-16 11:10:31.094  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-16 11:10:31.094  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-16 11:10:31.094  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-16 11:10:31.094  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:31.094  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-16 11:10:31.094  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-16 11:10:31.095  5619  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-16 11:10:31.097  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-16 11:10:31.097  5619  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-16 11:10:31.098  5619  5675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-16 11:10:31.097  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-16 11:10:31.098  4612  4612 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33064]" dev="sockfs" ino=33064 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:31.098  4612  4612 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33064]" dev="sockfs" ino=33064 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:31.102  5619  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-16 11:10:31.102  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.102  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-16 11:10:31.103  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-16 11:10:31.104  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-16 11:10:31.104  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-16 11:10:31.107  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.107  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.107  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-16 11:10:31.107  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-16 11:10:31.107  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:31.107  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-16 11:10:31.107  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:31.107  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:31.108  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.108  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-16 11:10:31.108  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:31.108  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.108  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.108  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.109  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:31.112  4598  4818 D BtGatt.GattService: registerClient() - UUID=4c33021a-85b4-4ff2-9bfd-a5fb69199a2f
11-16 11:10:31.112  4598  4660 D BtGatt.GattService: onClientRegistered() - UUID=4c33021a-85b4-4ff2-9bfd-a5fb69199a2f, clientIf=5
11-16 11:10:31.112  5619  5629 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-16 11:10:31.113  4598  4664 D BtGatt.AdvertiseManager: message : 0
11-16 11:10:31.115  4598  4664 D BtGatt.AdvertiseManager: starting multi advertising
11-16 11:10:31.124  4598  4660 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-16 11:10:31.129  4598  4660 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-16 11:10:31.130  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.130  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.130  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-16 11:10:31.130  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.130  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.130  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.130  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.130  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.130  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-16 11:10:31.132  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-16 11:10:31.132  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.133  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.133  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.133  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.133  5619  5666 I io.jxcore.node.ConnectionHelper: start: OK
11-16 11:10:31.133  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:31.133  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.133  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:31.133  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-16 11:10:31.133  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.133  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.133  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:31.134  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.134  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-16 11:10:31.134  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-16 11:10:31.134  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.134  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.134  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-16 11:10:31.134  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.136  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.137  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-16 11:10:31.137  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.137  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.137  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.137  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-16 11:10:31.634  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-16 11:10:31.634  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-16 11:10:31.634  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-16 11:10:31.634  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-16 11:10:31.635  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-16 11:10:31.635  5619  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-16 11:10:31.635  5619  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-16 11:10:31.635  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-16 11:10:31.635  5619  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-16 11:10:31.635  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-16 11:10:31.636  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-16 11:10:31.636  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-16 11:10:31.636  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c113e1 removed from the list
,11-16 11:10:31.636  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-16 11:10:31.636  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-16 11:10:31.636  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-16 11:10:31.636  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-16 11:10:31.636  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-16 11:10:31.637  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-16 11:10:31.637  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.637  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.637  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.638  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.640  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:31.640  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-16 11:10:31.642  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:31.642  5619  5666 D BluetoothLeScanner: could not find callback wrapper
11-16 11:10:31.642  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-16 11:10:31.643  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.643  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.643  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.643  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-16 11:10:31.643  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.645  4598  4664 D BtGatt.AdvertiseManager: message : 1
11-16 11:10:31.646  4598  4664 D BtGatt.AdvertiseManager: stop advertise for client 5
11-16 11:10:31.658  4598  4660 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-16 11:10:31.658  4598  4660 D BtGatt.GattService: Client app is not null!
11-16 11:10:31.659  4598  4612 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-16 11:10:31.660  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-16 11:10:31.660  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.660  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:31.660  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.661  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.661  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.661  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-16 11:10:31.661  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-16 11:10:31.662  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-16 11:10:31.662  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:31.665  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.665  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:31.665  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.665  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:31.665  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14a3506 removed from the list
11-16 11:10:31.665  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:31.665  5619  5666 D io.jxcore.node.ConnectivityMonitor: stop
,11-16 11:10:31.665  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-16 11:10:31.665  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-16 11:10:31.666  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-16 11:10:31.666  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:31.666  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.666  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-16 11:10:31.666  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-16 11:10:31.666  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-16 11:10:31.667  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.667  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-16 11:10:31.667  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.669  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.669  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.669  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.669  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:31.670  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-16 11:10:32.171  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-16 11:10:36.041   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:36.670  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-16 11:10:36.672  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-16 11:10:36.672  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:36.673  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-16 11:10:36.678  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-16 11:10:36.679  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-16 11:10:36.680  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-16 11:10:36.680  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-16 11:10:36.680  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-16 11:10:36.680  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-16 11:10:36.680  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-16 11:10:36.680  5619  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-16 11:10:36.682  5619  5676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-16 11:10:36.683  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-16 11:10:36.685  5619  5666 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-16 11:10:36.685  5619  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-16 11:10:36.685  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-16 11:10:36.686  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:36.686  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-16 11:10:36.687  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-16 11:10:36.685  4818  4818 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33073]" dev="sockfs" ino=33073 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:36.690  5619  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-16 11:10:36.685  4818  4818 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33073]" dev="sockfs" ino=33073 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-16 11:10:36.700  5619  5666 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
11-16 11:10:36.701  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-16 11:10:36.701  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-16 11:10:36.701  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-16 11:10:36.701  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-16 11:10:36.702  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-16 11:10:36.702  5619  5676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-16 11:10:36.702  5619  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-16 11:10:36.702  5619  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-16 11:10:36.702  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-16 11:10:36.703  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-16 11:10:36.703  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-16 11:10:36.704  5619  5666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c113e1 not in the list
11-16 11:10:36.704  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-16 11:10:36.704  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-16 11:10:36.704  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-16 11:10:36.704  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-16 11:10:36.704  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-16 11:10:36.704  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-16 11:10:36.704  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:36.706  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:36.706  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:36.706  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:36.706  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:36.706  5619  5666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14a3506 not in the list
,11-16 11:10:36.706  5619  5666 D io.jxcore.node.ConnectivityMonitor: stop
11-16 11:10:36.707  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:36.707  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:36.707  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:36.708  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-16 11:10:36.709  5619  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-16 11:10:36.709  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-16 11:10:36.709  5619  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-16 11:10:36.709  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-16 11:10:36.709  5619  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-16 11:10:36.709  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-16 11:10:36.710  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-16 11:10:36.711  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-16 11:10:36.712  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-16 11:10:36.712  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-16 11:10:36.712  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-16 11:10:36.713  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-16 11:10:36.713  5619  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-16 11:10:36.713  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-16 11:10:36.713  5619  5666 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-16 11:10:36.713  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-16 11:10:36.713  5619  5666 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-16 11:10:36.714  5619  5666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-16 11:10:36.714  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-16 11:10:36.714  5619  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-16 11:10:36.714  5619  5666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-16 11:10:36.715  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-16 11:10:36.715  5619  5666 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-16 11:10:36.715  5619  5666 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-16 11:10:36.715  5619  5666 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-16 11:10:36.715  5619  5666 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-16 11:10:36.716  5619  5666 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-16 11:10:36.716  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-16 11:10:36.716  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb4024 added. We now have 3 listener(s)
,11-16 11:10:36.718  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-16 11:10:36.718  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-16 11:10:36.718  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-16 11:10:36.718  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-16 11:10:36.718  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbd778d added. We now have 3 listener(s)
11-16 11:10:36.718  5619  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-16 11:10:36.719  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-16 11:10:36.721  5619  5666 D BluetoothAdapter: enable(): BT is already enabled..!
,11-16 11:10:36.722   927  3743 D WifiService: setWifiEnabled: true pid=5619, uid=10077
11-16 11:10:36.722   927  3743 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-16 11:10:36.723  5619  5666 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-16 11:10:36.726  5619  5666 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-16 11:10:36.726  5619  5666 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-16 11:10:36.729  5619  5666 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-16 11:10:36.730  5619  5666 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-16 11:10:36.734  4598  4656 D BluetoothAdapterState: Current state: ON, message: 23
,11-16 11:10:36.735  4598  4656 D BluetoothAdapterProperties: Setting state to 13
11-16 11:10:36.735  4598  4656 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-16 11:10:36.735  4598  4656 D BluetoothAdapterProperties: onBluetoothDisable()
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-16 11:10:36.736  5619  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-16 11:10:36.736  4598  4656 I BluetoothAdapterState: Entering PendingCommandState
11-16 11:10:36.737  5619  5666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-16 11:10:36.737  5619  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-16 11:10:36.737  4598  4660 D BluetoothAdapterProperties: Scan Mode:20
,11-16 11:10:36.737  4598  4656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-16 11:10:36.739  4598  4598 D BluetoothMapService: onReceive
11-16 11:10:36.739  4598  4598 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-16 11:10:36.739  4598  4598 D BluetoothMapService: STATE_TURNING_OFF
11-16 11:10:36.740  4598  4598 D BluetoothMapService: MAP Service closeService in
11-16 11:10:36.740  4598  4598 D BluetoothMapMasInstance0: MAP Service shutdown
11-16 11:10:36.740  4598  4598 D ObexServerSockets0: shutdown(block = true)
11-16 11:10:36.741  4598  4598 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-16 11:10:36.741  4598  4598 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-16 11:10:36.741  4598  4820 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-16 11:10:36.741  4598  4821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-16 11:10:36.741  4598  4800 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-16 11:10:36.743  4598  4598 I BtOppRfcommListener: stopping Accept Thread
11-16 11:10:36.743  4598  5278 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-16 11:10:36.743  4598  5278 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-16 11:10:36.754   927   940 I ActivityManager: Start proc 5679:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-16 11:10:36.755  4598  4598 D HeadsetService: Received stop request...Stopping profile...
11-16 11:10:36.758   927   927 D BluetoothHeadset: Proxy object disconnected
11-16 11:10:36.759  3781  3994 D BluetoothHeadset: Proxy object disconnected
11-16 11:10:36.760  3095  3111 D BluetoothHeadset: Proxy object disconnected
11-16 11:10:36.760   927   927 D BluetoothHeadset: Proxy object disconnected
11-16 11:10:36.761   927   927 D BluetoothHeadset: Proxy object disconnected
11-16 11:10:36.761  4598  4598 D A2dpService: Received stop request...Stopping profile...
11-16 11:10:36.761  4598  4813 D A2dpStateMachine: Exit Disconnected: -1
11-16 11:10:36.762   927   927 D BluetoothA2dp: Proxy object disconnected
11-16 11:10:36.763  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-16 11:10:36.763  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:36.763  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:36.763  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:36.763  3095  3095 D HeadsetProfile: Bluetooth service disconnected
11-16 11:10:36.764  3095  3095 D BluetoothA2dp: Proxy object disconnected
11-16 11:10:36.764  4598  4598 D HidService: Received stop request...Stopping profile...
11-16 11:10:36.764  4598  4598 D HidService: Stopping Bluetooth HidService
11-16 11:10:36.765  3095  3095 D BluetoothInputDevice: Proxy object disconnected
11-16 11:10:36.765  3095  3095 D HidProfile: Bluetooth service disconnected
11-16 11:10:36.767  4598  4598 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-16 11:10:36.767  4598  4598 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-16 11:10:36.768  4598  4660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-16 11:10:36.768  4598  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-16 11:10:36.768  4598  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-16 11:10:36.768  4598  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-16 11:10:36.768  4598  4598 D HealthService: Received stop request...Stopping profile...
11-16 11:10:36.768  4598  4660 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-16 11:10:36.770  4598  4598 D PanService: Received stop request...Stopping profile...
11-16 11:10:36.771  3095  3095 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-16 11:10:36.771  3095  3095 D PanProfile: Bluetooth service disconnected
11-16 11:10:36.772  4598  4598 D BluetoothMapService: Received stop request...Stopping profile...
11-16 11:10:36.772  4598  4598 D BluetoothMapService: stop()
11-16 11:10:36.773  4598  4598 D BluetoothMapAppObserver: deinitObservers()
11-16 11:10:36.774  4598  4598 D BluetoothMapAppObserver: removeReceiver()
11-16 11:10:36.776  3095  3095 D BluetoothMap: Proxy object disconnected
11-16 11:10:36.776  3095  3095 D MapProfile: Bluetooth service disconnected
11-16 11:10:36.776  4598  4598 D SapService: Received stop request...Stopping profile...
11-16 11:10:36.776  4598  4598 V SapService: stop()
11-16 11:10:36.777  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-16 11:10:36.778  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:36.778  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:36.778  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:36.779  4598  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-16 11:10:36.779  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-16 11:10:36.779  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:36.779  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:36.779  4598  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-16 11:10:36.779  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:36.779  4598  4790 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-16 11:10:36.779  4598  4790 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-16 11:10:36.779  4598  4598 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-16 11:10:36.779  4598  4790 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-16 11:10:36.780  4598  4598 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-16 11:10:36.780  4598  4790 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-16 11:10:36.780  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-16 11:10:36.780  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:36.780  4598  4660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-16 11:10:36.780  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:36.780  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:36.780  4598  4598 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-16 11:10:36.780  4598  4660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-16 11:10:36.780  4598  4660 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-16 11:10:36.781  4598  4598 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-16 11:10:36.781  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-16 11:10:36.781  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:36.781  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:36.781  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:36.781  4598  4598 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-16 11:10:36.782  4598  4598 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-16 11:10:36.783  4598  4598 D BluetoothMapService: MAP Service closeService in
11-16 11:10:36.783  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-16 11:10:36.783  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:36.783  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:36.783  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:36.783  4598  4598 D BluetoothMapService: cleanup()
11-16 11:10:36.783  4598  4598 D BluetoothMapService: MAP Service closeService in
11-16 11:10:36.783  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-16 11:10:36.784  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:36.784  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:36.784  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:36.784  4598  4656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-16 11:10:36.784  4598  4656 D BluetoothAdapterProperties: Setting state to 15
11-16 11:10:36.784  4598  4656 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-16 11:10:36.785  4598  4656 I BluetoothAdapterState: Entering BleOnState
11-16 11:10:36.785  3095  3108 D BluetoothPbap: onBluetoothStateChange: up=false
11-16 11:10:36.786  3781  3807 D BluetoothHeadset: onBluetoothStateChange: up=false
11-16 11:10:36.787  3095  3957 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-16 11:10:36.790   927  3134 I ActivityManager: Killing 5407:com.android.chrome/u0a39 (adj 15): empty #17
11-16 11:10:36.811  3095  3108 D BluetoothMap: onBluetoothStateChange: up=false
,11-16 11:10:36.813  3095  3111 D BluetoothHeadset: onBluetoothStateChange: up=false
11-16 11:10:36.813   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-16 11:10:36.813  3095  3957 D BluetoothA2dp: onBluetoothStateChange: up=false
11-16 11:10:36.813   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-16 11:10:36.813   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-16 11:10:36.814  3095  3108 D BluetoothPan: onBluetoothStateChange on: false
11-16 11:10:36.814   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-16 11:10:36.815  4598  4656 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-16 11:10:36.815  4598  4656 D BluetoothAdapterProperties: Setting state to 16
11-16 11:10:36.815  4598  4656 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-16 11:10:36.815  4598  4656 D BluetoothAdapterProperties: onBleDisable
11-16 11:10:36.815  4598  4656 I BluetoothAdapterState: Entering PendingCommandState
11-16 11:10:36.816  4598  4657 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-16 11:10:36.817  4598  4660 D BluetoothAdapterProperties: Scan Mode:20
11-16 11:10:36.818  4598  4790 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-16 11:10:36.818  4598  4790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-16 11:10:36.826  5679  5679 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-16 11:10:36.842  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-16 11:10:36.846   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cf24eae:true
,11-16 11:10:36.848  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-16 11:10:36.861   927   938 I ActivityManager: Start proc 5691:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-16 11:10:36.873  5679  5679 D LocalBluetoothProfileManager: Adding local MAP profile
,11-16 11:10:36.876  5679  5679 D BluetoothMap: Create BluetoothMap proxy object
,11-16 11:10:36.887  5679  5679 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-16 11:10:36.899  5691  5691 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-16 11:10:36.903  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-16 11:10:36.911   927  3572 I ActivityManager: Killing 4945:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-16 11:10:37.029  4598  4660 I bt_hci  : shut_down
,11-16 11:10:37.033  4598  4666 D bt_hwcfg: hw_epilog_process
,11-16 11:10:37.033  4598  4666 I bt_vendor: low_power_mode_cb
,11-16 11:10:37.036  4598  4666 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-16 11:10:37.036  4598  4666 I bt_vendor: epilog_cb
11-16 11:10:37.036  4598  4666 I bt_hci  : epilog_finished_callback
11-16 11:10:37.038  4598  4660 I bt_hci_h4: hal_close
11-16 11:10:37.038  4598  4660 I bt_userial_vendor: device fd = 54 close
,11-16 11:10:37.042   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:37.105  5691  5691 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at java.io.File.exists(File.java:361)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-16 11:10:37.105  5691  5691 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-16 11:10:37.105  5691  5691 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.105  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-16 11:10:37.106  5691  5691 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:170)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-16 11:10:37.106  5691  5691 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.k.d(PG:583)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:170)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-16 11:10:37.106  5691  5691 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.File.exists(File.java:361)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-16 11:10:37.106  5691  5691 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.File.exists(File.java:361)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-16 11:10:37.106  5691  5691 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-16 11:10:37.106  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-16 11:10:37.109  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-16 11:10:37.114  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-16 11:10:37.115  5679  5679 D DockEventReceiver: finishStartingService: stopping service
11-16 11:10:37.117   927  3852 I ActivityManager: Killing 5105:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-16 11:10:37.158  4598  4657 D bt_stack_manager: event_shut_down_stack finished.
11-16 11:10:37.158  4598  4656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-16 11:10:37.160  4598  4656 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-16 11:10:37.160  4598  4598 D BtGatt.DebugUtils: handleDebugAction() action=null
11-16 11:10:37.160  4598  4598 D BtGatt.GattService: Received stop request...Stopping profile...
11-16 11:10:37.160  4598  4598 D BtGatt.GattService: stop()
11-16 11:10:37.161  4598  4598 D BtGatt.AdvertiseManager: advertise clients cleared
11-16 11:10:37.163  4598  4598 V BluetoothAdapterState: isTurningOff()=false
11-16 11:10:37.163  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:37.163  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:37.163  4598  4598 V BluetoothAdapterState: isBleTurningOff()=true
11-16 11:10:37.163  4598  4656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-16 11:10:37.163  4598  4656 D BluetoothAdapterProperties: Setting state to 10
11-16 11:10:37.164  4598  4656 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-16 11:10:37.164  4598  4656 I BluetoothAdapterState: Entering OffState
11-16 11:10:37.165   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-16 11:10:37.170  4598  4598 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-16 11:10:37.170  4598  4598 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-16 11:10:37.170  4598  4598 I BluetoothServiceJni: cleanupNative: return from cleanup
11-16 11:10:37.171  4598  4657 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-16 11:10:37.180  4598  4657 D bt_stack_manager: event_clean_up_stack finished.
11-16 11:10:37.180  4598  4598 I art     : System.exit called, status: 0
11-16 11:10:37.180  4598  4598 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-16 11:10:37.207  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-16 11:10:37.216   927   937 I ActivityManager: Process com.android.bluetooth (pid 4598) has died
,11-16 11:10:37.237  5619  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-16 11:10:37.237  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-16 11:10:37.237  5619  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-16 11:10:37.237  5619  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-16 11:10:37.240  5619  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-16 11:10:37.251   927   944 I ActivityManager: Start proc 5724:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-16 11:10:37.273  5691  5723 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-16 11:10:37.310  5724  5724 D AdapterServiceConfig: Adding HeadsetService
,11-16 11:10:37.310  5724  5724 D AdapterServiceConfig: Adding A2dpService
11-16 11:10:37.310  5724  5724 D AdapterServiceConfig: Adding HidService
,11-16 11:10:37.310  5724  5724 D AdapterServiceConfig: Adding HealthService
11-16 11:10:37.310  5724  5724 D AdapterServiceConfig: Adding PanService
,11-16 11:10:37.310  5724  5724 D AdapterServiceConfig: Adding GattService
11-16 11:10:37.310  5724  5724 D AdapterServiceConfig: Adding BluetoothMapService
11-16 11:10:37.311  5724  5724 D AdapterServiceConfig: Adding SapService
,11-16 11:10:37.318   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c205c2:true
,11-16 11:10:37.318  5724  5724 D BluetoothAdapterState: make() - Creating AdapterState
,11-16 11:10:37.320  5724  5724 I bt_bluedroid: init
,11-16 11:10:37.320  5724  5737 I BluetoothAdapterState: Entering OffState
,11-16 11:10:37.322  5724  5738 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-16 11:10:37.322  5724  5738 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-16 11:10:37.322  5724  5738 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-16 11:10:37.322  5724  5738 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-16 11:10:37.322  5724  5724 I bt_bluedroid: get_profile_interface socket
,11-16 11:10:37.323  5724  5724 I bt_bluedroid: get_profile_interface sdp
,11-16 11:10:37.324  5724  5741 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-16 11:10:37.325  5724  5741 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-16 11:10:37.328  5724  5735 I bt_bluedroid: config_hci_snoop_log
,11-16 11:10:37.329   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-16 11:10:37.332  5724  5737 D BluetoothAdapterState: Current state: OFF, message: 0
,11-16 11:10:37.332  5724  5737 D BluetoothAdapterProperties: Setting state to 14
,11-16 11:10:37.332  5724  5737 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-16 11:10:37.334  5724  5737 D BluetoothBondStateMachine: make
11-16 11:10:37.335  5724  5742 I BluetoothBondStateMachine: StableState(): Entering Off State
11-16 11:10:37.338  5724  5737 I BluetoothAdapterState: Entering PendingCommandState
11-16 11:10:37.339  5724  5724 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-16 11:10:37.340  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
,11-16 11:10:37.340  5724  5724 D BtGatt.DebugUtils: handleDebugAction() action=null
11-16 11:10:37.341  5724  5724 D BtGatt.GattService: Received start request. Starting profile...
11-16 11:10:37.341  5724  5724 D BtGatt.GattService: start()
11-16 11:10:37.341  5724  5724 I bt_bluedroid: get_profile_interface gatt
,11-16 11:10:37.341  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
11-16 11:10:37.341  5724  5724 D BtGatt.AdvertiseManager: advertise manager created
,11-16 11:10:37.345  5724  5724 V BluetoothAdapterState: isTurningOff()=false
,11-16 11:10:37.345  5724  5724 V BluetoothAdapterState: isTurningOn()=false
11-16 11:10:37.345  5724  5724 V BluetoothAdapterState: isBleTurningOn()=true
11-16 11:10:37.345  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,11-16 11:10:37.345  5724  5737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-16 11:10:37.346  5724  5737 I bt_bluedroid: bt_bluedroid
11-16 11:10:37.346  5724  5738 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-16 11:10:37.347  5724  5738 I bt_hci  : start_up
,11-16 11:10:37.351  5724  5738 I bt_vendor: alloc value 0xf3c6b871
,11-16 11:10:37.351  5724  5738 I bt_vendor: init
11-16 11:10:37.352  5724  5738 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-16 11:10:37.352  5724  5738 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-16 11:10:37.365  5691  5714 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-16 11:10:37.380   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bff564b:true
,11-16 11:10:37.459  5724  5738 D bt_hci  : start_up starting async portion
,11-16 11:10:37.459  5724  5745 I bt_hci  : event_finish_startup
11-16 11:10:37.459  5724  5745 I bt_hci_h4: hal_open
11-16 11:10:37.459  5724  5745 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-16 11:10:37.460  5724  5745 I bt_userial_vendor: device fd = 54 open
,11-16 11:10:37.455  5748  5748 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-16 11:10:37.473  5724  5745 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-16 11:10:37.475  5724  5745 D bt_hwcfg: Chipset BCM4358A3
,11-16 11:10:37.475  5724  5745 D bt_hwcfg: Target name = [BCM4358A3]
11-16 11:10:37.475  5724  5745 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-16 11:10:37.743  5724  5737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-16 11:10:37.763  3556  5753 V NQFileLogger: [128] e.a: about to write to file
,11-16 11:10:37.767  3556  5753 V ProcessReports: [128] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-16 11:10:37.804  5724  5745 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-16 11:10:37.805  5724  5745 D bt_hwcfg: Settlement delay -- 100 ms
11-16 11:10:37.805  5724  5745 I bt_hwcfg: Setting fw settlement delay to 100 
,11-16 11:10:37.928  5724  5745 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-16 11:10:37.928  5724  5745 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-16 11:10:37.929  5724  5745 I bt_hwcfg: vendor lib fwcfg completed
11-16 11:10:37.929  5724  5745 I bt_vendor: firmware callback
11-16 11:10:37.929  5724  5745 I bt_hci  : firmware_config_callback
,11-16 11:10:37.938  5724  5755 I bt_btu  : btu_task pending for preload complete event
,11-16 11:10:37.939  5724  5755 I bt_btu_task: Bluetooth chip preload is complete
11-16 11:10:37.939  5724  5755 I bt_btu  : btu_task received preload complete event
11-16 11:10:37.945  5724  5755 I         : BTE_InitTraceLevels -- TRC_HCI
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_AVDT
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_AVRC
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_A2D
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_BNEP
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_BTM
,11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_GAP
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_PAN
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_SDP
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_GATT
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_SMP
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-16 11:10:37.946  5724  5755 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-16 11:10:38.026  5724  5755 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3be9549
,11-16 11:10:38.026  5724  5755 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3be9549 
,11-16 11:10:38.036  5724  5741 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-16 11:10:38.038  5724  5741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-16 11:10:38.038  5724  5741 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-16 11:10:38.041  5724  5741 D BluetoothAdapterProperties: Name is: Nexus 6P
11-16 11:10:38.043   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:38.044  5724  5741 D BluetoothAdapterProperties: Scan Mode:20
,11-16 11:10:38.045  5724  5741 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-16 11:10:38.045  5724  5741 D bt_hci  : do_postload posting postload work item
,11-16 11:10:38.045  5724  5745 I bt_hci  : event_postload
11-16 11:10:38.045  5724  5745 I bt_vendor: sco_config_cb
11-16 11:10:38.045  5724  5745 I bt_hci  : sco_config_callback postload finished.
,11-16 11:10:38.049  5724  5741 D bt_bte_conf: Device ID record 1 : primary
11-16 11:10:38.050  5724  5741 D bt_bte_conf:   vendorId            = 000f
11-16 11:10:38.050  5724  5741 D bt_bte_conf:   vendorIdSource      = 0001
11-16 11:10:38.050  5724  5741 D bt_bte_conf:   product             = 1200
11-16 11:10:38.050  5724  5741 D bt_bte_conf:   version             = 1436
11-16 11:10:38.050  5724  5741 D bt_bte_conf:   clientExecutableURL = 
11-16 11:10:38.050  5724  5741 D bt_bte_conf:   serviceDescription  = 
,11-16 11:10:38.050  5724  5741 D bt_bte_conf:   documentationURL    = 
11-16 11:10:38.050  5724  5741 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-16 11:10:38.050  5724  5738 D bt_stack_manager: event_start_up_stack finished
,11-16 11:10:38.052  5724  5737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-16 11:10:38.052  5724  5737 D BluetoothAdapterProperties: Setting state to 15
11-16 11:10:38.052  5724  5737 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-16 11:10:38.053  5724  5737 I BluetoothAdapterState: Entering BleOnState
,11-16 11:10:38.058  5724  5745 I bt_vendor: low_power_mode_cb
11-16 11:10:38.058  5724  5737 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-16 11:10:38.059  5724  5737 D BluetoothAdapterProperties: Setting state to 11
11-16 11:10:38.059  5724  5737 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-16 11:10:38.071  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
,11-16 11:10:38.073  5724  5724 D HeadsetService: Received start request. Starting profile...
,11-16 11:10:38.075  5724  5724 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-16 11:10:38.076  5724  5724 D HeadsetStateMachine: make
,11-16 11:10:38.079  5724  5737 I BluetoothAdapterState: Entering PendingCommandState
,11-16 11:10:38.086  5724  5724 D HeadsetStateMachine: max_hf_connections = 1
11-16 11:10:38.086  5724  5724 I bt_bluedroid: get_profile_interface handsfree
11-16 11:10:38.086  5724  5741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-16 11:10:38.086  5724  5741 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,11-16 11:10:38.090  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
11-16 11:10:38.091  5724  5724 D A2dpService: Received start request. Starting profile...
11-16 11:10:38.092  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-16 11:10:38.092  5724  5724 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-16 11:10:38.092  5724  5724 I bt_bluedroid: get_profile_interface avrcp
,11-16 11:10:38.098  5724  5724 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-16 11:10:38.098  5724  5724 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-16 11:10:38.098  5724  5724 D A2dpStateMachine: make
,11-16 11:10:38.100  5724  5724 I bt_bluedroid: get_profile_interface a2dp
,11-16 11:10:38.101  5724  5741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-16 11:10:38.103  5724  5763 D A2dpStateMachine: Enter Disconnected: -2
,11-16 11:10:38.103  5724  5724 I BluetoothHidServiceJni: classInitNative: succeeds
,11-16 11:10:38.104  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
11-16 11:10:38.105  5679  5679 D BluetoothInputDevice: Proxy object connected
11-16 11:10:38.106  5679  5679 D HidProfile: Bluetooth service connected
11-16 11:10:38.106  5724  5724 D HidService: Received start request. Starting profile...
11-16 11:10:38.106  5724  5724 I bt_bluedroid: get_profile_interface hidhost
11-16 11:10:38.106  5724  5724 D HidService: setHidService(): set to: null
11-16 11:10:38.107  5724  5741 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bca56d
11-16 11:10:38.107  5724  5741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-16 11:10:38.107  5724  5724 I BluetoothHealthServiceJni: classInitNative: succeeds
11-16 11:10:38.108  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
11-16 11:10:38.109  5724  5724 D HealthService: Received start request. Starting profile...
11-16 11:10:38.110  5724  5724 I bt_bluedroid: get_profile_interface health
,11-16 11:10:38.111  5724  5724 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-16 11:10:38.112  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
,11-16 11:10:38.113  5679  5679 D BluetoothPan: BluetoothPAN Proxy object connected
,11-16 11:10:38.113  5724  5724 D PanService: Received start request. Starting profile...
11-16 11:10:38.113  5724  5724 D BluetoothPanServiceJni: initializeNative(L110): pan
11-16 11:10:38.113  5724  5724 I bt_bluedroid: get_profile_interface pan
11-16 11:10:38.114  5679  5679 D PanProfile: Bluetooth service connected
11-16 11:10:38.114  5724  5741 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-16 11:10:38.116  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
,11-16 11:10:38.117  5679  5679 D BluetoothMap: Proxy object connected
,11-16 11:10:38.118  5724  5724 D BluetoothMapService: Received start request. Starting profile...
11-16 11:10:38.118  5724  5724 D BluetoothMapService: start()
11-16 11:10:38.121  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-16 11:10:38.122  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-16 11:10:38.122  5724  5724 D BluetoothMapAppObserver: createReceiver()
11-16 11:10:38.123  5724  5724 D BluetoothMapAppObserver: initObservers()
11-16 11:10:38.123  5724  5724 D BluetoothMapAppObserver: getEnabledAccountItems()
11-16 11:10:38.129  5724  5724 V SapService: SapBinder()
11-16 11:10:38.130  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
11-16 11:10:38.130  5724  5724 D SapService: Received start request. Starting profile...
11-16 11:10:38.130  5724  5724 V SapService: start()
11-16 11:10:38.131  5679  5679 D MapProfile: Bluetooth service connected
,11-16 11:10:38.131  5679  5679 D BluetoothMap: getConnectedDevices()
11-16 11:10:38.132  5679  5679 D BluetoothMap: Bluetooth is Not enabled
,11-16 11:10:38.133  5724  5724 V BluetoothAdapterState: isTurningOff()=false
,11-16 11:10:38.133  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-16 11:10:38.133  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:38.133  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:38.134  5724  5761 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-16 11:10:38.134  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-16 11:10:38.134  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-16 11:10:38.134  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:38.134  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
,11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:38.135  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-16 11:10:38.137  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-16 11:10:38.137  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-16 11:10:38.137  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-16 11:10:38.137  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,11-16 11:10:38.137  5724  5737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-16 11:10:38.137  5724  5737 D BluetoothAdapterProperties: ScanMode =  20
11-16 11:10:38.137  5724  5737 D BluetoothAdapterProperties: State =  11
11-16 11:10:38.138  5724  5737 D BluetoothAdapterProperties: Setting state to 12
11-16 11:10:38.138  5724  5737 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-16 11:10:38.138  5724  5737 I BluetoothAdapterState: Entering OnState
11-16 11:10:38.138  3095  3957 D BluetoothPbap: onBluetoothStateChange: up=true
,11-16 11:10:38.142  5724  5741 D BluetoothAdapterProperties: Scan Mode:21
,11-16 11:10:38.142  5724  5741 D BluetoothAdapterProperties: Discoverable Timeout:120
11-16 11:10:38.143  3781  3994 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-16 11:10:38.143  5679  5689 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-16 11:10:38.143  3095  3111 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-16 11:10:38.145  3095  3095 D BluetoothInputDevice: Proxy object connected
11-16 11:10:38.145  3095  3957 D BluetoothMap: onBluetoothStateChange: up=true
11-16 11:10:38.145  3095  3095 D HidProfile: Bluetooth service connected
11-16 11:10:38.146  3095  3957 D BluetoothHeadset: onBluetoothStateChange: up=true
11-16 11:10:38.146  5679  5690 D BluetoothMap: onBluetoothStateChange: up=true
11-16 11:10:38.147   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-16 11:10:38.147  3095  3095 D BluetoothMap: Proxy object connected
,11-16 11:10:38.147  3095  3095 D MapProfile: Bluetooth service connected
11-16 11:10:38.147  3095  3095 D BluetoothMap: getConnectedDevices()
11-16 11:10:38.147  3095  3111 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-16 11:10:38.148  5679  5689 D BluetoothPan: onBluetoothStateChange on: true
11-16 11:10:38.148  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-16 11:10:38.149  5679  5690 D BluetoothPbap: onBluetoothStateChange: up=true
11-16 11:10:38.149  5724  5724 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-16 11:10:38.150   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-16 11:10:38.150   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-16 11:10:38.150  3095  3108 D BluetoothPan: onBluetoothStateChange on: true
11-16 11:10:38.151  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-16 11:10:38.152   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-16 11:10:38.152  3095  3095 D BluetoothPan: BluetoothPAN Proxy object connected
11-16 11:10:38.152  3095  3095 D PanProfile: Bluetooth service connected
11-16 11:10:38.153   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-16 11:10:38.154  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-16 11:10:38.155  5724  5724 D ObexServerSockets: Succeed to create listening sockets 
11-16 11:10:38.155  5724  5724 D ObexServerSockets0: startAccept()
11-16 11:10:38.155  5724  5724 D ObexServerSockets0: prepareForNewConnect()
11-16 11:10:38.156  5679  5679 D LocalBluetoothProfileManager: Adding local A2DP profile
11-16 11:10:38.158  5724  5724 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-16 11:10:38.158  5724  5724 D BluetoothSdpJni: SDP Create record success - handle: 0
11-16 11:10:38.159  5679  5679 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-16 11:10:38.159  5724  5770 D ObexServerSockets0: Accepting socket connection...
11-16 11:10:38.159  5724  5771 D ObexServerSockets0: Accepting socket connection...
,11-16 11:10:38.161   927   927 D BluetoothA2dp: Proxy object connected
11-16 11:10:38.161  5724  5724 D BluetoothMapService: onReceive
11-16 11:10:38.161  5724  5724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-16 11:10:38.161  5724  5724 D BluetoothMapService: STATE_ON
11-16 11:10:38.165  5724  5772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-16 11:10:38.166  5724  5772 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-16 11:10:38.166  5724  5772 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-16 11:10:38.167  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-16 11:10:38.170  3095  3095 D BluetoothA2dp: Proxy object connected
,11-16 11:10:38.170  5679  5679 D BluetoothA2dp: Proxy object connected
,11-16 11:10:38.176  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-16 11:10:38.178  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-16 11:10:38.183  3095  3095 D BluetoothPbap: Proxy object connected
,11-16 11:10:38.183  5679  5679 D BluetoothPbap: Proxy object connected
11-16 11:10:38.183  3095  3095 D PbapServerProfile: Bluetooth service connected
,11-16 11:10:38.183  5679  5679 D PbapServerProfile: Bluetooth service connected
,11-16 11:10:38.189  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-16 11:10:38.189  5724  5724 D ObexServerSockets0: prepareForNewConnect()
,11-16 11:10:38.190  5724  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-16 11:10:38.205  5724  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-16 11:10:38.206  5724  5780 I BtOppRfcommListener: Accept thread started.
,11-16 11:10:38.244   927   927 D BluetoothHeadset: Proxy object connected
,11-16 11:10:38.245  3781  3807 D BluetoothHeadset: Proxy object connected
11-16 11:10:38.245  3095  3957 D BluetoothHeadset: Proxy object connected
11-16 11:10:38.245  3095  3095 D HeadsetProfile: Bluetooth service connected
11-16 11:10:38.245   927   927 D BluetoothHeadset: Proxy object connected
11-16 11:10:38.245   927   927 D BluetoothHeadset: Proxy object connected
11-16 11:10:38.247  3095  3111 D BluetoothHeadset: Proxy object connected
,11-16 11:10:38.248  3095  3095 D HeadsetProfile: Bluetooth service connected
11-16 11:10:38.248   927   944 D BluetoothHeadset: Proxy object connected
,11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-16 11:10:38.249  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-16 11:10:38.250   927   944 D BluetoothHeadset: Proxy object connected
,11-16 11:10:38.251  5619  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-16 11:10:38.252   927   944 D BluetoothHeadset: Proxy object connected
,11-16 11:10:38.252  5619  5666 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-16 11:10:38.253   927  3133 D WifiService: setWifiEnabled: false pid=5619, uid=10077
,11-16 11:10:38.253   927  3133 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-16 11:10:38.254   927  2930 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-16 11:10:38.255   927  2930 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-16 11:10:38.255   927  2930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-16 11:10:38.255   927  2930 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-16 11:10:38.255  5619  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-16 11:10:38.262  5679  5689 D BluetoothHeadset: Proxy object connected
,11-16 11:10:38.265  5679  5679 D HeadsetProfile: Bluetooth service connected
,11-16 11:10:38.268   927  5365 D DhcpClient: Clearing IP address
,11-16 11:10:38.268   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-16 11:10:38.274   508   921 D CommandListener: Setting iface cfg
,11-16 11:10:38.276  3556  5420 V NativeCrypto: Read error: ssl=0x7f7c921280: I/O error during system call, Connection timed out
,11-16 11:10:38.278  3556  5420 V NativeCrypto: SSL shutdown failed: ssl=0x7f7c921280: I/O error during system call, Broken pipe
11-16 11:10:38.280   927   937 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-16 11:10:38.280   927  5361 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-16 11:10:38.282   927  5361 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-16 11:10:38.283   927  2939 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-16 11:10:38.283   927  2939 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-16 11:10:38.284   927  2939 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-16 11:10:38.285   927  2939 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-16 11:10:38.285   927  2939 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-16 11:10:38.289   535   535 E Parcel  : Reading a NULL string not supported here.
11-16 11:10:38.292   927   927 D RttService: SCAN_AVAILABLE : 1
11-16 11:10:38.292   927  3061 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-16 11:10:38.293   927  2939 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-16 11:10:38.294  3742  3900 W QCNEJ   : |CORE| network lost: 100
11-16 11:10:38.295  3742  3900 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-16 11:10:38.304   927  5366 D DhcpClient: Receive thread stopped
,11-16 11:10:38.309   927  2930 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-16 11:10:38.315   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-16 11:10:38.319   927  2930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-16 11:10:38.337   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-16 11:10:38.338   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-16 11:10:38.338   927  2939 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-16 11:10:38.339   927  2939 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-16 11:10:38.342   927   944 D Tethering: MasterInitialState.processMessage what=3
11-16 11:10:38.342  5264  5264 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6213dbf and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-16 11:10:38.343   927  2930 D DhcpClient: doQuit
11-16 11:10:38.343   927  2930 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-16 11:10:38.344   927  5365 D DhcpClient: onQuitting
11-16 11:10:38.344  3417  3417 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-16 11:10:38.352  5031  5055 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-16 11:10:38.352  5031  5055 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-16 11:10:38.352  5031  5055 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-16 11:10:38.352  5031  5055 E SarControlService: no key has been found,reset the power
11-16 11:10:38.353  5031  5068 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-16 11:10:38.353  5031  5068 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-16 11:10:38.353  5031  5068 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-16 11:10:38.353  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-16 11:10:38.353  5056  5056 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-16 11:10:38.354  5031  5068 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-16 11:10:38.355  5031  5068 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-16 11:10:38.356  3846  3846 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-16 11:10:38.356  5031  5068 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-16 11:10:38.357  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-16 11:10:38.357  5056  5056 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-16 11:10:38.359  3846  3846 D SystemUpdateService: onCreate
,11-16 11:10:38.360  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e38285d HexData = [00000000ea03000000000000ffffffff]
11-16 11:10:38.360  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-16 11:10:38.360  5056  5070 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-16 11:10:38.360  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-16 11:10:38.360  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-16 11:10:38.363  3846  3846 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-16 11:10:38.365  3846  5793 I SystemUpdateService: active receiver: enabled
11-16 11:10:38.366  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e38285d HexData = [00000000eb03000000000000ffffffff]
11-16 11:10:38.366  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-16 11:10:38.366  5056  5070 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-16 11:10:38.366  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-16 11:10:38.366  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-16 11:10:38.369  3846  5793 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-16 11:10:38.370  3417  3417 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-16 11:10:38.371  3846  5793 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-16 11:10:38.371  3846  5793 I SystemUpdateService: now status is 0 (complete)
11-16 11:10:38.371  3846  5793 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-16 11:10:38.371  3846  5793 I SystemUpdateService: file has been verified
11-16 11:10:38.371  3846  5793 I SystemUpdateService: OTA package size = 21989297
11-16 11:10:38.372  3846  3846 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-16 11:10:38.375  3846  5793 I SystemUpdateService: showing system update notification
,11-16 11:10:38.375  3846  5391 I iu.UploadsManager: num queued entries: 0
11-16 11:10:38.375  3417  3417 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-16 11:10:38.376  3846  5391 I iu.UploadsManager: num updated entries: 0
11-16 11:10:38.378  3846  5391 I iu.SyncManager: NEXT; no task
,11-16 11:10:38.387  3846  3846 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-16 11:10:38.388  3846  3846 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-16 11:10:38.389  3846  3846 D SystemUpdateService: onDestroy
,11-16 11:10:38.400   927  3822 I ActivityManager: Start proc 5797:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-16 11:10:38.403  3417  3417 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-16 11:10:38.406   508   921 E Netd    : netlink response contains error (No such file or directory)
,11-16 11:10:38.407   508   921 D TetherController: Setting IP forward enable = 0
,11-16 11:10:38.408   927  2939 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-16 11:10:38.415  3417  3417 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-16 11:10:38.433  5797  5797 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-16 11:10:38.435  5797  5797 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-16 11:10:38.442  5797  5797 D SprintDMHelper: simOperator: 
,11-16 11:10:38.443  5797  5797 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-16 11:10:38.448   508   921 D TetherController: Setting IP forward enable = 0
,11-16 11:10:38.455   927  3134 I ActivityManager: Start proc 5815:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-16 11:10:38.520   927  2930 D wifi    : In wifi stop Hal
,11-16 11:10:38.521   927  2930 D wifi    : halHandle = 0x7f7aae7180, mVM = 0x7f9710d140, mCls = 0x100a02
11-16 11:10:38.521   927  3416 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-16 11:10:38.521   927  3416 D WifiHAL : Got a signal to exit!!!
11-16 11:10:38.521   927  3416 I WifiHAL : Exit wifi_event_loop
11-16 11:10:38.522   927  2930 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-16 11:10:38.522   927  2930 E WifiHAL : Event processing terminated
11-16 11:10:38.522   927  2930 D wifi    : In wifi cleaned up handler
11-16 11:10:38.522   927  2930 I WifiHAL : Internal cleanup completed
,11-16 11:10:38.522  4055  4212 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-16 11:10:38.523  4981  4981 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-16 11:10:38.526  4981  5830 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-16 11:10:38.540   927  3572 I ActivityManager: Start proc 5831:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-16 11:10:38.543   927  3136 I ActivityManager: Killing 5442:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-16 11:10:38.543   927  3416 D wifi    : set interface wlan0 flags (DOWN)
11-16 11:10:38.544   927  2930 D WifiNative-HAL: HAL event thread stopped successfully
,11-16 11:10:38.585  5831  5831 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-16 11:10:38.592   927  3136 I ActivityManager: Killing 5264:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-16 11:10:38.750   927   944 D Tethering: InitialState.processMessage what=4
,11-16 11:10:38.756   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-16 11:10:38.766  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-16 11:10:38.772  5619  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-16 11:10:38.775   927  3136 D WifiService: setWifiEnabled: true pid=5619, uid=10077
,11-16 11:10:38.775   927  3136 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-16 11:10:38.777  5619  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-16 11:10:38.784   508   921 D SoftapController: Softap fwReload - Ok
,11-16 11:10:38.788   508   921 D CommandListener: Setting iface cfg
,11-16 11:10:38.788   508   921 D CommandListener: Trying to bring down wlan0
,11-16 11:10:38.790   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-16 11:10:38.793   927  2930 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-16 11:10:39.044   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:39.284   927  3822 D WifiService: setWifiEnabled: true pid=5619, uid=10077
,11-16 11:10:39.284   927  3822 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-16 11:10:39.393   927  2930 D wifi    : set interface wlan0 flags (UP)
,11-16 11:10:39.393   927  2930 I WifiHAL : Initializing wifi
,11-16 11:10:39.395   927  2930 I WifiHAL : Creating socket
,11-16 11:10:39.399   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-16 11:10:39.400   927  2930 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-16 11:10:39.401   927  2930 D wifi    : Did set static halHandle = 0x7f7aae7180
11-16 11:10:39.401   927  2930 D wifi    : halHandle = 0x7f7aae7180, mVM = 0x7f9710d140, mCls = 0x18ae
11-16 11:10:39.401   927  2930 D wifi    : array field set
,11-16 11:10:39.401   927  2930 I WifiNative-HAL: interface[0] = wlan0
11-16 11:10:39.403   927  5847 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547519099264
,11-16 11:10:39.403   927  5847 D wifi    : waitForHalEvents called, vm = 0x7f9710d140, obj = 0x18ae, env = 0x7f7bb3e380
,11-16 11:10:39.487  5848  5848 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-16 11:10:39.504   927  2930 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-16 11:10:39.514  5848  5848 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-16 11:10:39.537  5848  5848 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-16 11:10:39.537  5848  5848 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-16 11:10:39.556   927  2930 D WifiConfigStore: Loading config and enabling all networks 
,11-16 11:10:39.567   927  2930 D WifiConfigStore: loaded 0 passpoint configs
,11-16 11:10:39.568   927  2930 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-16 11:10:39.568   927  2930 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-16 11:10:39.569   927  2930 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-16 11:10:39.570   927  2930 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-16 11:10:39.570   927  2930 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-16 11:10:39.571   927  2930 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-16 11:10:39.571   927  2930 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-16 11:10:39.573   927  2930 D WifiNative-HAL: Setting external_sim to 1
,11-16 11:10:39.574  4981  4981 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-16 11:10:39.574   927  2930 D wifi    : setting dfs flag to true, 0x7f7fcdea20
,11-16 11:10:39.575   927  2930 D WifiStateMachine: Setting OUI to DA-A1-19
11-16 11:10:39.575   927  2930 D wifi    : setting scan oui 0x7f7fcdea20
11-16 11:10:39.575   927  2930 D WifiHAL : Sending mac address OUI
,11-16 11:10:39.579   927  2930 E native  : do suspend false
,11-16 11:10:39.586   927  2930 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-16 11:10:39.586   927   927 D RttService: SCAN_AVAILABLE : 3
11-16 11:10:39.586   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-16 11:10:39.586   927  3061 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-16 11:10:39.587   508   921 D CommandListener: Setting iface cfg
,11-16 11:10:39.591   927  2923 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,11-16 11:10:39.591   927  2923 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-16 11:10:39.604   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=132823 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-16 11:10:39.605   927  2923 D WifiNative-HAL: p2pGetDeviceAddress
,11-16 11:10:39.606   927  2923 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-16 11:10:39.796  5619  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-16 11:10:39.802  5619  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-16 11:10:39.805  5619  5666 D BluetoothAdapter: enable(): BT is already enabled..!
,11-16 11:10:39.806   927   937 D WifiService: setWifiEnabled: true pid=5619, uid=10077
,11-16 11:10:39.806   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-16 11:10:39.807  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-16 11:10:39.808  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-16 11:10:39.808  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-16 11:10:39.808  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb4024 removed from the list
,11-16 11:10:39.808  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-16 11:10:39.808  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbd778d removed from the list
11-16 11:10:39.809  5619  5666 D io.jxcore.node.ConnectivityMonitor: stop
,11-16 11:10:39.812  5619  5666 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-16 11:10:39.815  5619  5666 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-16 11:10:39.817  5619  5666 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-16 11:10:39.820  5619  5666 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-16 11:10:39.824  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-16 11:10:39.825  5619  5666 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-16 11:10:39.827  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-16 11:10:39.827  5619  5666 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-16 11:10:39.828  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-16 11:10:39.831  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-16 11:10:39.831  5619  5666 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@97feb5a Bundle[{}]
,11-16 11:10:39.832  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-16 11:10:39.832  5619  5666 I io.jxcore.node.LifeCycleMonitor: start: OK
11-16 11:10:39.832  5619  5666 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-16 11:10:39.833  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-16 11:10:39.833  5619  5666 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-16 11:10:39.834  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-16 11:10:39.834  5619  5666 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-16 11:10:39.835  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-16 11:10:39.835  5619  5666 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-16 11:10:39.835  5619  5666 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-16 11:10:39.836  5619  5666 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-16 11:10:39.837  5619  5666 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-16 11:10:39.839  5619  5666 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-16 11:10:39.840  5619  5666 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-16 11:10:39.841  5619  5666 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-16 11:10:39.842  5619  5666 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-16 11:10:39.843  5619  5666 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-16 11:10:39.844  5619  5666 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-16 11:10:39.845  5619  5666 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-16 11:10:39.846  5619  5666 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-16 11:10:39.848  5619  5666 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-16 11:10:39.849  5619  5666 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-16 11:10:39.849  5619  5666 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-16 11:10:39.849  5619  5666 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-16 11:10:39.850  5619  5666 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-16 11:10:39.850  5619  5666 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-16 11:10:39.850  5619  5666 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
11-16 11:10:39.851  5619  5666 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-16 11:10:39.852  5619  5666 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-16 11:10:39.852  5619  5666 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-16 11:10:39.853  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-16 11:10:39.853  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6f153 added. We now have 3 listener(s)
11-16 11:10:39.854  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-16 11:10:39.854  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-16 11:10:39.855  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-16 11:10:39.855  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-16 11:10:39.855  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e3a90 added. We now have 3 listener(s)
11-16 11:10:39.855  5619  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-16 11:10:39.855  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-16 11:10:39.860  5619  5666 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-16 11:10:39.861  5619  5666 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-16 11:10:39.861  5619  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-16 11:10:39.861  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-16 11:10:39.861  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.861  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.861  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.861  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:39.862  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-16 11:10:39.862  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-16 11:10:39.862  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:39.862  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-16 11:10:39.864  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-16 11:10:39.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-16 11:10:39.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-16 11:10:39.865  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-16 11:10:39.865  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-16 11:10:39.865  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-16 11:10:39.865  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-16 11:10:39.865  5619  5851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-16 11:10:39.865  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:39.865  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-16 11:10:39.866  5619  5851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-16 11:10:39.865  5769  5769 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31372]" dev="sockfs" ino=31372 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-16 11:10:39.865  5769  5769 W Binder_5: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31372]" dev="sockfs" ino=31372 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:39.869  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-16 11:10:39.869  5619  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-16 11:10:39.869  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-16 11:10:39.870  5619  5851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-16 11:10:39.873  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:39.873  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-16 11:10:39.874  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-16 11:10:39.874  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-16 11:10:39.874  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-16 11:10:39.876  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:39.876  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.876  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-16 11:10:39.877  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-16 11:10:39.877  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:39.877  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
,11-16 11:10:39.877  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:39.877  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:39.877  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.877  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-16 11:10:39.877  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-16 11:10:39.877  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.877  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.877  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:39.878  5619  5666 D BluetoothAdapter: STATE_ON
,11-16 11:10:39.881  5724  5735 D BtGatt.GattService: registerClient() - UUID=0984907f-6930-4ed1-90b0-de0794339bf8
,11-16 11:10:39.882  5724  5741 D BtGatt.GattService: onClientRegistered() - UUID=0984907f-6930-4ed1-90b0-de0794339bf8, clientIf=5
,11-16 11:10:39.883  5619  5629 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-16 11:10:39.885  5724  5743 D BtGatt.AdvertiseManager: message : 0
,11-16 11:10:39.887  5724  5743 D BtGatt.AdvertiseManager: starting multi advertising
,11-16 11:10:39.892  5724  5741 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-16 11:10:39.894  5724  5741 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-16 11:10:39.895  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:39.895  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.895  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-16 11:10:39.895  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.895  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.895  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.895  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:39.896  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.896  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-16 11:10:39.897  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-16 11:10:39.897  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:39.899  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.899  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.899  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:39.899  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:39.899  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.899  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:39.899  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-16 11:10:39.899  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.899  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.900  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:39.900  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.900  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-16 11:10:39.900  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-16 11:10:39.900  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.900  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.900  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-16 11:10:39.900  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.903  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.903  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-16 11:10:39.903  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.903  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.903  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:39.903  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-16 11:10:40.048   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:40.404  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-16 11:10:40.404  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-16 11:10:40.405  5619  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-16 11:10:41.048   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-16 11:10:42.672  5848  5848 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-16 11:10:42.676  5848  5848 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-16 11:10:42.682  5848  5848 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-16 11:10:42.686  5848  5848 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-16 11:10:42.741   927  3822 I ActivityManager: Killing 4670:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-16 11:10:42.750   927  2930 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-16 11:10:42.759   927  2930 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-16 11:10:42.759   927  2930 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-16 11:10:42.769   927  2930 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-16 11:10:42.800   927  2930 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-16 11:10:42.802  5848  5848 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-16 11:10:43.221  5848  5848 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-16 11:10:43.253  5848  5848 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-16 11:10:43.253  5848  5848 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-16 11:10:43.264   927  2930 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-16 11:10:43.265   927  2930 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-16 11:10:43.265   927  2939 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-16 11:10:43.279   927  2930 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-16 11:10:43.290   508   921 D CommandListener: Setting iface cfg
,11-16 11:10:43.295   927  2930 D WifiStateMachine: Start Dhcp Watchdog 2
,11-16 11:10:43.300   927  5858 D DhcpClient: Receive thread started
,11-16 11:10:43.304   927  2939 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-16 11:10:43.304   927  2930 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-16 11:10:43.304   927  2939 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-16 11:10:43.385   927  2930 E native  : do suspend false
,11-16 11:10:43.399   927  5857 D DhcpClient: Broadcasting DHCPDISCOVER
,11-16 11:10:43.402  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-16 11:10:43.402  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-16 11:10:43.402  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-16 11:10:43.402  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-16 11:10:43.403  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-16 11:10:43.403  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-16 11:10:43.403  5619  5851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-16 11:10:43.403  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-16 11:10:43.403  5619  5851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-16 11:10:43.404  5619  5851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-16 11:10:43.404  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-16 11:10:43.404  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-16 11:10:43.404  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-16 11:10:43.404  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-16 11:10:43.405  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-16 11:10:43.405  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-16 11:10:43.405  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.405  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.406  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.406  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.409  5619  5666 D BluetoothAdapter: STATE_ON
,11-16 11:10:43.410  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-16 11:10:43.412  5619  5666 D BluetoothAdapter: STATE_ON
,11-16 11:10:43.412  5619  5666 D BluetoothLeScanner: could not find callback wrapper
11-16 11:10:43.412  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-16 11:10:43.412  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.412  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.413  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.413  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-16 11:10:43.413  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.416  5724  5743 D BtGatt.AdvertiseManager: message : 1
11-16 11:10:43.417  5724  5743 D BtGatt.AdvertiseManager: stop advertise for client 5
11-16 11:10:43.419   927  5858 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172704, domain null
11-16 11:10:43.419   927  5857 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172704 seconds
11-16 11:10:43.422   927  5857 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-16 11:10:43.433  5724  5741 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-16 11:10:43.433   927  5858 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-16 11:10:43.434  5724  5741 D BtGatt.GattService: Client app is not null!
11-16 11:10:43.435   927  5857 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-16 11:10:43.435  5724  5760 D BtGatt.GattService: unregisterClient() - clientIf=5
11-16 11:10:43.438   508   921 D CommandListener: Setting iface cfg
,11-16 11:10:43.442  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-16 11:10:43.442   927  2930 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-16 11:10:43.442  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.442  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:43.442  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.443  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.443  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.443  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-16 11:10:43.443  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-16 11:10:43.445  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-16 11:10:43.446  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.447  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.448  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:43.448  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.448  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.448  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-16 11:10:43.448  5619  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-16 11:10:43.448  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-16 11:10:43.449  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-16 11:10:43.449  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:43.449  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:43.449  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:43.449  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.449  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-16 11:10:43.449  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-16 11:10:43.449  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.449  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.449  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-16 11:10:43.450  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.451  5619  5666 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-16 11:10:43.451  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-16 11:10:43.452  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.452  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.452  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.452  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.452  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-16 11:10:43.452  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-16 11:10:43.452  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-16 11:10:43.453  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-16 11:10:43.453  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:43.453  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-16 11:10:43.454   927  5857 D DhcpClient: Scheduling renewal in 86399s
11-16 11:10:43.455  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-16 11:10:43.459  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-16 11:10:43.459  5619  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-16 11:10:43.460  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-16 11:10:43.466  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.466  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-16 11:10:43.467  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-16 11:10:43.468  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-16 11:10:43.468  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-16 11:10:43.468   927  2930 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-16 11:10:43.469   927  2930 D WifiConfigStore: No blacklist allowed without epno enabled
11-16 11:10:43.469   927  2939 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-16 11:10:43.470   927  2930 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-16 11:10:43.471   927  2939 D ConnectivityService: Adding iface wlan0 to network 101
11-16 11:10:43.471  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-16 11:10:43.481  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-16 11:10:43.481  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:43.481  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-16 11:10:43.481  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-16 11:10:43.481  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-16 11:10:43.482  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-16 11:10:43.482  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.485  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:43.488  5724  5769 D BtGatt.GattService: registerClient() - UUID=63d8259a-9053-4286-be3c-904aa92d105f
11-16 11:10:43.489  5724  5741 D BtGatt.GattService: onClientRegistered() - UUID=63d8259a-9053-4286-be3c-904aa92d105f, clientIf=5
11-16 11:10:43.489  5619  5629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-16 11:10:43.490  5724  5735 D BtGatt.GattService: start scan with filters
11-16 11:10:43.494  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-16 11:10:43.494  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.494  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-16 11:10:43.494  5724  5744 D BtGatt.ScanManager: handling starting scan
11-16 11:10:43.495  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.495  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-16 11:10:43.495  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-16 11:10:43.495  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-16 11:10:43.495  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-16 11:10:43.496  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-16 11:10:43.496  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.496  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.496  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-16 11:10:43.496  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-16 11:10:43.497  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.497  5724  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb2cd6f
11-16 11:10:43.499  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.499  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-16 11:10:43.499  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.499  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:43.499  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.503  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.503  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.503  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:43.503  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-16 11:10:43.505  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-16 11:10:43.505  5724  5741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-16 11:10:43.505  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:43.506  5724  5744 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-16 11:10:43.512  5724  5741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-16 11:10:43.512  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:43.513  5724  5744 D BtGatt.ScanManager: Starting BLE batch scan
11-16 11:10:43.513  5724  5744 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-16 11:10:43.514   927  2939 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-16 11:10:43.514   927  2939 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-16 11:10:43.515   927  2939 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-16 11:10:43.516   927  2939 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-16 11:10:43.517   927  2939 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-16 11:10:43.522   927  2939 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-16 11:10:43.526   927  2939 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-16 11:10:43.526   927  2939 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-16 11:10:43.526   927  2939 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-16 11:10:43.526   927  2939 D ConnectivityService:    accepting network in place of null
11-16 11:10:43.526   927  2930 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-16 11:10:43.526   927  2930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-16 11:10:43.527  5724  5741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-16 11:10:43.527  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:43.527   927  2939 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-16 11:10:43.532  5724  5741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-16 11:10:43.532  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-16 11:10:43.548   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-16 11:10:43.565   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-16 11:10:43.568   927  2939 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-16 11:10:43.568   927  2939 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-16 11:10:43.568  3742  3900 W QCNEJ   : |CORE| network available: 101
,11-16 11:10:43.569   927  2939 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-16 11:10:43.571   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-16 11:10:43.572  3742  3900 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-16 11:10:43.573  3742  3900 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-16 11:10:43.573  3742  3900 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-16 11:10:43.583  3846  3846 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-16 11:10:43.586  3846  3846 D SystemUpdateService: onCreate
,11-16 11:10:43.589  3846  3846 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-16 11:10:43.590  5031  5055 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-16 11:10:43.590  5031  5055 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-16 11:10:43.590  5031  5055 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-16 11:10:43.591  5031  5055 E SarControlService: no key has been found,reset the power
11-16 11:10:43.591  5031  5068 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-16 11:10:43.591  5031  5068 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-16 11:10:43.592  5031  5068 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-16 11:10:43.592  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-16 11:10:43.592  5056  5056 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-16 11:10:43.593  5031  5068 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-16 11:10:43.593  5031  5068 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-16 11:10:43.593  5031  5068 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-16 11:10:43.594  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-16 11:10:43.594  5056  5056 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-16 11:10:43.598  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e38285d HexData = [00000000ec03000000000000ffffffff]
11-16 11:10:43.598  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-16 11:10:43.598  5056  5070 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-16 11:10:43.598  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-16 11:10:43.599  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-16 11:10:43.599  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e38285d HexData = [00000000ed03000000000000ffffffff]
11-16 11:10:43.599  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-16 11:10:43.599  5056  5070 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-16 11:10:43.600  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-16 11:10:43.600  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-16 11:10:43.609   927  5856 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136828, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-16 11:10:43.611  3846  3846 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-16 11:10:43.628  3846  5391 I iu.UploadsManager: num queued entries: 0
11-16 11:10:43.628  3846  5391 I iu.UploadsManager: num updated entries: 0
,11-16 11:10:43.629  3846  5391 I iu.SyncManager: NEXT; no task
,11-16 11:10:43.630  3846  3846 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-16 11:10:43.632  3846  3846 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-16 11:10:43.633  5797  5797 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-16 11:10:43.637  5797  5797 D SprintDMHelper: simOperator: 
,11-16 11:10:43.637  5797  5797 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-16 11:10:43.646  3846  5869 I SystemUpdateService: active receiver: enabled
,11-16 11:10:43.678  3846  5869 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-16 11:10:43.684  3846  5869 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-16 11:10:43.684  3846  5869 I SystemUpdateService: now status is 0 (complete)
11-16 11:10:43.684  3846  5869 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-16 11:10:43.684  3846  5869 I SystemUpdateService: file has been verified
11-16 11:10:43.685  3846  5869 I SystemUpdateService: OTA package size = 21989297
,11-16 11:10:43.690  3846  5869 I SystemUpdateService: showing system update notification
,11-16 11:10:43.699  3846  3846 D SystemUpdateService: onDestroy
,11-16 11:10:43.733   927  5855 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-16 11:10:43.838  4981  5874 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-16 11:10:43.839   927  5855 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Nov 2016 16:10:43 GMT], X-Android-Received-Millis=[1479312643837], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479312643815]}
,11-16 11:10:43.840   927  2939 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-16 11:10:43.840   927  2939 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-16 11:10:43.841   927  2939 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-16 11:10:43.844   927  2939 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-16 11:10:44.005  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-16 11:10:44.006  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-16 11:10:44.006  5619  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-16 11:10:44.036  5724  5724 D BtGatt.ScanManager: awakened up at time 137255
,11-16 11:10:44.039  5724  5744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-16 11:10:44.072  5724  5741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-16 11:10:44.072  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:44.072  5724  5741 D BtGatt.GattService: current time is 137291595022
11-16 11:10:44.073  5724  5741 D BtGatt.GattService: Batch record : [-64, 24, -42, 32, -70, 111, 1, -128, -60, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, -46, -4, -117, 6, 105, -37, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, -64, 24, -42, 32, -70, 111, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0]
,11-16 11:10:44.079  5724  5741 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
11-16 11:10:44.080  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-16 11:10:44.080  5724  5741 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
,11-16 11:10:44.083  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
,11-16 11:10:44.083  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=6F:BA:20:D6:18:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=137292276480}
,11-16 11:10:44.083  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=6F:BA:20:D6:18:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=137292276480}
,11-16 11:10:44.084  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
,11-16 11:10:44.085  5619  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-16 11:10:44.085  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 5]
11-16 11:10:44.085  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5]
,11-16 11:10:44.085  5619  5619 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 5]
11-16 11:10:44.085  5619  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
11-16 11:10:44.086  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [<no peer name> A8:81:95:E9:5F:6F 5]
11-16 11:10:44.086  5619  5619 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 5], added - the peer count is 1
11-16 11:10:44.087  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=6F:BA:20:D6:18:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=137092276480}
,11-16 11:10:44.087  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=6F:BA:20:D6:18:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=137092276480}
11-16 11:10:44.087  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
11-16 11:10:44.087  5619  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-16 11:10:44.087  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 5]
11-16 11:10:44.087  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5]
11-16 11:10:44.087  5619  5619 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 5]
,11-16 11:10:44.088  5619  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
11-16 11:10:44.088  5619  5619 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 5] updated - the peer count is 1
11-16 11:10:44.088  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=137192276480}
11-16 11:10:44.088  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=137192276480}
11-16 11:10:44.088  5619  5619 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
,11-16 11:10:44.569   927  2939 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-16 11:10:44.579  5724  5724 D BtGatt.ScanManager: awakened up at time 137797
,11-16 11:10:44.582  5724  5744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-16 11:10:44.610  5724  5741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-16 11:10:44.611  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:44.611  5724  5741 D BtGatt.GattService: current time is 137830167646
11-16 11:10:44.611  5724  5741 D BtGatt.GattService: Batch record : [-64, 24, -42, 32, -70, 111, 1, -128, -58, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-16 11:10:44.612  5724  5741 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
,11-16 11:10:44.612  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-16 11:10:44.614  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
11-16 11:10:44.615  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=6F:BA:20:D6:18:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=137830710152}
11-16 11:10:44.615  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=6F:BA:20:D6:18:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=137830710152}
,11-16 11:10:44.616  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
11-16 11:10:44.616  5619  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-16 11:10:44.616  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 5]
11-16 11:10:44.616  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5]
11-16 11:10:44.616  5619  5619 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 5]
,11-16 11:10:44.617  5619  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
,11-16 11:10:44.618  5619  5619 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 5] updated - the peer count is 1
,11-16 11:10:44.619  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=137430710152}
,11-16 11:10:44.619  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=137430710152}
,11-16 11:10:44.620  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
11-16 11:10:44.620  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-16 11:10:46.502  5619  5666 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-16 11:10:46.502  5619  5666 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-16 11:10:46.503  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-16 11:10:46.503  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.503  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.504  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-16 11:10:46.504  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.504  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
,11-16 11:10:46.504  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.505  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.505  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-16 11:10:46.505  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-16 11:10:46.505  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.506  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.506  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.509  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:46.510  5724  5760 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-16 11:10:46.511  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-16 11:10:46.512  5724  5744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-16 11:10:46.513  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:46.516  5724  5769 D BtGatt.GattService: stopScan() - queue size =1
,11-16 11:10:46.518  5724  5735 D BtGatt.GattService: unregisterClient() - clientIf=5
11-16 11:10:46.518  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-16 11:10:46.519  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.519  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:46.519  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.519  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-16 11:10:46.519  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.519  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.519  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-16 11:10:46.519  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-16 11:10:46.519  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-16 11:10:46.520  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-16 11:10:46.520  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.520  5724  5724 D BtGatt.ScanManager: awakened up at time 139739
11-16 11:10:46.521  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:46.524  5724  5760 D BtGatt.GattService: registerClient() - UUID=4cb699fc-a8d3-488f-8218-8762b6124600
11-16 11:10:46.525  5724  5741 D BtGatt.GattService: onClientRegistered() - UUID=4cb699fc-a8d3-488f-8218-8762b6124600, clientIf=5
11-16 11:10:46.525  5619  5630 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-16 11:10:46.526  5724  5769 D BtGatt.GattService: start scan with filters
11-16 11:10:46.529  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-16 11:10:46.529  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:46.530  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-16 11:10:46.530  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.530  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.530  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:46.530  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:46.530  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.530  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-16 11:10:46.530  5619  5666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-16 11:10:46.530  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-16 11:10:46.530  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-16 11:10:46.530  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.530  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-16 11:10:46.531  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.532  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-16 11:10:46.532  5724  5741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-16 11:10:46.532  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-16 11:10:46.532  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:46.532  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-16 11:10:46.532  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-16 11:10:46.532  5724  5741 D BtGatt.GattService: current time is 139751476699
11-16 11:10:46.532  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-16 11:10:46.532  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-16 11:10:46.532  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,11-16 11:10:46.533  5724  5741 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -89, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
11-16 11:10:46.533  5619  5881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-16 11:10:46.533  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-16 11:10:46.533  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-16 11:10:46.533  5619  5881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-16 11:10:46.533  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-16 11:10:46.534  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-16 11:10:46.534  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-16 11:10:46.534  5619  5666 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-16 11:10:46.531  5734  5734 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33282]" dev="sockfs" ino=33282 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:46.537  5619  5881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-16 11:10:46.531  5734  5734 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33282]" dev="sockfs" ino=33282 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-16 11:10:46.541  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.541  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.541  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.542  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-16 11:10:46.542  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-16 11:10:46.542  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-16 11:10:46.542  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
11-16 11:10:46.542  5619  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:46.542  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:46.542  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.542  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-16 11:10:46.542  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-16 11:10:46.543  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.543  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.543  5724  5741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-16 11:10:46.543  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:46.543  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.544  5724  5744 D B,tGatt.ScanManager: stopping BLe Batch
11-16 11:10:46.544  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:46.547  5724  5734 D BtGatt.GattService: registerClient() - UUID=66cbe1be-54e1-4c91-9ea3-f4700b3e3bdf
11-16 11:10:46.547  5724  5741 D BtGatt.GattService: onClientRegistered() - UUID=66cbe1be-54e1-4c91-9ea3-f4700b3e3bdf, clientIf=6
11-16 11:10:46.548  5619  5630 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-16 11:10:46.549  5724  5741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-16 11:10:46.549  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:46.549  5724  5743 D BtGatt.AdvertiseManager: message : 0
,11-16 11:10:46.550  5724  5744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-16 11:10:46.552  5724  5743 D BtGatt.AdvertiseManager: starting multi advertising
,11-16 11:10:46.554  5724  5741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-16 11:10:46.554  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-16 11:10:46.560  5724  5744 D BtGatt.ScanManager: handling starting scan
,11-16 11:10:46.563  5724  5741 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-16 11:10:46.567  5724  5741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-16 11:10:46.567  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:46.567  5724  5744 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-16 11:10:46.571  5724  5741 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-16 11:10:46.572  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-16 11:10:46.572  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
,11-16 11:10:46.572  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-16 11:10:46.574  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-16 11:10:46.574  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.575  5724  5741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-16 11:10:46.576  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:46.576  5724  5744 D BtGatt.ScanManager: Starting BLE batch scan
11-16 11:10:46.576  5724  5744 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-16 11:10:46.576  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.576  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.576  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:46.576  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-16 11:10:46.577  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 4. Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.577  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=137901823939}
,11-16 11:10:46.577  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=137901823939}
11-16 11:10:46.577  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
11-16 11:10:46.577  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-16 11:10:46.578  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=138301823939}
11-16 11:10:46.578  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=138301823939}
11-16 11:10:46.578  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-89, mTimestampNanos=138101823939}
11-16 11:10:46.578  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-89, mTimestampNanos=138101823939}
11-16 11:10:46.578  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
,11-16 11:10:46.578  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-89, mTimestampNanos=137951823939}
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-89, mTimestampNanos=137951823939}
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.579  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-16 11:10:46.579  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.580  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.580  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-16 11:10:46.580  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.582  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.582  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-16 11:10:46.582  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.583  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.583  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:46.583  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-16 11:10:46.585  5724  5741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-16 11:10:46.585  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-16 11:10:46.589  5724  5741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-16 11:10:46.589  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-16 11:10:47.084  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-16 11:10:47.084  5619  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-16 11:10:47.085  5619  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-16 11:10:48.003   927  2930 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,11-16 11:10:49.339   927  2939 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-16 11:10:49.342   927  2939 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 59
,11-16 11:10:49.586  5619  5666 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-16 11:10:49.586  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-16 11:10:49.586  5619  5666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-16 11:10:49.586  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-16 11:10:49.587  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-16 11:10:49.587  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-16 11:10:49.587  5619  5881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-16 11:10:49.587  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-16 11:10:49.587  5619  5881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-16 11:10:49.587  5619  5666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-16 11:10:49.587  5619  5881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-16 11:10:49.589  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-16 11:10:49.589  5619  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6f153 removed from the list
11-16 11:10:49.589  5619  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-16 11:10:49.589  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-16 11:10:49.589  5619  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-16 11:10:49.589  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-16 11:10:49.589  5619  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-16 11:10:49.589  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-16 11:10:49.590  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-16 11:10:49.591  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.591  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:49.591  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.591  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-16 11:10:49.592  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:49.593  5619  5666 D BluetoothAdapter: STATE_ON
11-16 11:10:49.594  5724  5735 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-16 11:10:49.596  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-16 11:10:49.596  5724  5744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-16 11:10:49.599  5619  5666 D BluetoothAdapter: STATE_ON
,11-16 11:10:49.602  5724  5760 D BtGatt.GattService: stopScan() - queue size =1
11-16 11:10:49.603  5724  5724 D BtGatt.ScanManager: awakened up at time 142822
11-16 11:10:49.603  5724  5768 D BtGatt.GattService: unregisterClient() - clientIf=5
11-16 11:10:49.604  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-16 11:10:49.604  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:49.604  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:49.605  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.605  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.605  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.605  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-16 11:10:49.605  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:49.607  5724  5743 D BtGatt.AdvertiseManager: message : 1
11-16 11:10:49.607  5724  5743 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-16 11:10:49.617  5724  5741 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-16 11:10:49.617  5724  5741 D BtGatt.GattService: Client app is not null!
,11-16 11:10:49.618  5724  5760 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-16 11:10:49.619  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-16 11:10:49.620  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.620  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-16 11:10:49.620  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.620  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.620  5619  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.620  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-16 11:10:49.620  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-16 11:10:49.621  5619  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-16 11:10:49.622  5619  5666 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
11-16 11:10:49.622  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:49.623  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-16 11:10:49.624  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:49.624  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.624  5619  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-16 11:10:49.624  5619  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e3a90 removed from the list
11-16 11:10:49.624  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-16 11:10:49.624  5619  5666 D io.jxcore.node.ConnectivityMonitor: stop
11-16 11:10:49.625  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-16 11:10:49.625  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:49.625  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.625  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-16 11:10:49.625  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-16 11:10:49.625  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.625  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.626  5619  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-16 11:10:49.626  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-16 11:10:49.626  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-16 11:10:49.626  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-16 11:10:49.626  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-16 11:10:49.626  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-16 11:10:49.626  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-16 11:10:49.626  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-16 11:10:49.626  5619  5666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-16 11:10:49.627  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-16 11:10:49.627  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.627  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.627  5619  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.627  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-16 11:10:49.627  5619  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-16 11:10:49.627  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.627  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-16 11:10:49.627  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-16 11:10:49.628  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.628  5619  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-16 11:10:49.628  5619  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-16 11:10:49.628  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,11-16 11:10:49.629  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-16 11:10:49.629  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-16 11:10:49.630  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-16 11:10:49.631  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-16 11:10:49.632  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-16 11:10:49.632  5619  5666 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-16 11:10:49.644  5724  5741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,11-16 11:10:49.644  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:49.644  5724  5741 D BtGatt.GattService: current time is 142863079119
11-16 11:10:49.644  5724  5741 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -92, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -92, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -87, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -97, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -90, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -89, -103, 117, -5, -30, 67, 1, -128, -55, 31, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, -89, -103, 117, -5, -30, 67, 1, -128, -55, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0]
11-16 11:10:49.645  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-16 11:10:49.646  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-16 11:10:49.646  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-16 11:10:49.646  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-16 11:10:49.647  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-16 11:10:49.647  5724  5741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-16 11:10:49.647  5724  5741 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
11-16 11:10:49.647  5724  5741 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
,11-16 11:10:49.652  5724  5741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-16 11:10:49.653  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-16 11:10:49.653  5724  5744 D BtGatt.ScanManager: stopping BLe Batch
,11-16 11:10:49.659  5724  5741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-16 11:10:49.659  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-16 11:10:49.659  5724  5744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-16 11:10:49.664  5724  5741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-16 11:10:49.664  5724  5741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-16 11:10:50.129  5619  5619 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-16 11:10:51.049   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:51.529   927  2939 D ConnectivityService: handlePromptUnvalidated 101
,11-16 11:10:51.637  5619  5666 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-16 11:10:51.759  5619  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-16 11:10:51.759  5619  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:10:52.050   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:52.352   927  2939 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-16 11:10:52.360   927  2939 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-16 11:10:52.550  5619  5883 W !!      : call onHalfStreamCopied
,11-16 11:10:52.550  5619  5883 I testCopyDataAndClose: closing input stream
,11-16 11:10:53.051   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-16 11:10:53.321  5619  5883 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-16 11:10:53.322  5619  5883 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-16 11:10:53.322  5619  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-16 11:10:54.053   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:54.602   927  2930 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-16 11:10:55.054   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:10:56.054   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-16 11:10:57.085  5619  5666 I StreamCopyingThreadTest: Starting test: testRun
,11-16 11:10:57.090  5619  5884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-16 11:10:57.090  5619  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:10:59.706   927  5856 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152925, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-16 11:11:02.098  5619  5885 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-16 11:11:02.100  5619  5666 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-16 11:11:02.214  5619  5887 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-16 11:11:02.214  5619  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:11:03.893  5619  5887 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-16 11:11:03.893  5619  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:11:03.893  5619  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-16 11:11:03.893  5619  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:11:03.893  5619  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-16 11:11:03.893  5619  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-16 11:11:03.893  5619  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-16 11:11:03.894  5619  5887 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-16 11:11:03.894  5619  5887 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-16 11:11:03.894  5619  5887 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-16 11:11:03.894  5619  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-16 11:11:07.837  5619  5666 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-16 11:11:07.838  5619  5888 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-16 11:11:07.838  5619  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-16 11:11:07.839  5619  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-16 11:11:07.840  5619  5666 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-16 11:11:07.840  5619  5666 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-16 11:11:07.841  5619  5666 I StreamCopyingThreadTest: Starting test: testRunWithException
11-16 11:11:07.842  5619  5889 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-16 11:11:07.842  5619  5889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-16 11:11:07.842  5619  5889 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
,11-16 11:11:07.842  5619  5889 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-16 11:11:07.842  5619  5889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-16 11:11:07.842  5619  5889 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-16 11:11:07.842  5619  5889 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-16 11:11:07.842  5619  5889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-16 11:11:07.843  5619  5666 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-16 11:11:07.843  5619  5666 E com.test.thalitest.ThaliTestRunner: 
11-16 11:11:07.843  5619  5666 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-16 11:11:07.843  5619  5666 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-16 11:11:07.844  5619,  5666 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-16 11:11:07.844  5619  5666 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-16 11:11:07.845  5619  5666 E com.test.,thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.Tha,liTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:07.845  5619  5666 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-16 11:11:07.847  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG UnitTest_app: 'Running unit tests'
11-16 11:11:07.847  5619  5666 I jxcore-log: 
11-16 11:11:07.847  5619  5666 I jxcore-log: *Native tests were executed*
11-16 11:11:07.847  5619  5666 I jxcore-log: 
11-16 11:11:07.847  5619  5666 I jxcore-log: Total number of executed tests:  82
11-16 11:11:07.847  5619  5666 I jxcore-log: 
11-16 11:11:07.847  5619  5666 I jxcore-log: Number of passed tests:  79
11-16 11:11:07.847  5619  5666 I jxcore-log: 
11-16 11:11:07.847  5619  5666 I jxcore-log: Number of failed tests:  3
11-16 11:11:07.847  5619  5666 I jxcore-log: 
11-16 11:11:07.847  5619  5666 I jxcore-log: Number of ignored tests:  0
11-16 11:11:07.847  5619  5666 I jxcore-log: 
11-16 11:11:07.848  5619  5666 I jxcore-log: Total duration:  38057
11-16 11:11:07.848  5619  5666 I jxcore-log: 
11-16 11:11:07.848  5619  5666 I jxcore-log: Failed to execute UT.
11-16 11:11:07.848  5619  5666 I jxcore-log: 
11-16 11:11:07.848  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-16 11:11:07.848  5619  5666 I jxcore-log: 
11-16 11:11:07.850  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-16 11:11:07.850  5619  5666 I jxcore-log: 
11-16 11:11:07.853  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'netw,orkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-16 11:11:07.853  5619  5666 I jxcore-log: 
11-16 11:11:07.853  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-16 11:11:07.853  5619  5666 I jxcore-log: 
11-16 11:11:07.854  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-16 11:11:07.854  5619  5666 I jxcore-log: 
11-16 11:11:07.855  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-16 11:11:07.855  5619  5666 I jxcore-log: 
11-16 11:11:07.856  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-16 11:11:07.856  5619  5666 I jxcore-log: 
11-16 11:11:07.856  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-16 11:11:07.856  5619  5666 I jxcore-log: 
11-16 11:11:07.856  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.856  5619  5666 I jxcore-log: 
11-16 11:11:07.857  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-16 11:11:07.857  5619  5666 I jxcore-log: 
11-16 11:11:07.857  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-16 11:11:07.857  5619  5666 I jxcore-log: 
11-16 11:11:07.857  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.857  5619  5666 I jxcore-log: 
11-16 11:11:07.857  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-16 11:11:07.857  5619  5666 I jxcore-log: 
11-16 11:11:07.857  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-16 11:11:07.857  5619  5666 I jxcore-log: 
,11-16 11:11:07.858  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.858  5619  5666 I jxcore-log: 
11-16 11:11:07.858  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-16 11:11:07.858  5619  5666 I jxcore-log: 
11-16 11:11:07.858  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.858  5619  5666 I jxcore-log: 
11-16 11:11:07.858  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-16 11:11:07.858  5619  5666 I jxcore-log: 
11-16 11:11:07.859  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-16 11:11:07.859  5619  5666 I jxcore-log: 
11-16 11:11:07.859  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-16 11:11:07.859  5619  5666 I jxcore-log: 
11-16 11:11:07.859  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.859  5619  5666 I jxcore-log: 
11-16 11:11:07.859  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-16 11:11:07.859  5619  5666 I jxcore-log: 
11-16 11:11:07.859  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-16 11:11:07.859  5619  5666 I jxcore-log: 
11-16 11:11:07.860  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-16 11:11:07.860  5619  5666 I jxcore-log: 
11-16 11:11:07.860  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-16 11:11:07.860  5619  5666 I jxcore-log: 
,11-16 11:11:07.860  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-16 11:11:07.860  5619  5666 I jxcore-log: 
11-16 11:11:07.860  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-16 11:11:07.860  5619  5666 I jxcore-log: 
11-16 11:11:07.861  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-16 11:11:07.861  5619  5666 I jxcore-log: 
11-16 11:11:07.861  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-16 11:11:07.861  5619  5666 I jxcore-log: 
11-16 11:11:07.861  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-16 11:11:07.861  5619  5666 I jxcore-log: 
11-16 11:11:07.863  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-16 11:11:07.863  5619  5666 I jxcore-log: 
,11-16 11:11:07.864  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.864  5619  5666 I jxcore-log: 
11-16 11:11:07.864  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-16 11:11:07.864  5619  5666 I jxcore-log: 
11-16 11:11:07.864  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-16 11:11:07.864  5619  5666 I jxcore-log: 
11-16 11:11:07.864  5619  5619 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-16 11:11:07.864  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.864  5619  5666 I jxcore-log: 
11-16 11:11:07.865  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}]'
11-16 11:11:07.865  5619  5666 I jxcore-log: 
11-16 11:11:07.865  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}'
11-16 11:11:07.865  5619  5666 I jxcore-log: 
11-16 11:11:07.865  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
11-16 11:11:07.865  5619  5666 I jxcore-log: 
,11-16 11:11:07.866  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-16 11:11:07.866  5619  5666 I jxcore-log: 
11-16 11:11:07.866  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-16 11:11:07.866  5619  5666 I jxcore-log: 
11-16 11:11:07.866  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.866  5619  5666 I jxcore-log: 
11-16 11:11:07.866  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-16 11:11:07.866  5619  5666 I jxcore-log: 
11-16 11:11:07.866  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-16 11:11:07.866  5619  5666 I jxcore-log: 
,11-16 11:11:07.871  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-16 11:11:07.871  5619  5666 I jxcore-log: 
11-16 11:11:07.871  5619  5666 I jxcore-log: 2016-11-16 16:11:07 - WARN testUtils: 'myNameCallback not set!'
11-16 11:11:07.871  5619  5666 I jxcore-log: 
,11-16 11:11:07.985  3556  5891 I VacuumService: Vacuum at: now=1479312667985 tag=VacuumService
,11-16 11:11:08.027  3556  5894 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-16 11:11:08.056  3556  5892 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-16 11:11:08.059  3556  5892 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-16 11:11:08.085  3556  5892 W Uploader:  no longer exists, so no auth token.
,11-16 11:11:08.092  3556  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-16 11:11:08.427  3556  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-16 11:11:08.646  3556  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-16 11:11:08.707  3556  5892 W Uploader:  no longer exists, so no auth token.
,11-16 11:11:08.717  3556  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-16 11:11:08.796  3556  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-16 11:11:09.883  5619  5666 I jxcore-log: 2016-11-16 16:11:09 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-16 11:11:09.883  5619  5666 I jxcore-log: 
,11-16 11:11:09.885  5619  5666 I jxcore-log: 2016-11-16 16:11:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-16 11:11:09.885  5619  5666 I jxcore-log: 
,11-16 11:11:10.239  5619  5666 I jxcore-log: 2016-11-16 16:11:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-16 11:11:10.239  5619  5666 I jxcore-log: 
,11-16 11:11:10.253  5619  5666 I jxcore-log: 2016-11-16 16:11:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-16 11:11:10.253  5619  5666 I jxcore-log: 
,11-16 11:11:11.056   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:11:11.387  5619  5666 I jxcore-log: 2016-11-16 16:11:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-16 11:11:11.387  5619  5666 I jxcore-log: 
,11-16 11:11:11.555  5619  5666 I jxcore-log: 2016-11-16 16:11:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-16 11:11:11.555  5619  5666 I jxcore-log: 
,11-16 11:11:11.561  5619  5666 I jxcore-log: 2016-11-16 16:11:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-16 11:11:11.561  5619  5666 I jxcore-log: 
,11-16 11:11:11.573  5619  5666 I jxcore-log: 2016-11-16 16:11:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-16 11:11:11.573  5619  5666 I jxcore-log: 
,11-16 11:11:12.057   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:11:12.066  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-16 11:11:12.066  5619  5666 I jxcore-log: 
,11-16 11:11:12.112  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-16 11:11:12.112  5619  5666 I jxcore-log: 
,11-16 11:11:12.125  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-16 11:11:12.125  5619  5666 I jxcore-log: 
,11-16 11:11:12.129  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-16 11:11:12.129  5619  5666 I jxcore-log: 
,11-16 11:11:12.414  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-16 11:11:12.414  5619  5666 I jxcore-log: 
,11-16 11:11:12.543  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-16 11:11:12.543  5619  5666 I jxcore-log: 
,11-16 11:11:12.931  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-16 11:11:12.931  5619  5666 I jxcore-log: 
,11-16 11:11:12.938  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-16 11:11:12.938  5619  5666 I jxcore-log: 
,11-16 11:11:12.942  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-16 11:11:12.942  5619  5666 I jxcore-log: 
,11-16 11:11:12.946  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-16 11:11:12.946  5619  5666 I jxcore-log: 
,11-16 11:11:12.951  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-16 11:11:12.951  5619  5666 I jxcore-log: 
,11-16 11:11:12.989  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-16 11:11:12.989  5619  5666 I jxcore-log: 
,11-16 11:11:12.995  5619  5666 I jxcore-log: 2016-11-16 16:11:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-16 11:11:12.995  5619  5666 I jxcore-log: 
,11-16 11:11:13.025  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-16 11:11:13.025  5619  5666 I jxcore-log: 
,11-16 11:11:13.057   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:11:13.064  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-16 11:11:13.064  5619  5666 I jxcore-log: 
,11-16 11:11:13.071  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-16 11:11:13.071  5619  5666 I jxcore-log: 
,11-16 11:11:13.078  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-16 11:11:13.078  5619  5666 I jxcore-log: 
,11-16 11:11:13.093  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-16 11:11:13.093  5619  5666 I jxcore-log: 
,11-16 11:11:13.108  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-16 11:11:13.108  5619  5666 I jxcore-log: 
,11-16 11:11:13.112   927  5856 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-16 11:11:13.114  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-16 11:11:13.114  5619  5666 I jxcore-log: 
,11-16 11:11:13.121  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-16 11:11:13.121  5619  5666 I jxcore-log: 
,11-16 11:11:13.134  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-16 11:11:13.134  5619  5666 I jxcore-log: 
,11-16 11:11:13.152  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-16 11:11:13.152  5619  5666 I jxcore-log: 
,11-16 11:11:13.166  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-16 11:11:13.166  5619  5666 I jxcore-log: 
,11-16 11:11:13.177  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-16 11:11:13.177  5619  5666 I jxcore-log: 
,11-16 11:11:13.190  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-16 11:11:13.190  5619  5666 I jxcore-log: 
,11-16 11:11:13.200  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-16 11:11:13.200  5619  5666 I jxcore-log: 
,11-16 11:11:13.214  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-16 11:11:13.214  5619  5666 I jxcore-log: 
,11-16 11:11:13.224  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-16 11:11:13.224  5619  5666 I jxcore-log: 
,11-16 11:11:13.230  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-16 11:11:13.230  5619  5666 I jxcore-log: 
,11-16 11:11:13.252  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-16 11:11:13.252  5619  5666 I jxcore-log: 
,11-16 11:11:13.258  5619  5666 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-16 11:11:13.259  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - INFO testUtils: 'BLE multiple advertisement supported'
11-16 11:11:13.259  5619  5666 I jxcore-log: 
,11-16 11:11:13.338  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:13.338  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:13.338  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:13.338  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:13.338  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:13.338  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:13.338  5619  5666 I jxcore-log: 
,11-16 11:11:13.544  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:13.544  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:13.544  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:13.544  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:13.544  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:13.544  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:13.544  5619  5666 I jxcore-log: 
,11-16 11:11:13.548  5619  5666 I jxcore-log: 2016-11-16 16:11:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:13.548  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:13.548  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:13.548  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:13.548  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:13.548  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:13.548  5619  5666 I jxcore-log: 
,11-16 11:11:14.026  5619  5666 I jxcore-log: 2016-11-16 16:11:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:14.026  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:14.026  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:14.026  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:14.026  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:14.026  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:14.026  5619  5666 I jxcore-log: 
,11-16 11:11:14.030  5619  5666 I jxcore-log: 2016-11-16 16:11:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:14.030  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:14.030  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:14.030  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:14.030  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:14.030  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:14.030  5619  5666 I jxcore-log: 
,11-16 11:11:14.058   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:11:14.838  5619  5666 I jxcore-log: 2016-11-16 16:11:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:14.838  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:14.838  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:14.838  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:14.838  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:14.838  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:14.838  5619  5666 I jxcore-log: 
,11-16 11:11:14.843  5619  5666 I jxcore-log: 2016-11-16 16:11:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:14.843  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:14.843  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:14.843  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:14.843  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:14.843  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:14.843  5619  5666 I jxcore-log: 
,11-16 11:11:15.059   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-16 11:11:15.768  5619  5666 I jxcore-log: 2016-11-16 16:11:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:15.768  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:15.768  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:15.768  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:15.768  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:15.768  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:15.768  5619  5666 I jxcore-log: 
,11-16 11:11:15.774  5619  5666 I jxcore-log: 2016-11-16 16:11:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:15.774  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:15.774  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:15.774  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:15.774  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:15.774  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:15.774  5619  5666 I jxcore-log: 
,11-16 11:11:16.060   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-16 11:11:16.812  5619  5666 I jxcore-log: 2016-11-16 16:11:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:16.812  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:16.812  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:16.812  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:16.812  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:16.812  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:16.812  5619  5666 I jxcore-log: 
,11-16 11:11:16.815  5619  5666 I jxcore-log: 2016-11-16 16:11:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:16.815  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:16.815  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:16.815  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:16.815  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:16.815  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:16.815  5619  5666 I jxcore-log: 
,11-16 11:11:17.849  5619  5666 I jxcore-log: 2016-11-16 16:11:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:17.849  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:17.849  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:17.849  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:17.849  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:17.849  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:17.849  5619  5666 I jxcore-log: 
,11-16 11:11:17.856  5619  5666 I jxcore-log: 2016-11-16 16:11:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:17.856  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:17.856  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:17.856  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:17.856  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:17.856  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:17.856  5619  5666 I jxcore-log: 
,11-16 11:11:18.890  5619  5666 I jxcore-log: 2016-11-16 16:11:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:18.890  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:18.890  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:18.890  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:18.890  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:18.890  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:18.890  5619  5666 I jxcore-log: 
,11-16 11:11:18.896  5619  5666 I jxcore-log: 2016-11-16 16:11:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:18.896  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:18.896  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:18.896  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:18.896  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:18.896  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:18.896  5619  5666 I jxcore-log: 
,11-16 11:11:19.926  5619  5666 I jxcore-log: 2016-11-16 16:11:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:19.926  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:19.926  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:19.926  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:19.926  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:19.926  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:19.926  5619  5666 I jxcore-log: 
,11-16 11:11:19.931  5619  5666 I jxcore-log: 2016-11-16 16:11:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:19.931  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:19.931  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:19.931  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:19.931  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:19.931  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:19.931  5619  5666 I jxcore-log: 
,11-16 11:11:20.966  5619  5666 I jxcore-log: 2016-11-16 16:11:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:20.966  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:20.966  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:20.966  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:20.966  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:20.966  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:20.966  5619  5666 I jxcore-log: 
,11-16 11:11:20.970  5619  5666 I jxcore-log: 2016-11-16 16:11:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:20.970  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:20.970  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:20.970  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:20.970  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:20.970  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:20.970  5619  5666 I jxcore-log: 
,11-16 11:11:22.039  5619  5666 I jxcore-log: 2016-11-16 16:11:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:22.039  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:22.039  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:22.039  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:22.039  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:22.039  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:22.039  5619  5666 I jxcore-log: 
,11-16 11:11:22.043  5619  5666 I jxcore-log: 2016-11-16 16:11:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:22.043  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:22.043  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:22.043  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:22.043  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:22.043  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:22.043  5619  5666 I jxcore-log: 
,11-16 11:11:23.083  5619  5666 I jxcore-log: 2016-11-16 16:11:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:23.083  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:23.083  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:23.083  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:23.083  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:23.083  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:23.083  5619  5666 I jxcore-log: 
,11-16 11:11:23.090  5619  5666 I jxcore-log: 2016-11-16 16:11:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13,
11-16 11:11:23.090  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:23.090  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:23.090  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:23.090  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:23.090  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:23.090  5619  5666 I jxcore-log: 
,11-16 11:11:23.518   927  2930 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-16 11:11:24.136  5619  5666 I jxcore-log: 2016-11-16 16:11:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:24.136  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:24.136  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:24.136  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:24.136  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:24.136  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:24.136  5619  5666 I jxcore-log: 
,11-16 11:11:24.142  5619  5666 I jxcore-log: 2016-11-16 16:11:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:24.142  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:24.142  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:24.142  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:24.142  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:24.142  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:24.142  5619  5666 I jxcore-log: 
,11-16 11:11:24.485   927  5856 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-16 11:11:25.175  5619  5666 I jxcore-log: 2016-11-16 16:11:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:25.175  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:25.175  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:25.175  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:25.175  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:25.175  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:25.175  5619  5666 I jxcore-log: 
,11-16 11:11:25.180  5619  5666 I jxcore-log: 2016-11-16 16:11:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:25.180  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:25.180  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:25.180  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:25.180  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:25.180  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:25.180  5619  5666 I jxcore-log: 
,11-16 11:11:26.215  5619  5666 I jxcore-log: 2016-11-16 16:11:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:26.215  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:26.215  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:26.215  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:26.215  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:26.215  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:26.215  5619  5666 I jxcore-log: 
,11-16 11:11:26.219  5619  5666 I jxcore-log: 2016-11-16 16:11:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:26.219  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:26.219  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:26.219  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:26.219  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:26.219  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:26.219  5619  5666 I jxcore-log: 
,11-16 11:11:27.253  5619  5666 I jxcore-log: 2016-11-16 16:11:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-16 11:11:27.253  5619  5666 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-16 11:11:27.253  5619  5666 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-16 11:11:27.253  5619  5666 I jxcore-log: emit@events.js:82:1
11-16 11:11:27.253  5619  5666 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-16 11:11:27.253  5619  5666 I jxcore-log: emit@events.js:82:1'
11-16 11:11:27.253  5619  5666 I jxcore-log: 
,11-16 11:11:27.264  5619  5666 E jxcore  : Error!: error is undefined
11-16 11:11:27.264  5619  5666 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-16 11:11:27.268  5619  5666 I jxcore-log: 2016-11-16 16:11:27 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-16 11:11:27.268  5619  5666 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-16 11:11:27.268  5619  5666 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-16 11:11:27.268  5619  5666 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-16 11:11:27.268  5619  5666 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-16 11:11:27.268  5619  5666 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-16 11:11:27.268  5619  5666 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-16 11:11:27.268  5619  5666 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-16 11:11:27.270  5619  5666 I jxcore-log: 2016-11-16 16:11:27 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-16 11:11:27.270  5619  5666 I jxcore-log: 
,11-16 11:11:27.273  5619  5666 E jxcore-log: TypeError: 
11-16 11:11:27.273  5619  5666 E jxcore-log: error is undefined
11-16 11:11:27.273  5619  5666 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-16 11:11:27.273  5619  5666 E jxcore-log: 
,11-16 11:11:27.339   927  2899 W InputDispatcher: channel '7797368 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-16 11:11:27.339   927  2899 E InputDispatcher: channel '7797368 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-16 11:11:27.354   927  3136 D GraphicsStats: Buffer count: 2
11-16 11:11:27.354   927  3829 I WindowState: WIN DEATH: Window{7797368 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-16 11:11:27.354   927  3829 W InputDispatcher: Attempted to unregister already unregistered input channel '7797368 com.test.thalitest/com.test.thalitest.MainActivity (server)'
11-16 11:11:27.355   927  2937 D WifiService: Client connection lost with reason: 4
,11-16 11:11:27.369   528   528 I Zygote  : Process 5619 exited cleanly (139)
,11-16 11:11:27.371   927   937 I ActivityManager: Process com.test.thalitest (pid 5619) has died
,11-16 11:11:27.385   927   937 I ActivityManager: Start proc 5903:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-16 11:11:27.722   927  3852 I WindowManager: Screenshot max retries 4 of Token{40c70fa ActivityRecord{1bfb725 u0 com.test.thalitest/.MainActivity t6}} appWin=Window{97ef7a1 u0 Starting com.test.thalitest} drawState=4
,11-16 11:11:27.792  5903  5903 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-16 11:11:27.810  5903  5903 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-16 11:11:27.815  5903  5903 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1032-1033)
11-16 11:11:27.815  5903  5903 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-16 11:11:27.825  5903  5903 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cc78677}
,11-16 11:11:27.825  5903  5903 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-16 11:11:27.825  5903  5903 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-16 11:11:27.828  5903  5903 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-16 11:11:27.829  5903  5903 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-16 11:11:27.839  5903  5903 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-16 11:11:27.847  5903  5903 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-16 11:11:27.847  5903  5903 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-16 11:11:27.847  5903  5903 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-16 11:11:27.847  5903  5903 I Adreno  : Build Date                       : 12/06/15
11-16 11:11:27.847  5903  5903 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-16 11:11:27.847  5903  5903 I Adreno  : Local Branch                     : mybranch17112971
11-16 11:11:27.847  5903  5903 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-16 11:11:27.847  5903  5903 I Adreno  : Remote Branch                    : NONE
11-16 11:11:27.847  5903  5903 I Adreno  : Reconstruct Branch               : NOTHING
,11-16 11:11:27.864  5901  5901 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-16 11:11:27.884  5901  5901 D AndroidRuntime: CheckJNI is OFF
,11-16 11:11:27.892   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d89af9e:true
,11-16 11:11:27.908  3439  3439 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[14744]" dev="sockfs" ino=14744 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-16 11:11:27.912  5901  5901 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-16 11:11:27.908  3439  3439 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[14744]" dev="sockfs" ino=14744 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-16 11:11:27.922  5903  5903 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-16 11:11:27.930  5903  5903 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-16 11:11:27.940  5901  5901 I Radio-JNI: register_android_hardware_Radio DONE
,11-16 11:11:27.956  5901  5901 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-16 11:11:27.964   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-16 11:11:27.964   927   940 I ActivityManager: Killing 5903:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-16 11:11:28.086   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-16 11:11:28.087   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-16 11:11:28.088   927   940 E ActivityManager: Failure starting process com.test.thalitest
11-16 11:11:28.088   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-16 11:11:28.088   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:11:28.088   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:28.088   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-16 11:11:28.088   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-16 11:11:28.090   927   950 I art     : Starting a blocking GC Explicit
,11-16 11:11:28.090   927   940 I ActivityManager:   Force finishing activity ActivityRecord{1bfb725 u0 com.test.thalitest/.MainActivity t6}
,11-16 11:11:28.096   927   937 W ActivityManager: Spurious death for ProcessRecord{57ebe7c 0:com.test.thalitest/u0a77}, curProc for 5903: null
,11-16 11:11:28.100   927   945 W WindowManager: Failed looking up window
11-16 11:11:28.100   927   945 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@a392408 does not exist
11-16 11:11:28.100   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
11-16 11:11:28.100   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
11-16 11:11:28.100   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
11-16 11:11:28.100   927   945 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
11-16 11:11:28.100   927   945 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
11-16 11:11:28.100   927   945 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
11-16 11:11:28.100   927   945 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
11-16 11:11:28.100   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:11:28.100   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:28.100   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-16 11:11:28.100   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-16 11:11:28.169   927   950 I art     : Explicit concurrent mark sweep GC freed 15794(1034KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.564ms total 78.984ms
,11-16 11:11:28.187   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-16 11:11:28.190  5901  5901 I art     : System.exit called, status: 0
11-16 11:11:28.190  5901  5901 I AndroidRuntime: VM exiting with result code 0.
,11-16 11:11:28.196   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-16 11:11:28.200   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-16 11:11:28.205  5724  5724 D BluetoothMapAppObserver: onReceive
,11-16 11:11:28.205  5724  5724 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-16 11:11:28.209   927  2900 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-16 11:11:28.212  4055  4175 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-16 11:11:28.213  3668  3668 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-16 11:11:28.264  3781  3781 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-16 11:11:28.271  3668  5949 I Keyboard.Facilitator.DecoderInitializer: run()
,11-16 11:11:28.268   439   439 W kworker/4:1: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-16 11:11:28.267  3372  5950 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-16 11:11:28.271   439   439 W kworker/4:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-16 11:11:28.279  3556  3556 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-16 11:11:28.286   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-16 11:11:28.292  3668  5949 I Decoder : createOrResetDecoder
,11-16 11:11:28.295   439   439 W kworker/4:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-16 11:11:28.297  3815  3942 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-16 11:11:28.311  3846  5955 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-16 11:11:28.311  3846  5955 D AccountUtils: Clearing selected account for com.test.thalitest
11-16 11:11:28.311   927  3852 I ActivityManager: Start proc 5957:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-16 11:11:28.312  3815  3942 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-16 11:11:28.312  3815  3942 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3815
11-16 11:11:28.312  3815  3942 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:28.312  3815  3942 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-16 11:11:28.315   927  3829 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-16 11:11:28.315   927  5966 E DropBoxManagerService: Can't write: system_app_crash
11-16 11:11:28.315   927  5966 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-16 11:11:28.315   927  5966 E DropBoxManagerService: 	... 5 more
,11-16 11:11:28.322  3815  3942 I Process : Sending signal. PID: 3815 SIG: 9
,11-16 11:11:28.345  3372  3397 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj67633E9D5) - 
,11-16 11:11:28.365  3556  3556 I ConfigService: onCreate
,11-16 11:11:28.368  3556  5971 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-16 11:11:28.368  3556  5971 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-16 11:11:28.368  3556  5971 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-16 11:11:28.370  3556  5971 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-16 11:11:28.389  3846  5955 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-16 11:11:28.412  3668  5949 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-16 11:11:28.415  3846  5955 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:28.415  3846  5955 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-16 11:11:28.415  3846  5955 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:28.415  3846  5955 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-16 11:11:28.416  3846  5955 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-16 11:11:28.437  3372  3397 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-16 11:11:28.437  3372  3397 E AndroidRuntime: Process: android.process.acore, PID: 3372
11-16 11:11:28.437  3372  3397 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-16 11:11:28.437  3372  3397 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-16 11:11:28.472   927  3825 D GraphicsStats: Buffer count: 1
,11-16 11:11:28.473   927   938 I WindowState: WIN DEATH: Window{e7a2ae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
,11-16 11:11:28.477  3372  3397 I Process : Sending signal. PID: 3372 SIG: 9
11-16 11:11:28.478   927  3743 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3815) has died
11-16 11:11:28.478   927  3743 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-16 11:11:28.488   927   945 E WindowState: getStack: Window{e7a2ae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{b118111 token=Token{f232d38 ActivityRecord{d52e59b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t5}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,11-16 11:11:28.488   927   945 E WindowState: getStack: Window{e7a2ae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{b118111 token=Token{f232d38 ActivityRecord{d52e59b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t5}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
,11-16 11:11:28.489   927   945 E WindowState: getStack: Window{e7a2ae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{b118111 token=Token{f232d38 ActivityRecord{d52e59b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t5}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
11-16 11:11:28.489   927   945 E WindowState: getStack: Window{e7a2ae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{b118111 token=Token{f232d38 ActivityRecord{d52e59b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t5}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
,11-16 11:11:28.490   927   945 E WindowState: getStack: Window{e7a2ae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{b118111 token=Token{f232d38 ActivityRecord{d52e59b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t5}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
11-16 11:11:28.490   927   945 E WindowState: getStack: Window{e7a2ae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{b118111 token=Token{f232d38 ActivityRecord{d52e59b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t5}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,11-16 11:11:28.512  3846  5977 I GMPM-SVC: App measurement is starting up
,11-16 11:11:28.525  3846  5977 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-16 11:11:28.526  3846  5977 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-16 11:11:28.678   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
