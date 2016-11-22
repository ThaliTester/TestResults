#### Test 94852510110513c_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-22 12:27:25.310   927  3222 I ActivityManager: Killing 5317:org.codeaurora.ims/1001 (adj 15): empty #17
,--------- beginning of main
11-22 12:27:25.510  5622  5672 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-22 12:27:25.561  4005  4005 I ConfigFetchService: fetch service done; releasing wakelock
11-22 12:27:25.562  4005  4005 I ConfigFetchService: stopping self
11-22 12:27:25.572  4005  4997 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-22 12:27:25.598  5622  5672 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-22 12:27:25.642  4005  4997 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-22 12:27:25.677  5674  5674 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 12:27:25.677  5622  5672 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-22 12:27:25.680  5674  5674 D AndroidRuntime: CheckJNI is OFF
11-22 12:27:25.703  5674  5674 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 12:27:25.731  5674  5674 I Radio-JNI: register_android_hardware_Radio DONE
11-22 12:27:25.746  5674  5674 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-22 12:27:25.751   927   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 12:27:25.788   927   938 I ActivityManager: Start proc 5688:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 12:27:25.797  5674  5674 D AndroidRuntime: Shutting down VM
,11-22 12:27:26.127   927   937 I WindowManager: Screenshot max retries 4 of Token{683a14e ActivityRecord{8d6e449 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{bb1d381 u0 Starting com.test.thalitest} drawState=4
,11-22 12:27:26.212  5688  5688 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-22 12:27:26.238  5688  5688 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-22 12:27:26.300  5688  5688 I LibraryLoader: Time to load native libraries: 59 ms (timestamps 124-183)
,11-22 12:27:26.301  5688  5688 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-22 12:27:26.338  5688  5688 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5372b18}
,11-22 12:27:26.338  5688  5688 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 12:27:26.338  5688  5688 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-22 12:27:26.342  5688  5688 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-22 12:27:26.342  5688  5688 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-22 12:27:26.391  5688  5688 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-22 12:27:26.401  5688  5688 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-22 12:27:26.401  5688  5688 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 12:27:26.401  5688  5688 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 12:27:26.401  5688  5688 I Adreno  : Build Date                       : 12/06/15
11-22 12:27:26.401  5688  5688 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 12:27:26.401  5688  5688 I Adreno  : Local Branch                     : mybranch17112971
11-22 12:27:26.401  5688  5688 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 12:27:26.401  5688  5688 I Adreno  : Remote Branch                    : NONE
11-22 12:27:26.401  5688  5688 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 12:27:26.447   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dc0f9fe:true
,11-22 12:27:26.482   409   409 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23334]" dev="sockfs" ino=23334 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 12:27:26.482   409   409 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[23334]" dev="sockfs" ino=23334 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 12:27:26.496  5688  5688 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 12:27:26.504  5688  5688 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 12:27:26.528   409   409 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33164]" dev="sockfs" ino=33164 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 12:27:26.528   409   409 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33164]" dev="sockfs" ino=33164 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 12:27:26.531  5688  5725 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 12:27:26.532  3936  3936 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[23339]" dev="sockfs" ino=23339 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:27:26.532  3936  3936 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[23339]" dev="sockfs" ino=23339 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 12:27:26.538  5688  5712 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-22 12:27:26.568  5688  5725 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 12:27:26.642   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +510ms (total +874ms)
,11-22 12:27:26.667  5688  5688 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5688
,11-22 12:27:26.765  5688  5688 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 12:27:26.985  5688  5728 D jxcore_app_log: JniHelper::setJavaVM(0xf51fc000), pthread_self() = -584578768
,11-22 12:27:26.988   927  3039 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 12:27:26.992  5688  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 12:27:26.992  5688  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 12:27:26.992  5688  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 12:27:26.992  5688  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 12:27:26.992  5688  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-22 12:27:26.992  5688  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4ce68f added. We now have 1 listener(s)
,11-22 12:27:26.996  5688  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-22 12:27:26.997  5688  5728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-22 12:27:26.998  5688  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 12:27:26.998  5688  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-22 12:27:27.001  5688  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@872efa added. We now have 1 listener(s)
11-22 12:27:27.001  5688  5728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:27:27.005   927  3040 D WifiService: New client listening to asynchronous messages
,11-22 12:27:27.005  5688  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 12:27:27.006  5688  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-22 12:27:27.006  5688  5728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 12:27:27.006  5688  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-22 12:27:27.006  5688  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 12:27:27.006  5688  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 12:27:27.006  5688  5728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 12:27:27.008  5688  5728 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 12:27:27.114  5688  5688 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 12:27:27.536  5688  5697 I art     : Background partial concurrent mark sweep GC freed 56809(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.579ms total 111.837ms
,11-22 12:27:27.648  5688  5734 W jxcore-log: Initializing JXcore engine
11-22 12:27:27.648  5688  5734 W jxcore-log: JXcore engine is ready
,11-22 12:27:27.668  5734  5734 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11999 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 12:27:27.668  5734  5734 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15382]" dev="sockfs" ino=15382 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-22 12:27:27.668  5734  5734 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-22 12:27:27.668  5734  5734 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33137]" dev="sockfs" ino=33137 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 12:27:27.679  5688  5734 W jxcore-log: Starting JXcore engine
,11-22 12:27:27.729  5688  5734 W jxcore-log: Platform android
11-22 12:27:27.729  5688  5734 W jxcore-log: 
,11-22 12:27:27.730  5688  5734 W jxcore-log: Process ARCH arm
11-22 12:27:27.730  5688  5734 W jxcore-log: 
,11-22 12:27:27.913  5688  5734 I jxcore-log: JXcore Cordova bridge is ready!
11-22 12:27:27.913  5688  5734 I jxcore-log: 
,11-22 12:27:27.913  5688  5734 W jxcore-log: JXcore engine is started
,11-22 12:27:27.923  5688  5728 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-22 12:27:27.929  5688  5688 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 12:27:29.849   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:27:30.572  3646  3646 I ConfigService: onDestroy
,11-22 12:27:30.851   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:27:31.852   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:27:32.853   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:27:33.854   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:27:34.855   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 12:27:37.717  5688  5734 I jxcore-log: 2016-11-22 17:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 12:27:37.717  5688  5734 I jxcore-log: 
,11-22 12:27:37.718  5688  5734 I jxcore-log: 2016-11-22 17:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 12:27:37.718  5688  5734 I jxcore-log: 
,11-22 12:27:37.724  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:27:37.724  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 12:27:37.726  5688  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 12:27:37.728  5688  5734 I jxcore-log: 2016-11-22 17:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 12:27:37.728  5688  5734 I jxcore-log: 
,11-22 12:27:37.729  5688  5734 I jxcore-log: 2016-11-22 17:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 12:27:37.729  5688  5734 I jxcore-log: 
,11-22 12:27:37.973  5688  5734 I jxcore-log: 2016-11-22 17:27:37 - DEBUG UnitTest_app: 'Running unit tests'
11-22 12:27:37.973  5688  5734 I jxcore-log: 
,11-22 12:27:37.974  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:27:37.974  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e6542a added. We now have 2 listener(s)
11-22 12:27:37.975  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:27:37.975  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 12:27:37.975  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:27:37.975  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:27:37.975  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@632d21b added. We now have 2 listener(s)
,11-22 12:27:37.975  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:27:37.976  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 12:27:37.977  5688  5734 D executeNativeTests: Running unit tests
,11-22 12:27:38.020  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 12:27:38.020  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 added. We now have 3 listener(s)
11-22 12:27:38.021  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-22 12:27:38.021  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:27:38.021  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:27:38.021  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:27:38.021  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 added. We now have 3 listener(s)
11-22 12:27:38.021  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:27:38.022  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 12:27:38.024  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 12:27:38.024  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:27:38.024  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:27:38.024  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:27:38.025  5688  5734 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-22 12:27:38.025  5688  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 12:27:38.025  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 12:27:38.025  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:27:38.025  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:27:38.025  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:27:38.026  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:38.026  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:38.026  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:38.027  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:38.027  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:38.027  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:27:38.027  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 removed from the list
11-22 12:27:38.027  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:27:38.027  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 removed from the list
11-22 12:27:38.027  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:38.027  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.027  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.028  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.028  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.029  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:38.029  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:38.029  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:38.029  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:38.029  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:38.030  5688  5734 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-22 12:27:38.030  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:38.030  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:38.030  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:38.030  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:38.030  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:27:38.030  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:38.030  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:38.030  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:38.030  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:38.031  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:38.031  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.031  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.031  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.031  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.031  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 12:27:38.031  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:38.031  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:38.032  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 12:27:38.034  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-22 12:27:38.035  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 12:27:38.035  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:38.035  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:38.035  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 12:27:38.035  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:38.036  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:38.036  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:38.036  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:38.036  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:27:38.036  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:38.036  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.036  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.037  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.037  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.037  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.037  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:38.037  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 12:27:38.037  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:38.037  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:38.037  5688  5734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 12:27:38.039  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:27:38.039  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:27:38.044  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 12:27:38.045  5688  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 12:27:38.045  5688  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 12:27:38.045  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:27:38.045  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-22 12:27:38.045  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 12:27:38.045  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:27:38.045  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 12:27:38.048  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:27:38.049  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:27:38.049  5688  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:27:38.049  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 12:27:38.050  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:27:38.052  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.052  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 12:27:38.053  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:27:38.053  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:27:38.053  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 12:27:38.054  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-22 12:27:38.055  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 12:27:38.056  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.056  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:27:38.056  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:27:38.056  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:27:38.056  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 12:27:38.056  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.056  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:27:38.058  4656  4892 D BtGatt.GattService: registerClient() - UUID=2168e903-33a4-4ffa-805a-5303abf4ed81
11-22 12:27:38.059  4656  4730 D BtGatt.GattService: onClientRegistered() - UUID=2168e903-33a4-4ffa-805a-5303abf4ed81, clientIf=5
,11-22 12:27:38.060  5688  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 12:27:38.061  4656  5388 D BtGatt.GattService: start scan with filters
11-22 12:27:38.066  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 12:27:38.066  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.066  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 12:27:38.067  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.067  4656  4743 D BtGatt.ScanManager: handling starting scan
11-22 12:27:38.067  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:27:38.067  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:27:38.067  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.067  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 12:27:38.067  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:27:38.067  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.067  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 12:27:38.067  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.068  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.068  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.068  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.068  4656  4743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:27:38.069  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.069  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.069  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:38.070  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.070  5688  5734 I io.jxcore.node.ConnectionHelper: start: OK
11-22 12:27:38.073  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.073  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:27:38.074  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.074  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:38.074  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:27:38.076  4656  4730 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 12:27:38.076  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:38.076  4656  4743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 12:27:38.083  4656  4730 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 12:27:38.083  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:38.083  4656  4743 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:27:38.084  4656  4743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 12:27:38.095  4656  4730 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 12:27:38.095  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:38.101  4656  4730 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 12:27:38.101  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:38.576  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 12:27:38.576  5688  5688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 12:27:38.576  5688  5688 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 12:27:43.074  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:27:43.075  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:43.075  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 12:27:43.075  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:27:43.075  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 12:27:43.075  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:27:43.075  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:27:43.075  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:27:43.076  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.076  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-22 12:27:43.076  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:27:43.077  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.077  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.077  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.077  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 12:27:43.077  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.079  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:27:43.079  4656  4892 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:27:43.079  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:27:43.081  4656  4743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 12:27:43.081  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:27:43.083  4656  4671 D BtGatt.GattService: stopScan() - queue size =1
11-22 12:27:43.084  4656  4892 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 12:27:43.084  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:27:43.085  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.085  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:27:43.085  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:43.085  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.085  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:43.085  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.086  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:27:43.086  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:43.086  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.086  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:43.086  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:27:43.086  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:27:43.088  4656  4656 D BtGatt.ScanManager: awakened up at time 96971
,11-22 12:27:43.100  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 12:27:43.101  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.102  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:43.103  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:27:43.103  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.103  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:43.103  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:27:43.103  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-22 12:27:43.103  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 12:27:43.103  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:27:43.103  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:27:43.104  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:43.104  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:27:43.104  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:43.104  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-22 12:27:43.104  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:43.104  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:27:43.104  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:43.104  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 12:27:43.104  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:43.104  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 12:27:43.104  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:27:43.104  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:27:43.104  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:27:43.104  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:27:43.105  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 12:27:43.105  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 12:27:43.132  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 12:27:43.132  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:43.132  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 12:27:43.146  4656  4730 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
11-22 12:27:43.146  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:43.146  4656  4730 D BtGatt.GattService: current time is 97029913255
11-22 12:27:43.147  4656  4730 D BtGatt.GattService: Batch record : [-46, 57, 25, -57, 101, -38, 1, 0, -94, 97, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, 56, -106, 93, 3, 3, -12, 24, 62, 19, 46, 17, 28, 6, 8, 116, 105, 115, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -113, 84, 71, -35, 90, -24, 1, 0, -98, 90, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -17, -38, -29, -31, 108, -59, 10, 62, 53, -105, 93, 3, 2, -29, 24, -105, 103, 89, -101, 28, 6, 8, 116, 105, 110, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 116, -43, -111, -91, -20, -29, 1, -128, -71, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -71, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -76, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -70, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 50, -35, 86, -77, -92, -11, 1, 0, -94, 68, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -45, -105, 93, 3, 2, -33, 21, -106, -84, -17, -15, 28, 6, 8, 116, 105, 110, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 35, 97, 126, -92, 22, -56, 1, -128, -72, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 12:27:43.148  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, 56, -106, 93, 3, 3, -12, 24, 62, 19, 46, 17, 6, 8, 116, 105, 115, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,11-22 12:27:43.149  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -17, -38, -29, -31, 108, -59, 10, 62, 53, -105, 93, 3, 2, -29, 24, -105, 103, 89, -101, 6, 8, 116, 105, 110, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-22 12:27:43.149  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-22 12:27:43.149  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 12:27:43.150  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-22 12:27:43.150  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 12:27:43.150  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -45, -105, 93, 3, 2, -33, 21, -106, -84, -17, -15, 6, 8, 116, 105, 110, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-22 12:27:43.151  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-22 12:27:43.156  4656  4730 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 12:27:43.156  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:43.156  4656  4743 D BtGatt.ScanManager: stopping BLe Batch
,11-22 12:27:43.162  4656  4730 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 12:27:43.162  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:43.162  4656  4743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:27:43.166  4656  4730 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:27:43.167  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:43.208  4875  4935 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-22 12:27:43.209  4875  4875 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-22 12:27:43.211   927   937 I ActivityManager: Killing 5330:com.android.settings/1000 (adj 15): empty #17
,11-22 12:27:43.606  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:27:48.107  5688  5734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 12:27:48.113  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:27:48.113  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:27:48.127  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 12:27:48.131  5688  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 12:27:48.132  5688  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 12:27:48.132  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 12:27:48.132  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 12:27:48.132  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 12:27:48.132  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:27:48.132  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 12:27:48.136  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:27:48.138  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 12:27:48.138  5688  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:27:48.138  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 12:27:48.141  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:27:48.145  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.145  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 12:27:48.146  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 12:27:48.146  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:27:48.146  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 12:27:48.152  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.152  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:27:48.152  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:27:48.152  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:27:48.153  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-22 12:27:48.153  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.154  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:27:48.157  4656  4892 D BtGatt.GattService: registerClient() - UUID=188ee7ae-dfbd-479c-9759-2069e135fdcc
,11-22 12:27:48.158  4656  4730 D BtGatt.GattService: onClientRegistered() - UUID=188ee7ae-dfbd-479c-9759-2069e135fdcc, clientIf=5
,11-22 12:27:48.158  5688  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 12:27:48.159  4656  4669 D BtGatt.GattService: start scan with filters
,11-22 12:27:48.163  4656  4743 D BtGatt.ScanManager: handling starting scan
11-22 12:27:48.163  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 12:27:48.164  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.164  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-22 12:27:48.164  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.164  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:27:48.164  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:27:48.164  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-22 12:27:48.166  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 12:27:48.167  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.167  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 12:27:48.167  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:27:48.167  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.167  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-22 12:27:48.167  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.167  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.169  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.169  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.169  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.169  5688  5734 I io.jxcore.node.ConnectionHelper: start: OK
11-22 12:27:48.169  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.172  4656  4730 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 12:27:48.172  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.173  4656  4743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 12:27:48.176  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 12:27:48.176  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:48.176  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:27:48.176  5688  5734 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 12:27:48.176  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.176  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:48.176  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 12:27:48.176  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 12:27:48.176  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:27:48.176  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:27:48.176  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 12:27:48.176  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:27:48.177  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:27:48.177  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:27:48.177  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.177  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 12:27:48.177  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-22 12:27:48.177  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.177  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.177  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.177  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 12:27:48.177  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.179  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:27:48.179  4656  4671 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:27:48.179  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:27:48.180  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:27:48.181  4656  4669 D BtGatt.GattService: stopScan() - queue size =1
,11-22 12:27:48.183  4656  4892 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 12:27:48.184  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:27:48.184  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.184  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:27:48.184  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.184  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.184  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.184  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.185  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:27:48.185  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.185  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.185  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.185  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:27:48.185  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:27:48.185  4656  4730 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 12:27:48.185  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.186  4656  4743 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:27:48.186  4656  4743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 12:27:48.186  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:27:48.186  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.188  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.188  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:27:48.189  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.189  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.189  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:48.189  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:27:48.189  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:27:48.189  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:27:48.189  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:27:48.189  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:48.189  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:27:48.189  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:48.189  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.189  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:48.189  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:27:48.189  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:27:48.189  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:48.189  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 12:27:48.189  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:27:48.189  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.189  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.190  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.190  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:27:48.190  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.190  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.193  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.193  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.193  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.193  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.193  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.195  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.195  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.195  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.195  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:48.195  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:48.195  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:48.195  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:48.196  5688  5734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 12:27:48.199  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:27:48.199  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-22 12:27:48.200  4656  4730 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 12:27:48.200  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:27:48.205  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 12:27:48.207  4656  4730 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 12:27:48.207  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:48.208  5688  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 12:27:48.208  5688  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 12:27:48.208  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:27:48.208  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-22 12:27:48.208  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 12:27:48.208  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:27:48.208  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 12:27:48.211  4656  4743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:27:48.211  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:27:48.213  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:27:48.213  5688  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:27:48.213  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 12:27:48.214  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:27:48.216  4656  4730 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:27:48.216  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.216  4656  4730 E BtGatt.ContextMap: Context not found for ID 5
11-22 12:27:48.216  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.216  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 12:27:48.217  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:27:48.217  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:27:48.217  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 12:27:48.221  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.221  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:27:48.221  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:27:48.221  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:27:48.221  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-22 12:27:48.221  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.222  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:27:48.224  4656  4671 D BtGatt.GattService: registerClient() - UUID=8352f127-4cfa-47ad-85df-bfcbcbe16c2e
11-22 12:27:48.224  4656  4730 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 12:27:48.224  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.224  4656  4743 D BtGatt.ScanManager: stopping BLe Batch
11-22 12:27:48.224  4656  4730 D BtGatt.GattService: onClientRegistered() - UUID=8352f127-4cfa-47ad-85df-bfcbcbe16c2e, clientIf=5
,11-22 12:27:48.225  5688  5699 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 12:27:48.225  4656  4669 D BtGatt.GattService: start scan with filters
,11-22 12:27:48.228  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 12:27:48.228  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.228  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 12:27:48.228  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.228  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:27:48.228  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:27:48.228  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.228  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-22 12:27:48.228  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:27:48.228  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.228  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.229  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.229  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-22 12:27:48.229  4656  4730 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 12:27:48.229  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.229  4656  4743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:27:48.229  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 12:27:48.229  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.232  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.232  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:27:48.232  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:48.232  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:48.232  5688  5734 I io.jxcore.node.ConnectionHelper: start: OK
11-22 12:27:48.233  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.235  4656  4730 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:27:48.235  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.235  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.235  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.235  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:48.236  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:27:48.236  4656  4743 D BtGatt.ScanManager: handling starting scan
11-22 12:27:48.242  4656  4730 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 12:27:48.242  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.243  4656  4743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 12:27:48.247  4656  4730 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 12:27:48.247  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:48.247  4656  4743 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:27:48.247  4656  4743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 12:27:48.255  4656  4730 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 12:27:48.255  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:48.260  4656  4730 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 12:27:48.260  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:48.737  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-22 12:27:48.737  5688  5688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:27:48.737  5688  5688 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 12:27:50.160   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-22 12:27:50.164   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-22 12:27:51.128   927  5451 D NetlinkSocketObserver: NeighborEvent{elapsedMs=105010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 12:27:53.186   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:27:53.192   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-22 12:27:53.233  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:27:53.233  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-22 12:27:53.233  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-22 12:27:53.234  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 12:27:53.234  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 12:27:53.234  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:53.234  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:27:53.234  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:27:53.234  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:53.234  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 12:27:53.234  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:27:53.235  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.235  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.235  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.235  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 12:27:53.235  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.237  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:27:53.238  4656  4892 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:27:53.238  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:27:53.239  4656  4743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:27:53.246  4656  4656 D BtGatt.ScanManager: awakened up at time 107129
11-22 12:27:53.246  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:27:53.249  4656  4669 D BtGatt.GattService: stopScan() - queue size =1
,11-22 12:27:53.249   927  3939 I ActivityManager: Killing 5127:com.google.android.apps.maps/u0a58 (adj 15): empty #17
11-22 12:27:53.251  4656  4892 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 12:27:53.252  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:27:53.252  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.252  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:27:53.252  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:53.252  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.253  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.253  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.253  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:27:53.253  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.253  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.254  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:53.254  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:27:53.254  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 12:27:53.279  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 12:27:53.279  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.280  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.280  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 12:27:53.280  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.280  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:53.280  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:27:53.281  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:27:53.281  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:27:53.281  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-22 12:27:53.281  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:27:53.281  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 12:27:53.281  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 12:27:53.281  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:27:53.281  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:27:53.281  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:27:53.281  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 12:27:53.281  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:27:53.283  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:27:53.283  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:27:53.283  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 12:27:53.292  4656  4730 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-22 12:27:53.293  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:53.293  4656  4730 D BtGatt.GattService: current time is 107176218950
11-22 12:27:53.293  4656  4730 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -76, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -72, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -71, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -70, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -68, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -77, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 12:27:53.293  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-22 12:27:53.293  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 12:27:53.294  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 12:27:53.294  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 12:27:53.294  4656  4743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:27:53.294  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 12:27:53.294  4656  4730 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 12:27:53.294  4656  4730 E BtGatt.ContextMap: Context not found for ID 5
,11-22 12:27:53.299  4656  4730 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 12:27:53.300  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:53.300  4656  4730 E BtGatt.ContextMap: Context not found for ID 5
,11-22 12:27:53.306  4656  4730 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 12:27:53.306  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:27:53.307  4656  4743 D BtGatt.ScanManager: stopping BLe Batch
,11-22 12:27:53.311  4656  4730 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 12:27:53.311  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:53.311  4656  4743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 12:27:53.316  4656  4730 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 12:27:53.316  4656  4730 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:27:53.782  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:27:53.783  5688  5688 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:53.783  5688  5688 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 12:27:58.282  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:27:58.282  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.282  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.285  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:27:58.285  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:27:58.285  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:27:58.285  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.285  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 12:27:58.285  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.286  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.286  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:27:58.286  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:27:58.289  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.289  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.293  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.293  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.294  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.294  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.294  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 12:27:58.294  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.294  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.296  5688  5734 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-22 12:27:58.298  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:27:58.298  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.298  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.299  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:27:58.299  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.299  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.299  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.299  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.299  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:27:58.300  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.300  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.302  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.303  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.303  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.303  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.303  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:58.303  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.303  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.305  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 12:27:58.305  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:27:58.306  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.306  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.306  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.306  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.306  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.306  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:27:58.307  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.307  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.307  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.307  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.311  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.311  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.311  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.311  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.311  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:58.311  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.312  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.313  5688  5734 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-22 12:27:58.313  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:58.313  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.313  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.313  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.314  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:27:58.314  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.314  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.314  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.314  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.314  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.314  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.316  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.316  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.316  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.317  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.317  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 12:27:58.317  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.317  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.318  5688  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-22 12:27:58.318  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:58.318  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 12:27:58.318  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.319  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.319  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.319  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.319  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:27:58.319  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.319  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.319  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.319  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.321  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.322  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.322  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.322  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.322  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:58.322  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.322  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.323  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-22 12:27:58.324  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:27:58.324  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:27:58.324  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 12:27:58.324  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:27:58.324  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:27:58.324  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 12:27:58.324  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 12:27:58.325  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 12:27:58.325  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:58.325  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.325  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.325  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.325  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.325  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.325  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.326  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.326  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.326  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.326  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.328  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.329  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.329  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.329  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.329  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:58.329  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.329  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.330  5688  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:27:58.331  5688  5734 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 12:27:58.331  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-22 12:27:58.336  5688  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-22 12:27:58.337  5688  5734 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-22 12:27:58.337  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 12:27:58.337  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-22 12:27:58.337  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 12:27:58.337  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-22 12:27:58.337  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 12:27:58.337  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 12:27:58.338  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 12:27:58.339  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 12:27:58.340  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 12:27:58.340  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 12:27:58.341  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 12:27:58.341  5688  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-22 12:27:58.342  5688  5734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 12:27:58.342  5688  5734 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-22 12:27:58.342  5688  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:27:58.342  5688  5734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 12:27:58.342  5688  5734 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-22 12:27:58.342  5688  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:27:58.342  5688  5734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 12:27:58.342  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-22 12:27:58.347  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-22 12:27:58.348  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-22 12:27:58.348  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-22 12:27:58.349  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-22 12:27:58.349  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: con,nect: Started connecting to null in address 00:11:22:33:44:55
11-22 12:27:58.349  5688  5734 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-22 12:27:58.349  5688  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 12:27:58.350  5688  5734 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-22 12:27:58.350  5688  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-22 12:27:58.350  5688  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-22 12:27:58.350  5688  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-22 12:27:58.350  5688  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-22 12:27:58.351  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:58.351  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.351  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.351  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.351  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.351  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-22 12:27:58.352  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.352  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.352  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.352  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.352  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.353  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.354  5688  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-22 12:27:58.354  5688  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-22 12:27:58.354  5688  5736 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,11-22 12:27:58.354  5688  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:27:58.355  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.355  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.355  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.355  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.355  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 12:27:58.355  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.355  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.356  5688  5734 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-22 12:27:58.357  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:58.357  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.357  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.357  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:27:58.357  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.358  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.355  4892  4892 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30315]" dev="sockfs" ino=30315 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:27:58.355  4892  4892 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30315]" dev="sockfs" ino=30315 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 12:27:58.358  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.358  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:27:58.358  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.358  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.358  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.359  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.359  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.360  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.360  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.360  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:58.360  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.360  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.361  5688  5734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-22 12:27:58.361  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:58.361  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.361  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.362  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.362  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.362  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 12:27:58.362  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.362  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.362  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.362  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.362  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.364  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:27:58.364  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.364  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.364  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:27:58.364  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:58.364  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:27:58.364  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.365  5688  5734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-22 12:27:58.365  5688  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-22 12:27:58.365  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 12:27:58.365  5688  5734 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-22 12:27:58.365  5688  5734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 12:27:58.365  5688  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-22 12:27:58.365  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 12:27:58.366  5688  5734 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-22 12:27:58.366  5688  5734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 12:27:58.366  5688  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 12:27:58.366  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 12:27:58.366  5688  5734 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-22 12:27:58.366  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:27:58.366  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:27:58.366  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:27:58.366  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.366  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.366  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.367  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:27:58.367  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.367  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:27:58.367  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.367  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.370  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.370  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.371  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:27:58.371  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 12:27:58.371  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:27:58.371  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.371  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.371  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:27:58.371  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:27:58.372  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:27:58.372  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:27:58.372  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:27:58.372  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:27:59.856   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-22 12:27:59.856   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 12:28:03.372  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:03.373  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:28:03.373  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:03.373  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:03.373  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 12:28:03.374  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:03.374  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:03.374  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 12:28:03.375  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:03.375  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:03.375  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:28:03.375  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:03.375  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:28:03.376  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:03.376  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.376  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.379  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.380  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.380  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.380  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:03.380  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 12:28:03.380  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:03.381  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:28:03.384  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-22 12:28:03.385  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:28:03.385  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-22 12:28:03.391  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-22 12:28:03.393  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 12:28:03.393  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-22 12:28:03.393  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-22 12:28:03.394  5688  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-22 12:28:03.394  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 12:28:03.394  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:28:03.394  5688  5688 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-22 12:28:03.395  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:28:03.395  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-22 12:28:03.395  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-22 12:28:03.395  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 12:28:03.395  5688  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:03.395  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:28:03.396  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-22 12:28:03.397  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 12:28:03.397  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 12:28:03.397  5688  5688 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 12:28:03.397  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:03.397  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:28:03.397  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.398  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-22 12:28:03.398  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:28:03.398  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.395  4671  4671 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33193]" dev="sockfs" ino=33193 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:28:03.395  4671  4671 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33193]" dev="sockfs" ino=33193 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 12:28:03.400  5688  5738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-22 12:28:03.400  5688  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 12:28:03.400  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.400  5688  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-22 12:28:03.400  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:03.401  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.401  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.401  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:28:03.401  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:03.401  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:03.401  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:03.401  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:03.401  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:03.401  5688  5688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-22 12:28:03.401  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:03.402  5688  5688 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:03.402  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:03.402  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:28:03.402  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:28:03.402  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:03.402  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:28:03.402  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:03.402  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.403  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.405  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.405  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.405  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.406  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:03.406  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:03.406  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:03.406  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:28:03.408  5688  5734 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-22 12:28:03.408  5688  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 12:28:03.409  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 12:28:03.409  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 12:28:03.409  5688  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 12:28:03.409  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:03.409  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 12:28:03.410  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:03.411  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:03.411  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:28:03.411  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:28:03.411  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:03.411  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:28:03.411  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:03.411  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.411  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.415  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.415  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.415  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.415  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 12:28:03.415  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:03.415  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:03.416  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:28:03.423  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:03.423  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:03.423  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 12:28:03.423  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:03.424  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:03.424  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
,11-22 12:28:03.424  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:03.424  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
11-22 12:28:03.424  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:28:03.424  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.424  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.427  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.427  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.427  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.427  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:03.427  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:03.427  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:03.427  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:28:03.428  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:03.429  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:03.429  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:03.429  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:03.429  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:28:03.429  5688  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e10a6e8 not in the list
11-22 12:28:03.429  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:03.429  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:28:03.429  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:03.429  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.429  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.432  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.432  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:03.433  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:03.433  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:03.433  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:03.433  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:03.433  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f61f101 not in the list
,11-22 12:28:03.435  5688  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-22 12:28:03.435  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 12:28:03.435  5688  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-22 12:28:03.435  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 12:28:03.435  5688  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-22 12:28:03.435  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 12:28:03.438  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-22 12:28:03.438  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-22 12:28:03.438  5688  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-22 12:28:03.439  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 12:28:03.439  5688  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-22 12:28:03.439  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 12:28:03.439  5688  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-22 12:28:03.439  5688  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-22 12:28:03.439  5688  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-22 12:28:03.440  5688  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-22 12:28:03.440  5688  5734 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-22 12:28:03.441  5688  5734 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-22 12:28:03.441  5688  5734 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-22 12:28:03.441  5688  5734 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-22 12:28:03.442  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 12:28:03.442  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a44ba56 added. We now have 3 listener(s)
,11-22 12:28:03.442  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:03.444  5688  5734 D BluetoothAdapter: enable(): BT is already enabled..!
11-22 12:28:03.444   927   937 D WifiService: setWifiEnabled: true pid=5688, uid=10077
,11-22 12:28:03.445   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:28:03.484  4656  4863 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-22 12:28:03.484  5688  5736 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-22 12:28:03.485  5688  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-22 12:28:03.485  5688  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-22 12:28:03.485  4656  4869 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-22 12:28:03.902  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:28:04.857   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:05.858   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:06.859   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:06.993   927  3039 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 12:28:07.861   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:08.450  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 12:28:08.450  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48dbad7 added. We now have 4 listener(s)
,11-22 12:28:08.451  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:08.465  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:08.465  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48dbad7 removed from the list
11-22 12:28:08.465  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:28:08.467  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:08.467  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8903fc4 added. We now have 4 listener(s)
11-22 12:28:08.467  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:08.469  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:08.469  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8903fc4 removed from the list
11-22 12:28:08.469  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:28:08.471  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 12:28:08.471  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e710ead added. We now have 4 listener(s)
11-22 12:28:08.471  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:08.475   927   937 D WifiService: setWifiEnabled: false pid=5688, uid=10077
,11-22 12:28:08.475   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:28:08.478   927  3039 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 12:28:08.479   927  3039 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-22 12:28:08.479   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 12:28:08.479   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 12:28:08.483  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:28:08.484  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-22 12:28:08.487  4656  4726 D BluetoothAdapterState: Current state: ON, message: 23
11-22 12:28:08.487  4656  4726 D BluetoothAdapterProperties: Setting state to 13
11-22 12:28:08.487  4656  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-22 12:28:08.488  4656  4726 D BluetoothAdapterProperties: onBluetoothDisable()
11-22 12:28:08.489  4656  4726 I BluetoothAdapterState: Entering PendingCommandState
11-22 12:28:08.491  4656  4730 D BluetoothAdapterProperties: Scan Mode:20
11-22 12:28:08.492  4656  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 12:28:08.493   927  5452 D DhcpClient: Clearing IP address
11-22 12:28:08.493   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 12:28:08.495  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:28:08.495  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 12:28:08.495  4656  4656 D HeadsetService: Received stop request...Stopping profile...
11-22 12:28:08.496  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:08.496  5688  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 12:28:08.496  5688  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-22 12:28:08.502   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:08.502  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:08.504   927  5453 D DhcpClient: Receive thread stopped
11-22 12:28:08.506  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:08.506  3646  5506 V NativeCrypto: Read error: ssl=0x7f94385000: I/O error during system call, Connection timed out
11-22 12:28:08.508  3646  5506 V NativeCrypto: SSL shutdown failed: ssl=0x7f94385000: I/O error during system call, Broken pipe
,11-22 12:28:08.509  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:08.510   927  3939 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-22 12:28:08.511   927  5450 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-22 12:28:08.514   927  5450 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-22 12:28:08.514  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:08.514   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-22 12:28:08.514   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 12:28:08.516   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-22 12:28:08.520   927   940 I ActivityManager: Start proc 5743:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-22 12:28:08.524  3874  4222 D BluetoothHeadset: Proxy object disconnected
,11-22 12:28:08.525   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 12:28:08.525  3182  4035 D BluetoothHeadset: Proxy object disconnected
11-22 12:28:08.525   927   927 D BluetoothHeadset: Proxy object disconnected
,11-22 12:28:08.525   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 12:28:08.526  4656  4656 D A2dpService: Received stop request...Stopping profile...
11-22 12:28:08.527  4656  4897 D A2dpStateMachine: Exit Disconnected: -1
,11-22 12:28:08.528   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 12:28:08.529   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-22 12:28:08.529   927   927 D BluetoothA2dp: Proxy object disconnected
,11-22 12:28:08.530   533   533 E Parcel  : Reading a NULL string not supported here.
,11-22 12:28:08.531  3182  3182 D HeadsetProfile: Bluetooth service disconnected
11-22 12:28:08.531  3182  3182 D BluetoothA2dp: Proxy object disconnected
,11-22 12:28:08.534   927   927 D RttService: SCAN_AVAILABLE : 1
,11-22 12:28:08.534   927  3147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 12:28:08.535  4656  4656 V BluetoothAdapterState: isTurningOff()=true
,11-22 12:28:08.536  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.536  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:08.536  4656  4656 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 12:28:08.537  4656  4656 D HidService: Received stop request...Stopping profile...
,11-22 12:28:08.537  4656  4656 D HidService: Stopping Bluetooth HidService
11-22 12:28:08.538   927  3041 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-22 12:28:08.538  4656  4656 D BluetoothMapService: onReceive
11-22 12:28:08.538  4656  4656 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 12:28:08.538  4656  4656 D BluetoothMapService: STATE_TURNING_OFF
,11-22 12:28:08.539  3827  3965 W QCNEJ   : |CORE| network lost: 100
11-22 12:28:08.539  4656  4656 D HealthService: Received stop request...Stopping profile...
,11-22 12:28:08.541  3827  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-22 12:28:08.542  3182  3182 D BluetoothInputDevice: Proxy object disconnected
11-22 12:28:08.542  3182  3182 D HidProfile: Bluetooth service disconnected
11-22 12:28:08.544  4656  4656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 12:28:08.544  4656  4656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 12:28:08.544  4656  4863 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:08.545  4656  4863 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 12:28:08.545  4656  4863 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:08.545  4656  4730 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-22 12:28:08.545  4656  4730 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-22 12:28:08.545  4656  4656 D PanService: Received stop request...Stopping profile...
11-22 12:28:08.547  4656  4656 D BluetoothMapService: Received stop request...Stopping profile...
11-22 12:28:08.547  4656  4656 D BluetoothMapService: stop()
11-22 12:28:08.547  4656  4656 D BluetoothMapAppObserver: deinitObservers()
11-22 12:28:08.547  4656  4656 D BluetoothMapAppObserver: removeReceiver()
11-22 12:28:08.549  4656  4656 D SapService: Received stop request...Stopping profile...
11-22 12:28:08.549  4656  4656 V SapService: stop()
,11-22 12:28:08.550  4656  4656 V BluetoothAdapterState: isTurningOff()=true
,11-22 12:28:08.550  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.550  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:08.551  4656  4656 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 12:28:08.552  4656  4656 V BluetoothAdapterState: isTurningOff()=true
,11-22 12:28:08.552  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.552  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 12:28:08.553  4656  4656 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:08.553  4656  4863 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:08.553  4656  4863 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:08.553  4656  4656 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 12:28:08.553  4656  4656 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 12:28:08.553  4656  4730 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 12:28:08.553  4656  4863 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 12:28:08.553  4656  4863 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 12:28:08.553  4656  4863 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 12:28:08.553  4656  4656 I BtOppRfcommListener: stopping Accept Thread
11-22 12:28:08.553  4656  4730 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 12:28:08.553  4656  4863 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-22 12:28:08.554  4656  5387 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-22 12:28:08.554  4656  5387 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-22 12:28:08.557   927  3039 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 12:28:08.561  4656  4656 V BluetoothAdapterState: isTurningOff()=true
11-22 12:28:08.562  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.562  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:08.562  4656  4656 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:08.562  4656  4656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 12:28:08.562  4656  4730 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 12:28:08.562  3182  3182 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 12:28:08.562  3182  3182 D PanProfile: Bluetooth service disconnected
11-22 12:28:08.563  3182  3182 D BluetoothMap: Proxy object disconnected
11-22 12:28:08.563  3182  3182 D MapProfile: Bluetooth service disconnected
11-22 12:28:08.563  4656  4656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 12:28:08.564  4656  4656 V BluetoothAdapterState: isTurningOff()=true
11-22 12:28:08.564  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.564  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:08.564  4656  4656 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:08.564  4656  4656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 12:28:08.564  4656  4656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 12:28:08.565  4656  4656 D BluetoothMapService: MAP Service closeService in
11-22 12:28:08.565  4656  4656 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 12:28:08.566  4656  4656 D ObexServerSockets0: shutdown(block = true)
11-22 12:28:08.566  4656  4656 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 12:28:08.566  4656  4656 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 12:28:08.566  4656  4916 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 12:28:08.567  4656  4869 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 12:28:08.567   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 12:28:08.568  4656  4915 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-22 12:28:08.568  4656  4656 V BluetoothAdapterState: isTurningOff()=true
11-22 12:28:08.568  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.568  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:08.568  4656  4656 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:08.569  4656  4656 D BluetoothMapService: cleanup()
11-22 12:28:08.569  4656  4656 D BluetoothMapService: MAP Service closeService in
11-22 12:28:08.569  4656  4656 V BluetoothAdapterState: isTurningOff()=true
11-22 12:28:08.569  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.569  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:08.570  4656  4656 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:08.570  4656  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 12:28:08.570  4656  4726 D BluetoothAdapterProperties: Setting state to 15
11-22 12:28:08.570  4656  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 12:28:08.570  4656  4726 I BluetoothAdapterState: Entering BleOnState
11-22 12:28:08.571   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:08.571  3182  3196 D BluetoothPan: onBluetoothStateChange on: false
11-22 12:28:08.572  3182  4035 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:08.572   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 12:28:08.572   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:08.572  3182  3193 D BluetoothMap: onBluetoothStateChange: up=false
11-22 12:28:08.573  3182  3196 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 12:28:08.574   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:08.574  3874  3895 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:08.575  3182  4035 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 12:28:08.576  3182  3193 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 12:28:08.576   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 12:28:08.577  4656  4726 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 12:28:08.577  4656  4726 D BluetoothAdapterProperties: Setting state to 16
11-22 12:28:08.577  4656  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 12:28:08.577  4656  4726 D BluetoothAdapterProperties: onBleDisable
11-22 12:28:08.578  4656  4726 I BluetoothAdapterState: Entering PendingCommandState
11-22 12:28:08.578  4656  4727 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 12:28:08.579  4656  4730 D BluetoothAdapterProperties: Scan Mode:20
11-22 12:28:08.580  4656  4863 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 12:28:08.580  4656  4863 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:08.581  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:08.581  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 12:28:08.582  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:08.582  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 12:28:08.585  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:08.586  5743  5743 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-22 12:28:08.593   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 12:28:08.594   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 12:28:08.594   507   921 D TetherController: Setting IP forward enable = 0
11-22 12:28:08.595   927  3041 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-22 12:28:08.595   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 12:28:08.596   927   944 D Tethering: MasterInitialState.processMessage what=3
11-22 12:28:08.601   927  3039 D DhcpClient: doQuit
11-22 12:28:08.601   927  3039 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 12:28:08.602  5344  5344 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@465f184 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-22 12:28:08.602  3540  3540 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 12:28:08.602   927  5452 D DhcpClient: onQuitting
11-22 12:28:08.602  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:08.608  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:08.609  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 12:28:08.609  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:08.609  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 12:28:08.610  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 12:28:08.610  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 12:28:08.610  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 12:28:08.610  5115  5139 E SarControlService: no key has been found,reset the power
11-22 12:28:08.610  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 12:28:08.610  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 12:28:08.610  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 12:28:08.611  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 12:28:08.611  5140  5140 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 12:28:08.612  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 12:28:08.613  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-22 12:28:08.613  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 12:28:08.614  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 12:28:08.614  5140  5140 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 12:28:08.617  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ea03000000000000ffffffff]
11-22 12:28:08.617  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:08.617  5140  5154 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-22 12:28:08.617  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:28:08.617  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-22 12:28:08.623  5743  5743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 12:28:08.625  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000eb03000000000000ffffffff]
11-22 12:28:08.625  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:08.625  5140  5154 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-22 12:28:08.626  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:28:08.626  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-22 12:28:08.629   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d7eff79:true
,11-22 12:28:08.630  3540  3540 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 12:28:08.631  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:28:08.636  3540  3540 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-22 12:28:08.637   507   914 W SocketClient: write error (Broken pipe)
,11-22 12:28:08.638   507   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-22 12:28:08.638   507   914 W SocketListener: Error sending broadcast (Broken pipe)
,11-22 12:28:08.643   927  3931 I ActivityManager: Start proc 5772:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-22 12:28:08.655   507   921 E Netd    : netlink response contains error (No such file or directory)
,11-22 12:28:08.657   927  3041 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-22 12:28:08.658   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 12:28:08.658  5743  5743 D LocalBluetoothProfileManager: Adding local MAP profile
,11-22 12:28:08.659   507   921 D TetherController: Setting IP forward enable = 0
11-22 12:28:08.660  5743  5743 D BluetoothMap: Create BluetoothMap proxy object
,11-22 12:28:08.664  3540  3540 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 12:28:08.677  3540  3540 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 12:28:08.677  5743  5743 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-22 12:28:08.684   927  3039 D wifi    : In wifi stop Hal
,11-22 12:28:08.684  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 12:28:08.684   927  3039 D wifi    : halHandle = 0x7f7de56a40, mVM = 0x7f9a44d140, mCls = 0x100a02
11-22 12:28:08.684   927  3539 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 12:28:08.684   927  3539 D WifiHAL : Got a signal to exit!!!
11-22 12:28:08.684   927  3539 I WifiHAL : Exit wifi_event_loop
11-22 12:28:08.685   927  3039 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-22 12:28:08.685   927  3039 E WifiHAL : Event processing terminated
11-22 12:28:08.685   927  3039 D wifi    : In wifi cleaned up handler
11-22 12:28:08.685   927  3039 I WifiHAL : Internal cleanup completed
11-22 12:28:08.686  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:28:08.687  4209  4303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 12:28:08.690  5772  5772 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-22 12:28:08.701  5743  5743 D DockEventReceiver: finishStartingService: stopping service
,11-22 12:28:08.704   927   937 I ActivityManager: Killing 5055:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-22 12:28:08.707   927  3539 D wifi    : set interface wlan0 flags (DOWN)
,11-22 12:28:08.707   927  3039 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 12:28:08.789  4656  4730 I bt_hci  : shut_down
,11-22 12:28:08.793  4656  4746 D bt_hwcfg: hw_epilog_process
,11-22 12:28:08.793  4656  4746 I bt_vendor: low_power_mode_cb
,11-22 12:28:08.795  4656  4746 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 12:28:08.795  4656  4746 I bt_vendor: epilog_cb
11-22 12:28:08.795  4656  4746 I bt_hci  : epilog_finished_callback
,11-22 12:28:08.798  4656  4730 I bt_hci_h4: hal_close
,11-22 12:28:08.799  4656  4730 I bt_userial_vendor: device fd = 54 close
,11-22 12:28:08.861   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:08.901  5772  5772 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-22 12:28:08.901  5772  5772 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-22 12:28:08.901  5772  5772 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 12:28:08.901  5772  5772 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-22 12:28:08.901  5,772  5772 D StrictMode: 	at com.google.r.e.b(PG:170)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 12:28:08.901  5772  5772 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.k.d(PG:583)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.e.b(PG:170)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 1,2:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 12:28:08.901  5772  5772 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.901  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 12:28:08.902  5772  5772 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 12:28:08.902  5772  5772 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 12:28:08.902  5772  5772 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 12:28:08.907  5743  5743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 12:28:08.910   927   944 D Tethering: InitialState.processMessage what=4
11-22 12:28:08.915  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 12:28:08.916   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-22 12:28:08.916  5743  5743 D DockEventReceiver: finishStartingService: stopping service
11-22 12:28:08.917  4656  4727 D bt_stack_manager: event_shut_down_stack finished.
11-22 12:28:08.918  4656  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-22 12:28:08.920  4656  4726 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-22 12:28:08.920  4656  4656 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 12:28:08.920   927  3221 I ActivityManager: Killing 5481:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
11-22 12:28:08.920  4656  4656 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 12:28:08.921  4656  4656 D BtGatt.GattService: stop()
11-22 12:28:08.921  4656  4656 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 12:28:08.944  4656  4656 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:08.944  4656  4656 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:08.944  4656  4656 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:08.944  4656  4656 V BluetoothAdapterState: isBleTurningOff()=true
11-22 12:28:08.944  4656  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 12:28:08.945  4656  4726 D BluetoothAdapterProperties: Setting state to 10
11-22 12:28:08.945  4656  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 12:28:08.945  4656  4726 I BluetoothAdapterState: Entering OffState
11-22 12:28:08.946   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-22 12:28:08.953  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 12:28:08.954  4656  4656 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-22 12:28:08.954  4656  4656 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 12:28:08.954  4656  4656 I BluetoothServiceJni: cleanupNative: return from cleanup
11-22 12:28:08.956  4656  4727 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-22 12:28:08.961  4005  4005 D SystemUpdateService: onCreate
11-22 12:28:08.966  4656  4727 D bt_stack_manager: event_clean_up_stack finished.
11-22 12:28:08.983  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-22 12:28:08.990  4656  4656 I art     : System.exit called, status: 0
11-22 12:28:08.990  4656  4656 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 12:28:08.995  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 12:28:09.004  4005  5478 I iu.UploadsManager: num queued entries: 0
,11-22 12:28:09.005  4005  5478 I iu.UploadsManager: num updated entries: 0
11-22 12:28:09.005  4005  5478 I iu.SyncManager: NEXT; no task
,11-22 12:28:09.007  4005  5805 I SystemUpdateService: active receiver: enabled
,11-22 12:28:09.014  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 12:28:09.015  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 12:28:09.027   927  3221 I ActivityManager: Start proc 5808:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-22 12:28:09.031   927   937 I ActivityManager: Process com.android.bluetooth (pid 4656) has died
,11-22 12:28:09.037  4005  5805 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 12:28:09.047  4005  5805 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-22 12:28:09.047  4005  5805 I SystemUpdateService: now status is 0 (complete)
11-22 12:28:09.047  4005  5805 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 12:28:09.047  4005  5805 I SystemUpdateService: file has been verified
,11-22 12:28:09.047  4005  5805 I SystemUpdateService: OTA package size = 21989297
,11-22 12:28:09.075  5808  5808 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-22 12:28:09.086  5808  5808 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:28:09.097  5808  5808 D SprintDMHelper: simOperator: 
,11-22 12:28:09.097  5808  5808 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-22 12:28:09.100  4005  5805 I SystemUpdateService: showing system update notification
,11-22 12:28:09.115  5090  5820 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 12:28:09.122   927  3941 I ActivityManager: Start proc 5821:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-22 12:28:09.146  4005  4005 D SystemUpdateService: onDestroy
,11-22 12:28:09.148   927  3905 I ActivityManager: Killing 5344:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-22 12:28:09.164  5821  5821 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-22 12:28:09.188   927  3905 I ActivityManager: Killing 4753:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-22 12:28:09.278  5772  5797 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-22 12:28:09.287   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb012d2:true
,11-22 12:28:09.861   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 12:28:13.499   927   938 D WifiService: setWifiEnabled: true pid=5688, uid=10077
11-22 12:28:13.499   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:28:13.509   507   921 D SoftapController: Softap fwReload - Ok
,11-22 12:28:13.514   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:13.514   507   921 D CommandListener: Trying to bring down wlan0
11-22 12:28:13.516   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-22 12:28:13.521   927  3039 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 12:28:14.105   927  3039 D wifi    : set interface wlan0 flags (UP)
,11-22 12:28:14.108   927  3039 I WifiHAL : Initializing wifi
11-22 12:28:14.108   927  3039 I WifiHAL : Creating socket
,11-22 12:28:14.109   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 12:28:14.114   927  3039 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-22 12:28:14.114   927  3039 D wifi    : Did set static halHandle = 0x7f7de56a40
11-22 12:28:14.114   927  3039 D wifi    : halHandle = 0x7f7de56a40, mVM = 0x7f9a44d140, mCls = 0x2018de
,11-22 12:28:14.114   927  3039 D wifi    : array field set
11-22 12:28:14.114   927  3039 I WifiNative-HAL: interface[0] = wlan0
11-22 12:28:14.115   927  5841 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547573033536
11-22 12:28:14.116   927  5841 D wifi    : waitForHalEvents called, vm = 0x7f9a44d140, obj = 0x2018de, env = 0x7f7de5d580
,11-22 12:28:14.184  5842  5842 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 12:28:14.203  5842  5842 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 12:28:14.217   927  3039 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 12:28:14.219  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:28:14.233  5842  5842 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 12:28:14.233  5842  5842 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 12:28:14.250   927  3039 D WifiConfigStore: Loading config and enabling all networks 
,11-22 12:28:14.250  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:14.250  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 12:28:14.250  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:14.250  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 12:28:14.262   927  3039 D WifiConfigStore: loaded 0 passpoint configs
,11-22 12:28:14.262   927  3039 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-22 12:28:14.263   927  3039 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 12:28:14.264   927  3039 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-22 12:28:14.265   927  3039 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 12:28:14.265   927  3039 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-22 12:28:14.265   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-22 12:28:14.266   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-22 12:28:14.270   927  3039 D WifiNative-HAL: Setting external_sim to 1
,11-22 12:28:14.270  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 12:28:14.270   927  3039 D wifi    : setting dfs flag to true, 0x7f7e8bff60
11-22 12:28:14.271   927  3039 D WifiStateMachine: Setting OUI to DA-A1-19
,11-22 12:28:14.271   927  3039 D wifi    : setting scan oui 0x7f7e8bff60
11-22 12:28:14.271   927  3039 D WifiHAL : Sending mac address OUI
,11-22 12:28:14.275   927  3039 E native  : do suspend false
,11-22 12:28:14.287   927  3039 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-22 12:28:14.287   927   927 D RttService: SCAN_AVAILABLE : 3
11-22 12:28:14.287   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-22 12:28:14.287   927  3147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-22 12:28:14.288   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:14.293   927  3038 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
11-22 12:28:14.293   927  3038 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 12:28:14.304   927  3038 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 12:28:14.310   927  3038 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
11-22 12:28:14.310   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128193 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-22 12:28:14.864   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:15.865   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:16.866   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:17.403  5842  5842 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:17.407  5842  5842 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:17.411  5842  5842 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:17.417  5842  5842 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:17.486   927  3039 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-22 12:28:17.487   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 12:28:17.487   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 12:28:17.498   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 12:28:17.527   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 12:28:17.529  5842  5842 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 12:28:17.868   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:17.957  5842  5842 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 12:28:18.010  5842  5842 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 12:28:18.012  5842  5842 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 12:28:18.024   927  3039 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 12:28:18.025   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 12:28:18.025   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 12:28:18.044   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 12:28:18.057   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:18.064   927  3039 D WifiStateMachine: Start Dhcp Watchdog 2
,11-22 12:28:18.073   927  5848 D DhcpClient: Receive thread started
,11-22 12:28:18.075   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:28:18.075   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 12:28:18.075   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-22 12:28:18.156   927  3039 E native  : do suspend false
,11-22 12:28:18.170   927  5847 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 12:28:18.200   927  5848 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-22 12:28:18.201   927  5847 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-22 12:28:18.203   927  5847 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-22 12:28:18.253   927  5848 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 12:28:18.254   927  5847 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 12:28:18.260   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:18.265   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 12:28:18.270   927  5847 D DhcpClient: Scheduling renewal in 86399s
,11-22 12:28:18.282   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-22 12:28:18.282   927  3039 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 12:28:18.284   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 12:28:18.286   927  3041 D ConnectivityService: Adding iface wlan0 to network 101
,11-22 12:28:18.299   927  3039 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 12:28:18.341   927  3041 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-22 12:28:18.341   927  3041 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-22 12:28:18.344   927  3041 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-22 12:28:18.351   927  3041 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-22 12:28:18.352   927  3041 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-22 12:28:18.359   927  3041 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 12:28:18.363   927  3041 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-22 12:28:18.364   927  3041 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-22 12:28:18.364   927  3041 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-22 12:28:18.364   927  3039 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 12:28:18.364   927  3041 D ConnectivityService:    accepting network in place of null
11-22 12:28:18.364   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 12:28:18.365   927  3041 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 12:28:18.376   927  5846 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132259, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 12:28:18.389   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:28:18.410   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:28:18.413   927  3041 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-22 12:28:18.413   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 12:28:18.414  3827  3965 W QCNEJ   : |CORE| network available: 101
,11-22 12:28:18.415   927  3041 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-22 12:28:18.417   927   944 D Tethering: MasterInitialState.processMessage what=3
11-22 12:28:18.418  3827  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 12:28:18.419  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 12:28:18.419  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 12:28:18.419  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:18.419  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 12:28:18.419  3827  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 12:28:18.420  3827  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 12:28:18.423  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 12:28:18.425  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 12:28:18.426  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 12:28:18.426  5115  5139 E SarControlService: no key has been found,reset the power
11-22 12:28:18.426  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 12:28:18.426  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 12:28:18.427  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-22 12:28:18.427  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 12:28:18.427  5140  5140 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-22 12:28:18.428  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 12:28:18.429  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 12:28:18.429  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 12:28:18.429  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 12:28:18.429  5140  5140 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 12:28:18.433  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 12:28:18.434  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ec03000000000000ffffffff]
,11-22 12:28:18.434  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:18.434  5140  5154 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-22 12:28:18.437  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ed03000000000000ffffffff]
,11-22 12:28:18.437  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:18.437  5140  5154 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-22 12:28:18.437  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:28:18.437  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 12:28:18.438  4005  4005 D SystemUpdateService: onCreate
11-22 12:28:18.438  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:28:18.439  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 12:28:18.441   927  5845 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-22 12:28:18.442  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 12:28:18.454  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 12:28:18.461  4005  5478 I iu.UploadsManager: num queued entries: 0
,11-22 12:28:18.462  4005  5478 I iu.UploadsManager: num updated entries: 0
11-22 12:28:18.462  4005  5478 I iu.SyncManager: NEXT; no task
,11-22 12:28:18.464  4005  5858 I SystemUpdateService: active receiver: enabled
,11-22 12:28:18.465  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 12:28:18.466  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-22 12:28:18.468  5808  5808 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:28:18.472  5808  5808 D SprintDMHelper: simOperator: 
11-22 12:28:18.472  5808  5808 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 12:28:18.498   927  5845 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 17:28:18 GMT], X-Android-Received-Millis=[1479835698497], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479835698468]}
,11-22 12:28:18.498   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 12:28:18.498   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-22 12:28:18.498   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-22 12:28:18.499   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 12:28:18.504   927   938 D WifiService: setWifiEnabled: false pid=5688, uid=10077
11-22 12:28:18.504   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:28:18.505  4005  5858 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 12:28:18.505   927  3039 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-22 12:28:18.506   927  3039 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-22 12:28:18.506   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 12:28:18.506   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 12:28:18.515   927  5847 D DhcpClient: Clearing IP address
,11-22 12:28:18.515  4005  5858 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-22 12:28:18.515  4005  5858 I SystemUpdateService: now status is 0 (complete)
11-22 12:28:18.515  4005  5858 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 12:28:18.515   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 12:28:18.515  4005  5858 I SystemUpdateService: file has been verified
11-22 12:28:18.515  4005  5858 I SystemUpdateService: OTA package size = 21989297
11-22 12:28:18.517   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:18.523   927  5848 D DhcpClient: Receive thread stopped
,11-22 12:28:18.524  4005  5858 I SystemUpdateService: showing system update notification
11-22 12:28:18.528   927  3222 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-22 12:28:18.529   927  5845 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-22 12:28:18.529   927  5845 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-22 12:28:18.533   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 12:28:18.533   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-22 12:28:18.535   927  5845 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-22 12:28:18.536   533   533 E Parcel  : Reading a NULL string not supported here.
11-22 12:28:18.538   927   927 D RttService: SCAN_AVAILABLE : 1
,11-22 12:28:18.538   927  3147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 12:28:18.538   927  3041 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-22 12:28:18.541  3827  3965 W QCNEJ   : |CORE| network lost: 101
,11-22 12:28:18.541  3827  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-22 12:28:18.545   927  3039 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 12:28:18.546  4005  4005 D SystemUpdateService: onDestroy
11-22 12:28:18.546   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 12:28:18.564   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:28:18.582   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:28:18.582   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 12:28:18.583   927  3041 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-22 12:28:18.583   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:28:18.584   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-22 12:28:18.586  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:18.586  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 12:28:18.587  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:18.587   927  3039 D DhcpClient: doQuit
,11-22 12:28:18.587  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 12:28:18.587   927  3039 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 12:28:18.587   927  5847 D DhcpClient: onQuitting
11-22 12:28:18.587  5842  5842 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-22 12:28:18.592  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:18.592  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 12:28:18.592  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:18.592  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 12:28:18.593  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 12:28:18.596  4005  4005 D SystemUpdateService: onCreate
,11-22 12:28:18.598  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 12:28:18.598  5842  5842 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 12:28:18.598  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 12:28:18.598  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 12:28:18.598  5115  5139 E SarControlService: no key has been found,reset the power
11-22 12:28:18.599  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 12:28:18.599  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 12:28:18.599  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 12:28:18.599  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 12:28:18.599  5140  5140 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 12:28:18.601  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 12:28:18.601  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-22 12:28:18.601  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 12:28:18.601  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 12:28:18.601  5140  5140 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 12:28:18.602  5842  5842 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-22 12:28:18.605  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-22 12:28:18.605  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ee03000000000000ffffffff]
11-22 12:28:18.605  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:18.605  5140  5154 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-22 12:28:18.606  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:28:18.606  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 12:28:18.607  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000ef03000000000000ffffffff]
11-22 12:28:18.607  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:18.607  5140  5154 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-22 12:28:18.607  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:28:18.608  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 12:28:18.611  4005  5876 I SystemUpdateService: active receiver: enabled
,11-22 12:28:18.615  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 12:28:18.619  4005  5478 I iu.UploadsManager: num queued entries: 0
,11-22 12:28:18.619  4005  5478 I iu.UploadsManager: num updated entries: 0
,11-22 12:28:18.622  4005  5876 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 12:28:18.623  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 12:28:18.625  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 12:28:18.626  5808  5808 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:28:18.630  5808  5808 D SprintDMHelper: simOperator: 
,11-22 12:28:18.630  5808  5808 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 12:28:18.639  4005  5478 I iu.SyncManager: NEXT; no task
11-22 12:28:18.639   507   921 E Netd    : netlink response contains error (No such file or directory)
,11-22 12:28:18.639  4005  5876 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-22 12:28:18.639  4005  5876 I SystemUpdateService: now status is 0 (complete)
11-22 12:28:18.639  4005  5876 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 12:28:18.639  4005  5876 I SystemUpdateService: file has been verified
,11-22 12:28:18.639  4005  5876 I SystemUpdateService: OTA package size = 21989297
11-22 12:28:18.639   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 12:28:18.643  5842  5842 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 12:28:18.646  4005  5876 I SystemUpdateService: showing system update notification
,11-22 12:28:18.651  5842  5842 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 12:28:18.657  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 12:28:18.657   927  3039 D wifi    : In wifi stop Hal
,11-22 12:28:18.657   927  3039 D wifi    : halHandle = 0x7f7de56a40, mVM = 0x7f9a44d140, mCls = 0x2018de
11-22 12:28:18.657   927  5841 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 12:28:18.657   927  5841 D WifiHAL : Got a signal to exit!!!
11-22 12:28:18.657   927  5841 I WifiHAL : Exit wifi_event_loop
11-22 12:28:18.659   927  3039 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-22 12:28:18.659   927  3039 E WifiHAL : Event processing terminated
11-22 12:28:18.659   927  3039 D wifi    : In wifi cleaned up handler
11-22 12:28:18.659   927  3039 I WifiHAL : Internal cleanup completed
11-22 12:28:18.659  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:18.661  4209  4303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 12:28:18.670  4005  4005 D SystemUpdateService: onDestroy
,11-22 12:28:18.682   927  5841 D wifi    : set interface wlan0 flags (DOWN)
,11-22 12:28:18.682   927  3039 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 12:28:18.868   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:18.888   927   944 D Tethering: InitialState.processMessage what=4
,11-22 12:28:18.894   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 12:28:19.414   927  3041 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-22 12:28:19.869   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 12:28:23.502  5090  5863 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-22 12:28:23.502  5090  5863 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 12:28:23.507  5090  5863 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 12:28:23.539   927   944 I ActivityManager: Start proc 5882:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 12:28:23.613  5882  5882 D AdapterServiceConfig: Adding HeadsetService
,11-22 12:28:23.614  5882  5882 D AdapterServiceConfig: Adding A2dpService
,11-22 12:28:23.614  5882  5882 D AdapterServiceConfig: Adding HidService
,11-22 12:28:23.614  5882  5882 D AdapterServiceConfig: Adding HealthService
11-22 12:28:23.614  5882  5882 D AdapterServiceConfig: Adding PanService
11-22 12:28:23.614  5882  5882 D AdapterServiceConfig: Adding GattService
11-22 12:28:23.614  5882  5882 D AdapterServiceConfig: Adding BluetoothMapService
11-22 12:28:23.614  5882  5882 D AdapterServiceConfig: Adding SapService
,11-22 12:28:23.624   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b23ca78:true
,11-22 12:28:23.624  5882  5882 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 12:28:23.627  5882  5882 I bt_bluedroid: init
,11-22 12:28:23.627  5882  5894 I BluetoothAdapterState: Entering OffState
,11-22 12:28:23.629  5882  5895 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-22 12:28:23.629  5882  5895 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 12:28:23.630  5882  5895 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 12:28:23.630  5882  5895 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-22 12:28:23.630  5882  5882 I bt_bluedroid: get_profile_interface socket
,11-22 12:28:23.632  5882  5898 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-22 12:28:23.632  5882  5882 I bt_bluedroid: get_profile_interface sdp
11-22 12:28:23.633  5882  5898 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 12:28:23.636  5882  5893 I bt_bluedroid: config_hci_snoop_log
,11-22 12:28:23.637   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 12:28:23.641  5882  5894 D BluetoothAdapterState: Current state: OFF, message: 0
,11-22 12:28:23.641  5882  5894 D BluetoothAdapterProperties: Setting state to 14
11-22 12:28:23.641  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-22 12:28:23.642  5882  5894 D BluetoothBondStateMachine: make
,11-22 12:28:23.644  5882  5899 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 12:28:23.646  5882  5894 I BluetoothAdapterState: Entering PendingCommandState
,11-22 12:28:23.647  5882  5882 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 12:28:23.649  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:23.649  5882  5882 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 12:28:23.650  5882  5882 D BtGatt.GattService: Received start request. Starting profile...
11-22 12:28:23.650  5882  5882 D BtGatt.GattService: start()
11-22 12:28:23.650  5882  5882 I bt_bluedroid: get_profile_interface gatt
11-22 12:28:23.651  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:23.651  5882  5882 D BtGatt.AdvertiseManager: advertise manager created
,11-22 12:28:23.655  5882  5882 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:23.655  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:23.655  5882  5882 V BluetoothAdapterState: isBleTurningOn()=true
11-22 12:28:23.655  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 12:28:23.656  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-22 12:28:23.657  5882  5894 I bt_bluedroid: bt_bluedroid
11-22 12:28:23.657  5882  5895 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-22 12:28:23.657  5882  5895 I bt_hci  : start_up
,11-22 12:28:23.663  5882  5895 I bt_vendor: alloc value 0xf3eb3871
,11-22 12:28:23.663  5882  5895 I bt_vendor: init
11-22 12:28:23.663  5882  5895 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 12:28:23.663  5882  5895 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 12:28:23.772  5882  5895 D bt_hci  : start_up starting async portion
,11-22 12:28:23.772  5882  5902 I bt_hci  : event_finish_startup
11-22 12:28:23.772  5882  5902 I bt_hci_h4: hal_open
,11-22 12:28:23.772  5882  5902 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-22 12:28:23.775  5882  5902 I bt_userial_vendor: device fd = 54 open
,11-22 12:28:23.768  5903  5903 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 12:28:23.788  5882  5902 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 12:28:23.791  5882  5902 D bt_hwcfg: Chipset BCM4358A3
11-22 12:28:23.791  5882  5902 D bt_hwcfg: Target name = [BCM4358A3]
11-22 12:28:23.791  5882  5902 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 12:28:24.188  5882  5902 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 12:28:24.188  5882  5902 D bt_hwcfg: Settlement delay -- 100 ms
11-22 12:28:24.188  5882  5902 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 12:28:24.322  5882  5902 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-22 12:28:24.323  5882  5902 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-22 12:28:24.324  5882  5902 I bt_hwcfg: vendor lib fwcfg completed
11-22 12:28:24.324  5882  5902 I bt_vendor: firmware callback
11-22 12:28:24.325  5882  5902 I bt_hci  : firmware_config_callback
,11-22 12:28:24.332  5882  5905 I bt_btu  : btu_task pending for preload complete event
,11-22 12:28:24.332  5882  5905 I bt_btu_task: Bluetooth chip preload is complete
11-22 12:28:24.332  5882  5905 I bt_btu  : btu_task received preload complete event
11-22 12:28:24.339  5882  5905 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 12:28:24.340  5882  5905 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 12:28:24.340  5882  5905 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 12:28:24.340  5882  5905 I         : BTE_InitTraceLevels -- TRC_AVDT
11-22 12:28:24.340  5882  5905 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-22 12:28:24.340  5882  5905 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 12:28:24.340  5882  5905 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-22 12:28:24.340  5882  5905 I         : BTE_InitTraceLevels -- TRC_BTM
11-22 12:28:24.341  5882  5905 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 12:28:24.341  5882  5905 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 12:28:24.341  5882  5905 I         : BTE_InitTraceLevels -- TRC_SDP
,11-22 12:28:24.341  5882  5905 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 12:28:24.341  5882  5905 I         : BTE_InitTraceLevels -- TRC_SMP
,11-22 12:28:24.341  5882  5905 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 12:28:24.341  5882  5905 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 12:28:24.426  5882  5905 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e31549
11-22 12:28:24.426  5882  5905 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e31549 
,11-22 12:28:24.447  5882  5898 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 12:28:24.448  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 12:28:24.448  5882  5898 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-22 12:28:24.450  5882  5898 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 12:28:24.453  5882  5898 D BluetoothAdapterProperties: Scan Mode:20
11-22 12:28:24.453  5882  5898 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-22 12:28:24.453  5882  5898 D bt_hci  : do_postload posting postload work item
11-22 12:28:24.453  5882  5902 I bt_hci  : event_postload
11-22 12:28:24.454  5882  5902 I bt_vendor: sco_config_cb
11-22 12:28:24.454  5882  5902 I bt_hci  : sco_config_callback postload finished.
,11-22 12:28:24.455  5882  5898 D bt_bte_conf: Device ID record 1 : primary
11-22 12:28:24.455  5882  5898 D bt_bte_conf:   vendorId            = 000f
,11-22 12:28:24.456  5882  5898 D bt_bte_conf:   vendorIdSource      = 0001
11-22 12:28:24.456  5882  5898 D bt_bte_conf:   product             = 1200
11-22 12:28:24.456  5882  5898 D bt_bte_conf:   version             = 1436
11-22 12:28:24.456  5882  5898 D bt_bte_conf:   clientExecutableURL = 
11-22 12:28:24.456  5882  5898 D bt_bte_conf:   serviceDescription  = 
11-22 12:28:24.456  5882  5898 D bt_bte_conf:   documentationURL    = 
11-22 12:28:24.456  5882  5898 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 12:28:24.456  5882  5895 D bt_stack_manager: event_start_up_stack finished
11-22 12:28:24.457  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:24.458  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 12:28:24.458  5882  5894 D BluetoothAdapterProperties: Setting state to 15
11-22 12:28:24.458  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 12:28:24.459  5882  5894 I BluetoothAdapterState: Entering BleOnState
11-22 12:28:24.464  5882  5894 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 12:28:24.464  5882  5894 D BluetoothAdapterProperties: Setting state to 11
,11-22 12:28:24.464  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-22 12:28:24.468  5882  5902 I bt_vendor: low_power_mode_cb
11-22 12:28:24.470  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 12:28:24.472  5882  5882 D HeadsetService: Received start request. Starting profile...
11-22 12:28:24.475  5882  5882 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 12:28:24.476  5882  5882 D HeadsetStateMachine: make
,11-22 12:28:24.484  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:28:24.488  5882  5894 I BluetoothAdapterState: Entering PendingCommandState
,11-22 12:28:24.489  5882  5882 D HeadsetStateMachine: max_hf_connections = 1
,11-22 12:28:24.490  5882  5882 I bt_bluedroid: get_profile_interface handsfree
11-22 12:28:24.490  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 12:28:24.490  5882  5898 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-22 12:28:24.493  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:24.493  5882  5882 D A2dpService: Received start request. Starting profile...
,11-22 12:28:24.494  5882  5882 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-22 12:28:24.494  5882  5882 I bt_bluedroid: get_profile_interface avrcp
,11-22 12:28:24.499  5882  5882 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 12:28:24.500  5882  5882 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 12:28:24.500  5882  5882 D A2dpStateMachine: make
,11-22 12:28:24.501  5882  5882 I bt_bluedroid: get_profile_interface a2dp
11-22 12:28:24.501  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 12:28:24.503  5882  5914 D A2dpStateMachine: Enter Disconnected: -2
,11-22 12:28:24.504  5882  5882 I BluetoothHidServiceJni: classInitNative: succeeds
11-22 12:28:24.505  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 12:28:24.506  5743  5743 D BluetoothInputDevice: Proxy object connected
,11-22 12:28:24.506  5882  5882 D HidService: Received start request. Starting profile...
11-22 12:28:24.506  5882  5882 I bt_bluedroid: get_profile_interface hidhost
11-22 12:28:24.506  5882  5882 D HidService: setHidService(): set to: null
11-22 12:28:24.506  5882  5898 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e1256d
11-22 12:28:24.506  5743  5743 D HidProfile: Bluetooth service connected
11-22 12:28:24.507  5882  5882 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 12:28:24.507  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 12:28:24.507  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:24.508  5882  5882 D HealthService: Received start request. Starting profile...
,11-22 12:28:24.509  5882  5882 I bt_bluedroid: get_profile_interface health
11-22 12:28:24.510  5882  5882 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-22 12:28:24.511  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 12:28:24.512  5743  5743 D BluetoothPan: BluetoothPAN Proxy object connected
,11-22 12:28:24.512  5882  5882 D PanService: Received start request. Starting profile...
11-22 12:28:24.512  5882  5882 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 12:28:24.512  5882  5882 I bt_bluedroid: get_profile_interface pan
11-22 12:28:24.512  5743  5743 D PanProfile: Bluetooth service connected
11-22 12:28:24.512  5882  5898 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-22 12:28:24.516  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 12:28:24.517  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:28:24.517  5743  5743 D BluetoothMap: Proxy object connected
11-22 12:28:24.518  5882  5882 D BluetoothMapService: Received start request. Starting profile...
11-22 12:28:24.518  5882  5882 D BluetoothMapService: start()
11-22 12:28:24.518  5743  5743 D MapProfile: Bluetooth service connected
11-22 12:28:24.518  5743  5743 D BluetoothMap: getConnectedDevices()
11-22 12:28:24.519  5743  5743 D BluetoothMap: Bluetooth is Not enabled
,11-22 12:28:24.520  5882  5882 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-22 12:28:24.521  5882  5882 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-22 12:28:24.521  5882  5882 D BluetoothMapAppObserver: createReceiver()
11-22 12:28:24.522  5882  5882 D BluetoothMapAppObserver: initObservers()
11-22 12:28:24.522  5882  5882 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 12:28:24.529  5882  5882 V SapService: SapBinder()
,11-22 12:28:24.529  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 12:28:24.530  5882  5882 D SapService: Received start request. Starting profile...
11-22 12:28:24.530  5882  5882 V SapService: start()
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:24.532  5882  5910 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:24.532  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:24.533  5882  5882 V BluetoothAdapterState: isTurningOff()=false
,11-22 12:28:24.533  5882  5882 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:24.533  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:24.533  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:24.534  5882  5882 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:24.534  5882  5882 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:24.534  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:24.534  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:24.534  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 12:28:24.534  5882  5894 D BluetoothAdapterProperties: ScanMode =  20
11-22 12:28:24.534  5882  5894 D BluetoothAdapterProperties: State =  11
11-22 12:28:24.534  5882  5894 D BluetoothAdapterProperties: Setting state to 12
,11-22 12:28:24.535  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 12:28:24.535  5882  5894 I BluetoothAdapterState: Entering OnState
11-22 12:28:24.535   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:24.536  5882  5898 D BluetoothAdapterProperties: Scan Mode:21
11-22 12:28:24.536  5882  5898 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 12:28:24.536  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-22 12:28:24.537  5743  5753 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 12:28:24.537  3182  3196 D BluetoothPan: onBluetoothStateChange on: true
11-22 12:28:24.539  3182  3193 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:24.539  3182  3182 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 12:28:24.539  3182  3182 D PanProfile: Bluetooth service connected
11-22 12:28:24.539   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 12:28:24.540   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:24.540  3182  3196 D BluetoothMap: onBluetoothStateChange: up=true
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:24.540  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 12:28:24.540   927   927 D BluetoothA2dp: Proxy object connected
11-22 12:28:24.541  3182  3182 D BluetoothMap: Proxy object connected
11-22 12:28:24.542  5743  5755 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 12:28:24.542  3182  3182 D MapProfile: Bluetooth service connected
11-22 12:28:24.542  3182  3182 D BluetoothMap: getConnectedDevices()
11-22 12:28:24.542  3182  3193 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 12:28:24.542  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 12:28:24.543   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 12:28:24.543  3874  4055 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:24.544  5743  5753 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 12:28:24.545  3182  3196 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 12:28:24.546  3182  3182 D BluetoothA2dp: Proxy object connected
11-22 12:28:24.546  5743  5755 D BluetoothPan: onBluetoothStateChange on: true
11-22 12:28:24.546  3182  3193 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 12:28:24.547  5882  5882 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 12:28:24.548  5882  5882 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-22 12:28:24.548  3182  3182 D BluetoothInputDevice: Proxy object connected
11-22 12:28:24.548  3182  3182 D HidProfile: Bluetooth service connected
11-22 12:28:24.549  5882  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:24.550   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,11-22 12:28:24.551  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-22 12:28:24.553  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:24.553  5882  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:28:24.554  5743  5743 D LocalBluetoothProfileManager: Adding local A2DP profile
11-22 12:28:24.555  5882  5882 D ObexServerSockets: Succeed to create listening sockets 
11-22 12:28:24.555  5882  5882 D ObexServerSockets0: startAccept()
11-22 12:28:24.555  5882  5882 D ObexServerSockets0: prepareForNewConnect()
,11-22 12:28:24.557  5743  5743 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-22 12:28:24.558  5882  5882 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 12:28:24.558  5882  5882 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 12:28:24.559  5882  5920 D ObexServerSockets0: Accepting socket connection...
11-22 12:28:24.559  5882  5882 D BluetoothMapService: onReceive
11-22 12:28:24.560  5882  5882 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 12:28:24.560  5882  5921 D ObexServerSockets0: Accepting socket connection...
,11-22 12:28:24.560  5882  5882 D BluetoothMapService: STATE_ON
11-22 12:28:24.562  5882  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:24.563  5882  5922 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-22 12:28:24.564  5882  5922 D BluetoothSdpJni: SDP Create record success - handle: 1
11-22 12:28:24.564  5743  5743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 12:28:24.566  5743  5743 D BluetoothA2dp: Proxy object connected
,11-22 12:28:24.572  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:28:24.576  5743  5743 D DockEventReceiver: finishStartingService: stopping service
,11-22 12:28:24.579  3182  3182 D BluetoothPbap: Proxy object connected
11-22 12:28:24.579  5743  5743 D BluetoothPbap: Proxy object connected
11-22 12:28:24.580  3182  3182 D PbapServerProfile: Bluetooth service connected
11-22 12:28:24.580  5743  5743 D PbapServerProfile: Bluetooth service connected
,11-22 12:28:24.585  5882  5882 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 12:28:24.585  5882  5882 D ObexServerSockets0: prepareForNewConnect()
,11-22 12:28:24.588  5882  5926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:24.601  5882  5930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:24.602  5882  5930 I BtOppRfcommListener: Accept thread started.
,11-22 12:28:24.637  3874  4222 D BluetoothHeadset: Proxy object connected
11-22 12:28:24.637   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:28:24.637  3182  3193 D BluetoothHeadset: Proxy object connected
11-22 12:28:24.638  3182  3182 D HeadsetProfile: Bluetooth service connected
,11-22 12:28:24.638   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:28:24.638   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:28:24.639  3182  3196 D BluetoothHeadset: Proxy object connected
11-22 12:28:24.639  3182  3182 D HeadsetProfile: Bluetooth service connected
,11-22 12:28:24.639   927   944 D BluetoothHeadset: Proxy object connected
,11-22 12:28:24.643   927   944 D BluetoothHeadset: Proxy object connected
,11-22 12:28:24.644  3874  3895 D BluetoothHeadset: Proxy object connected
,11-22 12:28:24.660  5743  5755 D BluetoothHeadset: Proxy object connected
,11-22 12:28:24.661  5743  5743 D HeadsetProfile: Bluetooth service connected
,11-22 12:28:26.371   927  3041 D ConnectivityService: handlePromptUnvalidated 101
,11-22 12:28:28.520  5882  5894 D BluetoothAdapterState: Current state: ON, message: 23
,11-22 12:28:28.520  5882  5894 D BluetoothAdapterProperties: Setting state to 13
,11-22 12:28:28.521  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-22 12:28:28.522  5882  5894 D BluetoothAdapterProperties: onBluetoothDisable()
,11-22 12:28:28.523  5882  5894 I BluetoothAdapterState: Entering PendingCommandState
,11-22 12:28:28.527  5882  5882 D BluetoothMapService: onReceive
11-22 12:28:28.527  5882  5882 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 12:28:28.527  5882  5882 D BluetoothMapService: STATE_TURNING_OFF
11-22 12:28:28.528  5882  5882 D BluetoothMapService: MAP Service closeService in
,11-22 12:28:28.528  5882  5882 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 12:28:28.528  5882  5882 D ObexServerSockets0: shutdown(block = true)
11-22 12:28:28.529  5882  5882 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 12:28:28.530  5882  5920 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-22 12:28:28.530  5882  5882 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 12:28:28.530  5882  5921 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 12:28:28.530  5882  5907 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 12:28:28.533  5882  5882 I BtOppRfcommListener: stopping Accept Thread
11-22 12:28:28.534  5882  5930 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 12:28:28.534  5882  5930 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-22 12:28:28.534  5882  5898 D BluetoothAdapterProperties: Scan Mode:20
11-22 12:28:28.535  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:28.535  5688  5688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 12:28:28.536  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 12:28:28.537  5743  5743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 12:28:28.538  5688  5688 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 12:28:28.538  5688  5688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 12:28:28.541  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:28:28.546  5743  5743 D DockEventReceiver: finishStartingService: stopping service
11-22 12:28:28.549  5882  5882 D HeadsetService: Received stop request...Stopping profile...
,11-22 12:28:28.555  3874  3897 D BluetoothHeadset: Proxy object disconnected
,11-22 12:28:28.555   927   927 D BluetoothHeadset: Proxy object disconnected
,11-22 12:28:28.556  3182  4035 D BluetoothHeadset: Proxy object disconnected
,11-22 12:28:28.556  5882  5882 D A2dpService: Received stop request...Stopping profile...
11-22 12:28:28.556  5882  5914 D A2dpStateMachine: Exit Disconnected: -1
11-22 12:28:28.557  5743  5753 D BluetoothHeadset: Proxy object disconnected
11-22 12:28:28.557   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 12:28:28.557   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 12:28:28.558   927   927 D BluetoothA2dp: Proxy object disconnected
11-22 12:28:28.558  3182  3182 D HeadsetProfile: Bluetooth service disconnected
11-22 12:28:28.558  5743  5743 D HeadsetProfile: Bluetooth service disconnected
11-22 12:28:28.558  3182  3182 D BluetoothA2dp: Proxy object disconnected
11-22 12:28:28.558  5743  5743 D BluetoothA2dp: Proxy object disconnected
11-22 12:28:28.560  5882  5882 D HidService: Received stop request...Stopping profile...
11-22 12:28:28.560  5882  5882 D HidService: Stopping Bluetooth HidService
,11-22 12:28:28.562  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:28:28.562  3182  3182 D BluetoothInputDevice: Proxy object disconnected
11-22 12:28:28.562  3182  3182 D HidProfile: Bluetooth service disconnected
11-22 12:28:28.563  5743  5743 D BluetoothInputDevice: Proxy object disconnected
11-22 12:28:28.564  5743  5743 D HidProfile: Bluetooth service disconnected
,11-22 12:28:28.564  5882  5882 D HealthService: Received stop request...Stopping profile...
,11-22 12:28:28.566  5882  5882 D PanService: Received stop request...Stopping profile...
11-22 12:28:28.567  3182  3182 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 12:28:28.567  3182  3182 D PanProfile: Bluetooth service disconnected
11-22 12:28:28.568  5743  5743 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-22 12:28:28.568  5743  5743 D PanProfile: Bluetooth service disconnected
11-22 12:28:28.568  5882  5882 D BluetoothMapService: Received stop request...Stopping profile...
11-22 12:28:28.568  5882  5882 D BluetoothMapService: stop()
,11-22 12:28:28.569  5882  5882 D BluetoothMapAppObserver: deinitObservers()
11-22 12:28:28.570  5882  5882 D BluetoothMapAppObserver: removeReceiver()
,11-22 12:28:28.571  3182  3182 D BluetoothMap: Proxy object disconnected
,11-22 12:28:28.571  3182  3182 D MapProfile: Bluetooth service disconnected
11-22 12:28:28.572  5743  5743 D BluetoothMap: Proxy object disconnected
11-22 12:28:28.572  5743  5743 D MapProfile: Bluetooth service disconnected
,11-22 12:28:28.572  5882  5882 D SapService: Received stop request...Stopping profile...
,11-22 12:28:28.572  5882  5882 V SapService: stop()
,11-22 12:28:28.574  5882  5882 V BluetoothAdapterState: isTurningOff()=true
,11-22 12:28:28.574  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:28.574  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:28.574  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:28.576  5882  5882 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 12:28:28.576  5882  5882 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 12:28:28.576  5882  5905 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:28.576  5882  5905 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:28.576  5882  5905 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:28.576  5882  5882 V BluetoothAdapterState: isTurningOff()=true
,11-22 12:28:28.576  5882  5882 V BluetoothAdapterState: isTurningOn()=false
,11-22 12:28:28.576  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:28.576  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 12:28:28.577  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:28.577  5882  5898 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 12:28:28.578  5882  5905 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 12:28:28.578  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 12:28:28.578  5882  5905 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:28.578  5882  5905 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 12:28:28.579  5882  5905 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 12:28:28.579  5882  5905 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 12:28:28.579  5882  5905 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-22 12:28:28.580  3182  3182 D BluetoothPbap: Proxy object disconnected
11-22 12:28:28.580  3182  3182 D PbapServerProfile: Bluetooth service disconnected
11-22 12:28:28.580  5882  5882 V BluetoothAdapterState: isTurningOff()=true
11-22 12:28:28.580  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:28.580  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 12:28:28.580  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:28.580  5743  5743 D BluetoothPbap: Proxy object disconnected
11-22 12:28:28.580  5743  5743 D PbapServerProfile: Bluetooth service disconnected
11-22 12:28:28.580  5882  5882 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 12:28:28.581  5882  5882 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-22 12:28:28.581  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 12:28:28.581  5882  5882 V BluetoothAdapterState: isTurningOff()=true
11-22 12:28:28.581  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:28.581  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:28.581  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:28.581  5882  5882 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 12:28:28.582  5882  5882 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 12:28:28.582  5882  5882 V BluetoothAdapterState: isTurningOff()=true
,11-22 12:28:28.582  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:28.582  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:28.582  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:28.582  5882  5882 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 12:28:28.582  5882  5882 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 12:28:28.585  5882  5898 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 12:28:28.587  5882  5882 D BluetoothMapService: MAP Service closeService in
11-22 12:28:28.587  5882  5882 V BluetoothAdapterState: isTurningOff()=true
11-22 12:28:28.587  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:28.587  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 12:28:28.588  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:28.588  5882  5882 D BluetoothMapService: cleanup()
11-22 12:28:28.588  5882  5882 D BluetoothMapService: MAP Service closeService in
11-22 12:28:28.588  5882  5882 V BluetoothAdapterState: isTurningOff()=true
,11-22 12:28:28.588  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:28.588  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:28.588  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:28.589  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 12:28:28.589  5882  5894 D BluetoothAdapterProperties: Setting state to 15
11-22 12:28:28.589  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-22 12:28:28.590  5743  5755 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 12:28:28.590   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:28.590  5743  5753 D BluetoothMap: onBluetoothStateChange: up=false
11-22 12:28:28.590  5882  5894 I BluetoothAdapterState: Entering BleOnState
11-22 12:28:28.591  3182  4035 D BluetoothPan: onBluetoothStateChange on: false
11-22 12:28:28.592  3182  3193 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:28.592  5743  5755 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 12:28:28.592   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 12:28:28.593   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:28.593  3182  3196 D BluetoothMap: onBluetoothStateChange: up=false
11-22 12:28:28.594  5743  5753 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 12:28:28.595  3182  4035 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 12:28:28.595   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:28.595  3874  4055 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 12:28:28.595  5743  5755 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 12:28:28.596  3182  3193 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 12:28:28.597  5743  5753 D BluetoothPan: onBluetoothStateChange on: false
11-22 12:28:28.597  3182  3196 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 12:28:28.598  5882  5894 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 12:28:28.598  5882  5894 D BluetoothAdapterProperties: Setting state to 16
11-22 12:28:28.598  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 12:28:28.598  5882  5894 D BluetoothAdapterProperties: onBleDisable
11-22 12:28:28.599  5882  5894 I BluetoothAdapterState: Entering PendingCommandState
11-22 12:28:28.599  5882  5895 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 12:28:28.600  5882  5905 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 12:28:28.600  5882  5905 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 12:28:28.601  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 12:28:28.601  5882  5898 D BluetoothAdapterProperties: Scan Mode:20
11-22 12:28:28.601  5743  5743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 12:28:28.603  5688  5688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:28:28.606  5743  5743 D DockEventReceiver: finishStartingService: stopping service
,11-22 12:28:28.608  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:28:28.810  5882  5898 I bt_hci  : shut_down
,11-22 12:28:28.813  5882  5902 D bt_hwcfg: hw_epilog_process
,11-22 12:28:28.813  5882  5902 I bt_vendor: low_power_mode_cb
,11-22 12:28:28.815  5882  5902 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-22 12:28:28.815  5882  5902 I bt_vendor: epilog_cb
11-22 12:28:28.815  5882  5902 I bt_hci  : epilog_finished_callback
,11-22 12:28:28.817  5882  5898 I bt_hci_h4: hal_close
,11-22 12:28:28.818  5882  5898 I bt_userial_vendor: device fd = 54 close
,11-22 12:28:28.933  5882  5895 D bt_stack_manager: event_shut_down_stack finished.
,11-22 12:28:28.934  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 12:28:28.938  5882  5894 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-22 12:28:28.938  5882  5882 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 12:28:28.939  5882  5882 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 12:28:28.939  5882  5882 D BtGatt.GattService: stop()
11-22 12:28:28.939  5882  5882 D BtGatt.AdvertiseManager: advertise clients cleared
,11-22 12:28:28.942  5882  5882 V BluetoothAdapterState: isTurningOff()=false
,11-22 12:28:28.942  5882  5882 V BluetoothAdapterState: isTurningOn()=false
11-22 12:28:28.942  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 12:28:28.942  5882  5882 V BluetoothAdapterState: isBleTurningOff()=true
,11-22 12:28:28.943  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 12:28:28.943  5882  5894 D BluetoothAdapterProperties: Setting state to 10
11-22 12:28:28.943  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-22 12:28:28.944  5882  5894 I BluetoothAdapterState: Entering OffState
11-22 12:28:28.945   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 12:28:28.959  5882  5882 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 12:28:28.959  5882  5882 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-22 12:28:28.959  5882  5882 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-22 12:28:28.963  5882  5895 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 12:28:28.970  5882  5882 I art     : System.exit called, status: 0
,11-22 12:28:28.971  5882  5882 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 12:28:29.001   927  3222 I ActivityManager: Process com.android.bluetooth (pid 5882) has died
,11-22 12:28:29.870   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:30.871   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:31.872   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:32.873   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:33.518  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:28:33.518  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 12:28:33.524  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:33.524  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e710ead removed from the list
11-22 12:28:33.525  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:28:33.528  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 12:28:33.528  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e339430 added. We now have 4 listener(s)
,11-22 12:28:33.530  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:33.532  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:33.532  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e339430 removed from the list
11-22 12:28:33.532  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:33.534  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:33.534  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ce8a9 added. We now have 4 listener(s)
,11-22 12:28:33.534  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:33.874   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:34.874   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 12:28:38.547  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:28:38.583   927   944 I ActivityManager: Start proc 5938:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 12:28:38.668  5938  5938 D AdapterServiceConfig: Adding HeadsetService
,11-22 12:28:38.668  5938  5938 D AdapterServiceConfig: Adding A2dpService
11-22 12:28:38.668  5938  5938 D AdapterServiceConfig: Adding HidService
,11-22 12:28:38.669  5938  5938 D AdapterServiceConfig: Adding HealthService
11-22 12:28:38.679  5938  5938 D AdapterServiceConfig: Adding PanService
,11-22 12:28:38.680  5938  5938 D AdapterServiceConfig: Adding GattService
11-22 12:28:38.680  5938  5938 D AdapterServiceConfig: Adding BluetoothMapService
11-22 12:28:38.680  5938  5938 D AdapterServiceConfig: Adding SapService
,11-22 12:28:38.693   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f91db11:true
11-22 12:28:38.693  5938  5938 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 12:28:38.696  5938  5938 I bt_bluedroid: init
,11-22 12:28:38.696  5938  5950 I BluetoothAdapterState: Entering OffState
,11-22 12:28:38.699  5938  5951 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-22 12:28:38.699  5938  5951 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 12:28:38.699  5938  5951 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 12:28:38.700  5938  5951 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-22 12:28:38.700  5938  5938 I bt_bluedroid: get_profile_interface socket
,11-22 12:28:38.702  5938  5954 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-22 12:28:38.702  5938  5938 I bt_bluedroid: get_profile_interface sdp
,11-22 12:28:38.707  5938  5954 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 12:28:38.707  5938  5949 I bt_bluedroid: config_hci_snoop_log
11-22 12:28:38.708   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 12:28:38.712  5938  5950 D BluetoothAdapterState: Current state: OFF, message: 0
,11-22 12:28:38.712  5938  5950 D BluetoothAdapterProperties: Setting state to 14
11-22 12:28:38.712  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 12:28:38.714  5938  5950 D BluetoothBondStateMachine: make
11-22 12:28:38.715  5938  5955 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 12:28:38.718  5938  5950 I BluetoothAdapterState: Entering PendingCommandState
11-22 12:28:38.720  5938  5938 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 12:28:38.722  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:38.722  5938  5938 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 12:28:38.723  5938  5938 D BtGatt.GattService: Received start request. Starting profile...
11-22 12:28:38.723  5938  5938 D BtGatt.GattService: start()
11-22 12:28:38.723  5938  5938 I bt_bluedroid: get_profile_interface gatt
,11-22 12:28:38.724  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:38.724  5938  5938 D BtGatt.AdvertiseManager: advertise manager created
,11-22 12:28:38.729  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:38.729  5938  5938 V BluetoothAdapterState: isTurningOn()=false
,11-22 12:28:38.729  5938  5938 V BluetoothAdapterState: isBleTurningOn()=true
11-22 12:28:38.729  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:38.729  5938  5950 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 12:28:38.730  5938  5950 I bt_bluedroid: bt_bluedroid
,11-22 12:28:38.731  5938  5951 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-22 12:28:38.731  5938  5951 I bt_hci  : start_up
,11-22 12:28:38.736  5938  5951 I bt_vendor: alloc value 0xf3eb3871
,11-22 12:28:38.736  5938  5951 I bt_vendor: init
11-22 12:28:38.736  5938  5951 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 12:28:38.736  5938  5951 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 12:28:38.844  5938  5951 D bt_hci  : start_up starting async portion
,11-22 12:28:38.844  5938  5958 I bt_hci  : event_finish_startup
11-22 12:28:38.845  5938  5958 I bt_hci_h4: hal_open
11-22 12:28:38.845  5938  5958 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 12:28:38.842  5959  5959 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 12:28:38.848  5938  5958 I bt_userial_vendor: device fd = 54 open
,11-22 12:28:38.862  5938  5958 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 12:28:38.865  5938  5958 D bt_hwcfg: Chipset BCM4358A3
,11-22 12:28:38.865  5938  5958 D bt_hwcfg: Target name = [BCM4358A3]
11-22 12:28:38.866  5938  5958 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 12:28:39.378  5938  5958 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 12:28:39.378  5938  5958 D bt_hwcfg: Settlement delay -- 100 ms
11-22 12:28:39.378  5938  5958 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 12:28:39.513  5938  5958 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-22 12:28:39.514  5938  5958 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-22 12:28:39.515  5938  5958 I bt_hwcfg: vendor lib fwcfg completed
11-22 12:28:39.515  5938  5958 I bt_vendor: firmware callback
11-22 12:28:39.515  5938  5958 I bt_hci  : firmware_config_callback
,11-22 12:28:39.526  5938  5961 I bt_btu  : btu_task pending for preload complete event
11-22 12:28:39.526  5938  5961 I bt_btu_task: Bluetooth chip preload is complete
11-22 12:28:39.526  5938  5961 I bt_btu  : btu_task received preload complete event
,11-22 12:28:39.532  5938  5961 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 12:28:39.532  5938  5961 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 12:28:39.532  5938  5961 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_BTM
,11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 12:28:39.533  5938  5961 I         : BTE_InitTraceLevels -- TRC_SDP
,11-22 12:28:39.534  5938  5961 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 12:28:39.534  5938  5961 I         : BTE_InitTraceLevels -- TRC_SMP
,11-22 12:28:39.534  5938  5961 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 12:28:39.534  5938  5961 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 12:28:39.628  5938  5961 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e31549
11-22 12:28:39.628  5938  5961 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e31549 
,11-22 12:28:39.655  5938  5954 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 12:28:39.657  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 12:28:39.658  5938  5954 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-22 12:28:39.661  5938  5954 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 12:28:39.664  5938  5954 D BluetoothAdapterProperties: Scan Mode:20
,11-22 12:28:39.664  5938  5954 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 12:28:39.665  5938  5954 D bt_hci  : do_postload posting postload work item
11-22 12:28:39.665  5938  5958 I bt_hci  : event_postload
,11-22 12:28:39.665  5938  5958 I bt_vendor: sco_config_cb
,11-22 12:28:39.666  5938  5958 I bt_hci  : sco_config_callback postload finished.
11-22 12:28:39.666  5938  5954 D bt_bte_conf: Device ID record 1 : primary
11-22 12:28:39.667  5938  5954 D bt_bte_conf:   vendorId            = 000f
,11-22 12:28:39.667  5938  5954 D bt_bte_conf:   vendorIdSource      = 0001
11-22 12:28:39.667  5938  5954 D bt_bte_conf:   product             = 1200
11-22 12:28:39.667  5938  5954 D bt_bte_conf:   version             = 1436
11-22 12:28:39.667  5938  5954 D bt_bte_conf:   clientExecutableURL = 
11-22 12:28:39.667  5938  5954 D bt_bte_conf:   serviceDescription  = 
11-22 12:28:39.667  5938  5954 D bt_bte_conf:   documentationURL    = 
,11-22 12:28:39.667  5938  5954 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 12:28:39.667  5938  5951 D bt_stack_manager: event_start_up_stack finished
11-22 12:28:39.668  5938  5950 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-22 12:28:39.669  5938  5950 D BluetoothAdapterProperties: Setting state to 15
11-22 12:28:39.669  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 12:28:39.669  5938  5950 I BluetoothAdapterState: Entering BleOnState
,11-22 12:28:39.672  5938  5958 I bt_vendor: low_power_mode_cb
,11-22 12:28:39.673  5938  5950 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 12:28:39.673  5938  5950 D BluetoothAdapterProperties: Setting state to 11
11-22 12:28:39.673  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-22 12:28:39.679  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 12:28:39.683  5938  5938 D HeadsetService: Received start request. Starting profile...
11-22 12:28:39.686  5938  5938 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-22 12:28:39.686  5938  5938 D HeadsetStateMachine: make
,11-22 12:28:39.696  5938  5950 I BluetoothAdapterState: Entering PendingCommandState
,11-22 12:28:39.699  5938  5938 D HeadsetStateMachine: max_hf_connections = 1
11-22 12:28:39.699  5938  5938 I bt_bluedroid: get_profile_interface handsfree
11-22 12:28:39.700  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 12:28:39.700  5938  5954 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-22 12:28:39.702  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
,11-22 12:28:39.703  5938  5938 D A2dpService: Received start request. Starting profile...
,11-22 12:28:39.704  5938  5938 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 12:28:39.704  5938  5938 I bt_bluedroid: get_profile_interface avrcp
,11-22 12:28:39.710  5938  5938 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 12:28:39.710  5938  5938 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 12:28:39.711  5938  5938 D A2dpStateMachine: make
,11-22 12:28:39.712  5938  5938 I bt_bluedroid: get_profile_interface a2dp
,11-22 12:28:39.713  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-22 12:28:39.714  5938  5969 D A2dpStateMachine: Enter Disconnected: -2
,11-22 12:28:39.716  5938  5938 I BluetoothHidServiceJni: classInitNative: succeeds
11-22 12:28:39.717  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:39.717  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:28:39.718  5938  5938 D HidService: Received start request. Starting profile...
,11-22 12:28:39.718  5938  5938 I bt_bluedroid: get_profile_interface hidhost
11-22 12:28:39.718  5938  5938 D HidService: setHidService(): set to: null
11-22 12:28:39.718  5938  5954 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e1256d
11-22 12:28:39.719  5938  5938 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 12:28:39.719  5938  5954 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 12:28:39.719  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:39.720  5938  5938 D HealthService: Received start request. Starting profile...
,11-22 12:28:39.722  5938  5938 I bt_bluedroid: get_profile_interface health
,11-22 12:28:39.723  5938  5938 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 12:28:39.723  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:39.724  5938  5938 D PanService: Received start request. Starting profile...
11-22 12:28:39.724  5938  5938 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-22 12:28:39.724  5938  5938 I bt_bluedroid: get_profile_interface pan
11-22 12:28:39.724  5938  5954 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 12:28:39.726  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:39.727  5938  5938 D BluetoothMapService: Received start request. Starting profile...
,11-22 12:28:39.727  5938  5938 D BluetoothMapService: start()
,11-22 12:28:39.730  5938  5938 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 12:28:39.731  5938  5938 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-22 12:28:39.731  5938  5938 D BluetoothMapAppObserver: createReceiver()
11-22 12:28:39.733  5938  5938 D BluetoothMapAppObserver: initObservers()
,11-22 12:28:39.733  5938  5938 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 12:28:39.740  5938  5938 V SapService: SapBinder()
,11-22 12:28:39.740  5938  5938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:39.741  5938  5938 D SapService: Received start request. Starting profile...
11-22 12:28:39.741  5938  5938 V SapService: start()
,11-22 12:28:39.744  5938  5938 V BluetoothAdapterState: isTurningOff()=false
,11-22 12:28:39.744  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:39.744  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:39.744  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:39.744  5938  5966 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isTurningOff()=false
,11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 12:28:39.745  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isTurningOn()=true
,11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:39.746  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:39.747  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:39.747  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:39.747  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:39.747  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
11-22 12:28:39.748  5938  5938 V BluetoothAdapterState: isTurningOff()=false
11-22 12:28:39.748  5938  5938 V BluetoothAdapterState: isTurningOn()=true
11-22 12:28:39.748  5938  5938 V BluetoothAdapterState: isBleTurningOn()=false
11-22 12:28:39.748  5938  5938 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 12:28:39.748  5938  5950 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-22 12:28:39.748  5938  5950 D BluetoothAdapterProperties: ScanMode =  20
11-22 12:28:39.748  5938  5950 D BluetoothAdapterProperties: State =  11
11-22 12:28:39.749  5938  5950 D BluetoothAdapterProperties: Setting state to 12
11-22 12:28:39.749  5938  5950 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 12:28:39.749  5938  5950 I BluetoothAdapterState: Entering OnState
11-22 12:28:39.749  5743  5753 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:39.750  5938  5954 D BluetoothAdapterProperties: Scan Mode:21
11-22 12:28:39.750   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:39.750  5938  5954 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 12:28:39.750  5743  5755 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 12:28:39.752  3182  3196 D BluetoothPan: onBluetoothStateChange on: true
,11-22 12:28:39.754  5743  5743 D BluetoothMap: Proxy object connected
,11-22 12:28:39.754  5743  5743 D MapProfile: Bluetooth service connected
11-22 12:28:39.754  5743  5743 D BluetoothMap: getConnectedDevices()
11-22 12:28:39.755  3182  4035 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:39.755  3182  3182 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 12:28:39.755  3182  3182 D PanProfile: Bluetooth service connected
,11-22 12:28:39.756  5743  5755 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 12:28:39.758   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-22 12:28:39.758   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:39.758  3182  3193 D BluetoothMap: onBluetoothStateChange: up=true
11-22 12:28:39.759  5938  5938 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 12:28:39.759  5938  5938 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 12:28:39.761  5938  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:28:39.762  5938  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:39.763  5938  5938 D ObexServerSockets: Succeed to create listening sockets 
,11-22 12:28:39.764  5938  5938 D ObexServerSockets0: startAccept()
11-22 12:28:39.764  5938  5938 D ObexServerSockets0: prepareForNewConnect()
11-22 12:28:39.765  5743  5753 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 12:28:39.765  3182  3182 D BluetoothMap: Proxy object connected
11-22 12:28:39.765  3182  3182 D MapProfile: Bluetooth service connected
11-22 12:28:39.765  3182  3182 D BluetoothMap: getConnectedDevices()
,11-22 12:28:39.766  5938  5938 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 12:28:39.766  5938  5938 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 12:28:39.767  5938  5974 D ObexServerSockets0: Accepting socket connection...
11-22 12:28:39.767   927   927 D BluetoothA2dp: Proxy object connected
,11-22 12:28:39.768  5938  5975 D ObexServerSockets0: Accepting socket connection...
,11-22 12:28:39.769  3182  3193 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 12:28:39.771  5743  5743 D BluetoothA2dp: Proxy object connected
11-22 12:28:39.771   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:39.771  3874  4222 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 12:28:39.772  5743  5753 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 12:28:39.773  3182  4035 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 12:28:39.775  3182  3182 D BluetoothA2dp: Proxy object connected
11-22 12:28:39.775  5743  5755 D BluetoothPan: onBluetoothStateChange on: true
11-22 12:28:39.777  3182  3196 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 12:28:39.779  3182  3182 D BluetoothInputDevice: Proxy object connected
11-22 12:28:39.779  3182  3182 D HidProfile: Bluetooth service connected
11-22 12:28:39.780   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,11-22 12:28:39.781  5938  5938 D BluetoothMapService: onReceive
,11-22 12:28:39.781  5938  5938 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-22 12:28:39.781  5938  5938 D BluetoothMapService: STATE_ON
,11-22 12:28:39.783  5743  5743 D BluetoothInputDevice: Proxy object connected
,11-22 12:28:39.783  5743  5743 D HidProfile: Bluetooth service connected
,11-22 12:28:39.785  5938  5978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 12:28:39.786  5938  5978 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-22 12:28:39.787  5938  5978 D BluetoothSdpJni: SDP Create record success - handle: 1
11-22 12:28:39.787  5743  5743 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 12:28:39.787  5743  5743 D PanProfile: Bluetooth service connected
,11-22 12:28:39.791  5743  5743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 12:28:39.796  5743  5743 D DockEventReceiver: finishStartingService: stopping service
,11-22 12:28:39.797  3646  3646 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 12:28:39.803  5743  5743 D BluetoothPbap: Proxy object connected
11-22 12:28:39.804  5743  5743 D PbapServerProfile: Bluetooth service connected
,11-22 12:28:39.808  5938  5938 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 12:28:39.808  5938  5938 D ObexServerSockets0: prepareForNewConnect()
,11-22 12:28:39.811  5938  5982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:39.816  3182  3182 D BluetoothPbap: Proxy object connected
,11-22 12:28:39.816  3182  3182 D PbapServerProfile: Bluetooth service connected
,11-22 12:28:39.830  5938  5986 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 12:28:39.832  5938  5986 I BtOppRfcommListener: Accept thread started.
,11-22 12:28:39.851  3874  3895 D BluetoothHeadset: Proxy object connected
,11-22 12:28:39.851   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:28:39.852  3182  4035 D BluetoothHeadset: Proxy object connected
11-22 12:28:39.852  3182  3182 D HeadsetProfile: Bluetooth service connected
11-22 12:28:39.852  5743  5976 D BluetoothHeadset: Proxy object connected
,11-22 12:28:39.853   927   927 D BluetoothHeadset: Proxy object connected
11-22 12:28:39.853   927   927 D BluetoothHeadset: Proxy object connected
,11-22 12:28:39.854  5743  5743 D HeadsetProfile: Bluetooth service connected
,11-22 12:28:39.855  3182  3196 D BluetoothHeadset: Proxy object connected
,11-22 12:28:39.856  3182  3182 D HeadsetProfile: Bluetooth service connected
,11-22 12:28:39.858   927   944 D BluetoothHeadset: Proxy object connected
,11-22 12:28:39.871   927   944 D BluetoothHeadset: Proxy object connected
,11-22 12:28:39.873  3874  3897 D BluetoothHeadset: Proxy object connected
,11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:43.565  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 12:28:43.571  5688  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 12:28:43.572  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:43.572  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ce8a9 removed from the list
,11-22 12:28:43.572  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:28:43.574  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 12:28:43.575  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@488be2e added. We now have 4 listener(s)
11-22 12:28:43.575  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:43.578   927  3221 D WifiService: setWifiEnabled: false pid=5688, uid=10077
,11-22 12:28:43.578   927  3221 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:28:48.588  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 12:28:48.589   927  3221 D WifiService: setWifiEnabled: true pid=5688, uid=10077
11-22 12:28:48.589   927  3221 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 12:28:48.603   507   921 D SoftapController: Softap fwReload - Ok
,11-22 12:28:48.608   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:48.608   507   921 D CommandListener: Trying to bring down wlan0
11-22 12:28:48.610   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-22 12:28:48.616   927  3039 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 12:28:49.287   927  3039 D wifi    : set interface wlan0 flags (UP)
,11-22 12:28:49.290   927  3039 I WifiHAL : Initializing wifi
11-22 12:28:49.291   927  3039 I WifiHAL : Creating socket
,11-22 12:28:49.293   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 12:28:49.300   927  3039 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 12:28:49.300   927  3039 D wifi    : Did set static halHandle = 0x7f7de56a40
,11-22 12:28:49.300   927  3039 D wifi    : halHandle = 0x7f7de56a40, mVM = 0x7f9a44d140, mCls = 0x2017ba
11-22 12:28:49.301   927  3039 D wifi    : array field set
11-22 12:28:49.301   927  3039 I WifiNative-HAL: interface[0] = wlan0
,11-22 12:28:49.304   927  5991 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547573033536
11-22 12:28:49.305   927  5991 D wifi    : waitForHalEvents called, vm = 0x7f9a44d140, obj = 0x2017ba, env = 0x7f7e753900
,11-22 12:28:49.306   927  3039 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 12:28:49.309   927  3039 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-22 12:28:49.351  5992  5992 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 12:28:49.371  5992  5992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 12:28:49.398  5992  5992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 12:28:49.398  5992  5992 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 12:28:49.876   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:50.324   927  3039 D WifiConfigStore: Loading config and enabling all networks 
,11-22 12:28:50.342   927  3039 D WifiConfigStore: loaded 0 passpoint configs
,11-22 12:28:50.342   927  3039 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-22 12:28:50.342   927  3039 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 12:28:50.344   927  3039 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-22 12:28:50.346   927  3039 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-22 12:28:50.346   927  3039 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-22 12:28:50.346   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,11-22 12:28:50.347   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-22 12:28:50.351   927  3039 D WifiNative-HAL: Setting external_sim to 1
,11-22 12:28:50.352  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 12:28:50.352   927  3039 D wifi    : setting dfs flag to true, 0x7f7e849860
11-22 12:28:50.353   927  3039 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 12:28:50.353   927  3039 D wifi    : setting scan oui 0x7f7e849860
11-22 12:28:50.353   927  3039 D WifiHAL : Sending mac address OUI
,11-22 12:28:50.358   927  3039 E native  : do suspend false
,11-22 12:28:50.369   927  3039 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-22 12:28:50.369   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-22 12:28:50.369   927   927 D RttService: SCAN_AVAILABLE : 3
11-22 12:28:50.370   927  3147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 12:28:50.371   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:50.376   927  3038 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-22 12:28:50.376   927  3038 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 12:28:50.387   927  3038 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 12:28:50.387   927  3038 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-22 12:28:50.395   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164278 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,11-22 12:28:50.877   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:51.878   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:52.879   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:53.457  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:53.463  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:53.468  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:53.473  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 12:28:53.535   927  3039 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 12:28:53.536   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 12:28:53.536   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 12:28:53.548   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 12:28:53.579   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 12:28:53.581  5992  5992 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 12:28:53.604  5688  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 12:28:53.606  5688  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 12:28:53.606  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.606  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@488be2e removed from the list
11-22 12:28:53.606  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 12:28:53.610  5688  5734 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-22 12:28:53.611  5688  5734 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-22 12:28:53.613  5688  5734 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@92052cf Bundle[{}]
11-22 12:28:53.613  5688  5734 I io.jxcore.node.LifeCycleMonitor: start: OK
11-22 12:28:53.613  5688  5734 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-22 12:28:53.613  5688  5734 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-22 12:28:53.614  5688  5734 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-22 12:28:53.614  5688  5734 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-22 12:28:53.615  5688  5734 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-22 12:28:53.620  5688  5734 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-22 12:28:53.621  5688  5734 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-22 12:28:53.621  5688  5734 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-22 12:28:53.623  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.623  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf2dcf added. We now have 3 listener(s)
,11-22 12:28:53.624  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:28:53.624  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.624  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.625  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.625  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@775c35c added. We now have 4 listener(s)
11-22 12:28:53.625  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:53.626  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 12:28:53.628  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 12:28:53.628  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d26665 added. We now have 4 listener(s)
,11-22 12:28:53.630  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-22 12:28:53.630  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.630  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.630  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.631  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e68f3a added. We now have 5 listener(s)
11-22 12:28:53.631  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:53.631  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:53.631  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:53.631  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:53.631  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.631  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.631  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-22 12:28:53.631  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf2dcf removed from the list
11-22 12:28:53.632  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.632  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@775c35c removed from the list
11-22 12:28:53.632  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:53.632  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.632  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.633  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.633  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.634  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.634  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.634  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.634  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.634  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@775c35c not in the list
,11-22 12:28:53.634  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.634  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.635  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.635  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.635  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.636  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.636  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.636  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.636  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e68f3a removed from the list
11-22 12:28:53.636  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.636  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 12:28:53.636  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.636  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d26665 removed from the list
,11-22 12:28:53.637  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.637  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caad7eb added. We now have 3 listener(s)
,11-22 12:28:53.639  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-22 12:28:53.639  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.639  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.639  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.639  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49b948 added. We now have 4 listener(s)
11-22 12:28:53.639  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:53.640  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 12:28:53.641  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 12:28:53.641  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48803e1 added. We now have 4 listener(s)
,11-22 12:28:53.642  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-22 12:28:53.643  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.643  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.643  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.643  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6506 added. We now have 5 listener(s)
11-22 12:28:53.643  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 12:28:53.643  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:28:53.643  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 12:28:53.644  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 12:28:53.644  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:28:53.644  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-22 12:28:53.645  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 12:28:53.648  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 12:28:53.648  5688  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:28:53.648  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 12:28:53.651  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.651  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 12:28:53.651  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 12:28:53.652  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:28:53.652  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 12:28:53.654  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.654  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:28:53.654  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:28:53.654  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:28:53.654  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 12:28:53.654  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.654  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:28:53.656  5938  5948 D BtGatt.GattService: registerClient() - UUID=3aa5e704-ac63-4763-8411-cb3c48bdf1d4
11-22 12:28:53.657  5938  5954 D BtGatt.GattService: onClientRegistered() - UUID=3aa5e704-ac63-4763-8411-cb3c48bdf1d4, clientIf=5
,11-22 12:28:53.658  5688  5832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 12:28:53.658  5938  5967 D BtGatt.GattService: start scan with filters
,11-22 12:28:53.661  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 12:28:53.661  5938  5957 D BtGatt.ScanManager: handling starting scan
11-22 12:28:53.661  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.661  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-22 12:28:53.661  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.661  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:28:53.662  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:28:53.662  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.662  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 12:28:53.662  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:28:53.662  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.662  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.662  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.662  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-22 12:28:53.662  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 12:28:53.663  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.663  5938  5957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb20273
11-22 12:28:53.665  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.665  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:28:53.665  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.665  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.665  5688  5734 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 12:28:53.665  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:53.665  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.665  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-22 12:28:53.665  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.665  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:28:53.665  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.665  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 12:28:53.668  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.668  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-22 12:28:53.668  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.668  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:28:53.668  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:28:53.668  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.668  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 12:28:53.668  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:28:53.668  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.669  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.669  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.669  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 12:28:53.669  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.669  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:28:53.669  5938  5967 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:28:53.670  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:28:53.670  5938  5954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 12:28:53.670  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.670  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:28:53.671  5938  5949 D BtGatt.GattService: stopScan() - queue size =1
11-22 12:28:53.671  5938  5957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 12:28:53.672  5938  5948 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.672  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:28:53.673  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:28:53.673  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:28:53.673  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.674  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.674  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:53.674  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.674  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.675  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:53.675  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:53.675  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:28:53.675  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.676  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:28:53.676  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-22 12:28:53.676  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.676  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.676  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.676  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:53.676  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.676  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.677  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 12:28:53.677  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.678  5938  5957 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:28:53.678  5938  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 12:28:53.678  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.678  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.678  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 12:28:53.678  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 12:28:53.678  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:53.678  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:53.679  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.679  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.679  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.679  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caad7eb removed from the list
11-22 12:28:53.679  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:53.679  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49b948 removed from the list
11-22 12:28:53.679  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:53.679  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.679  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.680  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.680  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.680  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.680  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.680  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.680  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 12:28:53.680  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49b948 not in the list
11-22 12:28:53.680  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.680  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.681  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.681  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.681  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.681  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.681  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.681  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.682  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6506 removed from the list
11-22 12:28:53.682  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.682  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.682  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.682  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48803e1 removed from the list
11-22 12:28:53.683  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.683  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c185963 added. We now have 3 listener(s)
11-22 12:28:53.685  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:28:53.685  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.685  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.685  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.685  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72c6960 added. We now have 4 listener(s)
11-22 12:28:53.685  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:53.686  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 12:28:53.687  5938  5954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 12:28:53.687  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.687  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.687  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thali,project.p2p.btconnectorlib.ConnectionManager@6444e19 added. We now have 4 listener(s)
11-22 12:28:53.688  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:28:53.688  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.688  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.689  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.689  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b370ede added. We now have 5 listener(s)
11-22 12:28:53.689  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:53.689  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:28:53.689  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:28:53.689  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 12:28:53.689  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 12:28:53.689  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:28:53.690  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-22 12:28:53.691  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 12:28:53.691  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 12:28:53.691  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.693  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:28:53.693  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:28:53.693  5688  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:28:53.693  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 12:28:53.697  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 12:28:53.697  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.697  5938  5954 E BtGatt.ContextMap: Context not found for ID 5
11-22 12:28:53.697  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.697  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 12:28:53.698  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 12:28:53.698  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:28:53.698  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 12:28:53.701  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.701  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:28:53.701  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:28:53.702  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:28:53.702  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 12:28:53.702  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.702  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:28:53.702  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 12:28:53.702  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.702  5938  5957 D BtGatt.ScanManager: stopping BLe Batch
,11-22 12:28:53.704  5938  5967 D BtGatt.GattService: registerClient() - UUID=d8a25776-9ffa-45b3-8158-019453ce0496
,11-22 12:28:53.705  5938  5954 D BtGatt.GattService: onClientRegistered() - UUID=d8a25776-9ffa-45b3-8158-019453ce0496, clientIf=5
11-22 12:28:53.705  5688  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 12:28:53.705  5938  5948 D BtGatt.GattService: start scan with filters
,11-22 12:28:53.708  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 12:28:53.708  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.708  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:28:53.708  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 12:28:53.708  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.708  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 12:28:53.708  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.708  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-22 12:28:53.708  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:28:53.708  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.709  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 12:28:53.709  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 12:28:53.709  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.709  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.709  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.709  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-22 12:28:53.710  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 12:28:53.710  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.712  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:28:53.712  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:28:53.713  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.713  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 12:28:53.713  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.714  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.714  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.714  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:28:53.714  5938  5957 D BtGatt.ScanManager: handling starting scan
11-22 12:28:53.714  5688  5734 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 12:28:53.714  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:53.714  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:53.714  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:53.714  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.714  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.714  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:28:53.715  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.715  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.715  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c185963 removed from the list
11-22 12:28:53.715  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.715  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72c6960 removed from the list
11-22 12:28:53.715  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:53.715  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.715  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:28:53.715  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.715  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-22 12:28:53.715  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 12:28:53.716  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.716  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.716  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.716  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:28:53.716  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.716  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.716  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.717  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.717  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.717  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.717  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72c6960 not in the list
11-22 12:28:53.717  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.717  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.718  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.718  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 12:28:53.718  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.718  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:28:53.719  5938  5949 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:28:53.719  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:28:53.719  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:28:53.720  5938  5977 D BtGatt.GattService: stopScan() - queue size =1
11-22 12:28:53.720  5938  5954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 12:28:53.720  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.720  5938  5957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 12:28:53.720  5938  5949 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.721  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:28:53.721  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:28:53.722  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:28:53.722  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.723  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.723  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:53.724  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.724  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.724  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.724  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.724  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.724  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:53.724  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b370ede removed from the list
11-22 12:28:53.724  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 12:28:53.724  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:53.724  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.724  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.724  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:28:53.724  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6444e19 removed from the list
11-22 12:28:53.724  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.724  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:28:53.724  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 12:28:53.724  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.724  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.724  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.724  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:53.724  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.724  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.724  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.725  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99591db added. We now have 3 listener(s)
11-22 12:28:53.725  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 12:28:53.725  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.725  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.725  5938  5957 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:28:53.725  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.725  5938  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 12:28:53.725  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.726  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:28:53.726  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.726  5688  5734 D org.thaliproject.p2p.btconn,ectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.726  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.726  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1820478 added. We now have 4 listener(s)
11-22 12:28:53.726  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:53.726  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 12:28:53.730  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.730  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e88a751 added. We now have 4 listener(s)
11-22 12:28:53.732  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:28:53.732  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.732  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.732  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.732  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd01bb6 added. We now have 5 listener(s)
11-22 12:28:53.732  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:53.733  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:28:53.733  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 12:28:53.733  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 12:28:53.733  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 12:28:53.733  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-22 12:28:53.733  5938  5954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 12:28:53.733  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.734  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 12:28:53.738  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 12:28:53.739  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.739  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 12:28:53.739  5688  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 12:28:53.739  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 12:28:53.740  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 12:28:53.743  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.743  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 12:28:53.744  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 12:28:53.744  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 12:28:53.744  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 12:28:53.744  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:28:53.744  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.744  5938  5954 E BtGatt.ContextMap: Context not found for ID 5
,11-22 12:28:53.747  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.747  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 12:28:53.747  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 12:28:53.747  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 12:28:53.747  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 12:28:53.747  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.748  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:28:53.749  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 12:28:53.749  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.749  5938  5957 D BtGatt.ScanManager: stopping BLe Batch
11-22 12:28:53.750  5938  5949 D BtGatt.GattService: registerClient() - UUID=c5638517-159a-49cd-b3ce-8cb5351eb8c0
11-22 12:28:53.750  5938  5954 D BtGatt.GattService: onClientRegistered() - UUID=c5638517-159a-49cd-b3ce-8cb5351eb8c0, clientIf=5
,11-22 12:28:53.751  5688  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 12:28:53.751  5938  5977 D BtGatt.GattService: start scan with filters
11-22 12:28:53.753  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 12:28:53.753  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 12:28:53.753  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 12:28:53.753  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.753  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 12:28:53.754  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 12:28:53.754  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.754  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 12:28:53.754  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-22 12:28:53.754  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.754  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.754  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.754  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.754  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 12:28:53.754  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.754  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-22 12:28:53.754  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:28:53.755  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.757  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.757  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:28:53.757  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.757  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.757  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.758  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:28:53.759  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:28:53.759  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:53.759  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:53.759  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:53.759  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.759  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.759  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:28:53.759  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.759  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.759  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99591db removed from the list
11-22 12:28:53.759  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.759  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1820478 removed from the list
11-22 12:28:53.759  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:53.759  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.759  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:28:53.759  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.759  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.759  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 12:28:53.759  5688  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 12:28:53.759  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 12:28:53.759  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.760  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.760  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.760  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.760  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 12:28:53.760  5938  5957 D BtGatt.ScanManager: handling starting scan
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Threa,d-61,5,main], id: 61
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.761  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.761  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.761  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.761  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1820478 not in the list
11-22 12:28:53.761  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.761  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 12:28:53.761  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.762  5688  5734 D BluetoothAdapter: STATE_ON
11-22 12:28:53.762  5938  5967 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 12:28:53.762  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 12:28:53.763  5688  5734 D BluetoothAdapter: STATE_ON
,11-22 12:28:53.763  5938  5977 D BtGatt.GattService: stopScan() - queue size =1
,11-22 12:28:53.764  5938  5948 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.764  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.765  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 12:28:53.765  5938  5954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 12:28:53.765  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 12:28:53.765  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.765  5938  5957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 12:28:53.765  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 12:28:53.765  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.766  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.766  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:53.766  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.766  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.766  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.767  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.767  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.767  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:53.767  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd01bb6 removed from the list
,11-22 12:28:53.767  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.767  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 12:28:53.767  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.767  5688  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 12:28:53.767  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.767  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.767  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e88a751 removed from the list
11-22 12:28:53.767  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 12:28:53.767  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 12:28:53.767  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.767  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.767  5688  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.767  5688  5688 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 12:28:53.767  5688  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.767  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.767  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.767  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2826153 added. We now have 3 listener(s)
11-22 12:28:53.768  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:28:53.768  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.769  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.769  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.769  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45cea90 added. We now have 4 listener(s)
11-22 12:28:53.769  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:53.769  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 12:28:53.769  5938  5954 D BtGatt.ScanManager: callback done for clientIf - ,5 status - 0
11-22 12:28:53.769  5938  5957 D BtGatt.ScanManager: Starting BLE batch scan
11-22 12:28:53.769  5938  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 12:28:53.769  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.769  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.769  5688  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 12:28:53.770  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 12:28:53.771  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 12:28:53.771  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667ef89 added. We now have 4 listener(s)
11-22 12:28:53.772  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-22 12:28:53.772  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 12:28:53.772  5688  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 12:28:53.772  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 12:28:53.772  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232eb8e added. We now have 5 listener(s)
11-22 12:28:53.772  5688  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 12:28:53.772  5688  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 12:28:53.772  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:53.773  5688  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 12:28:53.773  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.773  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.773  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.773  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2826153 removed from the list
11-22 12:28:53.773  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.773  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45cea90 removed from the list
11-22 12:28:53.773  5688  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-22 12:28:53.773  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.773  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.774  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.774  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.774  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.774  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.774  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.774  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.774  5688  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45cea90 not in the list
11-22 12:28:53.774  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.774  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.778  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.778  5938  5954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 12:28:53.778  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.778  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.778  5688  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 12:28:53.778  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 12:28:53.778  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 12:28:53.778  5688  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 12:28:53.778  5688  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232eb8e removed from the list
11-22 12:28:53.778  5688  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 12:28:53.778  5688  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 12:28:53.778  5688  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 12:28:53.778  5688  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667ef89 removed from the list
11-22 12:28:53.779  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 12:28:53.779  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 12:28:53.779  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 12:28:53.779  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:28:53.779  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-22 12:28:53.780  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 12:28:53.782  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 12:28:53.782  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.783  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:28:53.787  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:28:53.787  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.787  5938  5954 E BtGatt.ContextMap: Context not found for ID 5
11-22 12:28:53.792  5938  5954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 12:28:53.792  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.792  5938  5957 D BtGatt.ScanManager: stopping BLe Batch
11-22 12:28:53.796  5938  5954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 12:28:53.796  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 12:28:53.796  5938  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 12:28:53.800  5938  5954 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 12:28:53.800  5938  5954 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 12:28:53.880   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:28:53.999  5992  5992 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 12:28:54.020  5992  5992 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 12:28:54.021  5992  5992 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 12:28:54.025   927  3039 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 12:28:54.025   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 12:28:54.025   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 12:28:54.035   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 12:28:54.043   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:54.046   927  3039 D WifiStateMachine: Start Dhcp Watchdog 3
,11-22 12:28:54.051   927  5997 D DhcpClient: Receive thread started
,11-22 12:28:54.055   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-22 12:28:54.055   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-22 12:28:54.055   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-22 12:28:54.134   927  3039 E native  : do suspend false
,11-22 12:28:54.142   927  5996 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 12:28:54.155   927  5997 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-22 12:28:54.155   927  5996 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-22 12:28:54.156   927  5996 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-22 12:28:54.170   927  5997 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 12:28:54.171   927  5996 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 12:28:54.172   507   921 D CommandListener: Setting iface cfg
,11-22 12:28:54.176   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-22 12:28:54.176  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-22 12:28:54.177   927  5996 D DhcpClient: Scheduling renewal in 86399s
,11-22 12:28:54.184   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-22 12:28:54.185   927  3039 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 12:28:54.185   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-22 12:28:54.190   927  3039 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-22 12:28:54.192   927  3041 D ConnectivityService: Adding iface wlan0 to network 102
,11-22 12:28:54.219   927  3041 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 12:28:54.220   927  3041 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-22 12:28:54.221   927  3041 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-22 12:28:54.223   927  3041 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-22 12:28:54.224  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:28:54.224   927  3041 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-22 12:28:54.230   927  3041 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 12:28:54.234   927  3041 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-22 12:28:54.234   927  3041 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-22 12:28:54.234   927  3041 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-22 12:28:54.234   927  3039 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 12:28:54.234   927  3041 D ConnectivityService:    accepting network in place of null
,11-22 12:28:54.234   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 12:28:54.235   927  3041 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 12:28:54.248   927  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 12:28:54.256   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:28:54.267  5688  5688 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 12:28:54.277   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 12:28:54.280   927  3041 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-22 12:28:54.280  3827  3965 W QCNEJ   : |CORE| network available: 102
,11-22 12:28:54.280   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 12:28:54.281   927  3041 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-22 12:28:54.283   927   944 D Tethering: MasterInitialState.processMessage what=3
11-22 12:28:54.284  3827  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-22 12:28:54.285  3827  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-22 12:28:54.285  3827  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 12:28:54.295  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 12:28:54.295  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 12:28:54.295  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-22 12:28:54.295  5115  5139 E SarControlService: no key has been found,reset the power
11-22 12:28:54.295  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 12:28:54.295  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 12:28:54.295  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 12:28:54.296  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 12:28:54.296  5140  5140 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 12:28:54.297  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 12:28:54.297  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 12:28:54.297  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 12:28:54.298  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 12:28:54.298  5140  5140 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 12:28:54.300  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 12:28:54.303  4005  4005 D SystemUpdateService: onCreate
11-22 12:28:54.305  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000f003000000000000ffffffff]
11-22 12:28:54.305  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:54.305  5140  5154 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-22 12:28:54.305  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-22 12:28:54.306  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 12:28:54.309  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 12:28:54.310  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@22a188a HexData = [00000000f103000000000000ffffffff]
11-22 12:28:54.310  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 12:28:54.310  5140  5154 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-22 12:28:54.311  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 12:28:54.311  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 12:28:54.316  4005  6007 I SystemUpdateService: active receiver: enabled
11-22 12:28:54.320   927  5994 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-22 12:28:54.335  4005  6007 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 12:28:54.338  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 12:28:54.348  4005  5478 I iu.UploadsManager: num queued entries: 0
,11-22 12:28:54.349  4005  5478 I iu.UploadsManager: num updated entries: 0
11-22 12:28:54.349  4005  5478 I iu.SyncManager: NEXT; no task
,11-22 12:28:54.353  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 12:28:54.355  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 12:28:54.352  4005  6007 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-22 12:28:54.355  4005  6007 I SystemUpdateService: now status is 0 (complete)
11-22 12:28:54.356  5808  5808 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 12:28:54.360  5808  5808 D SprintDMHelper: simOperator: 
11-22 12:28:54.360  5808  5808 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 12:28:54.356  4005  6007 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 12:28:54.363  4005  6007 I SystemUpdateService: file has been verified
11-22 12:28:54.363  4005  6007 I SystemUpdateService: OTA package size = 21989297
,11-22 12:28:54.381   927  5994 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 17:28:54 GMT], X-Android-Received-Millis=[1479835734381], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479835734350]}
,11-22 12:28:54.382   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 12:28:54.382   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-22 12:28:54.382   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 12:28:54.383   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 12:28:54.402  4005  6007 I SystemUpdateService: showing system update notification
,11-22 12:28:54.409  3646  6018 I VacuumService: Vacuum at: now=1479835734409 tag=VacuumService
,11-22 12:28:54.422  4005  4005 D SystemUpdateService: onDestroy
,11-22 12:28:54.431  3646  6021 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-22 12:28:54.470  3646  6019 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-22 12:28:54.472  3646  6019 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-22 12:28:54.479  5090  6013 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 12:28:54.514  3646  6019 W Uploader:  no longer exists, so no auth token.
,11-22 12:28:54.519  3646  6021 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:28:54.798  3646  6024 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:28:54.880   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 12:28:55.008  3646  6021 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:28:55.062  3646  6019 W Uploader:  no longer exists, so no auth token.
,11-22 12:28:55.074  3646  6024 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:28:55.167  3646  6021 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 12:28:55.931  5688  6030 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 12:28:55.931  5688  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:28:56.727  5688  6030 W !!      : call onHalfStreamCopied
,11-22 12:28:56.727  5688  6030 I testCopyDataAndClose: closing input stream
,11-22 12:28:57.078   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 12:28:57.511  5688  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 12:29:01.334  5688  6031 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:01.334  5688  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:29:02.240   927  3041 D ConnectivityService: handlePromptUnvalidated 102
,11-22 12:29:03.334  5688  5734 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-22 12:29:03.334  5688  5734 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:29:03.334  5688  5734 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-22 12:29:03.413  5688  6031 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-22 12:29:03.413  5688  6031 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:03.413  5688  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,11-22 12:29:03.482  5688  6032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 12:29:03.482  5688  6032 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 12:29:05.103  5688  6032 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 12:29:05.397   927  3039 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-22 12:29:08.881  5688  6033 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:08.881  5688  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:29:08.881  5688  6033 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:08.881  5688  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 12:29:08.881  5688  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 12:29:08.881  5688  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:29:08.881  5688  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 12:29:08.882  5688  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 12:29:08.882  5688  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-22 12:29:08.882  5688  6033 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 12:29:08.882  5688  6033 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 12:29:08.882  5688  6033 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:08.882  5688  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-22 12:29:08.884  5688  5734 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-22 12:29:08.887  5688  6034 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:08.887  5688  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 12:29:08.887  5688  6034 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-22 12:29:08.888  5688  6034 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:08.888  5688  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 12:29:08.888  5688  6034 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-22 12:29:08.888  5688  6034 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 12:29:08.888  5688  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 12:29:08.892  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-22 12:29:08.892  5688  5734 I jxcore-log: 
,11-22 12:29:08.893  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-22 12:29:08.893  5688  5734 I jxcore-log: 
11-22 12:29:08.893  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-22 12:29:08.893  5688  5734 I jxcore-log: 
11-22 12:29:08.893  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-22 12:29:08.893  5688  5734 I jxcore-log: 
11-22 12:29:08.893  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Total duration:  90871'
11-22 12:29:08.893  5688  5734 I jxcore-log: 
11-22 12:29:08.894  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Failures: 
11-22 12:29:08.894  5688  5734 I jxcore-log:  DiscoveryManager isRunning should return true
11-22 12:29:08.894  5688  5734 I jxcore-log: Expected: is <true>
11-22 12:29:08.894  5688  5734 I jxcore-log:      but: was <false>
11-22 12:29:08.894  5688  5734 I jxcore-log: '
11-22 12:29:08.894  5688  5734 I jxcore-log: 
11-22 12:29:08.895  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-22 12:29:08.895  5688  5734 I jxcore-log: 
11-22 12:29:08.896  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-22 12:29:08.896  5688  5734 I jxcore-log: 
,11-22 12:29:08.900  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:29:08.900  5688  5734 I jxcore-log: 
,11-22 12:29:08.901  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:29:08.901  5688  5734 I jxcore-log: 
11-22 12:29:08.902  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 12:29:08.902  5688  5734 I jxcore-log: 
11-22 12:29:08.902  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:29:08.902  5688  5734 I jxcore-log: 
11-22 12:29:08.902  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.902  5688  5734 I jxcore-log: 
,11-22 12:29:08.903  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:29:08.903  5688  5734 I jxcore-log: 
11-22 12:29:08.903  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.903  5688  5734 I jxcore-log: 
11-22 12:29:08.903  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:29:08.903  5688  5734 I jxcore-log: 
,11-22 12:29:08.904  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:29:08.904  5688  5734 I jxcore-log: 
11-22 12:29:08.904  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 12:29:08.904  5688  5734 I jxcore-log: 
11-22 12:29:08.904  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 12:29:08.904  5688  5734 I jxcore-log: 
11-22 12:29:08.905  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.905  5688  5734 I jxcore-log: 
,11-22 12:29:08.905  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:29:08.905  5688  5734 I jxcore-log: 
11-22 12:29:08.905  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.905  5688  5734 I jxcore-log: 
11-22 12:29:08.905  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:29:08.905  5688  5734 I jxcore-log: 
11-22 12:29:08.905  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.905  5688  5734 I jxcore-log: 
11-22 12:29:08.906  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:29:08.906  5688  5734 I jxcore-log: 
,11-22 12:29:08.906  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 12:29:08.906  5688  5734 I jxcore-log: 
11-22 12:29:08.906  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 12:29:08.906  5688  5734 I jxcore-log: 
11-22 12:29:08.907  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 12:29:08.907  5688  5734 I jxcore-log: 
11-22 12:29:08.907  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 12:29:08.907  5688  5734 I jxcore-log: 
,11-22 12:29:08.907  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 12:29:08.907  5688  5734 I jxcore-log: 
,11-22 12:29:08.909  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 12:29:08.909  5688  5734 I jxcore-log: 
11-22 12:29:08.910  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 12:29:08.910  5688  5734 I jxcore-log: 
,11-22 12:29:08.910  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 12:29:08.910  5688  5734 I jxcore-log: 
11-22 12:29:08.911  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 12:29:08.911  5688  5734 I jxcore-log: 
11-22 12:29:08.911  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-22 12:29:08.911  5688  5734 I jxcore-log: 
11-22 12:29:08.911  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 12:29:08.911  5688  5734 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-22 12:29:08.911  5688  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 12:29:08.911  5688  5734 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-22 12:29:08.912  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:29:08.912  5688  5734 I jxcore-log: 
11-22 12:29:08.912  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.912  5688  5734 I jxcore-log: 
11-22 12:29:08.912  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:29:08.912  5688  5734 I jxcore-log: 
,11-22 12:29:08.912  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.912  5688  5734 I jxcore-log: 
11-22 12:29:08.912  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 12:29:08.912  5688  5734 I jxcore-log: 
,11-22 12:29:08.913  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 12:29:08.913  5688  5734 I jxcore-log: 
,11-22 12:29:08.919  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-22 12:29:08.919  5688  5734 I jxcore-log: 
11-22 12:29:08.919  5688  5734 I jxcore-log: 2016-11-22 17:29:08 - WARN testUtils: 'myNameCallback not set!'
11-22 12:29:08.919  5688  5734 I jxcore-log: 
,11-22 12:29:08.920  5688  5688 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-22 12:29:11.000  5688  5734 I jxcore-log: 2016-11-22 17:29:11 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-22 12:29:11.000  5688  5734 I jxcore-log: 
,11-22 12:29:11.002  5688  5734 I jxcore-log: 2016-11-22 17:29:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-22 12:29:11.002  5688  5734 I jxcore-log: 
,11-22 12:29:11.356  5688  5734 I jxcore-log: 2016-11-22 17:29:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-22 12:29:11.356  5688  5734 I jxcore-log: 
,11-22 12:29:11.368  5688  5734 I jxcore-log: 2016-11-22 17:29:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-22 12:29:11.368  5688  5734 I jxcore-log: 
,11-22 12:29:12.490  5688  5734 I jxcore-log: 2016-11-22 17:29:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-22 12:29:12.490  5688  5734 I jxcore-log: 
,11-22 12:29:12.684  5688  5734 I jxcore-log: 2016-11-22 17:29:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-22 12:29:12.684  5688  5734 I jxcore-log: 
,11-22 12:29:12.690  5688  5734 I jxcore-log: 2016-11-22 17:29:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-22 12:29:12.690  5688  5734 I jxcore-log: 
,11-22 12:29:12.695  5688  5734 I jxcore-log: 2016-11-22 17:29:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-22 12:29:12.695  5688  5734 I jxcore-log: 
,11-22 12:29:13.185  5688  5734 I jxcore-log: 2016-11-22 17:29:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-22 12:29:13.185  5688  5734 I jxcore-log: 
,11-22 12:29:13.230  5688  5734 I jxcore-log: 2016-11-22 17:29:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-22 12:29:13.230  5688  5734 I jxcore-log: 
,11-22 12:29:13.244  5688  5734 I jxcore-log: 2016-11-22 17:29:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-22 12:29:13.244  5688  5734 I jxcore-log: 
,11-22 12:29:13.248  5688  5734 I jxcore-log: 2016-11-22 17:29:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-22 12:29:13.248  5688  5734 I jxcore-log: 
,11-22 12:29:13.520  5688  5734 I jxcore-log: 2016-11-22 17:29:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-22 12:29:13.520  5688  5734 I jxcore-log: 
,11-22 12:29:13.651  5688  5734 I jxcore-log: 2016-11-22 17:29:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-22 12:29:13.651  5688  5734 I jxcore-log: 
,11-22 12:29:14.027  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-22 12:29:14.027  5688  5734 I jxcore-log: 
,11-22 12:29:14.035  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-22 12:29:14.035  5688  5734 I jxcore-log: 
,11-22 12:29:14.039  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-22 12:29:14.039  5688  5734 I jxcore-log: 
,11-22 12:29:14.044  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-22 12:29:14.044  5688  5734 I jxcore-log: 
,11-22 12:29:14.049  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-22 12:29:14.049  5688  5734 I jxcore-log: 
,11-22 12:29:14.077  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-22 12:29:14.077  5688  5734 I jxcore-log: 
,11-22 12:29:14.113  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-22 12:29:14.113  5688  5734 I jxcore-log: 
,11-22 12:29:14.121  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-22 12:29:14.121  5688  5734 I jxcore-log: 
,11-22 12:29:14.127  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-22 12:29:14.127  5688  5734 I jxcore-log: 
,11-22 12:29:14.143  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-22 12:29:14.143  5688  5734 I jxcore-log: 
,11-22 12:29:14.159  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-22 12:29:14.159  5688  5734 I jxcore-log: 
,11-22 12:29:14.165  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-22 12:29:14.165  5688  5734 I jxcore-log: 
,11-22 12:29:14.170  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-22 12:29:14.170  5688  5734 I jxcore-log: 
,11-22 12:29:14.183  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-22 12:29:14.183  5688  5734 I jxcore-log: 
,11-22 12:29:14.201  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-22 12:29:14.201  5688  5734 I jxcore-log: 
,11-22 12:29:14.215  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-22 12:29:14.215  5688  5734 I jxcore-log: 
,11-22 12:29:14.226  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-22 12:29:14.226  5688  5734 I jxcore-log: 
,11-22 12:29:14.239  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-22 12:29:14.239  5688  5734 I jxcore-log: 
,11-22 12:29:14.249  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-22 12:29:14.249  5688  5734 I jxcore-log: 
,11-22 12:29:14.260  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-22 12:29:14.260  5688  5734 I jxcore-log: 
,11-22 12:29:14.269  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-22 12:29:14.269  5688  5734 I jxcore-log: 
,11-22 12:29:14.275  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-22 12:29:14.275  5688  5734 I jxcore-log: 
,11-22 12:29:14.294  5688  5734 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-22 12:29:14.295  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO testUtils: 'BLE multiple advertisement supported'
11-22 12:29:14.295  5688  5734 I jxcore-log: 
,11-22 12:29:14.325  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-22 12:29:14.325  5688  5734 I jxcore-log: 
,11-22 12:29:14.542  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - DEBUG CoordinatedClient: 'connected to the test server'
11-22 12:29:14.542  5688  5734 I jxcore-log: 
,11-22 12:29:14.805  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-22 12:29:14.805  5688  5734 I jxcore-log: 
,11-22 12:29:14.809  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - DEBUG CoordinatedClient: 'test client failed'
11-22 12:29:14.809  5688  5734 I jxcore-log: 
,11-22 12:29:14.813  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-22 12:29:14.813  5688  5734 I jxcore-log: 
,11-22 12:29:14.818  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:190:20
11-22 12:29:14.818  5688  5734 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-22 12:29:14.818  5688  5734 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-22 12:29:14.818  5688  5734 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-22 12:29:14.818  5688  5734 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-22 12:29:14.818  5688  5734 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-22 12:29:14.818  5688  5734 I jxcore-log: 
,11-22 12:29:14.819  5688  5734 I jxcore-log: 2016-11-22 17:29:14 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-22 12:29:14.819  5688  5734 I jxcore-log: 
,11-22 12:29:14.881   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:29:15.294  6043  6043 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-22 12:29:15.299  6043  6043 D AndroidRuntime: CheckJNI is OFF
,11-22 12:29:15.331  6043  6043 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-22 12:29:15.365  6043  6043 I Radio-JNI: register_android_hardware_Radio DONE
,11-22 12:29:15.382  6043  6043 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-22 12:29:15.395   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-22 12:29:15.396   927   940 I ActivityManager: Killing 5688:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-22 12:29:15.492   927  3645 I WindowState: WIN DEATH: Window{da060e5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-22 12:29:15.492   927  3040 D WifiService: Client connection lost with reason: 4
11-22 12:29:15.492   927  3221 D GraphicsStats: Buffer count: 2
,11-22 12:29:15.551   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-22 12:29:15.553   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-22 12:29:15.553   927   940 E ActivityManager: Failure starting process com.test.thalitest
11-22 12:29:15.553   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-22 12:29:15.553   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:29:15.553   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:29:15.553   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 12:29:15.553   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-22 12:29:15.554   927   940 I ActivityManager:   Force finishing activity ActivityRecord{8d6e449 u0 com.test.thalitest/.MainActivity t10}
,11-22 12:29:15.559   927  3941 W ActivityManager: Spurious death for ProcessRecord{f0d5a7e 0:com.test.thalitest/u0a77}, curProc for 5688: null
,11-22 12:29:15.561   927   950 I art     : Starting a blocking GC Explicit
,11-22 12:29:15.563   927   945 W WindowManager: Attempted to add application window with unknown token Token{683a14e ActivityRecord{8d6e449 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-22 12:29:15.563   927   945 W WindowManager: Token{683a14e ActivityRecord{8d6e449 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{683a14e ActivityRecord{8d6e449 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-22 12:29:15.564   927   945 W WindowManager: view not successfully added to wm, removing view
11-22 12:29:15.564   927   945 W WindowManager: Exception when adding starting window
11-22 12:29:15.564   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{45d0171 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-22 12:29:15.564   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-22 12:29:15.564   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-22 12:29:15.564   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-22 12:29:15.564   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-22 12:29:15.564   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-22 12:29:15.564   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:29:15.564   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:29:15.564   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 12:29:15.564   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-22 12:29:15.649   927   950 I art     : Explicit concurrent mark sweep GC freed 53230(3MB) AllocSpace objects, 10(356KB) LOS objects, 33% free, 29MB/43MB, paused 1.695ms total 87.029ms
,11-22 12:29:15.671   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-22 12:29:15.674  6043  6043 I art     : System.exit called, status: 0
,11-22 12:29:15.674  6043  6043 I AndroidRuntime: VM exiting with result code 0.
,11-22 12:29:15.679   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-22 12:29:15.691   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-22 12:29:15.693  3754  3754 I Keyboard.Facilitator: resetDictionaries() : en_US
11-22 12:29:15.694  5938  5938 D BluetoothMapAppObserver: onReceive
11-22 12:29:15.695  5938  5938 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-22 12:29:15.698   927  3003 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-22 12:29:15.699  4209  4260 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-22 12:29:15.745  3874  3874 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-22 12:29:15.753  3646  3646 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-22 12:29:15.753  3646  3646 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-22 12:29:15.752    27    27 W kworker/2:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 12:29:15.755    27    27 W kworker/2:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 12:29:15.762    27    27 W kworker/2:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 12:29:15.769   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-22 12:29:15.774  3754  6054 I Keyboard.Facilitator.DecoderInitializer: run()
11-22 12:29:15.774  3754  6054 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
11-22 12:29:15.774  3754  6054 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
11-22 12:29:15.774  3754  6054 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
11-22 12:29:15.774  3754  6054 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
11-22 12:29:15.774  3754  6054 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
11-22 12:29:15.774  3754  6054 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,11-22 12:29:15.776  3459  6056 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-22 12:29:15.777  4005  6060 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-22 12:29:15.777  4005  6060 D AccountUtils: Clearing selected account for com.test.thalitest
,11-22 12:29:15.782  3754  6054 I Decoder : createOrResetDecoder
,11-22 12:29:15.790  4005  6060 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-22 12:29:15.795   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-22 12:29:15.795  3900  4004 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-22 12:29:15.796   927   939 E PackageManager: Failed to write settings, restoring backup
11-22 12:29:15.796   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-22 12:29:15.796   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-22 12:29:15.796   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-22 12:29:15.796   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-22 12:29:15.796   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-22 12:29:15.796   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:29:15.796   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:29:15.796   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 12:29:15.801   927   940 E DropBoxManagerService: Can't write: system_server_wtf
11-22 12:29:15.801   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-22 12:29:15.801   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 12:29:15.801   927   940 E DropBoxManagerService: 	... 13 more
,11-22 12:29:15.810   927  3941 I ActivityManager: Start proc 6064:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-22 12:29:15.811  3900  4004 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-22 12:29:15.811  3900  4004 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3900
11-22 12:29:15.811  3900  4004 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:29:15.811  3900  4004 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 12:29:15.815   927  3222 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-22 12:29:15.815   927  6074 E DropBoxManagerService: Can't write: system_app_crash
11-22 12:29:15.815   927  6074 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 12:29:15.815   927  6074 E DropBoxManagerService: 	... 5 more
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:29:15.816  4005  6060 E SQLiteDataba,se: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:29:15.816  4005  6060 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 12:29:15.818  3900  4004 I Process : Sending signal. PID: 3900 SIG: 9
,11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-22 12:29:15.816  4005  6060 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 12:29:15.827  4005  6060 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-22 12:29:15.851  3646  3646 I ConfigService: onCreate
,11-22 12:29:15.853  3646  6078 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-22 12:29:15.853  3646  6078 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-22 12:29:15.854  3646  6078 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-22 12:29:15.857  3646  6078 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-22 12:29:15.881   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 12:29:15.878  3754  6054 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-22 12:29:15.914   927  3002 W InputDispatcher: channel 'c0cf45b com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-22 12:29:15.914   927  3002 E InputDispatcher: channel 'c0cf45b com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-22 12:29:15.915   927  3931 I WindowState: WIN DEATH: Window{c0cf45b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
11-22 12:29:15.915   927   937 D GraphicsStats: Buffer count: 1
11-22 12:29:15.915   927  3931 W InputDispatcher: Attempted to unregister already unregistered input channel 'c0cf45b com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-22 12:29:15.932   927   937 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3900) has died
11-22 12:29:15.933   927   937 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-22 12:29:15.938   927   945 E WindowState: getStack: Window{c0cf45b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{c3db544 token=Token{c599657 ActivityRecord{fb0d3d6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
11-22 12:29:15.938   927   945 E WindowState: getStack: Window{c0cf45b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{c3db544 token=Token{c599657 ActivityRecord{fb0d3d6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
,11-22 12:29:15.939   927   945 E WindowState: getStack: Window{c0cf45b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{c3db544 token=Token{c599657 ActivityRecord{fb0d3d6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
11-22 12:29:15.939   927   945 E WindowState: getStack: Window{c0cf45b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{c3db544 token=Token{c599657 ActivityRecord{fb0d3d6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
11-22 12:29:15.939   927   945 E WindowState: getStack: Window{c0cf45b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{c3db544 token=Token{c599657 ActivityRecord{fb0d3d6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
11-22 12:29:15.939   927   945 E WindowState: getStack: Window{c0cf45b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{c3db544 token=Token{c599657 ActivityRecord{fb0d3d6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,11-22 12:29:15.957  4005  6081 I GMPM-SVC: App measurement is starting up
,11-22 12:29:15.961  4005  6081 E GMPM-SVC: AppMeasurementService not registered/enabled
11-22 12:29:15.962  4005  6081 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-22 12:29:16.160   385   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
