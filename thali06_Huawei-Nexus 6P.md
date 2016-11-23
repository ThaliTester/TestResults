#### Test 9418709429da646_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 03:55:16.988  5627  5653 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.46
11-23 03:55:17.025  5627  5670 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
11-23 03:55:17.230   927   938 I ActivityManager: Killing 5327:org.codeaurora.ims/1001 (adj 15): empty #17
11-23 03:55:17.399  5627  5679 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-23 03:55:17.425  4001  4001 I ConfigFetchService: fetch service done; releasing wakelock
11-23 03:55:17.426  4001  4001 I ConfigFetchService: stopping self
11-23 03:55:17.431  5676  5676 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 03:55:17.434  5676  5676 D AndroidRuntime: CheckJNI is OFF
11-23 03:55:17.457  5676  5676 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 03:55:17.460  4001  4990 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-23 03:55:17.487  5676  5676 I Radio-JNI: register_android_hardware_Radio DONE
11-23 03:55:17.502  5676  5676 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-23 03:55:17.505   927  3198 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 03:55:17.506  5627  5679 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-23 03:55:17.542   927  3198 I ActivityManager: Start proc 5693:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 03:55:17.547  5676  5676 D AndroidRuntime: Shutting down VM
11-23 03:55:17.550  5627  5679 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-23 03:55:17.868   927  3848 I WindowManager: Screenshot max retries 4 of Token{d5ace5e ActivityRecord{2a95b99 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{5d1e4d1 u0 Starting com.test.thalitest} drawState=2
,11-23 03:55:17.913  4001  4990 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,11-23 03:55:17.951  5693  5693 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-23 03:55:17.980  5693  5693 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-23 03:55:18.041  5693  5693 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 9981-36)
,11-23 03:55:18.041  5693  5693 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 03:55:18.085  5693  5693 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {db78290}
,11-23 03:55:18.085  5693  5693 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 03:55:18.085  5693  5693 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 03:55:18.089  5693  5693 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 03:55:18.090  5693  5693 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 03:55:18.140  5693  5693 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 03:55:18.148  5693  5693 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 03:55:18.148  5693  5693 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 03:55:18.148  5693  5693 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 03:55:18.148  5693  5693 I Adreno  : Build Date                       : 12/06/15
11-23 03:55:18.148  5693  5693 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 03:55:18.148  5693  5693 I Adreno  : Local Branch                     : mybranch17112971
11-23 03:55:18.148  5693  5693 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 03:55:18.148  5693  5693 I Adreno  : Remote Branch                    : NONE
11-23 03:55:18.148  5693  5693 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 03:55:18.202   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5248b3c:true
,11-23 03:55:18.219   737   737 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23319]" dev="sockfs" ino=23319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 03:55:18.222   737   737 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[23319]" dev="sockfs" ino=23319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 03:55:18.233  5693  5693 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 03:55:18.242  5693  5693 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 03:55:18.269   737   737 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34098]" dev="sockfs" ino=34098 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 03:55:18.269   737   737 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34098]" dev="sockfs" ino=34098 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 03:55:18.272  5693  5730 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 03:55:18.272  3848  3848 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13987]" dev="sockfs" ino=13987 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 03:55:18.272  3848  3848 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[13987]" dev="sockfs" ino=13987 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 03:55:18.279  5693  5717 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 03:55:18.307  5693  5730 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 03:55:18.383   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +514ms (total +864ms)
,11-23 03:55:18.416  5693  5693 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5693
,11-23 03:55:18.511  5693  5693 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-23 03:55:18.729  5693  5733 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -606340816
,11-23 03:55:18.733  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 03:55:18.733  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 03:55:18.733  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 03:55:18.733  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 03:55:18.733  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-23 03:55:18.733  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@545b926 added. We now have 1 listener(s)
,11-23 03:55:18.736  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-23 03:55:18.736  5693  5733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 03:55:18.737  5693  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:55:18.737  5693  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-23 03:55:18.739  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd5f7bd added. We now have 1 listener(s)
,11-23 03:55:18.739  5693  5733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:55:18.751   927  3020 D WifiService: New client listening to asynchronous messages
,11-23 03:55:18.765  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 03:55:18.765  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 03:55:18.765  5693  5733 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 03:55:18.765  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 03:55:18.765  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 03:55:18.765  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 03:55:18.765  5693  5733 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-23 03:55:18.767  5693  5733 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 03:55:18.901  5693  5693 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-23 03:55:19.244  5693  5700 I art     : Background sticky concurrent mark sweep GC freed 77020(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.528ms total 276.100ms
,11-23 03:55:19.412   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:55:20.414  5693  5700 I art     : Background partial concurrent mark sweep GC freed 51476(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.040ms total 203.469ms
,11-23 03:55:20.636  5693  5739 W jxcore-log: Initializing JXcore engine
11-23 03:55:20.636  5693  5739 W jxcore-log: JXcore engine is ready
,11-23 03:55:20.659  5739  5739 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12487 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 03:55:20.659  5739  5739 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13507]" dev="sockfs" ino=13507 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-23 03:55:20.659  5739  5739 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-23 03:55:20.659  5739  5739 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34069]" dev="sockfs" ino=34069 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 03:55:20.669  5693  5739 W jxcore-log: Starting JXcore engine
,11-23 03:55:20.719  5693  5739 W jxcore-log: Platform android
11-23 03:55:20.719  5693  5739 W jxcore-log: 
,11-23 03:55:20.719  5693  5739 W jxcore-log: Process ARCH arm
11-23 03:55:20.719  5693  5739 W jxcore-log: 
,11-23 03:55:20.898  5693  5739 I jxcore-log: JXcore Cordova bridge is ready!
11-23 03:55:20.898  5693  5739 I jxcore-log: 
,11-23 03:55:20.899  5693  5739 W jxcore-log: JXcore engine is started
,11-23 03:55:20.911  5693  5733 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 03:55:20.917  5693  5693 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 03:55:22.085   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:22.436  3622  3622 I ConfigService: onDestroy
,11-23 03:55:23.086   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:24.087   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:25.088   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:26.089   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:27.090   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 03:55:30.563  5693  5739 I jxcore-log: 2016-11-23 08:55:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 03:55:30.563  5693  5739 I jxcore-log: 
,11-23 03:55:30.565  5693  5739 I jxcore-log: 2016-11-23 08:55:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 03:55:30.565  5693  5739 I jxcore-log: 
,11-23 03:55:30.572  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 03:55:30.573  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 03:55:30.574  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 03:55:30.575  5693  5739 I jxcore-log: 2016-11-23 08:55:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 03:55:30.575  5693  5739 I jxcore-log: 
,11-23 03:55:30.576  5693  5739 I jxcore-log: 2016-11-23 08:55:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 03:55:30.576  5693  5739 I jxcore-log: 
,11-23 03:55:30.817  5693  5739 I jxcore-log: 2016-11-23 08:55:30 - DEBUG UnitTest_app: 'Running unit tests'
11-23 03:55:30.817  5693  5739 I jxcore-log: 
,11-23 03:55:30.818  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:55:30.818  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd67d2e added. We now have 2 listener(s)
11-23 03:55:30.818  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:55:30.818  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:55:30.818  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:55:30.819  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:55:30.819  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40b80cf added. We now have 2 listener(s)
11-23 03:55:30.819  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:55:30.830  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 03:55:30.831  5693  5739 D executeNativeTests: Running unit tests
,11-23 03:55:30.869  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 03:55:30.869  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c added. We now have 3 listener(s)
11-23 03:55:30.869  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:55:30.870  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:55:30.870  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 03:55:30.870  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:55:30.870  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 added. We now have 3 listener(s)
11-23 03:55:30.870  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:55:30.870  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 03:55:30.872  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 03:55:30.872  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 03:55:30.872  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 03:55:30.872  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 03:55:30.873  5693  5739 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 03:55:30.873  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 03:55:30.873  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 03:55:30.873  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 03:55:30.873  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 03:55:30.873  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 03:55:30.873  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:30.873  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:30.873  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:30.873  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:30.874  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:30.874  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:55:30.874  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c removed from the list
,11-23 03:55:30.874  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:30.874  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 removed from the list
11-23 03:55:30.874  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:30.874  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.874  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.875  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.875  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.875  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:30.875  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:30.875  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:30.875  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:30.875  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:30.876  5693  5739 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 03:55:30.876  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:30.876  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 03:55:30.876  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:30.876  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:30.876  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:30.876  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:30.876  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:30.876  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:30.876  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:30.876  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.876  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:30.877  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.877  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.877  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.877  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:30.877  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:30.877  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:30.877  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 03:55:30.879  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 03:55:30.880  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 03:55:30.880  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:30.880  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:30.880  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:30.880  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:30.880  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:30.880  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:30.881  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:30.881  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:30.881  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:30.881  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.881  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.881  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.881  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.881  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.881  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:30.881  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:30.881  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:30.881  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:30.882  5693  5739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 03:55:30.883  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:55:30.883  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 03:55:30.886  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 03:55:30.887  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 03:55:30.887  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 03:55:30.887  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:55:30.887  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 03:55:30.887  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 03:55:30.887  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:55:30.887  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 03:55:30.889  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 03:55:30.889  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 03:55:30.889  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 03:55:30.889  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:55:30.891  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:30.891  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 03:55:30.891  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:55:30.892  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 03:55:30.892  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 03:55:30.892  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 03:55:30.893  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-23 03:55:30.894  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-23 03:55:30.894  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.894  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 03:55:30.894  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 03:55:30.894  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 03:55:30.895  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 03:55:30.895  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.895  5693  5739 D BluetoothAdapter: STATE_ON
,11-23 03:55:30.898  4639  4653 D BtGatt.GattService: registerClient() - UUID=49838bc8-372d-4ae7-8a5b-38bf75824c57
,11-23 03:55:30.898  4639  4725 D BtGatt.GattService: onClientRegistered() - UUID=49838bc8-372d-4ae7-8a5b-38bf75824c57, clientIf=5
11-23 03:55:30.899  5693  5702 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 03:55:30.899  4639  4871 D BtGatt.GattService: start scan with filters
11-23 03:55:30.902  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 03:55:30.902  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.903  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 03:55:30.903  4639  4731 D BtGatt.ScanManager: handling starting scan
11-23 03:55:30.903  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.903  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 03:55:30.903  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 03:55:30.903  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:55:30.903  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 03:55:30.903  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 03:55:30.903  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:55:30.903  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 03:55:30.903  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 03:55:30.903  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.904  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:55:30.904  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 03:55:30.905  4639  4731 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:55:30.907  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:30.907  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:55:30.907  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:30.907  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:30.907  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 03:55:30.907  5693  5739 I io.jxcore.node.ConnectionHelper: start: OK
11-23 03:55:30.909  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:55:30.909  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:30.909  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:30.909  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 03:55:30.912  4639  4725 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-23 03:55:30.912  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:30.912  4639  4731 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 03:55:30.917  4639  4725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 03:55:30.917  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:30.918  4639  4731 D BtGatt.ScanManager: Starting BLE batch scan
,11-23 03:55:30.918  4639  4731 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 03:55:30.927  4639  4725 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 03:55:30.927  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:55:30.932  4639  4725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 03:55:30.932  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:55:30.989  4882  4919 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-23 03:55:30.991  4882  4882 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-23 03:55:30.994   927  3463 I ActivityManager: Killing 5352:com.android.settings/1000 (adj 15): empty #17
,11-23 03:55:31.411  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 03:55:31.411  5693  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:55:31.411  5693  5693 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 03:55:35.911  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 03:55:35.912  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:35.912  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 03:55:35.912  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 03:55:35.912  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 03:55:35.912  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:35.912  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 03:55:35.913  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 03:55:35.913  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.913  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 03:55:35.913  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 03:55:35.914  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.914  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.914  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.914  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-23 03:55:35.914  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:35.915  5693  5739 D BluetoothAdapter: STATE_ON
,11-23 03:55:35.916  4639  4653 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 03:55:35.916  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 03:55:35.917  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:55:35.918  4639  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 03:55:35.918  4639  4652 D BtGatt.GattService: stopScan() - queue size =1
11-23 03:55:35.919  4639  4851 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 03:55:35.919  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 03:55:35.919  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:35.919  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 03:55:35.920  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.920  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.920  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.920  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.920  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 03:55:35.920  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.921  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:35.921  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.921  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 03:55:35.921  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 03:55:35.922  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:55:35.922  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.927  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.927  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:35.928  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:35.928  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:35.928  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:35.928  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:55:35.928  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:55:35.928  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:35.928  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:35.928  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:35.928  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:35.928  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:35.929  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:35.929  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:55:35.929  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 03:55:35.929  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 03:55:35.929  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 03:55:35.929  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 03:55:35.929  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 03:55:35.929  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:55:35.930  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-23 03:55:35.930  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:55:35.930  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:35.930  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 03:55:35.938  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 03:55:35.941  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:55:35.941  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:35.941  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 03:55:35.944  4639  4639 D BtGatt.ScanManager: awakened up at time 97939
,11-23 03:55:35.959  4639  4725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
11-23 03:55:35.959  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:35.959  4639  4725 D BtGatt.GattService: current time is 97955574490
11-23 03:55:35.960  4639  4725 D BtGatt.GattService: Batch record : [53, 33, -121, 80, 73, -44, 1, 0, -100, 98, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 23, -74, 94, 3, 2, -25, 21, 63, -4, 37, 32, 28, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 35, 97, 126, -92, 22, -56, 1, -128, -70, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 50, -35, 86, -77, -92, -11, 1, -128, -98, 92, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 78, 113, 94, 3, 2, -33, 21, 61, 115, -57, -69, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -76, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -77, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, 57, 25, -57, 101, -38, 1, 0, -93, 77, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, -75, 111, 94, 3, 3, -12, 24, 62, -87, 67, -127, 28, 6, 8, 116, 105, 115, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 37, -47, 14, -113, 116, -46, 1, -128, -75, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-23 03:55:35.962  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 23, -74, 94, 3, 2, -25, 21, 63, -4, 37, 32, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 03:55:35.963  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 03:55:35.963  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 78, 113, 94, 3, 2, -33, 21, 61, 115, -57, -69]
11-23 03:55:35.963  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-23 03:55:35.963  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-23 03:55:35.963  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 03:55:35.964  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 03:55:35.965  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, -75, 111, 94, 3, 3, -12, 24, 62, -87, 67, -127, 6, 8, 116, 105, 115, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 03:55:35.965  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 03:55:35.965  4639  4725 E BtGatt.ContextMap: Context not found for ID 5
11-23 03:55:35.972  4639  4725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 03:55:35.972  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:35.973  4639  4731 D BtGatt.ScanManager: stopping BLe Batch
11-23 03:55:35.978  4639  4725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 03:55:35.978  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:35.978  4639  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 03:55:35.983  4639  4725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:55:35.983  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:55:36.432  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 03:55:36.619   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 03:55:39.644   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 03:55:40.931  5693  5739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 03:55:40.938  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:55:40.938  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 03:55:40.951  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 03:55:40.954  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 03:55:40.955  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 03:55:40.955  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:55:40.955  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 03:55:40.955  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 03:55:40.955  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:55:40.955  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 03:55:40.960  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:55:40.963  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 03:55:40.963  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 03:55:40.963  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 03:55:40.965  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:55:40.970  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:40.970  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 03:55:40.971  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 03:55:40.972  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 03:55:40.972  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 03:55:40.977  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:40.977  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-23 03:55:40.977  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-23 03:55:40.977  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 03:55:40.977  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 03:55:40.978  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:40.979  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:55:40.982  4639  4653 D BtGatt.GattService: registerClient() - UUID=80bf516f-7072-4ed4-bb59-86685a6ab030
11-23 03:55:40.982  4639  4725 D BtGatt.GattService: onClientRegistered() - UUID=80bf516f-7072-4ed4-bb59-86685a6ab030, clientIf=5
11-23 03:55:40.983  5693  5704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 03:55:40.984  4639  4851 D BtGatt.GattService: start scan with filters
,11-23 03:55:40.986  3500  3500 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-23 03:55:40.988  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 03:55:40.988  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:40.989  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 03:55:40.989  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:40.989  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 03:55:40.989  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 03:55:40.989  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:55:40.989  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 03:55:40.989  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 03:55:40.989  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:55:40.990   927  3464 I ActivityManager: Killing 5127:com.google.android.apps.maps/u0a58 (adj 15): empty #17
11-23 03:55:40.989  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 03:55:40.990  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:55:40.991  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 03:55:40.991  4639  4731 D BtGatt.ScanManager: handling starting scan
11-23 03:55:40.991  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 03:55:40.991  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:40.995  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:40.995  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:55:40.995  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:40.996  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:40.996  5693  5739 I io.jxcore.node.ConnectionHelper: start: OK
11-23 03:55:40.996  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 03:55:41.000  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.000  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.000  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.000  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 03:55:41.000  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:41.000  5693  5739 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 03:55:41.000  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:41.000  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 03:55:41.001  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:55:41.001  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 03:55:41.001  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:41.001  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 03:55:41.001  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 03:55:41.001  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.001  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 03:55:41.001  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 03:55:41.002  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.002  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.002  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.002  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-23 03:55:41.002  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.003  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:55:41.003  4639  4871 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 03:55:41.003  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 03:55:41.004  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:55:41.005  4639  4653 D BtGatt.GattService: stopScan() - queue size =1
11-23 03:55:41.006  4639  4652 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 03:55:41.006  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.007  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.007  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.007  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 03:55:41.007  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-23 03:55:41.028  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:55:41.028  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:41.030  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:41.030  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:41.030  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.030  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.030  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:41.030  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:55:41.030  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:55:41.030  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:41.030  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:41.031  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:41.031  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:41.031  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:41.031  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 03:55:41.031  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:41.031  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:41.031  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 03:55:41.031  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.031  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 03:55:41.031  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 03:55:41.031  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.031  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.031  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.032  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.032  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 03:55:41.032  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:41.032  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.032  4639  4725 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 03:55:41.032  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.032  4639  4731 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 03:55:41.033  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.033  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.033  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.033  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:41.033  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:41.033  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:41.033  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:41.034  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.034  5693  5739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 03:55:41.035  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.035  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.035  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.037  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:55:41.037  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 03:55:41.039  4639  4725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 03:55:41.039  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.039  4639  4731 D BtGatt.ScanManager: Starting BLE batch scan
11-23 03:55:41.039  4639  4731 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 03:55:41.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 03:55:41.045  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 03:55:41.045  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 03:55:41.045  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:55:41.045  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 03:55:41.045  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 03:55:41.045  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:55:41.045  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 03:55:41.048  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:55:41.050  4639  4725 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 03:55:41.050  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.051  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:55:41.054  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 03:55:41.054  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 03:55:41.054  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 03:55:41.056  4639  4725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 03:55:41.056  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.058  4639  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 03:55:41.061  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.061  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 03:55:41.061  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 03:55:41.062  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 03:55:41.062  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 03:55:41.063  4639  4725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:55:41.063  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.064  4639  4725 E BtGatt.ContextMap: Context not found for ID 5
11-23 03:55:41.065  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.065  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 03:55:41.065  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 03:55:41.065  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 03:55:41.066  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 03:55:41.066  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.066  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:55:41.069  4639  4652 D BtGatt.GattService: registerClient() - UUID=a2a0f7d9-1336-451e-bcc5-a4ce0496b3ad
11-23 03:55:41.070  4639  4725 D BtGatt.GattService: onClientRegistered() - UUID=a2a0f7d9-1336-451e-bcc5-a4ce0496b3ad, clientIf=5
,11-23 03:55:41.070  5693  5702 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 03:55:41.071  4639  4725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 03:55:41.071  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.071  4639  4731 D BtGatt.ScanManager: stopping BLe Batch
11-23 03:55:41.071  4639  4653 D BtGatt.GattService: start scan with filters
11-23 03:55:41.075  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 03:55:41.075  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.075  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 03:55:41.075  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.075  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 03:55:41.075  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 03:55:41.075  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.075  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 03:55:41.075  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 03:55:41.075  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.075  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.075  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.075  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.076  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 03:55:41.076  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.077  4639  4725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 03:55:41.077  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.077  4639  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 03:55:41.079  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.079  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:55:41.079  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.079  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:41.079  5693  5739 I io.jxcore.node.ConnectionHelper: start: OK
11-23 03:55:41.079  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.082  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.082  4639  4725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:55:41.082  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.082  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.082  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:41.082  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:55:41.083  4639  4731 D BtGatt.ScanManager: handling starting scan
11-23 03:55:41.089  4639  4725 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 03:55:41.089  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.089  4639  4731 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 03:55:41.093  4639  4725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 03:55:41.094  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.094  4639  4731 D BtGatt.ScanManager: Starting BLE batch scan
11-23 03:55:41.094  4639  4731 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 03:55:41.102  4639  4725 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 03:55:41.102  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:41.106  4639  4725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 03:55:41.106  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:55:41.584  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 03:55:41.584  5693  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:55:41.584  5693  5693 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 03:55:42.672   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 03:55:45.695   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 03:55:46.079  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 03:55:46.080  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 03:55:46.080  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 03:55:46.080  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:55:46.080  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 03:55:46.081  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 03:55:46.081  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 03:55:46.081  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 03:55:46.081  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.081  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 03:55:46.081  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 03:55:46.082  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.082  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.082  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.082  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 03:55:46.083  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:46.085  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:55:46.086  4639  4653 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 03:55:46.086  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 03:55:46.088  4639  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 03:55:46.088  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:55:46.089  4639  4871 D BtGatt.GattService: stopScan() - queue size =1
11-23 03:55:46.091  4639  4652 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 03:55:46.092  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 03:55:46.092  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.092  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 03:55:46.092  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.092  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.093  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.093  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.093  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 03:55:46.093  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.093  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.094  4639  4639 D BtGatt.ScanManager: awakened up at time 108089
11-23 03:55:46.094  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.094  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 03:55:46.094  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 03:55:46.100  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:55:46.100  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:46.102  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.102  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:46.102  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.102  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:46.102  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:46.102  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:46.103  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 03:55:46.103  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.103  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 03:55:46.103  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 03:55:46.103  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.103  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.103  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.103  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:46.103  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.103  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.105  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.105  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:55:46.105  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 03:55:46.112  4639  4725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-23 03:55:46.112  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:46.112  4639  4725 D BtGatt.GattService: current time is 108108416327
11-23 03:55:46.113  4639  4725 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -74, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -73, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -75, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -75, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -74, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -71, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 03:55:46.113  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-23 03:55:46.113  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 03:55:46.113  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 03:55:46.114  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 03:55:46.114  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 03:55:46.115  4639  4725 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-23 03:55:46.121  4639  4725 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 03:55:46.121  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:55:46.121  4639  4731 D BtGatt.ScanManager: stopping BLe Batch
,11-23 03:55:46.126  4639  4725 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 03:55:46.126  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:55:46.127  4639  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 03:55:46.132  4639  4725 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 03:55:46.132  4639  4725 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:55:46.604  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 03:55:46.604  5693  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:46.605  5693  5693 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 03:55:51.104  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 03:55:51.104  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.104  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.105  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 03:55:51.105  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:55:51.105  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:55:51.105  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 03:55:51.105  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:51.106  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.106  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:51.106  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.106  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 03:55:51.113  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.113  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.116  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.116  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.116  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.116  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 03:55:51.117  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 03:55:51.117  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:55:51.117  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:51.118  5693  5739 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-23 03:55:51.120  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 03:55:51.120  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.120  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 03:55:51.121  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.121  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.122  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:51.122  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.122  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:51.122  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.122  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.122  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.125  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.125  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.125  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.125  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.125  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 03:55:51.125  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.126  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:51.128  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 03:55:51.128  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 03:55:51.128  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.128  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.128  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 03:55:51.129  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.129  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:51.129  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.129  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.129  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.129  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.130  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.132  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.133  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.133  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.133  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 03:55:51.133  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:51.133  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.133  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.135  5693  5739 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-23 03:55:51.135  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:51.135  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.135  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.136  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.136  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 03:55:51.136  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:51.136  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.136  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.136  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.137  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.137  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.140  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.140  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.140  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.140  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.140  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:51.140  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.140  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.142  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-23 03:55:51.142  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:51.142  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.142  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.143  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.143  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.143  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:51.143  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.143  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.143  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:55:51.144  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.144  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.146  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.146  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.146  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.146  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.147  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:51.147  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.147  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:51.148  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 03:55:51.148  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 03:55:51.148  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 03:55:51.148  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-23 03:55:51.148  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 03:55:51.148  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 03:55:51.148  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 03:55:51.148  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 03:55:51.148  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 03:55:51.149  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:51.149  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 03:55:51.149  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.149  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.149  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.149  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:51.149  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.149  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.149  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.149  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.149  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.153  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.153  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.153  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.153  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.153  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:51.153  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.153  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.154  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 03:55:51.155  5693  5739 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 03:55:51.155  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 03:55:51.158  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 03:55:51.159  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 03:55:51.159  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 03:55:51.160  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 03:55:51.161  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 03:55:51.161  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 03:55:51.161  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 03:55:51.162  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-23 03:55:51.162  5693  5739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 03:55:51.162  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 03:55:51.162  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 03:55:51.162  5693  5739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 03:55:51.162  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 03:55:51.162  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 03:55:51.163  5693  5739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 03:55:51.163  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-23 03:55:51.166  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-23 03:55:51.167  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,11-23 03:55:51.167  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-23 03:55:51.168  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 03:55:51.168  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 03:55:51.168  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 03:55:51.168  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 03:55:51.169  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 03:55:51.169  5693  5745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-23 03:55:51.169  5693  5745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 03:55:51.169  5693  5745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 03:55:51.169  5693  5745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-23 03:55:51.169  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:51.170  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.170  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.170  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.170  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.170  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 03:55:51.171  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:51.171  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.171  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.171  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.171  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.171  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.171  5693  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-23 03:55:51.171  5693  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-23 03:55:51.172  5693  5745 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 03:55:51.172  5693  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 03:55:51.173  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.173  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.169  4871  4871 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34211]" dev="sockfs" ino=34211 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 03:55:51.173  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.173  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.173  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:51.173  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.173  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.174  5693  5739 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-23 03:55:51.172  4871  4871 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34211]" dev="sockfs" ino=34211 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 03:55:51.175  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:51.175  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.175  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.175  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.175  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.175  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:51.175  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:55:51.175  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.175  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.175  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.176  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.176  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.177  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.177  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.177  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.177  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 03:55:51.177  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.177  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.178  5693  5739 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 03:55:51.178  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:51.179  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 03:55:51.179  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.179  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.179  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.179  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:51.179  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.179  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.179  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.180  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.180  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.181  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.181  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.181  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.181  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.181  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:51.181  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.181  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.182  5693  5739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 03:55:51.182  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,11-23 03:55:51.182  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 03:55:51.182  5693  5739 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 03:55:51.182  5693  5739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 03:55:51.182  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 03:55:51.182  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 03:55:51.182  5693  5739 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 03:55:51.182  5693  5739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 03:55:51.183  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 03:55:51.183  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-23 03:55:51.183  5693  5739 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 03:55:51.183  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:51.183  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:51.183  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:51.183  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.183  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.183  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:51.183  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.183  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.183  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:51.183  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.183  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:51.185  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.185  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.185  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:51.185  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:51.185  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:51.185  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.185  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.185  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:51.186  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:51.186  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:51.186  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:51.186  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:51.186  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:55:52.091   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-23 03:55:52.091   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 03:55:55.632   927  5453 D NetlinkSocketObserver: NeighborEvent{elapsedMs=117627, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 03:55:56.187  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:55:56.187  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:56.187  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:56.187  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 03:55:56.188  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:56.188  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 03:55:56.188  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:56.188  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 03:55:56.189  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:56.189  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 03:55:56.189  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:56.189  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:55:56.189  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:56.189  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:55:56.190  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.190  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.193  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.193  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.194  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.194  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:56.194  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 03:55:56.194  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.194  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:56.199  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-23 03:55:56.200  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:55:56.200  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 03:55:56.206  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-23 03:55:56.208  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-23 03:55:56.208  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-23 03:55:56.209  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-23 03:55:56.209  5693  5749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-23 03:55:56.209  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 03:55:56.209  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 03:55:56.209  5693  5693 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-23 03:55:56.210  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:56.210  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 03:55:56.210  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 03:55:56.210  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 03:55:56.210  5693  5749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 03:55:56.210  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 03:55:56.209  4871  4871 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31482]" dev="sockfs" ino=31482 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 03:55:56.212  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 03:55:56.212  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-23 03:55:56.212  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:56.212  5693  5693 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 03:55:56.212  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.212  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 03:55:56.213  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.213  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 03:55:56.213  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 03:55:56.213  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.214  5693  5749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 03:55:56.214  5693  5749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 03:55:56.214  5693  5749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 03:55:56.209  4871  4871 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31482]" dev="sockfs" ino=31482 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 03:55:56.216  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.216  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:56.216  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.216  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.217  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:56.217  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:56.217  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:56.217  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:55:56.217  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:56.217  5693  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 03:55:56.217  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:56.217  5693  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:56.217  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:56.217  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:56.217  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:55:56.217  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:56.218  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:55:56.218  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:56.218  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:56.218  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.218  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.221  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.222  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.222  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.222  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:56.222  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:56.222  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.222  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:56.225  5693  5739 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 03:55:56.225  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-23 03:55:56.225  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 03:55:56.225  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 03:55:56.225  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 03:55:56.226  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:56.226  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:56.226  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:56.226  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:56.226  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:56.226  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:56.226  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.227  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:56.227  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:56.227  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.227  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.230  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.231  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.231  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.231  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:56.231  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 03:55:56.231  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.231  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:56.236  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 03:55:56.236  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:56.236  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:56.237  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:56.237  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:56.237  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
11-23 03:55:56.237  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:55:56.237  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:56.237  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:56.237  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.237  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.239  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.239  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.239  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.239  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:56.239  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:56.239  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.239  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:56.241  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:55:56.241  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:55:56.241  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:55:56.241  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:55:56.242  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:55:56.242  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2bd28c not in the list
,11-23 03:55:56.242  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.242  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
11-23 03:55:56.242  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:55:56.242  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.242  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.244  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:55:56.244  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.244  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:55:56.244  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:55:56.244  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:55:56.244  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:55:56.244  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4177dd5 not in the list
,11-23 03:55:56.246  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 03:55:56.246  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 03:55:56.246  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-23 03:55:56.246  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-23 03:55:56.246  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 03:55:56.246  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-23 03:55:56.249  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-23 03:55:56.249  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 03:55:56.250  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 03:55:56.250  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 03:55:56.250  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-23 03:55:56.250  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 03:55:56.250  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 03:55:56.250  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-23 03:55:56.251  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-23 03:55:56.251  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 03:55:56.251  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 03:55:56.251  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 03:55:56.252  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-23 03:55:56.252  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-23 03:55:56.253  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:55:56.253  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce4619a added. We now have 3 listener(s)
11-23 03:55:56.253  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:55:56.255  5693  5739 D BluetoothAdapter: enable(): BT is already enabled..!
,11-23 03:55:56.255   927  3209 D WifiService: setWifiEnabled: true pid=5693, uid=10077
11-23 03:55:56.255   927  3209 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 03:55:56.300  4639  4831 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-23 03:55:56.301  4639  4848 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-23 03:55:56.301  5693  5745 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-23 03:55:56.301  5693  5745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 03:55:56.302  5693  5745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-23 03:55:56.718  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 03:55:57.092   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:58.093   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:59.094   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:55:59.418   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:56:00.094   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:01.095   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:01.262  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 03:56:01.262  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a16aacb added. We now have 4 listener(s)
,11-23 03:56:01.262  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:56:01.275  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:01.275  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a16aacb removed from the list
11-23 03:56:01.275  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:56:01.277  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:01.277  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b2c2a8 added. We now have 4 listener(s)
11-23 03:56:01.277  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:01.280  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:01.280  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b2c2a8 removed from the list
11-23 03:56:01.280  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:56:01.282  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 03:56:01.282  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45c41c1 added. We now have 4 listener(s)
11-23 03:56:01.282  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:56:01.287   927  4282 D WifiService: setWifiEnabled: false pid=5693, uid=10077
,11-23 03:56:01.287   927  4282 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 03:56:01.292   927  3019 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 03:56:01.292   927  3019 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 03:56:01.292   927  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 03:56:01.293   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 03:56:01.301  4639  4717 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 03:56:01.301  4639  4717 D BluetoothAdapterProperties: Setting state to 13
,11-23 03:56:01.301  4639  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 03:56:01.301  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:56:01.302  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 03:56:01.303  4639  4717 D BluetoothAdapterProperties: onBluetoothDisable()
,11-23 03:56:01.305  4639  4717 I BluetoothAdapterState: Entering PendingCommandState
11-23 03:56:01.309  4639  4725 D BluetoothAdapterProperties: Scan Mode:20
11-23 03:56:01.310  4639  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 03:56:01.312  4639  4639 D BluetoothMapService: onReceive
11-23 03:56:01.313  4639  4639 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-23 03:56:01.313  4639  4639 D BluetoothMapService: STATE_TURNING_OFF
11-23 03:56:01.313  4639  4639 D BluetoothMapService: MAP Service closeService in
11-23 03:56:01.313  4639  4639 D BluetoothMapMasInstance0: MAP Service shutdown
,11-23 03:56:01.313  4639  4639 D ObexServerSockets0: shutdown(block = true)
11-23 03:56:01.314  4639  4874 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-23 03:56:01.314  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:01.314  4639  4639 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 03:56:01.315  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 03:56:01.315  4639  4639 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 03:56:01.315  4639  4848 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 03:56:01.315  4639  4875 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 03:56:01.316   927  5454 D DhcpClient: Clearing IP address
11-23 03:56:01.316   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 03:56:01.316  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 03:56:01.317  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 03:56:01.318  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 03:56:01.318  4639  4639 I BtOppRfcommListener: stopping Accept Thread
11-23 03:56:01.319  4639  5384 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-23 03:56:01.322  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:01.324  4639  5384 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 03:56:01.325  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:01.328   507   920 D CommandListener: Setting iface cfg
11-23 03:56:01.328  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:01.331  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:01.331  3622  5509 V NativeCrypto: Read error: ssl=0x7f9a746180: I/O error during system call, Connection timed out
11-23 03:56:01.333  3622  5509 V NativeCrypto: SSL shutdown failed: ssl=0x7f9a746180: I/O error during system call, Broken pipe
,11-23 03:56:01.335   927   938 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-23 03:56:01.336   927  5452 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-23 03:56:01.339   927  5452 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-23 03:56:01.339   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-23 03:56:01.339   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 03:56:01.340   927  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-23 03:56:01.346   927   940 I ActivityManager: Start proc 5753:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-23 03:56:01.348  4639  4639 D HeadsetService: Received stop request...Stopping profile...
,11-23 03:56:01.349   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 03:56:01.349   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-23 03:56:01.351  3164  3180 D BluetoothHeadset: Proxy object disconnected
11-23 03:56:01.351  3164  3164 D HeadsetProfile: Bluetooth service disconnected
11-23 03:56:01.352   927   927 D BluetoothHeadset: Proxy object disconnected
,11-23 03:56:01.352   927   927 D BluetoothHeadset: Proxy object disconnected
11-23 03:56:01.352   533   533 E Parcel  : Reading a NULL string not supported here.
11-23 03:56:01.352  3831  3846 D BluetoothHeadset: Proxy object disconnected
11-23 03:56:01.352   927   927 D BluetoothHeadset: Proxy object disconnected
11-23 03:56:01.354  4639  4639 D A2dpService: Received stop request...Stopping profile...
,11-23 03:56:01.355  4639  4854 D A2dpStateMachine: Exit Disconnected: -1
11-23 03:56:01.358  4639  4639 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:01.358  4639  4639 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:01.358  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 03:56:01.358  4639  4639 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:01.359  4639  4639 D HidService: Received stop request...Stopping profile...
11-23 03:56:01.359  4639  4639 D HidService: Stopping Bluetooth HidService
11-23 03:56:01.360   927   927 D BluetoothA2dp: Proxy object disconnected
11-23 03:56:01.364   927   927 D RttService: SCAN_AVAILABLE : 1
11-23 03:56:01.364   927  5455 D DhcpClient: Receive thread stopped
11-23 03:56:01.364   927  3021 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-23 03:56:01.365   927  3129 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 03:56:01.365  4639  4639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 03:56:01.365  4639  4639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 03:56:01.365  4639  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 03:56:01.365  4639  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:01.365  4639  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:01.365  4639  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:01.365  4639  4639 D HealthService: Received stop request...Stopping profile...
11-23 03:56:01.365  4639  4725 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 03:56:01.366  3797  3944 W QCNEJ   : |CORE| network lost: 100
11-23 03:56:01.367  4639  4639 D PanService: Received stop request...Stopping profile...
11-23 03:56:01.367  3797  3944 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 03:56:01.368  4639  4639 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:01.368  4639  4639 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:01.368  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:01.368  4639  4639 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:01.369  3164  3164 D BluetoothA2dp: Proxy object disconnected
11-23 03:56:01.369  3164  3164 D BluetoothInputDevice: Proxy object disconnected
11-23 03:56:01.369  3164  3164 D HidProfile: Bluetooth service disconnected
11-23 03:56:01.370  3164  3164 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 03:56:01.370  3164  3164 D PanProfile: Bluetooth service disconnected
,11-23 03:56:01.370  4639  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:01.370  4639  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-23 03:56:01.371  4639  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 03:56:01.371  4639  4831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-23 03:56:01.371  4639  4831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-23 03:56:01.371  4639  4639 D BluetoothMapService: Received stop request...Stopping profile...
,11-23 03:56:01.371  4639  4831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 03:56:01.371  4639  4831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 03:56:01.371  4639  4639 D BluetoothMapService: stop()
,11-23 03:56:01.372  4639  4639 D BluetoothMapAppObserver: deinitObservers()
,11-23 03:56:01.372  4639  4639 D BluetoothMapAppObserver: removeReceiver()
,11-23 03:56:01.374  4639  4639 V BluetoothAdapterState: isTurningOff()=true
,11-23 03:56:01.374  4639  4639 V BluetoothAdapterState: isTurningOn()=false
,11-23 03:56:01.374  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 03:56:01.374  4639  4639 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 03:56:01.375  4639  4639 D SapService: Received stop request...Stopping profile...
11-23 03:56:01.375  4639  4639 V SapService: stop()
11-23 03:56:01.375   927  3019 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 03:56:01.376  4639  4639 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-23 03:56:01.376  4639  4639 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-23 03:56:01.376  4639  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 03:56:01.376  4639  4639 V BluetoothAdapterState: isTurningOff()=true
,11-23 03:56:01.376  4639  4639 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:01.377  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:01.377  4639  4639 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:01.377  4639  4639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 03:56:01.377  4639  4725 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 03:56:01.378  4639  4639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 03:56:01.379  4639  4639 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:01.380  4639  4639 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:01.380  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 03:56:01.380  4639  4639 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:01.380  4639  4639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 03:56:01.380  4639  4639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 03:56:01.381  4639  4639 D BluetoothMapService: MAP Service closeService in
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:01.382   927  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 03:56:01.382  4639  4639 D BluetoothMapService: cleanup()
11-23 03:56:01.382  4639  4639 D BluetoothMapService: MAP Service closeService in
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:01.382  4639  4639 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:01.383  4639  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 03:56:01.383  4639  4717 D BluetoothAdapterProperties: Setting state to 15
11-23 03:56:01.383  4639  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-23 03:56:01.383  4639  4717 I BluetoothAdapterState: Entering BleOnState
11-23 03:56:01.384  3164  4022 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 03:56:01.387  3164  3177 D BluetoothPan: onBluetoothStateChange on: false
11-23 03:56:01.387  3164  3180 D BluetoothMap: onBluetoothStateChange: up=false
11-23 03:56:01.388  3831  3847 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:01.388   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:01.389  3164  3177 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:01.389   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:01.389   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 03:56:01.389   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 03:56:01.389  3164  4022 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 03:56:01.390  3164  3180 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 03:56:01.391  4639  4717 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 03:56:01.391  4639  4717 D BluetoothAdapterProperties: Setting state to 16
11-23 03:56:01.391  4639  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 03:56:01.391  4639  4717 D BluetoothAdapterProperties: onBleDisable
11-23 03:56:01.391  4639  4717 I BluetoothAdapterState: Entering PendingCommandState
11-23 03:56:01.392  4639  4718 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 03:56:01.392  4639  4725 D BluetoothAdapterProperties: Scan Mode:20
11-23 03:56:01.394  4639  4831 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 03:56:01.394  4639  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:01.399  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:01.399  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 03:56:01.400  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:01.400  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 03:56:01.402  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:01.405   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 03:56:01.410  5753  5753 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 03:56:01.432   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 03:56:01.432   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-23 03:56:01.432   507   920 D TetherController: Setting IP forward enable = 0
,11-23 03:56:01.433   927  3021 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 03:56:01.434   927  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 03:56:01.434  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 03:56:01.437   927  3019 D DhcpClient: doQuit
,11-23 03:56:01.437   927  3019 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 03:56:01.438  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:01.438   927  5454 D DhcpClient: onQuitting
11-23 03:56:01.438   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-23 03:56:01.443  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:01.443  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 03:56:01.444  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:01.444  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 03:56:01.439  5370  5370 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@acc007c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-23 03:56:01.439  3500  3500 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-23 03:56:01.440  4994  4994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 03:56:01.447  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 03:56:01.447  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 03:56:01.447  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 03:56:01.447  5115  5139 E SarControlService: no key has been found,reset the power
11-23 03:56:01.447  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-23 03:56:01.447  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 03:56:01.447  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 03:56:01.448  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:01.448  5140  5140 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 03:56:01.449  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 03:56:01.449  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 03:56:01.449  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 03:56:01.450  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:01.450  5140  5140 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 03:56:01.453  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000ea03000000000000ffffffff]
11-23 03:56:01.453  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:01.453  5140  5154 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 03:56:01.454  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 03:56:01.454  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 03:56:01.460   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@54a33e8:true
11-23 03:56:01.461  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 03:56:01.463  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000eb03000000000000ffffffff]
11-23 03:56:01.463  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:01.463  5140  5154 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 03:56:01.463  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 03:56:01.464  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 03:56:01.467  3500  3500 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 03:56:01.470  3500  3500 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 03:56:01.474   927  3198 I ActivityManager: Start proc 5782:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-23 03:56:01.489  5753  5753 D LocalBluetoothProfileManager: Adding local MAP profile
,11-23 03:56:01.493   507   920 E Netd    : netlink response contains error (No such file or directory)
11-23 03:56:01.494  5753  5753 D BluetoothMap: Create BluetoothMap proxy object
,11-23 03:56:01.495   507   920 D TetherController: Setting IP forward enable = 0
,11-23 03:56:01.496   927  3021 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-23 03:56:01.496   927  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 03:56:01.506  3500  3500 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-23 03:56:01.510  5753  5753 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-23 03:56:01.517  5782  5782 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
11-23 03:56:01.522  5753  5753 D DockEventReceiver: finishStartingService: stopping service
11-23 03:56:01.528  3500  3500 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-23 03:56:01.529   927   938 I ActivityManager: Killing 5040:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-23 03:56:01.600  4639  4725 I bt_hci  : shut_down
,11-23 03:56:01.606  4639  4732 D bt_hwcfg: hw_epilog_process
,11-23 03:56:01.606  4639  4732 I bt_vendor: low_power_mode_cb
,11-23 03:56:01.608  4639  4732 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 03:56:01.608  4639  4732 I bt_vendor: epilog_cb
11-23 03:56:01.608  4639  4732 I bt_hci  : epilog_finished_callback
,11-23 03:56:01.611  4639  4725 I bt_hci_h4: hal_close
11-23 03:56:01.612  4639  4725 I bt_userial_vendor: device fd = 54 close
,11-23 03:56:01.629   927  3019 D wifi    : In wifi stop Hal
,11-23 03:56:01.629  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 03:56:01.630   927  3019 D wifi    : halHandle = 0x7f84227900, mVM = 0x7fa080d140, mCls = 0x100a02
,11-23 03:56:01.630   927  3498 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 03:56:01.630   927  3498 D WifiHAL : Got a signal to exit!!!
11-23 03:56:01.630   927  3498 I WifiHAL : Exit wifi_event_loop
11-23 03:56:01.630   927  3019 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 03:56:01.630   927  3019 E WifiHAL : Event processing terminated
11-23 03:56:01.631   927  3019 D wifi    : In wifi cleaned up handler
,11-23 03:56:01.631   927  3019 I WifiHAL : Internal cleanup completed
11-23 03:56:01.632  4168  4294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 03:56:01.633  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:01.656   927  3498 D wifi    : set interface wlan0 flags (DOWN)
,11-23 03:56:01.656   927  3019 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 03:56:01.701  5782  5782 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 03:56:01.701  5782  5782 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 03:56:01.701  5782  5782 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 03:56:01.701  5782  5782 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.701  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 03:56:01.702  5782  5782 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.r.k.d(PG:583)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 03:56:01.702  5782  5782 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 03:56:01.702  5782  5782 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.702,  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 03:56:01.702  5782  5782 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 03:56:01.702  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 03:56:01.708  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 03:56:01.715  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 03:56:01.720  4639  4718 D bt_stack_manager: event_shut_down_stack finished.
,11-23 03:56:01.721  4639  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 03:56:01.722  5753  5753 D DockEventReceiver: finishStartingService: stopping service
11-23 03:56:01.722  4639  4717 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 03:56:01.723  4639  4639 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 03:56:01.723  4639  4639 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 03:56:01.723  4639  4639 D BtGatt.GattService: stop()
11-23 03:56:01.723  4639  4639 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 03:56:01.726  4639  4639 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:01.726  4639  4639 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:01.726  4639  4639 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:01.726  4639  4639 V BluetoothAdapterState: isBleTurningOff()=true
11-23 03:56:01.726  4639  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 03:56:01.727  4639  4717 D BluetoothAdapterProperties: Setting state to 10
11-23 03:56:01.727  4639  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 03:56:01.727  4639  4717 I BluetoothAdapterState: Entering OffState
,11-23 03:56:01.729   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-23 03:56:01.734  4639  4639 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-23 03:56:01.734  4639  4639 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-23 03:56:01.734  4639  4639 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 03:56:01.735  4639  4718 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 03:56:01.738  4639  4639 I art     : System.exit called, status: 0
11-23 03:56:01.738  4639  4639 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 03:56:01.741   927  3906 I ActivityManager: Killing 5480:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-23 03:56:01.777  4001  4001 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 03:56:01.782   927  4282 I ActivityManager: Process com.android.bluetooth (pid 4639) has died
,11-23 03:56:01.785  4001  4001 D SystemUpdateService: onCreate
,11-23 03:56:01.788  4001  4001 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 03:56:01.795  4001  4001 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 03:56:01.807  4001  5478 I iu.UploadsManager: num queued entries: 0
,11-23 03:56:01.807  4001  5478 I iu.UploadsManager: num updated entries: 0
11-23 03:56:01.808  4001  5478 I iu.SyncManager: NEXT; no task
,11-23 03:56:01.815  4001  4001 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 03:56:01.816  4001  4001 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 03:56:01.818  4001  5816 I SystemUpdateService: active receiver: enabled
,11-23 03:56:01.827   927  3906 I ActivityManager: Start proc 5818:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 03:56:01.844  4001  5816 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 03:56:01.856  5818  5818 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 03:56:01.858   927   944 D Tethering: InitialState.processMessage what=4
,11-23 03:56:01.861   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 03:56:01.862  5818  5818 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 03:56:01.869  4001  5816 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 03:56:01.869  4001  5816 I SystemUpdateService: now status is 0 (complete)
11-23 03:56:01.869  4001  5816 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 03:56:01.869  4001  5816 I SystemUpdateService: file has been verified
,11-23 03:56:01.869  4001  5816 I SystemUpdateService: OTA package size = 21989297
11-23 03:56:01.870  5818  5818 D SprintDMHelper: simOperator: 
,11-23 03:56:01.870  5818  5818 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 03:56:01.881  5089  5831 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 03:56:01.893   927  3198 I ActivityManager: Start proc 5832:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 03:56:01.904  4001  5816 I SystemUpdateService: showing system update notification
,11-23 03:56:01.927  5832  5832 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 03:56:01.943   927  3464 I ActivityManager: Killing 5370:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 03:56:01.988  4001  4001 D SystemUpdateService: onDestroy
,11-23 03:56:01.989   927  3906 I ActivityManager: Killing 4736:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 03:56:02.084  5782  5808 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-23 03:56:02.096   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 03:56:02.097   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16b5f65:true
,11-23 03:56:06.321   927  3850 D WifiService: setWifiEnabled: true pid=5693, uid=10077
11-23 03:56:06.321   927  3850 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 03:56:06.330   507   920 D SoftapController: Softap fwReload - Ok
,11-23 03:56:06.334   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:06.334   507   920 D CommandListener: Trying to bring down wlan0
11-23 03:56:06.336   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 03:56:06.341   927  3019 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 03:56:06.913   927  3019 D wifi    : set interface wlan0 flags (UP)
,11-23 03:56:06.917   927  3019 I WifiHAL : Initializing wifi
,11-23 03:56:06.917   927  3019 I WifiHAL : Creating socket
,11-23 03:56:06.917   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 03:56:06.922   927  3019 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 03:56:06.923   927  3019 D wifi    : Did set static halHandle = 0x7f84227900
11-23 03:56:06.923   927  3019 D wifi    : halHandle = 0x7f84227900, mVM = 0x7fa080d140, mCls = 0x101982
,11-23 03:56:06.923   927  3019 D wifi    : array field set
,11-23 03:56:06.923   927  3019 I WifiNative-HAL: interface[0] = wlan0
11-23 03:56:06.927   927  5851 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547677698304
11-23 03:56:06.927   927  5851 D wifi    : waitForHalEvents called, vm = 0x7fa080d140, obj = 0x101982, env = 0x7f86376340
,11-23 03:56:06.992  5852  5852 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 03:56:07.005  5852  5852 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 03:56:07.014  5852  5852 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-23 03:56:07.014  5852  5852 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 03:56:07.027   927  3019 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 03:56:07.030  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:07.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 03:56:07.030  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:07.030  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 03:56:07.035   927  3019 D WifiConfigStore: Loading config and enabling all networks 
11-23 03:56:07.036  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:07.049   927  3019 D WifiConfigStore: loaded 0 passpoint configs
,11-23 03:56:07.050   927  3019 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-23 03:56:07.050   927  3019 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 03:56:07.052   927  3019 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 03:56:07.053   927  3019 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 03:56:07.053   927  3019 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 03:56:07.053   927  3019 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 03:56:07.053   927  3019 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 03:56:07.056  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 03:56:07.056   927  3019 D WifiNative-HAL: Setting external_sim to 1
11-23 03:56:07.057   927  3019 D wifi    : setting dfs flag to true, 0x7f84232e40
11-23 03:56:07.057   927  3019 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 03:56:07.057   927  3019 D wifi    : setting scan oui 0x7f84232e40
11-23 03:56:07.057   927  3019 D WifiHAL : Sending mac address OUI
,11-23 03:56:07.061   927  3019 E native  : do suspend false
,11-23 03:56:07.068   927   927 D RttService: SCAN_AVAILABLE : 3
11-23 03:56:07.068   927  3019 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 03:56:07.068   927  3129 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 03:56:07.072   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 03:56:07.073   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:07.076   927  3018 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-23 03:56:07.076   927  3018 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 03:56:07.081   927  3018 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 03:56:07.085   927  3018 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
11-23 03:56:07.085   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129081 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-23 03:56:07.096   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:08.097   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:09.098   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:10.099   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:10.156  5852  5852 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:56:10.161  5852  5852 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:56:10.167  5852  5852 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:56:10.172  5852  5852 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:56:10.242   927  3019 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 03:56:10.243   927  3019 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 03:56:10.243   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 03:56:10.256   927  3019 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 03:56:10.287   927  3019 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 03:56:10.289  5852  5852 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 03:56:10.710  5852  5852 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 03:56:10.747  5852  5852 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 03:56:10.749  5852  5852 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 03:56:10.760   927  3019 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 03:56:10.760   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 03:56:10.761   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 03:56:10.774   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 03:56:10.784   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:10.789   927  3019 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 03:56:10.794   927  5858 D DhcpClient: Receive thread started
,11-23 03:56:10.798   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 03:56:10.799   927  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 03:56:10.799   927  3021 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 03:56:10.879   927  3019 E native  : do suspend false
,11-23 03:56:10.893   927  5857 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 03:56:10.910   927  5858 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-23 03:56:10.911   927  5857 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-23 03:56:10.916   927  5857 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-23 03:56:10.934   927  5858 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-23 03:56:10.935   927  5857 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 03:56:10.939   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:10.944   927  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 03:56:10.948   927  5857 D DhcpClient: Scheduling renewal in 86399s
,11-23 03:56:10.959   927  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 03:56:10.961   927  3019 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 03:56:10.962   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 03:56:10.967   927  3021 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 03:56:10.970   927  3019 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 03:56:11.015   927  3021 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 03:56:11.015   927  3021 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-23 03:56:11.021   927  3021 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 03:56:11.023   927  3021 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 03:56:11.025   927  3021 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 03:56:11.031   927  3021 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 03:56:11.035   927  3021 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-23 03:56:11.035   927  3021 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-23 03:56:11.035   927  3021 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,11-23 03:56:11.035   927  3019 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 03:56:11.035   927  3021 D ConnectivityService:    accepting network in place of null
11-23 03:56:11.035   927  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 03:56:11.036   927  3021 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 03:56:11.051   927  5856 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133047, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 03:56:11.056   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 03:56:11.076   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 03:56:11.080   927  3021 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 03:56:11.080   927  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 03:56:11.080  3797  3944 W QCNEJ   : |CORE| network available: 101
11-23 03:56:11.081   927  3021 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-23 03:56:11.082   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-23 03:56:11.086  3797  3944 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 03:56:11.086  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 03:56:11.086  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 03:56:11.086  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:11.086  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 03:56:11.087  3797  3944 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-23 03:56:11.088  3797  3944 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 03:56:11.094  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 03:56:11.094  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 03:56:11.094  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 03:56:11.095  5115  5139 E SarControlService: no key has been found,reset the power
11-23 03:56:11.095  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 03:56:11.095  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 03:56:11.095  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 03:56:11.096  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:11.096  5140  5140 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 03:56:11.097  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 03:56:11.097  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-23 03:56:11.097  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 03:56:11.098  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:11.098  5140  5140 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 03:56:11.099  4994  4994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-23 03:56:11.099   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:11.101  4001  4001 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 03:56:11.105  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000ec03000000000000ffffffff]
11-23 03:56:11.105  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:11.105  5140  5154 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 03:56:11.105  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000ed03000000000000ffffffff]
,11-23 03:56:11.105  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:11.105  5140  5154 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-23 03:56:11.106  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 03:56:11.106  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 03:56:11.106  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 03:56:11.107  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 03:56:11.107  4001  4001 D SystemUpdateService: onCreate
,11-23 03:56:11.111  4001  4001 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 03:56:11.120  4001  4001 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 03:56:11.125  4001  5478 I iu.UploadsManager: num queued entries: 0
,11-23 03:56:11.125  4001  5478 I iu.UploadsManager: num updated entries: 0
11-23 03:56:11.125  4001  5478 I iu.SyncManager: NEXT; no task
,11-23 03:56:11.128   927  5855 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
,11-23 03:56:11.129  4001  5868 I SystemUpdateService: active receiver: enabled
,11-23 03:56:11.130  4001  4001 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 03:56:11.132  4001  4001 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 03:56:11.133  5818  5818 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 03:56:11.137  5818  5818 D SprintDMHelper: simOperator: 
,11-23 03:56:11.137  5818  5818 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 03:56:11.160  4001  5868 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 03:56:11.172  4001  5868 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 03:56:11.172  4001  5868 I SystemUpdateService: now status is 0 (complete)
11-23 03:56:11.172  4001  5868 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 03:56:11.172  4001  5868 I SystemUpdateService: file has been verified
11-23 03:56:11.172  4001  5868 I SystemUpdateService: OTA package size = 21989297
,11-23 03:56:11.178  4001  5868 I SystemUpdateService: showing system update notification
,11-23 03:56:11.186  4001  4001 D SystemUpdateService: onDestroy
,11-23 03:56:11.189   927  5855 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 08:56:11 GMT], X-Android-Received-Millis=[1479891371188], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479891371161]}
,11-23 03:56:11.189   927  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 03:56:11.189   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-23 03:56:11.190   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 03:56:11.191   927  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 03:56:11.280  5089  5873 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-23 03:56:11.329   927   938 D WifiService: setWifiEnabled: false pid=5693, uid=10077
11-23 03:56:11.329   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 03:56:11.335   927  3019 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 03:56:11.335   927  3019 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-23 03:56:11.335   927  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 03:56:11.336   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 03:56:11.351   927  5857 D DhcpClient: Clearing IP address
11-23 03:56:11.352   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 03:56:11.358   507   920 D CommandListener: Setting iface cfg
11-23 03:56:11.358  3622  5878 V NativeCrypto: Read error: ssl=0x7f9a745700: I/O error during system call, Connection timed out
11-23 03:56:11.359  3622  5878 V NativeCrypto: SSL shutdown failed: ssl=0x7f9a745700: I/O error during system call, Broken pipe
,11-23 03:56:11.374   927  3198 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-23 03:56:11.375   927  5855 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-23 03:56:11.375   927  5855 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
11-23 03:56:11.377   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 03:56:11.377   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-23 03:56:11.382   533   533 E Parcel  : Reading a NULL string not supported here.
11-23 03:56:11.383   927  3021 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-23 03:56:11.385   927   927 D RttService: SCAN_AVAILABLE : 1
11-23 03:56:11.385  3797  3944 W QCNEJ   : |CORE| network lost: 101
11-23 03:56:11.385   927  5855 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:804::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-23 03:56:11.385   927  3129 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 03:56:11.385  3797  3944 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 03:56:11.386   927  3019 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 03:56:11.391   927  5858 D DhcpClient: Receive thread stopped
,11-23 03:56:11.392   927  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 03:56:11.407   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 03:56:11.424   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 03:56:11.425   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-23 03:56:11.425   927  3021 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 03:56:11.425   927  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 03:56:11.428   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-23 03:56:11.430  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:11.430  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 03:56:11.430  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:11.430  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 03:56:11.431   927  3019 D DhcpClient: doQuit
11-23 03:56:11.431   927  3019 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 03:56:11.431   927  5857 D DhcpClient: onQuitting
11-23 03:56:11.431  5852  5852 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-23 03:56:11.434  4994  4994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-23 03:56:11.434  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:11.434  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 03:56:11.434  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:11.434  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 03:56:11.438  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 03:56:11.438  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 03:56:11.438  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 03:56:11.438  5115  5139 E SarControlService: no key has been found,reset the power
11-23 03:56:11.438  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 03:56:11.438  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 03:56:11.438  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 03:56:11.439  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:11.439  5140  5140 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 03:56:11.440  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 03:56:11.440  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 03:56:11.440  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 03:56:11.440  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:11.440  5140  5140 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 03:56:11.443  4001  4001 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 03:56:11.446  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000ee03000000000000ffffffff]
11-23 03:56:11.446  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:11.446  5140  5154 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-23 03:56:11.446  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000ef03000000000000ffffffff]
11-23 03:56:11.446  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:11.447  5140  5154 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-23 03:56:11.447  5852  5852 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-23 03:56:11.447  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-23 03:56:11.447  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 03:56:11.448  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 03:56:11.448  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 03:56:11.449  4001  4001 D SystemUpdateService: onCreate
11-23 03:56:11.449  5852  5852 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 03:56:11.452  4001  4001 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-23 03:56:11.456  4001  5888 I SystemUpdateService: active receiver: enabled
,11-23 03:56:11.460  4001  4001 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 03:56:11.464  4001  5478 I iu.UploadsManager: num queued entries: 0
,11-23 03:56:11.468  4001  4001 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-23 03:56:11.469  4001  4001 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 03:56:11.471  5818  5818 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 03:56:11.475  5818  5818 D SprintDMHelper: simOperator: 
11-23 03:56:11.475  5818  5818 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 03:56:11.476  4001  5888 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 03:56:11.478  5852  5852 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 03:56:11.465  4001  5478 I iu.UploadsManager: num updated entries: 0
,11-23 03:56:11.484   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-23 03:56:11.485   927  3021 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-23 03:56:11.485   927  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 03:56:11.489  5089  5892 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 03:56:11.494  5852  5852 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 03:56:11.500  4001  5888 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 03:56:11.500  4001  5888 I SystemUpdateService: now status is 0 (complete)
11-23 03:56:11.500  4001  5888 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 03:56:11.500  4001  5888 I SystemUpdateService: file has been verified
11-23 03:56:11.501  4001  5888 I SystemUpdateService: OTA package size = 21989297
11-23 03:56:11.503  4001  5478 I iu.SyncManager: NEXT; no task
,11-23 03:56:11.510  4001  5888 I SystemUpdateService: showing system update notification
,11-23 03:56:11.519  4001  4001 D SystemUpdateService: onDestroy
,11-23 03:56:11.596   927  3019 D wifi    : In wifi stop Hal
,11-23 03:56:11.596   927  3019 D wifi    : halHandle = 0x7f84227900, mVM = 0x7fa080d140, mCls = 0x101982
11-23 03:56:11.597   927  5851 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 03:56:11.597   927  5851 D WifiHAL : Got a signal to exit!!!
11-23 03:56:11.597   927  5851 I WifiHAL : Exit wifi_event_loop
11-23 03:56:11.598   927  3019 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 03:56:11.598   927  3019 E WifiHAL : Event processing terminated
11-23 03:56:11.598   927  3019 D wifi    : In wifi cleaned up handler
11-23 03:56:11.598   927  3019 I WifiHAL : Internal cleanup completed
11-23 03:56:11.599  4168  4294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 03:56:11.601  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:11.601  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 03:56:11.634   927  5851 D wifi    : set interface wlan0 flags (DOWN)
,11-23 03:56:11.634   927  3019 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 03:56:11.840   927   944 D Tethering: InitialState.processMessage what=4
,11-23 03:56:11.847   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 03:56:12.081   927  3021 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 03:56:12.100   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 03:56:16.371   927   944 I ActivityManager: Start proc 5894:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 03:56:16.465  5894  5894 D AdapterServiceConfig: Adding HeadsetService
,11-23 03:56:16.465  5894  5894 D AdapterServiceConfig: Adding A2dpService
11-23 03:56:16.465  5894  5894 D AdapterServiceConfig: Adding HidService
11-23 03:56:16.465  5894  5894 D AdapterServiceConfig: Adding HealthService
11-23 03:56:16.465  5894  5894 D AdapterServiceConfig: Adding PanService
11-23 03:56:16.465  5894  5894 D AdapterServiceConfig: Adding GattService
11-23 03:56:16.465  5894  5894 D AdapterServiceConfig: Adding BluetoothMapService
11-23 03:56:16.466  5894  5894 D AdapterServiceConfig: Adding SapService
,11-23 03:56:16.476   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@682320:true
,11-23 03:56:16.476  5894  5894 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 03:56:16.479  5894  5894 I bt_bluedroid: init
,11-23 03:56:16.479  5894  5906 I BluetoothAdapterState: Entering OffState
,11-23 03:56:16.481  5894  5907 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 03:56:16.482  5894  5907 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 03:56:16.482  5894  5907 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 03:56:16.482  5894  5907 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 03:56:16.482  5894  5894 I bt_bluedroid: get_profile_interface socket
,11-23 03:56:16.484  5894  5910 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-23 03:56:16.485  5894  5894 I bt_bluedroid: get_profile_interface sdp
11-23 03:56:16.486  5894  5910 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 03:56:16.489  5894  5905 I bt_bluedroid: config_hci_snoop_log
,11-23 03:56:16.490   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 03:56:16.494  5894  5906 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 03:56:16.494  5894  5906 D BluetoothAdapterProperties: Setting state to 14
11-23 03:56:16.494  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 03:56:16.495  5894  5906 D BluetoothBondStateMachine: make
,11-23 03:56:16.496  5894  5911 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 03:56:16.499  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
,11-23 03:56:16.500  5894  5894 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 03:56:16.502  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:16.502  5894  5894 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 03:56:16.503  5894  5894 D BtGatt.GattService: Received start request. Starting profile...
11-23 03:56:16.503  5894  5894 D BtGatt.GattService: start()
11-23 03:56:16.503  5894  5894 I bt_bluedroid: get_profile_interface gatt
,11-23 03:56:16.504  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:16.504  5894  5894 D BtGatt.AdvertiseManager: advertise manager created
,11-23 03:56:16.509  5894  5894 V BluetoothAdapterState: isTurningOff()=false
,11-23 03:56:16.509  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:16.509  5894  5894 V BluetoothAdapterState: isBleTurningOn()=true
11-23 03:56:16.509  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:16.509  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 03:56:16.510  5894  5906 I bt_bluedroid: bt_bluedroid
,11-23 03:56:16.511  5894  5907 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 03:56:16.511  5894  5907 I bt_hci  : start_up
,11-23 03:56:16.516  5894  5907 I bt_vendor: alloc value 0xf3bab871
11-23 03:56:16.516  5894  5907 I bt_vendor: init
11-23 03:56:16.516  5894  5907 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 03:56:16.516  5894  5907 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 03:56:16.627  5894  5907 D bt_hci  : start_up starting async portion
,11-23 03:56:16.628  5894  5914 I bt_hci  : event_finish_startup
11-23 03:56:16.628  5894  5914 I bt_hci_h4: hal_open
11-23 03:56:16.628  5894  5914 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 03:56:16.625  5915  5915 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 03:56:16.631  5894  5914 I bt_userial_vendor: device fd = 54 open
,11-23 03:56:16.645  5894  5914 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 03:56:16.648  5894  5914 D bt_hwcfg: Chipset BCM4358A3
,11-23 03:56:16.648  5894  5914 D bt_hwcfg: Target name = [BCM4358A3]
11-23 03:56:16.648  5894  5914 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 03:56:17.056  5894  5914 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 03:56:17.056  5894  5914 D bt_hwcfg: Settlement delay -- 100 ms
11-23 03:56:17.056  5894  5914 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 03:56:17.190  5894  5914 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-23 03:56:17.190  5894  5914 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-23 03:56:17.192  5894  5914 I bt_hwcfg: vendor lib fwcfg completed
11-23 03:56:17.192  5894  5914 I bt_vendor: firmware callback
11-23 03:56:17.193  5894  5914 I bt_hci  : firmware_config_callback
,11-23 03:56:17.201  5894  5917 I bt_btu  : btu_task pending for preload complete event
,11-23 03:56:17.201  5894  5917 I bt_btu_task: Bluetooth chip preload is complete
11-23 03:56:17.201  5894  5917 I bt_btu  : btu_task received preload complete event
,11-23 03:56:17.207  5894  5917 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 03:56:17.207  5894  5917 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 03:56:17.207  5894  5917 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-23 03:56:17.208  5894  5917 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 03:56:17.208  5894  5917 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-23 03:56:17.208  5894  5917 I         : BTE_InitTraceLevels -- TRC_A2D
,11-23 03:56:17.208  5894  5917 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 03:56:17.208  5894  5917 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 03:56:17.208  5894  5917 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 03:56:17.208  5894  5917 I         : BTE_InitTraceLevels -- TRC_PAN
,11-23 03:56:17.209  5894  5917 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 03:56:17.209  5894  5917 I         : BTE_InitTraceLevels -- TRC_GATT
,11-23 03:56:17.209  5894  5917 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 03:56:17.209  5894  5917 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 03:56:17.209  5894  5917 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 03:56:17.296  5894  5917 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b29549
,11-23 03:56:17.296  5894  5917 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b29549 
,11-23 03:56:17.314  5894  5910 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 03:56:17.316  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 03:56:17.317  5894  5910 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 03:56:17.320  5894  5910 D BluetoothAdapterProperties: Name is: Nexus 6P
11-23 03:56:17.322  5894  5910 D BluetoothAdapterProperties: Scan Mode:20
11-23 03:56:17.323  5894  5910 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 03:56:17.323  5894  5910 D bt_hci  : do_postload posting postload work item
11-23 03:56:17.323  5894  5914 I bt_hci  : event_postload
11-23 03:56:17.323  5894  5914 I bt_vendor: sco_config_cb
11-23 03:56:17.323  5894  5914 I bt_hci  : sco_config_callback postload finished.
11-23 03:56:17.326  5894  5910 D bt_bte_conf: Device ID record 1 : primary
11-23 03:56:17.326  5894  5910 D bt_bte_conf:   vendorId            = 000f
11-23 03:56:17.326  5894  5910 D bt_bte_conf:   vendorIdSource      = 0001
11-23 03:56:17.326  5894  5910 D bt_bte_conf:   product             = 1200
11-23 03:56:17.326  5894  5910 D bt_bte_conf:   version             = 1436
11-23 03:56:17.326  5894  5910 D bt_bte_conf:   clientExecutableURL = 
,11-23 03:56:17.326  5894  5910 D bt_bte_conf:   serviceDescription  = 
11-23 03:56:17.326  5894  5910 D bt_bte_conf:   documentationURL    = 
11-23 03:56:17.326  5894  5910 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 03:56:17.326  5894  5907 D bt_stack_manager: event_start_up_stack finished
11-23 03:56:17.327  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 03:56:17.328  5894  5906 D BluetoothAdapterProperties: Setting state to 15
,11-23 03:56:17.328  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 03:56:17.329  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:17.330  5894  5906 I BluetoothAdapterState: Entering BleOnState
,11-23 03:56:17.337  5894  5906 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 03:56:17.337  5894  5906 D BluetoothAdapterProperties: Setting state to 11
,11-23 03:56:17.337  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 03:56:17.339  5894  5914 I bt_vendor: low_power_mode_cb
,11-23 03:56:17.341  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:17.342  5894  5894 D HeadsetService: Received start request. Starting profile...
11-23 03:56:17.345  5894  5894 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 03:56:17.345  5894  5894 D HeadsetStateMachine: make
11-23 03:56:17.348  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:17.358  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
,11-23 03:56:17.358  5894  5894 D HeadsetStateMachine: max_hf_connections = 1
11-23 03:56:17.358  5894  5894 I bt_bluedroid: get_profile_interface handsfree
11-23 03:56:17.358  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 03:56:17.358  5894  5910 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 03:56:17.362  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:17.363  5894  5894 D A2dpService: Received start request. Starting profile...
,11-23 03:56:17.363  5894  5894 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 03:56:17.364  5894  5894 I bt_bluedroid: get_profile_interface avrcp
,11-23 03:56:17.369  5894  5894 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 03:56:17.369  5894  5894 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 03:56:17.369  5894  5894 D A2dpStateMachine: make
,11-23 03:56:17.370  5894  5894 I bt_bluedroid: get_profile_interface a2dp
11-23 03:56:17.371  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 03:56:17.372  5894  5925 D A2dpStateMachine: Enter Disconnected: -2
,11-23 03:56:17.372  5894  5894 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 03:56:17.373  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:17.374  5894  5894 D HidService: Received start request. Starting profile...
,11-23 03:56:17.374  5894  5894 I bt_bluedroid: get_profile_interface hidhost
11-23 03:56:17.375  5894  5894 D HidService: setHidService(): set to: null
11-23 03:56:17.375  5894  5910 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b0a56d
11-23 03:56:17.375  5753  5753 D BluetoothInputDevice: Proxy object connected
11-23 03:56:17.375  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 03:56:17.375  5894  5894 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 03:56:17.375  5753  5753 D HidProfile: Bluetooth service connected
11-23 03:56:17.376  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
11-23 03:56:17.376  5894  5894 D HealthService: Received start request. Starting profile...
,11-23 03:56:17.378  5894  5894 I bt_bluedroid: get_profile_interface health
,11-23 03:56:17.380  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 03:56:17.381  5894  5894 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 03:56:17.381  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
11-23 03:56:17.382  5753  5753 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 03:56:17.382  5894  5894 D PanService: Received start request. Starting profile...
11-23 03:56:17.382  5894  5894 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 03:56:17.382  5894  5894 I bt_bluedroid: get_profile_interface pan
11-23 03:56:17.383  5894  5910 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 03:56:17.383  5753  5753 D PanProfile: Bluetooth service connected
,11-23 03:56:17.385  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:17.386  5894  5894 D BluetoothMapService: Received start request. Starting profile...
,11-23 03:56:17.386  5894  5894 D BluetoothMapService: start()
11-23 03:56:17.386  5753  5753 D BluetoothMap: Proxy object connected
11-23 03:56:17.387  5753  5753 D MapProfile: Bluetooth service connected
11-23 03:56:17.387  5753  5753 D BluetoothMap: getConnectedDevices()
11-23 03:56:17.387  5753  5753 D BluetoothMap: Bluetooth is Not enabled
11-23 03:56:17.388  5894  5894 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 03:56:17.389  5894  5894 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 03:56:17.389  5894  5894 D BluetoothMapAppObserver: createReceiver()
,11-23 03:56:17.390  5894  5894 D BluetoothMapAppObserver: initObservers()
11-23 03:56:17.390  5894  5894 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 03:56:17.396  5894  5894 V SapService: SapBinder()
11-23 03:56:17.396  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:17.397  5894  5894 D SapService: Received start request. Starting profile...
,11-23 03:56:17.397  5894  5894 V SapService: start()
,11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isTurningOff()=false
,11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:17.399  5894  5922 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:17.399  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:17.400  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:17.400  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:17.400  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:17.400  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:17.400  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:17.400  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:17.400  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isTurningOff()=false
,11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:17.401  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 03:56:17.402  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:17.402  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:17.402  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:17.402  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:17.403  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 03:56:17.403  5894  5906 D BluetoothAdapterProperties: ScanMode =  20
11-23 03:56:17.403  5894  5906 D BluetoothAdapterProperties: State =  11
11-23 03:56:17.403  5894  5906 D BluetoothAdapterProperties: Setting state to 12
11-23 03:56:17.403  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-23 03:56:17.404  3164  4022 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 03:56:17.405  5894  5910 D BluetoothAdapterProperties: Scan Mode:21
11-23 03:56:17.405  5894  5910 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 03:56:17.405  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 03:56:17.406  5894  5906 I BluetoothAdapterState: Entering OnState
,11-23 03:56:17.406  3164  3164 D BluetoothInputDevice: Proxy object connected
11-23 03:56:17.406  3164  3164 D HidProfile: Bluetooth service connected
,11-23 03:56:17.407  5753  5764 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 03:56:17.408  3164  3177 D BluetoothPan: onBluetoothStateChange on: true
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:17.409  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 03:56:17.410  3164  3180 D BluetoothMap: onBluetoothStateChange: up=true
11-23 03:56:17.410  3164  3164 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 03:56:17.411  3164  3164 D PanProfile: Bluetooth service connected
11-23 03:56:17.411  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 03:56:17.412  3164  3164 D BluetoothMap: Proxy object connected
,11-23 03:56:17.412  3164  3164 D MapProfile: Bluetooth service connected
11-23 03:56:17.412  3164  3164 D BluetoothMap: getConnectedDevices()
11-23 03:56:17.412  3831  3847 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:17.413  5753  5767 D BluetoothPan: onBluetoothStateChange on: true
11-23 03:56:17.413   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:17.414  5753  5764 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 03:56:17.414  3164  4022 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 03:56:17.414   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:17.415  5753  5767 D BluetoothMap: onBluetoothStateChange: up=true
11-23 03:56:17.415   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:17.415   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 03:56:17.415  3164  3177 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 03:56:17.416  5894  5894 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 03:56:17.417  3164  3180 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 03:56:17.417  5894  5894 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-23 03:56:17.418  5894  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 03:56:17.421   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 03:56:17.421  5894  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 03:56:17.422  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-23 03:56:17.423  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:17.423  5753  5753 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-23 03:56:17.424  5894  5894 D ObexServerSockets: Succeed to create listening sockets 
11-23 03:56:17.424  5894  5894 D ObexServerSockets0: startAccept()
11-23 03:56:17.424  5894  5894 D ObexServerSockets0: prepareForNewConnect()
11-23 03:56:17.426  5894  5894 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 03:56:17.426  5894  5894 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 03:56:17.427  5753  5753 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-23 03:56:17.427  5894  5932 D ObexServerSockets0: Accepting socket connection...
11-23 03:56:17.427  5894  5933 D ObexServerSockets0: Accepting socket connection...
11-23 03:56:17.428  5894  5894 D BluetoothMapService: onReceive
11-23 03:56:17.428   927   927 D BluetoothA2dp: Proxy object connected
11-23 03:56:17.428  5894  5894 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-23 03:56:17.428  5894  5894 D BluetoothMapService: STATE_ON
11-23 03:56:17.430  5894  5934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 03:56:17.431  5894  5934 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 03:56:17.431  5894  5934 D BluetoothSdpJni: SDP Create record success - handle: 1
11-23 03:56:17.433  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 03:56:17.435  5753  5753 D BluetoothA2dp: Proxy object connected
,11-23 03:56:17.439  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 03:56:17.444  3164  3164 D BluetoothA2dp: Proxy object connected
,11-23 03:56:17.445  5753  5753 D DockEventReceiver: finishStartingService: stopping service
,11-23 03:56:17.446  5753  5753 D BluetoothPbap: Proxy object connected
11-23 03:56:17.447  3164  3164 D BluetoothPbap: Proxy object connected
,11-23 03:56:17.447  3164  3164 D PbapServerProfile: Bluetooth service connected
11-23 03:56:17.451  5753  5753 D PbapServerProfile: Bluetooth service connected
,11-23 03:56:17.454  5894  5894 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 03:56:17.454  5894  5894 D ObexServerSockets0: prepareForNewConnect()
11-23 03:56:17.456  5894  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 03:56:17.468  5894  5942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 03:56:17.470  5894  5942 I BtOppRfcommListener: Accept thread started.
,11-23 03:56:17.515  3164  4022 D BluetoothHeadset: Proxy object connected
,11-23 03:56:17.515  3164  3177 D BluetoothHeadset: Proxy object connected
11-23 03:56:17.515  3164  3164 D HeadsetProfile: Bluetooth service connected
11-23 03:56:17.515   927   927 D BluetoothHeadset: Proxy object connected
11-23 03:56:17.515   927   927 D BluetoothHeadset: Proxy object connected
11-23 03:56:17.515   927   944 D BluetoothHeadset: Proxy object connected
11-23 03:56:17.515   927   944 D BluetoothHeadset: Proxy object connected
11-23 03:56:17.516  3831  4049 D BluetoothHeadset: Proxy object connected
11-23 03:56:17.516   927   927 D BluetoothHeadset: Proxy object connected
,11-23 03:56:17.518  3164  3164 D HeadsetProfile: Bluetooth service connected
,11-23 03:56:17.530  5753  5767 D BluetoothHeadset: Proxy object connected
,11-23 03:56:17.531  5753  5753 D HeadsetProfile: Bluetooth service connected
,11-23 03:56:19.043   927  3021 D ConnectivityService: handlePromptUnvalidated 101
,11-23 03:56:21.350  5894  5906 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 03:56:21.350  5894  5906 D BluetoothAdapterProperties: Setting state to 13
,11-23 03:56:21.351  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-23 03:56:21.352  5894  5906 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 03:56:21.353  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
11-23 03:56:21.357  5894  5894 D BluetoothMapService: onReceive
,11-23 03:56:21.357  5894  5894 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 03:56:21.358  5894  5894 D BluetoothMapService: STATE_TURNING_OFF
,11-23 03:56:21.358  5894  5894 D BluetoothMapService: MAP Service closeService in
11-23 03:56:21.358  5894  5894 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 03:56:21.358  5894  5894 D ObexServerSockets0: shutdown(block = true)
11-23 03:56:21.359  5894  5932 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 03:56:21.361  5894  5894 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 03:56:21.363  5894  5894 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 03:56:21.364  5894  5910 D BluetoothAdapterProperties: Scan Mode:20
11-23 03:56:21.365  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 03:56:21.365  5894  5933 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-23 03:56:21.368  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 03:56:21.370  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:21.370  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 03:56:21.370  5894  5919 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 03:56:21.371  5894  5894 I BtOppRfcommListener: stopping Accept Thread
,11-23 03:56:21.371  5894  5942 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 03:56:21.372  5894  5942 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 03:56:21.373  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 03:56:21.373  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 03:56:21.374  5894  5894 D HeadsetService: Received stop request...Stopping profile...
11-23 03:56:21.378  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:21.380  5753  5767 D BluetoothHeadset: Proxy object disconnected
,11-23 03:56:21.381  5894  5894 D A2dpService: Received stop request...Stopping profile...
11-23 03:56:21.382  5894  5925 D A2dpStateMachine: Exit Disconnected: -1
11-23 03:56:21.383  5753  5753 D DockEventReceiver: finishStartingService: stopping service
11-23 03:56:21.383  3164  3180 D BluetoothHeadset: Proxy object disconnected
11-23 03:56:21.383   927   927 D BluetoothHeadset: Proxy object disconnected
11-23 03:56:21.383   927   927 D BluetoothHeadset: Proxy object disconnected
,11-23 03:56:21.384  3831  3846 D BluetoothHeadset: Proxy object disconnected
,11-23 03:56:21.384  5753  5753 D HeadsetProfile: Bluetooth service disconnected
11-23 03:56:21.384   927   927 D BluetoothHeadset: Proxy object disconnected
11-23 03:56:21.386   927   927 D BluetoothA2dp: Proxy object disconnected
11-23 03:56:21.386  5753  5753 D BluetoothA2dp: Proxy object disconnected
,11-23 03:56:21.390  5894  5894 V BluetoothAdapterState: isTurningOff()=true
,11-23 03:56:21.390  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.390  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.390  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 03:56:21.392  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 03:56:21.392  5894  5894 D HidService: Received stop request...Stopping profile...
11-23 03:56:21.392  5894  5894 D HidService: Stopping Bluetooth HidService
11-23 03:56:21.394  3164  3164 D HeadsetProfile: Bluetooth service disconnected
11-23 03:56:21.394  3164  3164 D BluetoothA2dp: Proxy object disconnected
,11-23 03:56:21.395  3164  3164 D BluetoothInputDevice: Proxy object disconnected
11-23 03:56:21.395  3164  3164 D HidProfile: Bluetooth service disconnected
11-23 03:56:21.396  5753  5753 D BluetoothInputDevice: Proxy object disconnected
11-23 03:56:21.396  5753  5753 D HidProfile: Bluetooth service disconnected
,11-23 03:56:21.396  5894  5894 D HealthService: Received stop request...Stopping profile...
11-23 03:56:21.398  5894  5894 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 03:56:21.398  5894  5894 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 03:56:21.399  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:21.399  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:21.399  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 03:56:21.399  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-23 03:56:21.399  5894  5910 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-23 03:56:21.400  5894  5894 D PanService: Received stop request...Stopping profile...
11-23 03:56:21.401  3164  3164 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 03:56:21.401  3164  3164 D PanProfile: Bluetooth service disconnected
11-23 03:56:21.402  5894  5894 D BluetoothMapService: Received stop request...Stopping profile...
,11-23 03:56:21.402  5894  5894 D BluetoothMapService: stop()
11-23 03:56:21.403  5894  5894 D BluetoothMapAppObserver: deinitObservers()
11-23 03:56:21.403  5894  5894 D BluetoothMapAppObserver: removeReceiver()
11-23 03:56:21.406  5753  5753 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 03:56:21.406  5753  5753 D PanProfile: Bluetooth service disconnected
11-23 03:56:21.406  5753  5753 D BluetoothMap: Proxy object disconnected
11-23 03:56:21.406  5753  5753 D MapProfile: Bluetooth service disconnected
11-23 03:56:21.406  3164  3164 D BluetoothMap: Proxy object disconnected
,11-23 03:56:21.406  3164  3164 D MapProfile: Bluetooth service disconnected
11-23 03:56:21.407  5894  5894 V BluetoothAdapterState: isTurningOff()=true
,11-23 03:56:21.408  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.408  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.408  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:21.409  5894  5894 D SapService: Received stop request...Stopping profile...
11-23 03:56:21.409  5894  5894 V SapService: stop()
,11-23 03:56:21.413  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 03:56:21.413  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-23 03:56:21.413  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 03:56:21.413  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 03:56:21.413  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 03:56:21.414  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 03:56:21.414  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-23 03:56:21.414  3164  3164 D BluetoothPbap: Proxy object disconnected
11-23 03:56:21.414  3164  3164 D PbapServerProfile: Bluetooth service disconnected
11-23 03:56:21.415  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:21.415  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.415  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.415  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:21.415  5894  5894 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 03:56:21.415  5894  5894 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 03:56:21.415  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:21.416  5894  5894 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 03:56:21.416  5894  5910 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 03:56:21.416  5894  5894 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.416  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:21.417  5894  5894 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 03:56:21.417  5894  5894 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 03:56:21.417  5894  5894 D BluetoothMapService: MAP Service closeService in
11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:21.418  5894  5894 D BluetoothMapService: cleanup()
11-23 03:56:21.418  5894  5894 D BluetoothMapService: MAP Service closeService in
,11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.418  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:21.419  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 03:56:21.419  5894  5906 D BluetoothAdapterProperties: Setting state to 15
11-23 03:56:21.419  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-23 03:56:21.419  5894  5906 I BluetoothAdapterState: Entering BleOnState
11-23 03:56:21.420  3164  3180 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-23 03:56:21.421  5753  5948 D BluetoothPbap: onBluetoothStateChange: up=false
,11-23 03:56:21.422  3164  3177 D BluetoothPan: onBluetoothStateChange on: false
11-23 03:56:21.423  3164  4022 D BluetoothMap: onBluetoothStateChange: up=false
11-23 03:56:21.423  3831  3847 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:21.423  5753  5764 D BluetoothPan: onBluetoothStateChange on: false
11-23 03:56:21.424  5753  5767 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:21.424   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:21.424  5753  5948 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 03:56:21.425  3164  3180 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:21.425   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:21.425  5753  5764 D BluetoothMap: onBluetoothStateChange: up=false
11-23 03:56:21.426   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 03:56:21.426   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 03:56:21.426  3164  3177 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 03:56:21.426  5753  5767 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 03:56:21.427  3164  4022 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 03:56:21.427  5894  5906 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 03:56:21.427  5894  5906 D BluetoothAdapterProperties: Setting state to 16
11-23 03:56:21.428  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 03:56:21.428  5753  5753 D BluetoothPbap: Proxy object disconnected
11-23 03:56:21.428  5753  5753 D PbapServerProfile: Bluetooth service disconnected
11-23 03:56:21.428  5894  5906 D BluetoothAdapterProperties: onBleDisable
11-23 03:56:21.428  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
,11-23 03:56:21.428  5894  5907 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 03:56:21.430  5894  5917 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 03:56:21.430  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 03:56:21.430  5894  5910 D BluetoothAdapterProperties: Scan Mode:20
,11-23 03:56:21.431  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 03:56:21.432  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 03:56:21.434  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:21.440  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 03:56:21.449  5753  5753 D DockEventReceiver: finishStartingService: stopping service
,11-23 03:56:21.642  5894  5910 I bt_hci  : shut_down
,11-23 03:56:21.651  5894  5914 D bt_hwcfg: hw_epilog_process
,11-23 03:56:21.651  5894  5914 I bt_vendor: low_power_mode_cb
,11-23 03:56:21.653  5894  5914 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 03:56:21.653  5894  5914 I bt_vendor: epilog_cb
11-23 03:56:21.653  5894  5914 I bt_hci  : epilog_finished_callback
,11-23 03:56:21.657  5894  5910 I bt_hci_h4: hal_close
,11-23 03:56:21.658  5894  5910 I bt_userial_vendor: device fd = 54 close
,11-23 03:56:21.768  5894  5907 D bt_stack_manager: event_shut_down_stack finished.
,11-23 03:56:21.768  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 03:56:21.771  5894  5906 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 03:56:21.771  5894  5894 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 03:56:21.772  5894  5894 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 03:56:21.772  5894  5894 D BtGatt.GattService: stop()
11-23 03:56:21.772  5894  5894 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 03:56:21.775  5894  5894 V BluetoothAdapterState: isTurningOff()=false
,11-23 03:56:21.775  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:21.775  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:21.775  5894  5894 V BluetoothAdapterState: isBleTurningOff()=true
,11-23 03:56:21.776  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 03:56:21.776  5894  5906 D BluetoothAdapterProperties: Setting state to 10
11-23 03:56:21.776  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 03:56:21.777  5894  5906 I BluetoothAdapterState: Entering OffState
,11-23 03:56:21.779   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 03:56:21.787  5894  5894 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 03:56:21.789  5894  5894 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 03:56:21.789  5894  5894 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 03:56:21.789  5894  5907 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 03:56:21.793  5894  5894 I art     : System.exit called, status: 0
,11-23 03:56:21.793  5894  5894 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 03:56:21.817   927   938 I ActivityManager: Process com.android.bluetooth (pid 5894) has died
,11-23 03:56:22.100   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:23.101   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:24.102   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:25.103   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:26.105   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:26.348  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:56:26.349  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 03:56:26.355  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:26.356  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45c41c1 removed from the list
,11-23 03:56:26.356  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:56:26.358  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 03:56:26.358  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c56154 added. We now have 4 listener(s)
11-23 03:56:26.358  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:26.361  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:26.361  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c56154 removed from the list
11-23 03:56:26.362  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:56:26.363  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:26.364  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@daa38fd added. We now have 4 listener(s)
11-23 03:56:26.364  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:56:27.106   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 03:56:31.376  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:31.413   927   944 I ActivityManager: Start proc 5953:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 03:56:31.504  5953  5953 D AdapterServiceConfig: Adding HeadsetService
,11-23 03:56:31.505  5953  5953 D AdapterServiceConfig: Adding A2dpService
11-23 03:56:31.505  5953  5953 D AdapterServiceConfig: Adding HidService
11-23 03:56:31.505  5953  5953 D AdapterServiceConfig: Adding HealthService
11-23 03:56:31.505  5953  5953 D AdapterServiceConfig: Adding PanService
11-23 03:56:31.505  5953  5953 D AdapterServiceConfig: Adding GattService
,11-23 03:56:31.506  5953  5953 D AdapterServiceConfig: Adding BluetoothMapService
11-23 03:56:31.506  5953  5953 D AdapterServiceConfig: Adding SapService
,11-23 03:56:31.516   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8dd9299:true
,11-23 03:56:31.517  5953  5953 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 03:56:31.520  5953  5953 I bt_bluedroid: init
,11-23 03:56:31.520  5953  5965 I BluetoothAdapterState: Entering OffState
,11-23 03:56:31.522  5953  5966 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 03:56:31.522  5953  5966 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 03:56:31.522  5953  5966 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 03:56:31.522  5953  5966 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 03:56:31.523  5953  5953 I bt_bluedroid: get_profile_interface socket
,11-23 03:56:31.524  5953  5969 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 03:56:31.525  5953  5953 I bt_bluedroid: get_profile_interface sdp
11-23 03:56:31.526  5953  5969 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 03:56:31.530  5953  5964 I bt_bluedroid: config_hci_snoop_log
,11-23 03:56:31.531   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 03:56:31.536  5953  5965 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 03:56:31.536  5953  5965 D BluetoothAdapterProperties: Setting state to 14
11-23 03:56:31.536  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 03:56:31.537  5953  5965 D BluetoothBondStateMachine: make
,11-23 03:56:31.539  5953  5970 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 03:56:31.542  5953  5965 I BluetoothAdapterState: Entering PendingCommandState
,11-23 03:56:31.543  5953  5953 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 03:56:31.545  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
11-23 03:56:31.546  5953  5953 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 03:56:31.546  5953  5953 D BtGatt.GattService: Received start request. Starting profile...
11-23 03:56:31.546  5953  5953 D BtGatt.GattService: start()
11-23 03:56:31.546  5953  5953 I bt_bluedroid: get_profile_interface gatt
11-23 03:56:31.547  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:31.548  5953  5953 D BtGatt.AdvertiseManager: advertise manager created
,11-23 03:56:31.554  5953  5953 V BluetoothAdapterState: isTurningOff()=false
,11-23 03:56:31.554  5953  5953 V BluetoothAdapterState: isTurningOn()=false
11-23 03:56:31.554  5953  5953 V BluetoothAdapterState: isBleTurningOn()=true
11-23 03:56:31.554  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 03:56:31.554  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-23 03:56:31.556  5953  5965 I bt_bluedroid: bt_bluedroid
11-23 03:56:31.556  5953  5966 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 03:56:31.557  5953  5966 I bt_hci  : start_up
,11-23 03:56:31.562  5953  5966 I bt_vendor: alloc value 0xf3bab871
11-23 03:56:31.562  5953  5966 I bt_vendor: init
11-23 03:56:31.562  5953  5966 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 03:56:31.562  5953  5966 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 03:56:31.671  5953  5966 D bt_hci  : start_up starting async portion
,11-23 03:56:31.672  5953  5973 I bt_hci  : event_finish_startup
11-23 03:56:31.672  5953  5973 I bt_hci_h4: hal_open
11-23 03:56:31.672  5953  5973 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 03:56:31.669  5974  5974 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-23 03:56:31.674  5953  5973 I bt_userial_vendor: device fd = 54 open
,11-23 03:56:31.688  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 03:56:31.691  5953  5973 D bt_hwcfg: Chipset BCM4358A3
11-23 03:56:31.691  5953  5973 D bt_hwcfg: Target name = [BCM4358A3]
11-23 03:56:31.691  5953  5973 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 03:56:32.201  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 03:56:32.201  5953  5973 D bt_hwcfg: Settlement delay -- 100 ms
11-23 03:56:32.202  5953  5973 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 03:56:32.335  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-23 03:56:32.336  5953  5973 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-23 03:56:32.338  5953  5973 I bt_hwcfg: vendor lib fwcfg completed
11-23 03:56:32.338  5953  5973 I bt_vendor: firmware callback
,11-23 03:56:32.338  5953  5973 I bt_hci  : firmware_config_callback
11-23 03:56:32.347  5953  5976 I bt_btu  : btu_task pending for preload complete event
11-23 03:56:32.347  5953  5976 I bt_btu_task: Bluetooth chip preload is complete,
,11-23 03:56:32.347  5953  5976 I bt_btu  : btu_task received preload complete event
,11-23 03:56:32.354  5953  5976 I         : BTE_InitTraceLevels -- TRC_HCI
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 03:56:32.355  5953  5976 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 03:56:32.356  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 03:56:32.356  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 03:56:32.449  5953  5976 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b29549
,11-23 03:56:32.449  5953  5976 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b29549 
,11-23 03:56:32.468  5953  5969 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 03:56:32.471  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 03:56:32.471  5953  5969 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-23 03:56:32.473  5953  5969 D BluetoothAdapterProperties: Name is: Nexus 6P
11-23 03:56:32.476  5953  5969 D BluetoothAdapterProperties: Scan Mode:20
,11-23 03:56:32.476  5953  5969 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 03:56:32.476  5953  5969 D bt_hci  : do_postload posting postload work item
,11-23 03:56:32.476  5953  5973 I bt_hci  : event_postload
11-23 03:56:32.476  5953  5973 I bt_vendor: sco_config_cb
,11-23 03:56:32.476  5953  5973 I bt_hci  : sco_config_callback postload finished.
11-23 03:56:32.479  5953  5969 D bt_bte_conf: Device ID record 1 : primary
11-23 03:56:32.479  5953  5969 D bt_bte_conf:   vendorId            = 000f
11-23 03:56:32.479  5953  5969 D bt_bte_conf:   vendorIdSource      = 0001
11-23 03:56:32.480  5953  5969 D bt_bte_conf:   product             = 1200
11-23 03:56:32.480  5953  5969 D bt_bte_conf:   version             = 1436
11-23 03:56:32.480  5953  5969 D bt_bte_conf:   clientExecutableURL = 
11-23 03:56:32.480  5953  5969 D bt_bte_conf:   serviceDescription  = 
11-23 03:56:32.480  5953  5969 D bt_bte_conf:   documentationURL    = 
11-23 03:56:32.480  5953  5969 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-23 03:56:32.481  5953  5966 D bt_stack_manager: event_start_up_stack finished
11-23 03:56:32.482  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-23 03:56:32.482  5953  5965 D BluetoothAdapterProperties: Setting state to 15
11-23 03:56:32.482  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 03:56:32.484  5953  5965 I BluetoothAdapterState: Entering BleOnState
,11-23 03:56:32.488  5953  5973 I bt_vendor: low_power_mode_cb
11-23 03:56:32.491  5953  5965 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 03:56:32.491  5953  5965 D BluetoothAdapterProperties: Setting state to 11
11-23 03:56:32.491  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 03:56:32.500  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:32.502  5953  5953 D HeadsetService: Received start request. Starting profile...
,11-23 03:56:32.505  5953  5953 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 03:56:32.505  5953  5953 D HeadsetStateMachine: make
,11-23 03:56:32.516  5953  5965 I BluetoothAdapterState: Entering PendingCommandState
,11-23 03:56:32.517  5953  5953 D HeadsetStateMachine: max_hf_connections = 1
11-23 03:56:32.517  5953  5953 I bt_bluedroid: get_profile_interface handsfree
11-23 03:56:32.518  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 03:56:32.518  5953  5969 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 03:56:32.524  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:32.524  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 03:56:32.524  5953  5953 D A2dpService: Received start request. Starting profile...
11-23 03:56:32.525  5953  5953 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 03:56:32.526  5953  5953 I bt_bluedroid: get_profile_interface avrcp
,11-23 03:56:32.532  5953  5953 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-23 03:56:32.532  5953  5953 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-23 03:56:32.533  5953  5953 D A2dpStateMachine: make
,11-23 03:56:32.534  5953  5953 I bt_bluedroid: get_profile_interface a2dp
,11-23 03:56:32.534  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 03:56:32.536  5953  5984 D A2dpStateMachine: Enter Disconnected: -2
11-23 03:56:32.536  5953  5953 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 03:56:32.537  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
11-23 03:56:32.538  5953  5953 D HidService: Received start request. Starting profile...
,11-23 03:56:32.538  5953  5953 I bt_bluedroid: get_profile_interface hidhost
11-23 03:56:32.538  5953  5953 D HidService: setHidService(): set to: null
11-23 03:56:32.538  5953  5969 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b0a56d
11-23 03:56:32.538  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 03:56:32.539  5953  5953 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 03:56:32.539  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
11-23 03:56:32.540  5953  5953 D HealthService: Received start request. Starting profile...
,11-23 03:56:32.542  5953  5953 I bt_bluedroid: get_profile_interface health
,11-23 03:56:32.543  5953  5953 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 03:56:32.544  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:32.544  5953  5953 D PanService: Received start request. Starting profile...
,11-23 03:56:32.545  5953  5953 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 03:56:32.545  5953  5953 I bt_bluedroid: get_profile_interface pan
11-23 03:56:32.545  5953  5969 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 03:56:32.547  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:32.550  5953  5953 D BluetoothMapService: Received start request. Starting profile...
,11-23 03:56:32.550  5953  5953 D BluetoothMapService: start()
11-23 03:56:32.553  5953  5953 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 03:56:32.555  5953  5953 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 03:56:32.555  5953  5953 D BluetoothMapAppObserver: createReceiver()
11-23 03:56:32.556  5953  5953 D BluetoothMapAppObserver: initObservers()
,11-23 03:56:32.556  5953  5953 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 03:56:32.563  5953  5953 V SapService: SapBinder()
11-23 03:56:32.564  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:32.565  5953  5953 D SapService: Received start request. Starting profile...
11-23 03:56:32.565  5953  5953 V SapService: start()
,11-23 03:56:32.567  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:32.567  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:32.567  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 03:56:32.567  5953  5981 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 03:56:32.567  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:32.567  5953  5953 V BluetoothAdapterState: isTurningOff()=false
,11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:32.568  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:32.569  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:32.569  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 03:56:32.569  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:32.570  5953  5953 V BluetoothAdapterState: isTurningOff()=false
11-23 03:56:32.570  5953  5953 V BluetoothAdapterState: isTurningOn()=true
11-23 03:56:32.570  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
11-23 03:56:32.570  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
11-23 03:56:32.570  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-23 03:56:32.570  5953  5965 D BluetoothAdapterProperties: ScanMode =  20
11-23 03:56:32.570  5953  5965 D BluetoothAdapterProperties: State =  11
11-23 03:56:32.571  5953  5965 D BluetoothAdapterProperties: Setting state to 12
11-23 03:56:32.571  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 03:56:32.571  3164  4022 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 03:56:32.571  5953  5969 D BluetoothAdapterProperties: Scan Mode:21
11-23 03:56:32.572  5953  5969 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 03:56:32.572  5953  5965 I BluetoothAdapterState: Entering OnState
,11-23 03:56:32.575  5753  5767 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 03:56:32.576  3164  3164 D BluetoothInputDevice: Proxy object connected
11-23 03:56:32.576  3164  3164 D HidProfile: Bluetooth service connected
11-23 03:56:32.577  3164  3177 D BluetoothPan: onBluetoothStateChange on: true
11-23 03:56:32.580  3164  3180 D BluetoothMap: onBluetoothStateChange: up=true
,11-23 03:56:32.581  3164  3164 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 03:56:32.581  3164  3164 D PanProfile: Bluetooth service connected
11-23 03:56:32.582  3831  4049 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:32.583  5953  5953 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 03:56:32.583  5753  5948 D BluetoothPan: onBluetoothStateChange on: true
,11-23 03:56:32.583  5953  5953 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-23 03:56:32.585  5753  5767 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 03:56:32.586  5953  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 03:56:32.586   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:32.586  5753  5764 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 03:56:32.587  5953  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 03:56:32.585  5753  5753 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 03:56:32.588  5753  5753 D PanProfile: Bluetooth service connected
11-23 03:56:32.589  3164  3177 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:32.589  5753  5753 D BluetoothInputDevice: Proxy object connected
,11-23 03:56:32.589  5753  5753 D HidProfile: Bluetooth service connected
,11-23 03:56:32.589  5953  5953 D ObexServerSockets: Succeed to create listening sockets 
,11-23 03:56:32.589  5953  5953 D ObexServerSockets0: startAccept()
11-23 03:56:32.589  5953  5953 D ObexServerSockets0: prepareForNewConnect()
11-23 03:56:32.589   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:32.589  5753  5948 D BluetoothMap: onBluetoothStateChange: up=true
11-23 03:56:32.590  5953  5953 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 03:56:32.590  5953  5953 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-23 03:56:32.591  5953  5989 D ObexServerSockets0: Accepting socket connection...
11-23 03:56:32.591   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 03:56:32.591   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 03:56:32.591  5953  5990 D ObexServerSockets0: Accepting socket connection...
11-23 03:56:32.592  3164  3164 D BluetoothMap: Proxy object connected
11-23 03:56:32.592  3164  3164 D MapProfile: Bluetooth service connected
11-23 03:56:32.592  3164  3164 D BluetoothMap: getConnectedDevices()
11-23 03:56:32.592  3164  4022 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 03:56:32.593   927   927 D BluetoothA2dp: Proxy object connected
11-23 03:56:32.593  5753  5753 D BluetoothMap: Proxy object connected
,11-23 03:56:32.594  5753  5753 D MapProfile: Bluetooth service connected
11-23 03:56:32.594  5753  5753 D BluetoothMap: getConnectedDevices()
11-23 03:56:32.594  5753  5767 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 03:56:32.596  3164  3177 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 03:56:32.597  3164  3164 D BluetoothA2dp: Proxy object connected
11-23 03:56:32.598   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 03:56:32.600  5953  5953 D BluetoothMapService: onReceive
11-23 03:56:32.600  5953  5953 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 03:56:32.601  5953  5953 D BluetoothMapService: STATE_ON
11-23 03:56:32.601  5753  5753 D BluetoothA2dp: Proxy object connected
11-23 03:56:32.604  5953  5993 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 03:56:32.606  5953  5993 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 03:56:32.606  5953  5993 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 03:56:32.609  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 03:56:32.614  3622  3622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 03:56:32.614  5753  5753 D DockEventReceiver: finishStartingService: stopping service
,11-23 03:56:32.623  5753  5753 D BluetoothPbap: Proxy object connected
,11-23 03:56:32.623  5753  5753 D PbapServerProfile: Bluetooth service connected
,11-23 03:56:32.627  5953  5953 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 03:56:32.627  5953  5953 D ObexServerSockets0: prepareForNewConnect()
11-23 03:56:32.627  5953  5998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 03:56:32.629  3164  3164 D BluetoothPbap: Proxy object connected
11-23 03:56:32.629  3164  3164 D PbapServerProfile: Bluetooth service connected
,11-23 03:56:32.647  5953  6002 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 03:56:32.649  5953  6002 I BtOppRfcommListener: Accept thread started.
,11-23 03:56:32.684  5753  5764 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.685  3164  4022 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.685   927   927 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.685   927   927 D BluetoothHeadset: Proxy object connected
,11-23 03:56:32.685  3164  3164 D HeadsetProfile: Bluetooth service connected
11-23 03:56:32.685  3831  3846 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.685   927   927 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.686  5753  5948 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.686   927   944 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.687  5753  5753 D HeadsetProfile: Bluetooth service connected
,11-23 03:56:32.689  3164  3177 D BluetoothHeadset: Proxy object connected
,11-23 03:56:32.689  5753  5753 D HeadsetProfile: Bluetooth service connected
11-23 03:56:32.689   927   944 D BluetoothHeadset: Proxy object connected
11-23 03:56:32.689  3164  3164 D HeadsetProfile: Bluetooth service connected
,11-23 03:56:32.691   927   944 D BluetoothHeadset: Proxy object connected
,11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:36.392  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 03:56:36.398  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 03:56:36.398  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:36.399  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@daa38fd removed from the list
,11-23 03:56:36.399  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 03:56:36.402  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 03:56:36.403  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8589f2 added. We now have 4 listener(s)
11-23 03:56:36.403  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:56:36.406   927   937 D WifiService: setWifiEnabled: false pid=5693, uid=10077
,11-23 03:56:36.406   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 03:56:41.415  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 03:56:41.416   927   937 D WifiService: setWifiEnabled: true pid=5693, uid=10077
,11-23 03:56:41.416   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 03:56:41.426   507   920 D SoftapController: Softap fwReload - Ok
,11-23 03:56:41.432   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:41.432   507   920 D CommandListener: Trying to bring down wlan0
11-23 03:56:41.435   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 03:56:41.440   927  3019 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 03:56:42.105   927  3019 D wifi    : set interface wlan0 flags (UP)
,11-23 03:56:42.108   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:42.108   927  3019 I WifiHAL : Initializing wifi
,11-23 03:56:42.108   927  3019 I WifiHAL : Creating socket
,11-23 03:56:42.114   927  3019 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 03:56:42.114   927  3019 D wifi    : Did set static halHandle = 0x7f84227900
,11-23 03:56:42.115   927  3019 D wifi    : halHandle = 0x7f84227900, mVM = 0x7fa080d140, mCls = 0x18be
,11-23 03:56:42.115   927  3019 D wifi    : array field set
,11-23 03:56:42.115   927  3019 I WifiNative-HAL: interface[0] = wlan0
,11-23 03:56:42.117   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-23 03:56:42.120   927  6007 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547677698304
11-23 03:56:42.121   927  6007 D wifi    : waitForHalEvents called, vm = 0x7fa080d140, obj = 0x18be, env = 0x7f95d61840
11-23 03:56:42.122   927  3019 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-23 03:56:42.123   927  3019 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-23 03:56:42.167  6008  6008 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 03:56:42.186  6008  6008 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 03:56:42.244  6008  6008 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 03:56:42.245  6008  6008 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 03:56:43.109   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:43.143   927  3019 D WifiConfigStore: Loading config and enabling all networks 
,11-23 03:56:43.172   927  3019 D WifiConfigStore: loaded 0 passpoint configs
,11-23 03:56:43.172   927  3019 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-23 03:56:43.173   927  3019 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 03:56:43.174   927  3019 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 03:56:43.176   927  3019 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 03:56:43.176   927  3019 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 03:56:43.176   927  3019 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 03:56:43.176   927  3019 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 03:56:43.182  5089  5089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 03:56:43.183   927  3019 D WifiNative-HAL: Setting external_sim to 1
,11-23 03:56:43.184   927  3019 D wifi    : setting dfs flag to true, 0x7f84232e60
,11-23 03:56:43.185   927  3019 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 03:56:43.185   927  3019 D wifi    : setting scan oui 0x7f84232e60
,11-23 03:56:43.185   927  3019 D WifiHAL : Sending mac address OUI
,11-23 03:56:43.191   927  3019 E native  : do suspend false
,11-23 03:56:43.204   927  3019 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 03:56:43.205   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 03:56:43.205   927   927 D RttService: SCAN_AVAILABLE : 3
11-23 03:56:43.205   927  3129 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 03:56:43.206   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:43.212   927  3018 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-23 03:56:43.212   927  3018 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 03:56:43.228   927  3018 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 03:56:43.229   927  3018 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-23 03:56:43.236   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=165232 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=24 mControllerEnergyUsed=91 }
,11-23 03:56:44.111   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:45.112   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:46.113   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:56:46.304  6008  6008 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:56:46.318  6008  6008 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:56:46.326  6008  6008 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:56:46.364   927  3019 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 03:56:46.366   927  3019 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 03:56:46.366   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 03:56:46.385   927  3019 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 03:56:46.429   927  3019 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 03:56:46.433  6008  6008 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 03:56:46.438  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 03:56:46.441  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 03:56:46.441  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:46.441  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8589f2 removed from the list
,11-23 03:56:46.441  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:56:46.445  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-23 03:56:46.445  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-23 03:56:46.447  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c03666 Bundle[{}]
,11-23 03:56:46.447  5693  5739 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 03:56:46.448  5693  5739 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 03:56:46.448  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-23 03:56:46.448  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-23 03:56:46.449  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 03:56:46.449  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-23 03:56:46.456  5693  5739 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-23 03:56:46.457  5693  5739 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 03:56:46.457  5693  5739 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-23 03:56:46.459  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 03:56:46.459  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0fa843 added. We now have 3 listener(s)
11-23 03:56:46.461  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.461  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.461  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.461  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.461  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c13ec0 added. We now have 4 listener(s)
11-23 03:56:46.461  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:56:46.462  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 03:56:46.463  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.463  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce667f9 added. We now have 4 listener(s)
11-23 03:56:46.464  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 03:56:46.464  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.464  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.464  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.465  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55e533e added. We now have 5 listener(s)
11-23 03:56:46.465  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.465  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:56:46.465  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:56:46.465  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:56:46.465  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.465  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.465  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.465  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0fa843 removed from the list
11-23 03:56:46.465  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:46.465  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c13ec0 removed from the list
11-23 03:56:46.465  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:56:46.465  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.465  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.467  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.467  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.467  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.467  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.467  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 03:56:46.467  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.467  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c13ec0 not in the list
11-23 03:56:46.468  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.468  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.469  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.469  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.469  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.469  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.469  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.469  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.469  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55e533e removed from the list
11-23 03:56:46.469  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.469  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.469  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 03:56:46.469  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce667f9 removed from the list
11-23 03:56:46.470  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.470  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67a859f added. We now have 3 listener(s)
11-23 03:56:46.471  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.471  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.471  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.472  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.472  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edb86ec added. We now have 4 listener(s)
11-23 03:56:46.472  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.472  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 03:56:46.473  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.473  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1c8ab5 added. We now have 4 listener(s)
11-23 03:56:46.475  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.475  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 03:56:46.475  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.476  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.476  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@468654a added. We now have 5 listener(s)
11-23 03:56:46.476  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.476  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:56:46.476  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 03:56:46.476  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 03:56:46.476  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:56:46.476  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 03:56:46.478  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 03:56:46.481  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 03:56:46.481  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 03:56:46.481  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 03:56:46.486  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.486  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 03:56:46.487  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 03:56:46.487  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 03:56:46.487  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 03:56:46.489  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.490  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 03:56:46.490  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-23 03:56:46.490  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 03:56:46.490  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 03:56:46.490  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.490  5693  5739 D BluetoothAdapter: STATE_ON
,11-23 03:56:46.493  5953  5992 D BtGatt.GattService: registerClient() - UUID=4b371e22-d1cf-4535-af7a-9f39f3245f32
,11-23 03:56:46.494  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=4b371e22-d1cf-4535-af7a-9f39f3245f32, clientIf=5
,11-23 03:56:46.495  5693  5702 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 03:56:46.496  5953  5991 D BtGatt.GattService: start scan with filters
,11-23 03:56:46.500  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 03:56:46.500  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.500  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 03:56:46.500  5953  5972 D BtGatt.ScanManager: handling starting scan
,11-23 03:56:46.500  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.500  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 03:56:46.500  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 03:56:46.500  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.500  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 03:56:46.500  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 03:56:46.500  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.501  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.501  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.501  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.501  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 03:56:46.501  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.501  5953  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a679fcb
,11-23 03:56:46.503  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.503  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:56:46.503  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.503  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.504  5693  5739 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 03:56:46.504  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 03:56:46.504  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.504  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 03:56:46.504  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.504  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:56:46.504  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.504  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 03:56:46.506  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.506  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.506  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.506  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 03:56:46.506  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:56:46.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 03:56:46.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 03:56:46.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.506  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 03:56:46.507  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.507  5693  5739 D BluetoothAdapter: STATE_ON
,11-23 03:56:46.507  5953  5992 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 03:56:46.508  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 03:56:46.508  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:56:46.509  5953  5964 D BtGatt.GattService: stopScan() - queue size =1
11-23 03:56:46.509  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 03:56:46.509  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.510  5953  5963 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 03:56:46.510  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 03:56:46.510  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 03:56:46.510  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.510  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 03:56:46.510  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.511  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 03:56:46.511  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 03:56:46.512  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 03:56:46.512  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.513  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.513  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:56:46.513  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.513  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.513  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:56:46.513  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:56:46.513  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 03:56:46.513  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.513  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 03:56:46.513  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 03:56:46.513  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.513  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.514  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.514  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:56:46.514  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.514  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.515  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 03:56:46.515  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.516  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.516  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.516  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.516  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
11-23 03:56:46.516  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stop,ping all activities and killing connections
11-23 03:56:46.516  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 03:56:46.516  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:56:46.516  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:56:46.516  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.516  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.516  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.516  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67a859f removed from the list
11-23 03:56:46.516  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.517  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edb86ec removed from the list
11-23 03:56:46.517  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:56:46.517  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.517  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.518  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.518  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.518  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.518  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 03:56:46.518  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.518  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.518  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edb86ec not in the list
11-23 03:56:46.518  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.518  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.521  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.521  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.521  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.522  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.522  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.522  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.522  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@468654a removed from the list
11-23 03:56:46.522  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.522  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.522  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.522  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1c8ab5 removed from the list
,11-23 03:56:46.523  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.523  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8918997 added. We now have 3 listener(s)
11-23 03:56:46.525  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.525  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.525  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.525  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.526  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fadc784 added. We now have 4 listener(s)
11-23 03:56:46.526  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 03:56:46.526  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 03:56:46.527  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 03:56:46.527  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.527  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.527  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e05b6d added. We now have 4 listener(s)
,11-23 03:56:46.529  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.529  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.529  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.529  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.529  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b053a2 added. We now have 5 listener(s)
11-23 03:56:46.530  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.530  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:56:46.530  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:56:46.530  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 03:56:46.530  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 03:56:46.531  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 03:56:46.531  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 03:56:46.532  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 03:56:46.532  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.532  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 03:56:46.535  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 03:56:46.535  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 03:56:46.535  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 03:56:46.535  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 03:56:46.538  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.538  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 03:56:46.539  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 03:56:46.539  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 03:56:46.539  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 03:56:46.539  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:56:46.539  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.540  5953  5969 E BtGatt.ContextMap: Context not found for ID 5
,11-23 03:56:46.542  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.542  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-23 03:56:46.542  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 03:56:46.542  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 03:56:46.542  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 03:56:46.542  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.543  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:56:46.546  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 03:56:46.546  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.546  5953  5964 D BtGatt.GattService: registerClient() - UUID=d98cf9cd-e9db-43af-8f82-23eeb8f0cb90
11-23 03:56:46.546  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
11-23 03:56:46.546  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=d98cf9cd-e9db-43af-8f82-23eeb8f0cb90, clientIf=5
11-23 03:56:46.546  5693  5702 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 03:56:46.547  5953  5992 D BtGatt.GattService: start scan with filters
,11-23 03:56:46.549  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 03:56:46.549  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.549  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 03:56:46.549  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.550  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 03:56:46.550  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 03:56:46.550  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.550  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 03:56:46.550  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 03:56:46.550  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.550  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.550  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.550  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.551  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 03:56:46.551  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.551  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 03:56:46.551  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.552  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 03:56:46.553  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.553  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:56:46.553  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.553  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.553  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:56:46.553  5693  5739 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 03:56:46.553  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:56:46.553  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.553  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:56:46.553  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 03:56:46.553  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.553  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.553  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:56:46.553  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.553  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.553  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8918997 removed from the list
11-23 03:56:46.554  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.554  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fadc784 removed from the list
11-23 03:56:46.554  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:56:46.554  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.554  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:56:46.554  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.554  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.554  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 03:56:46.554  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.554  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:56:46.554  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.555  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.555  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.555  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.555  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.555  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.555  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.555  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.555  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.555  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.555  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:56:46.555  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fadc784 not in the list
11-23 03:56:46.555  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 03:56:46.555  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.555  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 03:56:46.555  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 03:56:46.556  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.556  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.556  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.556  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 03:56:46.556  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.557  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:56:46.557  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.557  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:56:46.557  5953  5982 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 03:56:46.558  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 03:56:46.558  5953  5972 D BtGatt.ScanManager: handling starting scan
,11-23 03:56:46.558  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:56:46.559  5953  5992 D BtGatt.GattService: stopScan() - queue size =1
,11-23 03:56:46.559  5953  5964 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 03:56:46.560  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 03:56:46.562  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 03:56:46.562  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.563  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.563  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 03:56:46.563  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.563  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.563  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.564  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 03:56:46.564  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.564  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.564  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.564  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:56:46.564  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b053a2 removed from the list
11-23 03:56:46.564  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.564  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:56:46.564  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.564  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 03:56:46.564  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-23 03:56:46.564  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.564  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.564  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e05b6d removed from the list
11-23 03:56:46.564  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 03:56:46.564  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 03:56:46.564  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.564  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.564  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.564  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 03:56:46.564  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.564  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.564  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.564  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f16148f added. We now have 3 listener(s)
11-23 03:56:46.565  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.565  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.565  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.566  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.566  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.566  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.566  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.566  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c44831c added. We now have 4 listener(s)
11-23 03:56:46.566  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.566  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 03:56:46.567  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 03:56:46.567  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc68b25 added. We now have 4 listener(s)
11-23 03:56:46.568  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.568  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.569  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.569  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.569  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28cb4fa added. We now have 5 listener(s)
11-23 03:56:46.569  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.569  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:56:46.569  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 03:56:46.569  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 03:56:46.569  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 03:56:46.569  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 03:56:46.571  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 03:56:46.573  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 03:56:46.573  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 03:56:46.573  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 03:56:46.573  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 03:56:46.573  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.573  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
11-23 03:56:46.573  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 03:56:46.576  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.576  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 03:56:46.577  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 03:56:46.577  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 03:56:46.577  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 03:56:46.580  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.580  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 03:56:46.580  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 03:56:46.580  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 03:56:46.580  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 03:56:46.581  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.581  5693  5739 D BluetoothAdapter: STATE_ON
,11-23 03:56:46.583  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 03:56:46.583  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.584  5953  5964 D BtGatt.GattService: registerClient() - UUID=30aa5505-d9da-40aa-90a5-c6c6f34fdb39
11-23 03:56:46.584  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=30aa5505-d9da-40aa-90a5-c6c6f34fdb39, clientIf=5
,11-23 03:56:46.584  5693  5702 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 03:56:46.585  5953  5992 D BtGatt.GattService: start scan with filters
11-23 03:56:46.587  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 03:56:46.587  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.587  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 03:56:46.587  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.587  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 03:56:46.587  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 03:56:46.587  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.587  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 03:56:46.587  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 03:56:46.587  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.588  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.588  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.588  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.588  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 03:56:46.588  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.588  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 03:56:46.588  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.589  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 03:56:46.590  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.590  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:56:46.590  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.591  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.591  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.592  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:56:46.593  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:56:46.593  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:56:46.593  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.593  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.593  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:56:46.593  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.593  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.593  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f16148f removed from the list
,11-23 03:56:46.593  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.593  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c44831c removed from the list
11-23 03:56:46.593  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:56:46.593  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.593  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:56:46.593  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.593  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.593  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 03:56:46.593  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 03:56:46.593  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 03:56:46.593  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.593  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.594  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.594  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.594  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 03:56:46.594  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:56:46.594  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.594  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.594  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.594  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.594  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.594  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.595  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.595  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.595  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c44831c not in the list
11-23 03:56:46.595  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 03:56:46.595  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.595  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 03:56:46.595  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 03:56:46.595  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.595  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.595  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.595  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 03:56:46.595  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.595  5693  5739 D BluetoothAdapter: STATE_ON
,11-23 03:56:46.596  5953  5982 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 03:56:46.596  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 03:56:46.596  5693  5739 D BluetoothAdapter: STATE_ON
11-23 03:56:46.597  5953  5964 D BtGatt.GattService: stopScan() - queue size =0
11-23 03:56:46.597  5953  5963 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 03:56:46.597  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 03:56:46.597  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.598  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 03:56:46.598  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 03:56:46.599  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 03:56:46.599  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.600  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 03:56:46.600  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:56:46.600  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.600  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 03:56:46.600  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.600  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.600  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.600  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
11-23 03:56:46.601  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.601  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:46.601  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28cb4fa removed from the list
11-23 03:56:46.601  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.601  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.601  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.601  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc68b25 removed from the list
11-23 03:56:46.602  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.602  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b520687 added. We now have 3 listener(s)
11-23 03:56:46.603  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.603  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.603  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.603  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 03:56:46.604  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35419b4 added. We now have 4 listener(s)
,11-23 03:56:46.604  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.601  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:56:46.604  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 03:56:46.604  5693  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 03:56:46.604  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.604  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 03:56:46.604  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 03:56:46.604  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.605  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.605  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.605  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 03:56:46.605  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.605  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.605  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 03:56:46.605  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.605  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 03:56:46.606  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.606  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 03:56:46.606  5693  5693 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 03:56:46.607  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 03:56:46.608  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 03:56:46.609  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdbf9dd added. We now have 4 listener(s)
11-23 03:56:46.610  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:56:46.610  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.610  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 03:56:46.610  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 03:56:46.610  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 03:56:46.610  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 03:56:46.611  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8e952 added. We now have 5 listener(s)
11-23 03:56:46.611  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 03:56:46.611  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 03:56:46.611  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:56:46.611  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 03:56:46.611  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.611  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.611  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.611  5953  5972 D BtGatt.ScanManager: handling starting scan
11-23 03:56:46.611  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b520687 removed from the list
11-23 03:56:46.611  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:46.611  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35419b4 removed from the list
11-23 03:56:46.611  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
11-23 03:56:46.612  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.612  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.612  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.612  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.613  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.613  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.613  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 03:56:46.613  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 03:56:46.613  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35419b4 not in the list
11-23 03:56:46.613  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.613  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.616  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 03:56:46.616  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.616  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.617  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.617  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 03:56:46.617  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 03:56:46.617  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 03:56:46.617  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 03:56:46.617  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 03:56:46.617  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b8e952 removed from the list
11-23 03:56:46.617  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 03:56:46.617  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 03:56:46.617  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 03:56:46.617  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdbf9dd removed from the list
11-23 03:56:46.618  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 03:56:46.618  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 03:56:46.619  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 03:56:46.619  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 03:56:46.619  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 03:56:46.619  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 03:56:46.621  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 03:56:46.622  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.622  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
11-23 03:56:46.622  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 03:56:46.630  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 03:56:46.630  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.635  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 03:56:46.635  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.636  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 03:56:46.640  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 03:56:46.640  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.641  5953  5969 E BtGatt.ContextMap: Context not found for ID 5
,11-23 03:56:46.646  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 03:56:46.646  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 03:56:46.647  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
,11-23 03:56:46.651  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 03:56:46.652  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.652  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 03:56:46.656  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 03:56:46.656  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 03:56:46.864  6008  6008 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 03:56:46.905  6008  6008 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 03:56:46.906  6008  6008 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 03:56:46.916   927  3019 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 03:56:46.917   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 03:56:46.917   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 03:56:46.936   927  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 03:56:46.948   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:46.953   927  3019 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 03:56:46.959   927  6013 D DhcpClient: Receive thread started
,11-23 03:56:46.964   927  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 03:56:46.964   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 03:56:46.964   927  3021 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 03:56:47.014  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 03:56:47.053   927  3019 E native  : do suspend false
,11-23 03:56:47.065  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 03:56:47.078   927  6012 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 03:56:47.096   927  6013 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,11-23 03:56:47.097   927  6012 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,11-23 03:56:47.099   927  6012 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-23 03:56:47.106  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 03:56:47.114   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 03:56:47.122   927  6013 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 03:56:47.123   927  6012 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-23 03:56:47.126   507   920 D CommandListener: Setting iface cfg
,11-23 03:56:47.131   927  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 03:56:47.143   927  6012 D DhcpClient: Scheduling renewal in 86399s
,11-23 03:56:47.149   927  3019 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-23 03:56:47.150   927  3019 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 03:56:47.153   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 03:56:47.158   927  3019 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 03:56:47.161   927  3021 D ConnectivityService: Adding iface wlan0 to network 102
,11-23 03:56:47.205   927  3021 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 03:56:47.206   927  3021 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-23 03:56:47.207   927  3021 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-23 03:56:47.209   927  3021 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 03:56:47.211   927  3021 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 03:56:47.218   927  3021 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:56:47.223   927  3021 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 03:56:47.223   927  3021 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-23 03:56:47.224   927  3021 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 03:56:47.224   927  3019 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 03:56:47.224   927  3021 D ConnectivityService:    accepting network in place of null
11-23 03:56:47.224   927  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 03:56:47.224   927  3021 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 03:56:47.237   927  6011 D NetlinkSocketObserver: NeighborEvent{elapsedMs=169232, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 03:56:47.246   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 03:56:47.268   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 03:56:47.272   927  3021 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-23 03:56:47.272   927  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 03:56:47.272  3797  3944 W QCNEJ   : |CORE| network available: 102
11-23 03:56:47.273   927  3021 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-23 03:56:47.274   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-23 03:56:47.280  3797  3944 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 03:56:47.281  3797  3944 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 03:56:47.281  3797  3944 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 03:56:47.291  4994  4994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-23 03:56:47.293  5115  5139 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 03:56:47.293  5115  5139 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-23 03:56:47.293  5115  5139 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 03:56:47.293  5115  5139 E SarControlService: no key has been found,reset the power
11-23 03:56:47.293  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 03:56:47.293  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 03:56:47.293  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 03:56:47.294  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:47.294  5140  5140 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 03:56:47.295  5115  5152 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 03:56:47.295  5115  5152 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 03:56:47.295  5115  5152 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 03:56:47.296  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 03:56:47.296  5140  5140 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 03:56:47.298  4001  4001 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 03:56:47.303  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000f003000000000000ffffffff]
11-23 03:56:47.303  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:47.303  5140  5154 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-23 03:56:47.304  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 03:56:47.304  5115  5125 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 03:56:47.304  4001  4001 D SystemUpdateService: onCreate
11-23 03:56:47.305   927  6010 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
11-23 03:56:47.306  5140  5154 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7d1542 HexData = [00000000f103000000000000ffffffff]
11-23 03:56:47.306  5140  5154 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 03:56:47.306  5140  5154 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,11-23 03:56:47.308  5140  5140 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 03:56:47.308  5115  5126 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 03:56:47.310  4001  4001 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 03:56:47.323  4001  4001 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 03:56:47.324  4001  5478 I iu.UploadsManager: num queued entries: 0
11-23 03:56:47.325  4001  5478 I iu.UploadsManager: num updated entries: 0
11-23 03:56:47.325  4001  5478 I iu.SyncManager: NEXT; no task
,11-23 03:56:47.344  4001  6023 I SystemUpdateService: active receiver: enabled
,11-23 03:56:47.346  4001  4001 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 03:56:47.349  4001  4001 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 03:56:47.353  5818  5818 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 03:56:47.355   927  6010 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 08:56:47 GMT], X-Android-Received-Millis=[1479891407353], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479891407328]}
,11-23 03:56:47.356   927  3021 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 03:56:47.356   927  3021 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-23 03:56:47.356   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:56:47.357   927  3021 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 03:56:47.360  5818  5818 D SprintDMHelper: simOperator: 
11-23 03:56:47.360  5818  5818 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 03:56:47.389  4001  6023 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 03:56:47.405  4001  6023 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 03:56:47.405  4001  6023 I SystemUpdateService: now status is 0 (complete)
11-23 03:56:47.405  4001  6023 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 03:56:47.406  4001  6023 I SystemUpdateService: file has been verified
11-23 03:56:47.406  4001  6023 I SystemUpdateService: OTA package size = 21989297
,11-23 03:56:47.408  3622  6034 I VacuumService: Vacuum at: now=1479891407408 tag=VacuumService
,11-23 03:56:47.410  4001  6023 I SystemUpdateService: showing system update notification
,11-23 03:56:47.425  4001  4001 D SystemUpdateService: onDestroy
,11-23 03:56:47.433  3622  6037 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-23 03:56:47.473  5089  6030 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-23 03:56:47.480  3622  6035 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-23 03:56:47.482  3622  6035 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-23 03:56:47.523  3622  6035 W Uploader:  no longer exists, so no auth token.
,11-23 03:56:47.530  3622  6037 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 03:56:47.878  3622  6040 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 03:56:48.120  3622  6037 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 03:56:48.187  3622  6035 W Uploader:  no longer exists, so no auth token.
,11-23 03:56:48.201  3622  6040 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 03:56:48.288  3622  6037 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 03:56:48.783  5693  6045 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 03:56:48.783  5693  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:56:49.591  5693  6045 W !!      : call onHalfStreamCopied
,11-23 03:56:49.591  5693  6045 I testCopyDataAndClose: closing input stream
,11-23 03:56:49.987   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 03:56:50.368  5693  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 03:56:54.174  5693  6046 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:56:54.174  5693  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:56:55.229   927  3021 D ConnectivityService: handlePromptUnvalidated 102
,11-23 03:56:56.029   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:56:56.174  5693  5739 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-23 03:56:56.174  5693  5739 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:56:56.174  5693  5739 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-23 03:56:56.231  5693  6046 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 03:56:56.231  5693  6046 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:56:56.231  5693  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-23 03:56:56.297  5693  6047 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 03:56:56.297  5693  6047 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 03:56:57.952  5693  6047 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 03:56:58.228   927  3019 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-23 03:56:59.062   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:57:01.771  5693  6048 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:57:01.771  5693  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:57:01.771  5693  6048 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:57:01.771  5693  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 03:57:01.771  5693  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 03:57:01.771  5693  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 03:57:01.772  5693  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 03:57:01.772  5693  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 03:57:01.772  5693  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 03:57:01.772  5693  6048 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 03:57:01.772  5693  6048 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 03:57:01.772  5693  6048 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:57:01.772  5693  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-23 03:57:01.774  5693  5739 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-23 03:57:01.777  5693  6049 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:57:01.777  5693  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 03:57:01.777  5693  6049 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-23 03:57:01.778  5693  6049 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:57:01.778  5693  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 03:57:01.778  5693  6049 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 03:57:01.778  5693  6049 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 03:57:01.778  5693  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 03:57:01.783  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 03:57:01.783  5693  5739 I jxcore-log: 
,11-23 03:57:01.783  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 03:57:01.783  5693  5739 I jxcore-log: 
11-23 03:57:01.784  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 03:57:01.784  5693  5739 I jxcore-log: 
11-23 03:57:01.784  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 03:57:01.784  5693  5739 I jxcore-log: 
11-23 03:57:01.784  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG UnitTest_app: 'Total duration:  90911'
11-23 03:57:01.784  5693  5739 I jxcore-log: 
,11-23 03:57:01.787  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 03:57:01.787  5693  5739 I jxcore-log: 
,11-23 03:57:01.791  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 03:57:01.791  5693  5739 I jxcore-log: 
11-23 03:57:01.792  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 03:57:01.792  5693  5739 I jxcore-log: 
11-23 03:57:01.792  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 03:57:01.792  5693  5739 I jxcore-log: 
,11-23 03:57:01.793  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 03:57:01.793  5693  5739 I jxcore-log: 
11-23 03:57:01.793  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.793  5693  5739 I jxcore-log: 
,11-23 03:57:01.793  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 03:57:01.793  5693  5739 I jxcore-log: 
11-23 03:57:01.793  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.793  5693  5739 I jxcore-log: 
,11-23 03:57:01.794  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 03:57:01.794  5693  5739 I jxcore-log: 
,11-23 03:57:01.794  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 03:57:01.794  5693  5739 I jxcore-log: 
11-23 03:57:01.794  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 03:57:01.794  5693  5739 I jxcore-log: 
,11-23 03:57:01.795  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 03:57:01.795  5693  5739 I jxcore-log: 
11-23 03:57:01.795  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.795  5693  5739 I jxcore-log: 
11-23 03:57:01.795  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 03:57:01.795  5693  5739 I jxcore-log: 
,11-23 03:57:01.795  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.795  5693  5739 I jxcore-log: 
11-23 03:57:01.795  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 03:57:01.795  5693  5739 I jxcore-log: 
,11-23 03:57:01.796  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.796  5693  5739 I jxcore-log: 
11-23 03:57:01.796  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 03:57:01.796  5693  5739 I jxcore-log: 
11-23 03:57:01.796  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 03:57:01.796  5693  5739 I jxcore-log: 
11-23 03:57:01.796  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 03:57:01.796  5693  5739 I jxcore-log: 
11-23 03:57:01.797  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 03:57:01.797  5693  5739 I jxcore-log: 
11-23 03:57:01.797  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 03:57:01.797  5693  5739 I jxcore-log: 
11-23 03:57:01.797  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 03:57:01.797  5693  5739 I jxcore-log: 
11-23 03:57:01.798  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 03:57:01.798  5693  5739 I jxcore-log: 
11-23 03:57:01.798  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 03:57:01.798  5693  5739 I jxcore-log: 
11-23 03:57:01.800  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 03:57:01.800  5693  5739 I jxcore-log: 
11-23 03:57:01.800  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 03:57:01.800  5693  5739 I jxcore-log: 
11-23 03:57:01.801  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-23 03:57:01.801  5693  5739 I jxcore-log: 
11-23 03:57:01.801  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 03:57:01.801  5693  5739 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-23 03:57:01.801  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 03:57:01.801  5693  5739 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 03:57:01.801  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 03:57:01.801  5693  5739 I jxcore-log: 
,11-23 03:57:01.802  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.802  5693  5739 I jxcore-log: 
11-23 03:57:01.802  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 03:57:01.802  5693  5739 I jxcore-log: 
11-23 03:57:01.802  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.802  5693  5739 I jxcore-log: 
11-23 03:57:01.802  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 03:57:01.802  5693  5739 I jxcore-log: 
11-23 03:57:01.802  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 03:57:01.802  5693  5739 I jxcore-log: 
,11-23 03:57:01.808  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 03:57:01.808  5693  5739 I jxcore-log: 
11-23 03:57:01.808  5693  5739 I jxcore-log: 2016-11-23 08:57:01 - WARN testUtils: 'myNameCallback not set!'
11-23 03:57:01.808  5693  5739 I jxcore-log: 
,11-23 03:57:01.813  5693  5693 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 03:57:03.851  5693  5739 I jxcore-log: 2016-11-23 08:57:03 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 03:57:03.851  5693  5739 I jxcore-log: 
,11-23 03:57:03.853  5693  5739 I jxcore-log: 2016-11-23 08:57:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 03:57:03.853  5693  5739 I jxcore-log: 
,11-23 03:57:04.202  5693  5739 I jxcore-log: 2016-11-23 08:57:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 03:57:04.202  5693  5739 I jxcore-log: 
,11-23 03:57:04.213  5693  5739 I jxcore-log: 2016-11-23 08:57:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 03:57:04.213  5693  5739 I jxcore-log: 
,11-23 03:57:05.312  5693  5739 I jxcore-log: 2016-11-23 08:57:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 03:57:05.312  5693  5739 I jxcore-log: 
,11-23 03:57:05.500  5693  5739 I jxcore-log: 2016-11-23 08:57:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 03:57:05.500  5693  5739 I jxcore-log: 
,11-23 03:57:05.505  5693  5739 I jxcore-log: 2016-11-23 08:57:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 03:57:05.505  5693  5739 I jxcore-log: 
,11-23 03:57:05.510  5693  5739 I jxcore-log: 2016-11-23 08:57:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 03:57:05.510  5693  5739 I jxcore-log: 
,11-23 03:57:05.992  5693  5739 I jxcore-log: 2016-11-23 08:57:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 03:57:05.992  5693  5739 I jxcore-log: 
,11-23 03:57:06.037  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 03:57:06.037  5693  5739 I jxcore-log: 
,11-23 03:57:06.050  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 03:57:06.050  5693  5739 I jxcore-log: 
,11-23 03:57:06.054  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 03:57:06.054  5693  5739 I jxcore-log: 
,11-23 03:57:06.323  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 03:57:06.323  5693  5739 I jxcore-log: 
,11-23 03:57:06.450  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 03:57:06.450  5693  5739 I jxcore-log: 
,11-23 03:57:06.830  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 03:57:06.830  5693  5739 I jxcore-log: 
,11-23 03:57:06.838  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 03:57:06.838  5693  5739 I jxcore-log: 
,11-23 03:57:06.842  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 03:57:06.842  5693  5739 I jxcore-log: 
,11-23 03:57:06.848  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 03:57:06.848  5693  5739 I jxcore-log: 
,11-23 03:57:06.853  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 03:57:06.853  5693  5739 I jxcore-log: 
,11-23 03:57:06.881  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 03:57:06.881  5693  5739 I jxcore-log: 
,11-23 03:57:06.916  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 03:57:06.916  5693  5739 I jxcore-log: 
,11-23 03:57:06.924  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 03:57:06.924  5693  5739 I jxcore-log: 
,11-23 03:57:06.930  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 03:57:06.930  5693  5739 I jxcore-log: 
,11-23 03:57:06.946  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 03:57:06.946  5693  5739 I jxcore-log: 
,11-23 03:57:06.961  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 03:57:06.961  5693  5739 I jxcore-log: 
,11-23 03:57:06.967  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 03:57:06.967  5693  5739 I jxcore-log: 
,11-23 03:57:06.972  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 03:57:06.972  5693  5739 I jxcore-log: 
,11-23 03:57:06.985  5693  5739 I jxcore-log: 2016-11-23 08:57:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 03:57:06.985  5693  5739 I jxcore-log: 
,11-23 03:57:07.003  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 03:57:07.003  5693  5739 I jxcore-log: 
,11-23 03:57:07.017  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 03:57:07.017  5693  5739 I jxcore-log: 
,11-23 03:57:07.028  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 03:57:07.028  5693  5739 I jxcore-log: 
,11-23 03:57:07.040  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 03:57:07.040  5693  5739 I jxcore-log: 
,11-23 03:57:07.051  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 03:57:07.051  5693  5739 I jxcore-log: 
,11-23 03:57:07.064  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 03:57:07.064  5693  5739 I jxcore-log: 
,11-23 03:57:07.074  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 03:57:07.074  5693  5739 I jxcore-log: 
,11-23 03:57:07.080  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 03:57:07.080  5693  5739 I jxcore-log: 
,11-23 03:57:07.102  5693  5739 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 03:57:07.103  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 03:57:07.103  5693  5739 I jxcore-log: 
,11-23 03:57:07.115   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:07.134  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 03:57:07.134  5693  5739 I jxcore-log: 
,11-23 03:57:07.371  5693  5739 I jxcore-log: 2016-11-23 08:57:07 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 03:57:07.371  5693  5739 I jxcore-log: 
,11-23 03:57:08.117   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:09.118   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:10.119   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:11.120   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:12.121   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 03:57:27.212   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:57:37.122   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 03:57:37.122   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 03:57:47.123   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:48.125   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:49.126   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:50.128   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:50.984  6008  6008 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 03:57:51.129   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:52.130   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 03:57:57.132   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:58.134   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:57:59.135   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:00.136   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:01.137   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:02.138   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 03:58:07.217   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:58:12.139   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:13.140   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:14.142   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:15.143   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:16.145   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:17.145   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 03:58:27.218   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:58:32.147   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:33.148   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:34.150   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:35.151   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:36.152   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:37.153   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 03:58:57.086   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:58:57.155   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:58.156   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:58:59.157   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:00.107   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:59:00.158   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:01.158   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:02.159   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 03:59:07.222   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:59:09.179   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:59:12.209   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:59:27.160   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 03:59:27.160   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 03:59:27.222   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:59:42.161   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:43.163   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:44.164   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:45.166   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:46.167   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:47.168   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 03:59:47.223   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 03:59:48.523   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:59:51.557   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 03:59:52.169   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:53.171   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:54.172   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:55.173   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:56.175   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 03:59:57.175   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 04:00:07.176   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:08.178   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:09.179   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:10.181   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:11.182   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:12.183   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 04:00:27.185   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:27.225   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 04:00:28.186   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:29.188   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:30.189   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:31.190   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:32.191   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 04:00:47.227   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 04:00:52.192   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:53.193   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:54.195   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:55.196   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:56.198   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:00:57.199   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 04:01:07.245   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 04:01:22.199   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 04:01:22.200   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 04:01:27.247   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 04:01:34.493   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 04:01:37.524   927  3021 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 04:01:42.201   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:43.202   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:44.204   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:45.205   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:46.206   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:47.207   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 04:01:47.248   927  3019 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 04:01:52.209   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:53.210   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:54.211   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:55.212   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:56.213   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 04:01:57.214   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 04:02:00.929  5693  5739 I jxcore-log: 2016-11-23 09:02:00 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 04:02:00.929  5693  5739 I jxcore-log: 
,11-23 04:02:01.279  5693  5739 I jxcore-log: 2016-11-23 09:02:01 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 04:02:01.279  5693  5739 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 04:02:01.279  5693  5739 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 04:02:01.279  5693  5739 I jxcore-log: emit@events.js:82:1
11-23 04:02:01.279  5693  5739 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 04:02:01.279  5693  5739 I jxcore-log: emit@events.js:82:1''
11-23 04:02:01.279  5693  5739 I jxcore-log: 
,11-23 04:02:01.280  5693  5739 I jxcore-log: 2016-11-23 09:02:01 - DEBUG CoordinatedClient: 'test client failed'
11-23 04:02:01.280  5693  5739 I jxcore-log: 
,11-23 04:02:01.291  5693  5739 I jxcore-log: 2016-11-23 09:02:01 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 04:02:01.291  5693  5739 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 04:02:01.291  5693  5739 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 04:02:01.291  5693  5739 I jxcore-log: emit@events.js:82:1
11-23 04:02:01.291  5693  5739 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 04:02:01.291  5693  5739 I jxcore-log: emit@events.js:82:1''
11-23 04:02:01.291  5693  5739 I jxcore-log: 
11-23 04:02:01.292  5693  5739 I jxcore-log: 2016-11-23 09:02:01 - DEBUG CoordinatedClient: 'test client failed'
11-23 04:02:01.292  5693  5739 I jxcore-log: 
,11-23 04:02:01.297  5693  5739 I jxcore-log: 2016-11-23 09:02:01 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 04:02:01.297  5693  5739 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 04:02:01.297  5693  5739 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 04:02:01.297  5693  5739 I jxcore-log: emit@events.js:82:1
11-23 04:02:01.297  5693  5739 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 04:02:01.297  5693  5739 I jxcore-log: emit@events.js:82:1''
11-23 04:02:01.297  5693  5739 I jxcore-log: 
,11-23 04:02:01.298  5693  5739 I jxcore-log: 2016-11-23 09:02:01 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 04:02:01.298  5693  5739 I jxcore-log: 
,11-23 04:02:01.906  6059  6059 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 04:02:01.918  6059  6059 D AndroidRuntime: CheckJNI is OFF
,11-23 04:02:01.948  6059  6059 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 04:02:01.981  6059  6059 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 04:02:01.997  6059  6059 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 04:02:02.005   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 04:02:02.006   927   940 I ActivityManager: Killing 5693:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 04:02:02.113   927  3020 D WifiService: Client connection lost with reason: 4
,11-23 04:02:02.113   927  3464 I WindowState: WIN DEATH: Window{98f6535 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-23 04:02:02.115   927  3848 D GraphicsStats: Buffer count: 2
,11-23 04:02:02.164   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-23 04:02:02.164   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-23 04:02:02.165   927   940 E ActivityManager: Failure starting process com.test.thalitest
11-23 04:02:02.165   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-23 04:02:02.165   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 04:02:02.165   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 04:02:02.165   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 04:02:02.165   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-23 04:02:02.165   927   940 I ActivityManager:   Force finishing activity ActivityRecord{2a95b99 u0 com.test.thalitest/.MainActivity t10}
,11-23 04:02:02.173   927  3198 W ActivityManager: Spurious death for ProcessRecord{94ee6c1 0:com.test.thalitest/u0a77}, curProc for 5693: null
,11-23 04:02:02.174   927   950 I art     : Starting a blocking GC Explicit
,11-23 04:02:02.183   927   945 W WindowManager: Attempted to add application window with unknown token Token{d5ace5e ActivityRecord{2a95b99 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-23 04:02:02.183   927   945 W WindowManager: Token{d5ace5e ActivityRecord{2a95b99 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{d5ace5e ActivityRecord{2a95b99 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-23 04:02:02.183   927   945 W WindowManager: view not successfully added to wm, removing view
11-23 04:02:02.184   927   945 W WindowManager: Exception when adding starting window
11-23 04:02:02.184   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{2fd77c0 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-23 04:02:02.184   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-23 04:02:02.184   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-23 04:02:02.184   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-23 04:02:02.184   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-23 04:02:02.184   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-23 04:02:02.184   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 04:02:02.184   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 04:02:02.184   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 04:02:02.184   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-23 04:02:02.279   927   950 I art     : Explicit concurrent mark sweep GC freed 136141(9MB) AllocSpace objects, 87(2MB) LOS objects, 33% free, 29MB/43MB, paused 1.652ms total 105.030ms
,11-23 04:02:02.301   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 04:02:02.304  6059  6059 I art     : System.exit called, status: 0
11-23 04:02:02.304  6059  6059 I AndroidRuntime: VM exiting with result code 0.
,11-23 04:02:02.308   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 04:02:02.320   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-23 04:02:02.326  5953  5953 D BluetoothMapAppObserver: onReceive
,11-23 04:02:02.326  5953  5953 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-23 04:02:02.335  4168  4243 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-23 04:02:02.335  3735  3735 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 04:02:02.341   927  3004 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 04:02:02.351  3735  6073 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 04:02:02.356  3735  6073 I Decoder : createOrResetDecoder
,11-23 04:02:02.360  3831  3831 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 04:02:02.373  3447  6075 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 04:02:02.385   204   204 W kworker/3:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 04:02:02.395   204   204 W kworker/3:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 04:02:02.405   204   204 W kworker/3:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 04:02:02.412  3447  3472 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjBB61DB96F) - 
,11-23 04:02:02.413  3622  3622 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-23 04:02:02.415  3622  3622 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-23 04:02:02.415  3622  3622 E AndroidRuntime: FATAL EXCEPTION: main
11-23 04:02:02.415  3622  3622 E AndroidRuntime: Process: com.google.process.gapps, PID: 3622
11-23 04:02:02.415  3622  3622 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-23 04:02:02.415  3622  3622 E AndroidRuntime: 	... 8 more
11-23 04:02:02.422  3622  3622 I Process : Sending signal. PID: 3622 SIG: 9
,11-23 04:02:02.426   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 04:02:02.427   927  6079 E DropBoxManagerService: Can't write: system_app_crash
11-23 04:02:02.427   927  6079 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 04:02:02.427   927  6079 E DropBoxManagerService: 	... 5 more
,11-23 04:02:02.447  3855  3998 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-23 04:02:02.447   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-23 04:02:02.448   927   939 E PackageManager: Failed to write settings, restoring backup
11-23 04:02:02.448   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-23 04:02:02.448   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-23 04:02:02.448   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-23 04:02:02.448   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-23 04:02:02.448   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-23 04:02:02.448   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 04:02:02.448   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 04:02:02.448   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 04:02:02.449  3447  6075 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-23 04:02:02.450  3447  6075 I Process : Sending signal. PID: 3447 SIG: 9
11-23 04:02:02.450   927   940 E DropBoxManagerService: Can't write: system_server_wtf
11-23 04:02:02.450   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-23 04:02:02.450   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 04:02:02.450   927   940 E DropBoxManagerService: 	... 13 more
,11-23 04:02:02.456   927  3020 D WifiService: Client connection lost with reason: 4
,11-23 04:02:02.470   927  3906 I ActivityManager: Start proc 6081:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-23 04:02:02.471   927  3209 I ActivityManager: Process com.google.process.gapps (pid 3622) has died
11-23 04:02:02.471  3855  3998 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-23 04:02:02.471  3855  3998 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3855
11-23 04:02:02.471  3855  3998 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 04:02:02.471  3855  3998 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 04:02:02.471   927  3209 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,11-23 04:02:02.472   927  3209 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 11000ms
11-23 04:02:02.472   927  3209 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
11-23 04:02:02.472   927  3209 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
,11-23 04:02:02.475   927   937 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 04:02:02.475   927  6089 E DropBoxManagerService: Can't write: system_app_crash
11-23 04:02:02.475   927  6089 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 04:02:02.475   927  6089 E DropBoxManagerService: 	... 5 more
,11-23 04:02:02.482  3855  3998 I Process : Sending signal. PID: 3855 SIG: 9
,11-23 04:02:02.515   927  3463 D GraphicsStats: Buffer count: 1
,11-23 04:02:02.515   927  3198 I WindowState: WIN DEATH: Window{eb60588 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
11-23 04:02:02.515   927   938 I ActivityManager: Start proc 6095:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,11-23 04:02:02.521   927  4282 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3855) has died
11-23 04:02:02.522   927  4282 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40949ms
,11-23 04:02:02.526   927   938 I ActivityManager: Process android.process.acore (pid 3447) has died
,11-23 04:02:02.527   927   938 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40945ms
,11-23 04:02:02.532   927   945 E WindowState: getStack: Window{eb60588 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{7e71e2f token=Token{552b40e ActivityRecord{37f8a09 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,11-23 04:02:02.532   927   945 E WindowState: getStack: Window{eb60588 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{7e71e2f token=Token{552b40e ActivityRecord{37f8a09 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
11-23 04:02:02.533   927   945 E WindowState: getStack: Window{eb60588 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{7e71e2f token=Token{552b40e ActivityRecord{37f8a09 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
11-23 04:02:02.533   927   945 E WindowState: getStack: Window{eb60588 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{7e71e2f token=Token{552b40e ActivityRecord{37f8a09 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
11-23 04:02:02.533   927   945 E WindowState: getStack: Window{eb60588 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{7e71e2f token=Token{552b40e ActivityRecord{37f8a09 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
11-23 04:02:02.533   927   945 E WindowState: getStack: Window{eb60588 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{7e71e2f token=Token{552b40e ActivityRecord{37f8a09 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,11-23 04:02:02.781   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
