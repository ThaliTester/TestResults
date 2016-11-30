#### Test 95813110eafd18b_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-30 17:02:34.919  5657  5684 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.46
11-30 17:02:34.987  5657  5699 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
11-30 17:02:35.140   926  3941 I ActivityManager: Killing 5352:org.codeaurora.ims/1001 (adj 15): empty #17
11-30 17:02:35.348  5657  5709 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-30 17:02:35.373  3937  3937 I ConfigFetchService: fetch service done; releasing wakelock
11-30 17:02:35.374  3937  3937 I ConfigFetchService: stopping self
11-30 17:02:35.388  5706  5706 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-30 17:02:35.391  5706  5706 D AndroidRuntime: CheckJNI is OFF
11-30 17:02:35.409  5657  5709 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-30 17:02:35.413  5706  5706 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-30 17:02:35.439  5657  5709 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-30 17:02:35.443  5706  5706 I Radio-JNI: register_android_hardware_Radio DONE
11-30 17:02:35.458  5706  5706 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-30 17:02:35.461   926  3941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-30 17:02:35.466  3937  5042 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-30 17:02:35.490   926  3941 I ActivityManager: Start proc 5723:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-30 17:02:35.511  5706  5706 D AndroidRuntime: Shutting down VM
,11-30 17:02:35.825   926  3515 I WindowManager: Screenshot max retries 4 of Token{5b34892 ActivityRecord{d534e1d u0 com.test.thalitest/.MainActivity t10}} appWin=Window{7ef23d5 u0 Starting com.test.thalitest} drawState=2
,11-30 17:02:35.892  5723  5723 I CordovaLog: Changing log level to DEBUG(3)
11-30 17:02:35.892  5723  5723 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-30 17:02:35.893  5723  5723 D CordovaActivity: CordovaActivity.onCreate()
,11-30 17:02:35.900  5723  5723 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-30 17:02:35.917  3937  5042 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,11-30 17:02:35.928  5723  5723 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-30 17:02:35.993  5723  5723 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 5444-5499)
,11-30 17:02:35.993  5723  5723 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-30 17:02:36.031  5723  5723 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {833501a}
11-30 17:02:36.031  5723  5723 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-30 17:02:36.031  5723  5723 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-30 17:02:36.035  5723  5723 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-30 17:02:36.036  5723  5723 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-30 17:02:36.084  5723  5723 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-30 17:02:36.097  5723  5723 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-30 17:02:36.097  5723  5723 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-30 17:02:36.097  5723  5723 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-30 17:02:36.097  5723  5723 I Adreno  : Build Date                       : 12/06/15
11-30 17:02:36.097  5723  5723 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-30 17:02:36.097  5723  5723 I Adreno  : Local Branch                     : mybranch17112971
11-30 17:02:36.097  5723  5723 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-30 17:02:36.097  5723  5723 I Adreno  : Remote Branch                    : NONE
11-30 17:02:36.097  5723  5723 I Adreno  : Reconstruct Branch               : NOTHING
,11-30 17:02:36.163   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d08f88d:true
,11-30 17:02:36.200  4240  4240 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22466]" dev="sockfs" ino=22466 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 17:02:36.200  4240  4240 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22466]" dev="sockfs" ino=22466 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 17:02:36.215  5723  5723 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-30 17:02:36.224  5723  5723 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-30 17:02:36.229  5723  5723 D PluginManager: init()
,11-30 17:02:36.231  5723  5723 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-30 17:02:36.250  5723  5723 D CordovaActivity: Started the activity.
11-30 17:02:36.251  5723  5723 D CordovaActivity: Resumed the activity.
,11-30 17:02:36.250  4240  4240 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30456]" dev="sockfs" ino=30456 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 17:02:36.250  4240  4240 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30456]" dev="sockfs" ino=30456 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:36.255  5723  5761 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-30 17:02:36.253  3948  3948 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22477]" dev="sockfs" ino=22477 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 17:02:36.260  5723  5723 D CordovaActivity: Paused the activity.
11-30 17:02:36.253  3948  3948 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[22477]" dev="sockfs" ino=22477 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 17:02:36.262  5723  5748 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-30 17:02:36.294  5723  5761 I OpenGLRenderer: Initialized EGL, version 1.4
,11-30 17:02:36.309  5723  5723 D CordovaActivity: Stopped the activity.
,11-30 17:02:36.372   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +545ms (total +894ms)
,11-30 17:02:36.380  5723  5723 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-30 17:02:36.402  5723  5723 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5723
,11-30 17:02:36.532  5723  5723 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-30 17:02:36.640  5723  5764 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -581695184
,11-30 17:02:36.643  5723  5764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-30 17:02:36.643  5723  5764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-30 17:02:36.643  5723  5764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-30 17:02:36.643  5723  5764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-30 17:02:36.643  5723  5764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-30 17:02:36.643  5723  5764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@574ec83 added. We now have 1 listener(s)
,11-30 17:02:36.645  5723  5764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
11-30 17:02:36.645  5723  5764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:02:36.646  5723  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-30 17:02:36.646  5723  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-30 17:02:36.648  5723  5764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98fcddf added. We now have 1 listener(s)
,11-30 17:02:36.648  5723  5764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 17:02:36.653   926  3054 D WifiService: New client listening to asynchronous messages
,11-30 17:02:36.653  5723  5764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 17:02:36.653  5723  5764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-30 17:02:36.654  5723  5764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-30 17:02:36.654  5723  5764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-30 17:02:36.654  5723  5764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-30 17:02:36.654  5723  5764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-30 17:02:36.654  5723  5764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-30 17:02:36.655  5723  5764 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-30 17:02:36.729  5723  5723 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-30 17:02:36.731  5723  5723 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-30 17:02:36.731  5723  5723 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-30 17:02:36.951  5723  5732 I art     : Background sticky concurrent mark sweep GC freed 88223(8MB) AllocSpace objects, 16(1476KB) LOS objects, 20% free, 26MB/32MB, paused 2.185ms total 104.013ms
,11-30 17:02:37.104  5723  5770 W jxcore-log: Initializing JXcore engine
,11-30 17:02:37.104  5723  5770 W jxcore-log: JXcore engine is ready
,11-30 17:02:37.123  5770  5770 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12244 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-30 17:02:37.123  5770  5770 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14355]" dev="sockfs" ino=14355 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-30 17:02:37.123  5770  5770 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-30 17:02:37.123  5770  5770 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30434]" dev="sockfs" ino=30434 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-30 17:02:37.137  5723  5770 W jxcore-log: Starting JXcore engine
,11-30 17:02:37.187  5723  5770 W jxcore-log: Platform android
11-30 17:02:37.187  5723  5770 W jxcore-log: 
,11-30 17:02:37.187  5723  5770 W jxcore-log: Process ARCH arm
11-30 17:02:37.187  5723  5770 W jxcore-log: 
,11-30 17:02:37.342  5723  5770 I jxcore-log: JXcore Cordova bridge is ready!
11-30 17:02:37.342  5723  5770 I jxcore-log: 
11-30 17:02:37.342  5723  5770 W jxcore-log: JXcore engine is started
,11-30 17:02:37.351  5723  5764 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-30 17:02:37.355  5723  5723 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-30 17:02:37.355  5723  5723 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-30 17:02:40.385  3677  3677 I ConfigService: onDestroy
,11-30 17:02:40.794   926  3047 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 17:02:43.960   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:02:44.961   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:02:45.963   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:02:46.964   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:02:47.018  5723  5770 I jxcore-log: 2016-11-30 22:02:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-30 17:02:47.018  5723  5770 I jxcore-log: 
,11-30 17:02:47.020  5723  5770 I jxcore-log: 2016-11-30 22:02:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-30 17:02:47.020  5723  5770 I jxcore-log: 
,11-30 17:02:47.025  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 17:02:47.026  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 17:02:47.027  5723  5770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 17:02:47.030  5723  5770 I jxcore-log: 2016-11-30 22:02:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-30 17:02:47.030  5723  5770 I jxcore-log: 
,11-30 17:02:47.031  5723  5770 I jxcore-log: 2016-11-30 22:02:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-30 17:02:47.031  5723  5770 I jxcore-log: 
,11-30 17:02:47.278  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 17:02:47.278  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fc7b18 added. We now have 2 listener(s)
11-30 17:02:47.279  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:02:47.279  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 17:02:47.279  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 17:02:47.279  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-30 17:02:47.279  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d91e971 added. We now have 2 listener(s)
,11-30 17:02:47.279  5723  5770 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 17:02:47.280  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 17:02:47.281  5723  5770 D ExecuteNativeTests: Running unit tests
,11-30 17:02:47.282  5723  5770 D BluetoothAdapter: enable(): BT is already enabled..!
11-30 17:02:47.282   926   937 D WifiService: setWifiEnabled: true pid=5723, uid=10077
,11-30 17:02:47.282   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 17:02:47.965   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:02:48.876  4938  4972 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-30 17:02:48.878  4938  4938 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-30 17:02:48.882   926  3515 I ActivityManager: Killing 5365:com.android.settings/1000 (adj 15): empty #17
,11-30 17:02:48.967   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 17:02:51.798   926  5484 D NetlinkSocketObserver: NeighborEvent{elapsedMs=91305, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-30 17:02:57.287  5723  5770 I com.test.thalitest.ThaliTestRunner: Running UT
,11-30 17:02:57.362  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-30 17:02:57.362  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63bd6db added. We now have 3 listener(s)
,11-30 17:02:57.363  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:02:57.363  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 17:02:57.363  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 17:02:57.363  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 17:02:57.363  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b536578 added. We now have 3 listener(s)
11-30 17:02:57.363  5723  5770 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 17:02:57.365  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 17:02:57.375  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-30 17:02:57.375  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 17:02:57.375  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:57.376  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:57.376  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:57.377  5723  5770 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-30 17:02:57.377  5723  5770 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-30 17:02:57.377  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 17:02:57.377  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:02:57.377  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:02:57.378  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:02:57.378  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-30 17:02:57.379  5723  5770 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-30 17:02:57.380  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-30 17:02:57.382  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-30 17:02:57.382  5723  5770 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-30 17:02:57.383  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:02:57.383  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 17:02:57.386  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 17:02:57.387  5723  5770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-30 17:02:57.387  5723  5770 D io.jxcore.node.ConnectivityMonitor: start: OK
11-30 17:02:57.387  5723  5770 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,11-30 17:02:57.388  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-30 17:02:57.388  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.388  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.388  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.388  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 17:02:57.388  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 17:02:57.388  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 17:02:57.388  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:02:57.389  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 17:02:57.389  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 17:02:57.390  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-30 17:02:57.390  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 17:02:57.390  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 17:02:57.390  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 17:02:57.390  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 17:02:57.390  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 17:02:57.390  5723  5772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 17:02:57.392  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 17:02:57.392  5723  5770 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 17:02:57.392  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 17:02:57.394  5723  5772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:02:57.395  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.395  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 17:02:57.397  5723  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 17:02:57.397  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 17:02:57.398  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 17:02:57.398  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-30 17:02:57.393  4906  4906 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16229]" dev="sockfs" ino=16229 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:57.393  4906  4906 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[16229]" dev="sockfs" ino=16229 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:57.398  5723  5772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-30 17:02:57.399  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.399  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.399  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 17:02:57.399  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 17:02:57.400  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:02:57.400  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-30 17:02:57.400  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:57.400  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:57.400  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.400  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 17:02:57.400  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:57.401  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.401  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.401  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.401  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:57.402  5723  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 17:02:57.402  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 17:02:57.404  4689  4906 D BtGatt.GattService: registerClient() - UUID=268d35fe-bb26-4c49-9c17-633ef52402c9
11-30 17:02:57.406  4689  4776 D BtGatt.GattService: onClientRegistered() - UUID=268d35fe-bb26-4c49-9c17-633ef52402c9, clientIf=5
,11-30 17:02:57.409  5723  5734 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 17:02:57.413  4689  4781 D BtGatt.AdvertiseManager: message : 0
,11-30 17:02:57.417  4689  4781 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 17:02:57.432  4689  4776 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 17:02:57.440  4689  4776 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 17:02:57.442  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.442  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.442  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-30 17:02:57.442  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.442  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.442  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.442  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.442  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.442  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 17:02:57.443  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 17:02:57.443  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.444  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:57.444  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.444  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.445  5723  5770 I io.jxcore.node.ConnectionHelper: start: OK
11-30 17:02:57.445  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-30 17:02:57.445  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.445  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:57.445  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 17:02:57.446  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.446  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-30 17:02:57.446  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:57.446  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.447  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 17:02:57.447  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-30 17:02:57.447  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.447  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-30 17:02:57.447  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-30 17:02:57.447  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.447  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.451  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 17:02:57.451  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 17:02:57.451  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.452  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.452  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 17:02:57.946  5723  5773 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 17:02:57.948  5723  5770 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-30 17:02:57.948  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 17:02:57.949  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-30 17:02:57.950  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 17:02:57.951  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 17:02:57.951  5723  5770 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-30 17:02:57.952  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 17:02:57.952  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 17:02:57.952  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 17:02:57.952  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 17:02:57.952  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 17:02:57.953  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 17:02:57.953  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 17:02:57.953  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 17:02:57.953  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 17:02:57.954  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 17:02:57.954  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 17:02:57.954  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.954  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 17:02:57.954  5723  5772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 17:02:57.954  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 17:02:57.954  5723  5772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 17:02:57.954  5723  5772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 17:02:57.955  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.955  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.955  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:57.956  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.957  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:57.958  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 17:02:57.959  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:57.959  5723  5770 D BluetoothLeScanner: could not find callback wrapper
11-30 17:02:57.959  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 17:02:57.959  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.959  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.959  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.960  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 17:02:57.960  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.961  4689  4781 D BtGatt.AdvertiseManager: message : 1
11-30 17:02:57.963  4689  4781 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 17:02:57.976  4689  4776 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 17:02:57.976  4689  4776 D BtGatt.GattService: Client app is not null!
,11-30 17:02:57.978  4689  4704 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 17:02:57.979  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 17:02:57.979  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.979  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 17:02:57.979  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.979  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:57.980  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.980  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 17:02:57.981  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 17:02:57.982  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 17:02:57.982  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.984  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.984  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:02:57.984  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.984  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.985  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 17:02:57.985  5723  5723 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 17:02:57.986  5723  5774 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-30 17:02:57.986  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 17:02:57.987  5723  5770 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 17:02:57.987  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:02:57.987  5723  5770 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 17:02:57.987  5723  5770 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,11-30 17:02:57.987  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-30 17:02:57.987  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:02:57.987  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 17:02:57.987  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.987  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 17:02:57.987  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.987  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:57.987  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:57.988  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 17:02:57.988  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.988  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 17:02:57.988  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 17:02:57.988  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 17:02:57.988  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:02:57.988  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-30 17:02:57.988  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.988  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.988  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.988  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:02:57.989  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.989  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.991  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 17:02:57.993  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 17:02:57.993  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-30 17:02:57.993  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 17:02:57.993  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 17:02:57.994  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.994  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.995  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:57.995  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-30 17:02:57.995  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-30 17:02:57.996  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:02:57.996  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 17:02:57.997  5723  5775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 17:02:57.997  4930  4930 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33207]" dev="sockfs" ino=33207 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:57.998  5723  5775 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:02:58.002  5723  5775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-30 17:02:57.997  4930  4930 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33207]" dev="sockfs" ino=33207 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:58.003  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 17:02:58.003  5723  5770 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 17:02:58.003  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 17:02:58.009  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.009  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-30 17:02:58.010  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 17:02:58.010  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 17:02:58.010  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-30 17:02:58.013  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.013  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.013  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 17:02:58.013  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 17:02:58.013  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-30 17:02:58.013  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-30 17:02:58.014  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.014  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.014  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.014  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 17:02:58.014  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.014  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.014  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:58.014  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.016  5723  5770 D BluetoothAdapter: STATE_ON
,11-30 17:02:58.019  4689  4931 D BtGatt.GattService: registerClient() - UUID=0ab5bc4f-db49-42c1-b408-cbb266cac107
11-30 17:02:58.020  4689  4776 D BtGatt.GattService: onClientRegistered() - UUID=0ab5bc4f-db49-42c1-b408-cbb266cac107, clientIf=5
,11-30 17:02:58.020  5723  5733 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 17:02:58.021  4689  4781 D BtGatt.AdvertiseManager: message : 0
,11-30 17:02:58.024  4689  4781 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 17:02:58.038  4689  4776 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 17:02:58.045  4689  4776 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 17:02:58.046  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.047  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.047  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 17:02:58.047  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.047  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.047  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:58.047  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.047  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.047  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-30 17:02:58.049  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-30 17:02:58.049  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.051  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.051  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.051  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.051  5723  5770 I io.jxcore.node.ConnectionHelper: start: OK
11-30 17:02:58.051  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.052  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 17:02:58.052  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 17:02:58.053  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.053  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.053  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.053  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.053  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 17:02:58.057  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.057  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 17:02:58.058  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.058  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.058  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 17:02:58.143   926  2879 I hubconnection: sensorhub said: 'set_bias 3: -4.8000, 0.0000, 0.0000'
,11-30 17:02:58.553  5723  5776 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 17:02:58.556  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-30 17:02:58.556  5723  5770 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 17:02:58.556  5723  5770 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-30 17:02:58.557  5723  5770 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-30 17:02:58.557  5723  5770 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-30 17:02:58.557  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-30 17:02:58.558  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.558  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:58.558  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.559  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 17:02:58.560  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.561  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-30 17:02:58.562  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.562  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.562  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.565  4689  4781 D BtGatt.AdvertiseManager: message : 1
11-30 17:02:58.566  4689  4781 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 17:02:58.581  4689  4776 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 17:02:58.581  4689  4776 D BtGatt.GattService: Client app is not null!
,11-30 17:02:58.583  4689  4931 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 17:02:58.584  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 17:02:58.584  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.585  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 17:02:58.585  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.585  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.586  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.586  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 17:02:58.586  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.586  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.586  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.587  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 17:02:58.587  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 17:02:58.587  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:02:58.587  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,11-30 17:02:58.587  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.587  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.588  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.588  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-30 17:02:58.588  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.588  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.588  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.588  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.590  5723  5770 D BluetoothAdapter: STATE_ON
,11-30 17:02:58.600  4689  4704 D BtGatt.GattService: registerClient() - UUID=a7953b7c-1c96-4b56-b24a-831feed4e515
,11-30 17:02:58.601  4689  4776 D BtGatt.GattService: onClientRegistered() - UUID=a7953b7c-1c96-4b56-b24a-831feed4e515, clientIf=5
,11-30 17:02:58.601  5723  5734 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 17:02:58.603  4689  4781 D BtGatt.AdvertiseManager: message : 0
,11-30 17:02:58.606  4689  4781 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 17:02:58.621  4689  4776 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 17:02:58.629  4689  4776 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 17:02:58.630  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.630  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.630  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 17:02:58.631  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.631  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 17:02:58.631  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 17:02:58.631  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-30 17:02:58.631  5723  5770 I io.jxcore.node.ConnectionHelper: start: OK
11-30 17:02:58.631  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.631  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.632  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 17:02:58.632  572,3  5777 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.632  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.632  5723  5770 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-30 17:02:58.632  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 17:02:58.632  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 17:02:58.633  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 17:02:58.633  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 17:02:58.633  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 17:02:58.633  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 17:02:58.633  5723  5775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 17:02:58.633  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 17:02:58.633  5723  5775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 17:02:58.633  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 17:02:58.633  5723  5775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 17:02:58.633  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 17:02:58.633  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 17:02:58.633  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 17:02:58.633  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.634  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 17:02:58.634  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 17:02:58.634  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.634  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.634  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.634  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.635  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:58.635  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 17:02:58.636  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:58.636  5723  5770 D BluetoothLeScanner: could not find callback wrapper
11-30 17:02:58.636  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 17:02:58.636  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.636  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.636  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.636  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 17:02:58.636  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.637  4689  4781 D BtGatt.AdvertiseManager: message : 1
11-30 17:02:58.638  4689  4781 D BtGatt.AdvertiseManager: stop advertise for client 5
11-30 17:02:58.645  4689  4776 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 17:02:58.646  4689  4776 D BtGatt.GattService: Client app is not null!
11-30 17:02:58.646  4689  4704 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 17:02:58.647  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 17:02:58.647  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.647  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 17:02:58.647  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.648  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.648  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.648  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 17:02:58.648  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 17:02:58.648  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 17:02:58.648  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.650  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.650  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:02:58.650  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.650  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.650  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 17:02:58.650  5723  5723 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 17:02:58.651  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 17:02:58.651  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 17:02:58.651  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:02:58.651  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:02:58.651  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:58.651  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.651  5723  5778 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-30 17:02:58.651  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 17:02:58.651  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 17:02:58.651  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.651  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.652  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.652  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:02:58.652  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.652  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.652  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-30 17:02:58.652  5723  5770 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-30 17:02:58.654  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.654  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-30 17:02:58.654  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.654  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.654  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-30 17:02:58.655  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-30 17:02:58.656  5723  5770 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-30 17:02:58.657  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-30 17:02:58.657  5723  5770 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-30 17:02:58.658  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-30 17:02:58.658  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 17:02:58.658  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:58.658  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:58.658  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:58.658  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 17:02:58.659  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:02:58.659  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:02:58.659  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:02:58.659  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 17:02:58.659  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:58.659  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:58.659  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 17:02:58.660  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-30 17:02:58.660  5723  5770 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 17:02:58.660  5723  5770 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 17:02:58.660  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-30 17:02:58.663  5723  5770 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 17:02:58.663  5723  5770 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-30 17:02:58.663  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-30 17:02:58.663  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-30 17:02:58.663  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-30 17:02:58.663  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-30 17:02:58.663  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-30 17:02:58.663  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 17:02:58.664  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 17:02:58.665  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 17:02:58.665  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-30 17:02:58.665  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-30 17:02:58.665  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 17:02:58.665  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 17:02:58.665  5723  5770 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-30 17:02:58.665  5723  5770 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 17:02:58.665  5723  5770 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-30 17:02:58.665  5723  5770 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 17:02:58.665  5723  5770 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 17:02:58.665  5723  5770 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-30 17:02:58.666  5723  5770 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 17:02:58.666  5723  5770 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 17:02:58.666  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-30 17:02:58.671  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-30 17:02:58.671  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-30 17:02:58.671  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-30 17:02:58.672  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-30 17:02:58.672  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-30 17:02:58.672  5723  5770 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-30 17:02:58.672  5723  5770 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 17:02:58.672  5723  5770 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-30 17:02:58.673  5723  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
11-30 17:02:58.674  5723  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-30 17:02:58.674  5723  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-30 17:02:58.674  5723  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-30 17:02:58.674  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-30 17:02:58.674  5723  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-30 17:02:58.674  5723  5779 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-30 17:02:58.674  5723  5770 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-30 17:02:58.674  5723  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:02:58.675  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-30 17:02:58.675  5723  5770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-30 17:02:58.676  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-30 17:02:58.673  4930  4930 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33215]" dev="sockfs" ino=33215 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:58.673  4930  4930 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33215]" dev="sockfs" ino=33215 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:58.677  5723  5770 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-30 17:02:58.677  5723  5770 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-30 17:02:58.677  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 17:02:58.677  5723  5770 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-30 17:02:58.677  5723  5770 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 17:02:58.677  5723  5770 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-30 17:02:58.677  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 17:02:58.677  5723  5770 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-30 17:02:58.677  5723  5770 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 17:02:58.677  5723  5770 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 17:02:58.677  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 17:02:58.677  5723  5770 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-30 17:02:58.678  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-30 17:02:58.678  5723  5770 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 17:02:58.678  5723  5770 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 17:02:58.678  5723  5770 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-30 17:02:58.678  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-30 17:02:58.678  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.678  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.679  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.679  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 17:02:58.679  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 17:02:58.679  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 17:02:58.679  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:02:58.679  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 17:02:58.680  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 17:02:58.680  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 17:02:58.680  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 17:02:58.680  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 17:02:58.680  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 17:02:58.680  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:02:58.680  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 17:02:58.680  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 17:02:58.680  5723  5780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 17:02:58.681  5723  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:02:58.683  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 17:02:58.683  5723  5770 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 17:02:58.683  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 17:02:58.684  5723  5780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 17:02:58.680  4931  4931 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33217]" dev="sockfs" ino=33217 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:58.680  4931  4931 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33217]" dev="sockfs" ino=33217 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:02:58.687  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.687  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 17:02:58.688  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 17:02:58.688  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 17:02:58.688  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-30 17:02:58.690  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.690  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.690  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 17:02:58.690  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 17:02:58.690  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:02:58.690  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-30 17:02:58.690  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.690  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.690  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.691  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 17:02:58.691  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:02:58.691  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.691  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.691  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.691  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:58.694  4689  4906 D BtGatt.GattService: registerClient() - UUID=2ab486c1-348d-49e6-bd29-0c405e18f3e7
11-30 17:02:58.694  4689  4776 D BtGatt.GattService: onClientRegistered() - UUID=2ab486c1-348d-49e6-bd29-0c405e18f3e7, clientIf=5
11-30 17:02:58.695  5723  5734 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 17:02:58.695  4689  4781 D BtGatt.AdvertiseManager: message : 0
11-30 17:02:58.697  4689  4781 D BtGatt.AdvertiseManager: starting multi advertising
11-30 17:02:58.705  4689  4776 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 17:02:58.711  4689  4776 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-30 17:02:58.711  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.711  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.711  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 17:02:58.712  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.712  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.712  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.712  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.712  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.712  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 17:02:58.713  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 17:02:58.713  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.714  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.714  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.714  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:58.714  5723  5770 I io.jxcore.node.ConnectionHelper: start: OK
11-30 17:02:58.715  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 17:02:58.715  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.715  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:58.715  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 17:02:58.715  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.715  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.715  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:58.716  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.716  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 17:02:58.716  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 17:02:58.716  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.716  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.716  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.716  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.716  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.719  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.719  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 17:02:58.719  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.719  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:58.719  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 17:02:59.217  5723  5773 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 17:02:59.218  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 17:02:59.218  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 17:02:59.218  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 17:02:59.218  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 17:02:59.219  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 17:02:59.219  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 17:02:59.219  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 17:02:59.219  5723  5780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 17:02:59.219  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-30 17:02:59.219  5723  5780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 17:02:59.220  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-30 17:02:59.220  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 17:02:59.220  5723  5780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 17:02:59.220  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 17:02:59.221  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-30 17:02:59.221  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 17:02:59.223  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63bd6db removed from the list
11-30 17:02:59.224  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 17:02:59.224  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 17:02:59.224  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.224  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 17:02:59.224  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 17:02:59.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.225  5723  5781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
11-30 17:02:59.226  5723  5781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-30 17:02:59.226  5723  5781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
11-30 17:02:59.227  5723  5781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
11-30 17:02:59.227  4689  4902 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-30 17:02:59.227  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:59.227  5723  5779 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-30 17:02:59.227  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 17:02:59.227  5723  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-30 17:02:59.228  5723  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
11-30 17:02:59.229  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:02:59.229  5723  5770 D BluetoothLeScanner: could not find callback wrapper
11-30 17:02:59.229  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 17:02:59.230  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.230  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.230  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.230  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 17:02:59.230  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.232  4689  4781 D BtGatt.AdvertiseManager: message : 1
11-30 17:02:59.234  4689  4781 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 17:02:59.245  4689  4776 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 17:02:59.245  4689  4776 D BtGatt.GattService: Client app is not null!
11-30 17:02:59.246  4689  4704 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 17:02:59.247  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 17:02:59.247  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:59.247  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 17:02:59.247  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:02:59.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 17:02:59.248  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 17:02:59.249  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-30 17:02:59.249  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.251  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.251  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:02:59.251  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.251  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:02:59.251  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b536578 removed from the list
,11-30 17:02:59.252  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:02:59.252  5723  5770 D io.jxcore.node.ConnectivityMonitor: stop
11-30 17:02:59.252  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 17:02:59.252  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:02:59.252  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 17:02:59.252  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:02:59.252  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-30 17:02:59.252  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 17:02:59.252  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:02:59.252  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 17:02:59.253  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:02:59.253  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:02:59.253  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-30 17:02:59.253  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 17:02:59.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:02:59.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:02:59.256  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-30 17:02:59.755  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 17:02:59.989   926   926 I ActivityManager: Killing 5162:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-30 17:03:03.803  4689  4896 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-30 17:03:03.803  4689  4896 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-30 17:03:04.255  5723  5774 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-30 17:03:04.257  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-30 17:03:04.260  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-30 17:03:04.260  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:03:04.260  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 17:03:04.267  4930  4930 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30497]" dev="sockfs" ino=30497 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:03:04.270  4930  4930 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30497]" dev="sockfs" ino=30497 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:03:04.266  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 17:03:04.267  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 17:03:04.267  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-30 17:03:04.268  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 17:03:04.268  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 17:03:04.268  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-30 17:03:04.268  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 17:03:04.268  5723  5782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 17:03:04.270  5723  5782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 17:03:04.270  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-30 17:03:04.271  5723  5770 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-30 17:03:04.272  5723  5770 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-30 17:03:04.272  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 17:03:04.272  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:03:04.272  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 17:03:04.273  5723  5782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 17:03:04.274  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-30 17:03:04.285  5723  5770 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-30 17:03:04.286  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 17:03:04.286  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 17:03:04.286  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 17:03:04.286  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 17:03:04.286  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 17:03:04.287  5723  5782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 17:03:04.287  5723  5782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 17:03:04.287  5723  5782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 17:03:04.287  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 17:03:04.287  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 17:03:04.287  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 17:03:04.288  5723  5770 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63bd6db not in the list
,11-30 17:03:04.288  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 17:03:04.288  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 17:03:04.288  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 17:03:04.288  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 17:03:04.288  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:04.288  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 17:03:04.288  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 17:03:04.288  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:04.290  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:04.290  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:03:04.291  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:04.291  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:04.291  5723  5770 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b536578 not in the list
11-30 17:03:04.291  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:03:04.291  5723  5770 D io.jxcore.node.ConnectivityMonitor: stop
11-30 17:03:04.291  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:03:04.291  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-30 17:03:04.293  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-30 17:03:04.293  5723  5770 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-30 17:03:04.294  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 17:03:04.294  5723  5770 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-30 17:03:04.294  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 17:03:04.294  5723  5770 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-30 17:03:04.294  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-30 17:03:04.295  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-30 17:03:04.297  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-30 17:03:04.299  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-30 17:03:04.299  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-30 17:03:04.300  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-30 17:03:04.300  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-30 17:03:04.301  5723  5770 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-30 17:03:04.301  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-30 17:03:04.301  5723  5770 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-30 17:03:04.301  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-30 17:03:04.301  5723  5770 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-30 17:03:04.302  5723  5770 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-30 17:03:04.303  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-30 17:03:04.303  5723  5770 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-30 17:03:04.303  5723  5770 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-30 17:03:04.304  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-30 17:03:04.304  5723  5770 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-30 17:03:04.305  5723  5770 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-30 17:03:04.305  5723  5770 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-30 17:03:04.305  5723  5770 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-30 17:03:04.306  5723  5770 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-30 17:03:04.307  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 17:03:04.307  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@673e766 added. We now have 3 listener(s)
11-30 17:03:04.309  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:03:04.309  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 17:03:04.310  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 17:03:04.310  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-30 17:03:04.310  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebecaa7 added. We now have 3 listener(s)
11-30 17:03:04.310  5723  5770 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 17:03:04.311  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 17:03:04.314  5723  5770 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 17:03:04.315   926   937 D WifiService: setWifiEnabled: true pid=5723, uid=10077
11-30 17:03:04.315   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 17:03:04.317  5723  5770 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-30 17:03:04.320  5723  5770 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-30 17:03:04.322  5723  5770 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-30 17:03:04.322  5723  5770 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-30 17:03:04.328  4689  4768 D BluetoothAdapterState: Current state: ON, message: 23
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 17:03:04.328  5723  5770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 17:03:04.328  4689  4768 D BluetoothAdapterProperties: Setting state to 13
11-30 17:03:04.328  4689  4768 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-30 17:03:04.329  5723  5770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-30 17:03:04.329  4689  4768 D BluetoothAdapterProperties: onBluetoothDisable()
11-30 17:03:04.329  5723  5770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-30 17:03:04.330  4689  4768 I BluetoothAdapterState: Entering PendingCommandState
,11-30 17:03:04.331  4689  4689 D BluetoothMapService: onReceive
11-30 17:03:04.331  4689  4689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 17:03:04.331  4689  4689 D BluetoothMapService: STATE_TURNING_OFF
,11-30 17:03:04.332  4689  4689 D BluetoothMapService: MAP Service closeService in
,11-30 17:03:04.332  4689  4689 D BluetoothMapMasInstance0: MAP Service shutdown
11-30 17:03:04.332  4689  4689 D ObexServerSockets0: shutdown(block = true)
,11-30 17:03:04.333  4689  4689 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 17:03:04.333  4689  4951 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-30 17:03:04.333  4689  4689 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 17:03:04.333  4689  4902 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-30 17:03:04.333  4689  4952 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-30 17:03:04.335  4689  4689 I BtOppRfcommListener: stopping Accept Thread
11-30 17:03:04.335  4689  5399 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-30 17:03:04.335  4689  5399 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-30 17:03:04.350   926   939 I ActivityManager: Start proc 5785:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-30 17:03:04.354  4689  4776 D BluetoothAdapterProperties: Scan Mode:20
,11-30 17:03:04.355  4689  4768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-30 17:03:04.358  4689  4689 D HeadsetService: Received stop request...Stopping profile...
,11-30 17:03:04.362  4689  4689 D A2dpService: Received stop request...Stopping profile...
11-30 17:03:04.362   926   926 D BluetoothHeadset: Proxy object disconnected
11-30 17:03:04.363   926   926 D BluetoothHeadset: Proxy object disconnected
11-30 17:03:04.363  4689  4919 D A2dpStateMachine: Exit Disconnected: -1
11-30 17:03:04.363  3217  3238 D BluetoothHeadset: Proxy object disconnected
11-30 17:03:04.364  3862  3880 D BluetoothHeadset: Proxy object disconnected
11-30 17:03:04.364   926   926 D BluetoothHeadset: Proxy object disconnected
11-30 17:03:04.366   926   926 D BluetoothA2dp: Proxy object disconnected
,11-30 17:03:04.368  4689  4689 D HidService: Received stop request...Stopping profile...
,11-30 17:03:04.368  4689  4689 D HidService: Stopping Bluetooth HidService
,11-30 17:03:04.370  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-30 17:03:04.370  4689  4689 V BluetoothAdapterState: isTurningOn()=false
,11-30 17:03:04.370  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
,11-30 17:03:04.370  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 17:03:04.371  4689  4689 D HealthService: Received stop request...Stopping profile...
,11-30 17:03:04.373  4689  4689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-30 17:03:04.373  4689  4689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-30 17:03:04.373  4689  4896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 17:03:04.374  4689  4896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 17:03:04.374  4689  4896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 17:03:04.374  4689  4689 D PanService: Received stop request...Stopping profile...
11-30 17:03:04.374  4689  4776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-30 17:03:04.374  4689  4776 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-30 17:03:04.375  4689  4689 D BluetoothMapService: Received stop request...Stopping profile...
,11-30 17:03:04.376  4689  4689 D BluetoothMapService: stop()
,11-30 17:03:04.380  3217  3217 D HeadsetProfile: Bluetooth service disconnected
,11-30 17:03:04.380  3217  3217 D BluetoothA2dp: Proxy object disconnected
,11-30 17:03:04.381  3217  3217 D BluetoothInputDevice: Proxy object disconnected
11-30 17:03:04.382  3217  3217 D HidProfile: Bluetooth service disconnected
11-30 17:03:04.382  3217  3217 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-30 17:03:04.382  3217  3217 D PanProfile: Bluetooth service disconnected
,11-30 17:03:04.380  4689  4689 D BluetoothMapAppObserver: deinitObservers()
,11-30 17:03:04.382  4689  4689 D BluetoothMapAppObserver: removeReceiver()
11-30 17:03:04.383  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-30 17:03:04.383  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.383  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:04.383  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:04.384  4689  4896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 17:03:04.384  4689  4776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-30 17:03:04.385  4689  4896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 17:03:04.385  4689  4896 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-30 17:03:04.385  4689  4896 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 17:03:04.385  4689  4896 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-30 17:03:04.385  4689  4896 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 17:03:04.385  4689  4689 D SapService: Received stop request...Stopping profile...
,11-30 17:03:04.385  4689  4689 V SapService: stop()
11-30 17:03:04.386  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-30 17:03:04.386  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.386  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
,11-30 17:03:04.386  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 17:03:04.387  4689  4689 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-30 17:03:04.387  4689  4689 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-30 17:03:04.387  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-30 17:03:04.387  4689  4776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-30 17:03:04.387  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.387  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:04.387  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 17:03:04.387  4689  4689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-30 17:03:04.387  4689  4776 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-30 17:03:04.388  4689  4689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-30 17:03:04.388  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-30 17:03:04.388  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.388  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:04.388  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:04.388  4689  4689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-30 17:03:04.388  4689  4689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-30 17:03:04.389  4689  4689 D BluetoothMapService: MAP Service closeService in
11-30 17:03:04.389  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-30 17:03:04.390  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.390  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:04.390  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:04.390  4689  4689 D BluetoothMapService: cleanup()
11-30 17:03:04.390  4689  4689 D BluetoothMapService: MAP Service closeService in
11-30 17:03:04.390  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-30 17:03:04.390  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.391  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:04.391  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:04.391  3217  3217 D BluetoothMap: Proxy object disconnected
11-30 17:03:04.391  3217  3217 D MapProfile: Bluetooth service disconnected
11-30 17:03:04.391  4689  4768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-30 17:03:04.392  4689  4768 D BluetoothAdapterProperties: Setting state to 15
11-30 17:03:04.392  4689  4768 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-30 17:03:04.393  3217  5722 D BluetoothMap: onBluetoothStateChange: up=false
11-30 17:03:04.393  4689  4768 I BluetoothAdapterState: Entering BleOnState
11-30 17:03:04.393  3862  4880 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 17:03:04.394  3217  3233 D BluetoothPbap: onBluetoothStateChange: up=false
11-30 17:03:04.394   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 17:03:04.395  3217  4082 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 17:03:04.395  3217  3238 D BluetoothPan: onBluetoothStateChange on: false
11-30 17:03:04.398   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 17:03:04.398  3217  5722 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-30 17:03:04.399   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-30 17:03:04.399   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 17:03:04.399  3217  3233 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-30 17:03:04.402  4689  4768 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-30 17:03:04.402  4689  4768 D BluetoothAdapterProperties: Setting state to 16
11-30 17:03:04.402  4689  4768 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-30 17:03:04.403  4689  4768 D BluetoothAdapterProperties: onBleDisable
11-30 17:03:04.403  4689  4768 I BluetoothAdapterState: Entering PendingCommandState
11-30 17:03:04.403  4689  4769 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-30 17:03:04.405  4689  4896 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-30 17:03:04.405  4689  4896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 17:03:04.405  4689  4776 D BluetoothAdapterProperties: Scan Mode:20
,11-30 17:03:04.412  5785  5785 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-30 17:03:04.426  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 17:03:04.430   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@938fc87:true
,11-30 17:03:04.432  3677  3677 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 17:03:04.445   926  3250 I ActivityManager: Start proc 5797:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-30 17:03:04.459  5785  5785 D LocalBluetoothProfileManager: Adding local MAP profile
,11-30 17:03:04.463  5785  5785 D BluetoothMap: Create BluetoothMap proxy object
,11-30 17:03:04.475  5785  5785 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-30 17:03:04.484  5797  5797 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-30 17:03:04.489  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,11-30 17:03:04.497   926  3941 I ActivityManager: Killing 5090:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-30 17:03:04.609  4689  4776 I bt_hci  : shut_down
,11-30 17:03:04.613  4689  4783 D bt_hwcfg: hw_epilog_process
,11-30 17:03:04.613  4689  4783 I bt_vendor: low_power_mode_cb
,11-30 17:03:04.616  4689  4783 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-30 17:03:04.616  4689  4783 I bt_vendor: epilog_cb
,11-30 17:03:04.616  4689  4783 I bt_hci  : epilog_finished_callback
,11-30 17:03:04.618  4689  4776 I bt_hci_h4: hal_close
,11-30 17:03:04.618  4689  4776 I bt_userial_vendor: device fd = 54 close
,11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:170)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.k.d(PG:583)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:170)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 17:03:04.678  5797  5797 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 17:03:04.678  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 17:03:04.682  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-30 17:03:04.686  3677  3677 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-30 17:03:04.689  5785  5785 D DockEventReceiver: finishStartingService: stopping service
11-30 17:03:04.704   926  3948 I ActivityManager: Killing 5513:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-30 17:03:04.730  4689  4769 D bt_stack_manager: event_shut_down_stack finished.
11-30 17:03:04.730  4689  4768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-30 17:03:04.732  4689  4689 D BtGatt.DebugUtils: handleDebugAction() action=null
11-30 17:03:04.732  4689  4768 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-30 17:03:04.732  4689  4689 D BtGatt.GattService: Received stop request...Stopping profile...
11-30 17:03:04.732  4689  4689 D BtGatt.GattService: stop()
11-30 17:03:04.732  4689  4689 D BtGatt.AdvertiseManager: advertise clients cleared
11-30 17:03:04.733  4689  4689 V BluetoothAdapterState: isTurningOff()=false
11-30 17:03:04.733  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.733  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:04.733  4689  4689 V BluetoothAdapterState: isBleTurningOff()=true
11-30 17:03:04.734  4689  4768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-30 17:03:04.734  4689  4768 D BluetoothAdapterProperties: Setting state to 10
11-30 17:03:04.734  4689  4768 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-30 17:03:04.734  4689  4768 I BluetoothAdapterState: Entering OffState
11-30 17:03:04.735   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-30 17:03:04.743  4689  4689 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-30 17:03:04.743  4689  4689 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-30 17:03:04.743  4689  4689 I BluetoothServiceJni: cleanupNative: return from cleanup
11-30 17:03:04.743  4689  4769 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-30 17:03:04.755  4689  4769 D bt_stack_manager: event_clean_up_stack finished.
,11-30 17:03:04.761  4689  4689 I art     : System.exit called, status: 0
,11-30 17:03:04.761  4689  4689 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-30 17:03:04.792  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 17:03:04.808   926  3515 I ActivityManager: Process com.android.bluetooth (pid 4689) has died
,11-30 17:03:04.829  5723  5783 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 17:03:04.829  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 17:03:04.829  5723  5783 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-30 17:03:04.829  5723  5783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 17:03:04.832  5723  5770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 17:03:04.842   926   943 I ActivityManager: Start proc 5829:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-30 17:03:04.892  5797  5814 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-30 17:03:04.902  5829  5829 D AdapterServiceConfig: Adding HeadsetService
,11-30 17:03:04.902  5829  5829 D AdapterServiceConfig: Adding A2dpService
11-30 17:03:04.902  5829  5829 D AdapterServiceConfig: Adding HidService
11-30 17:03:04.902  5829  5829 D AdapterServiceConfig: Adding HealthService
11-30 17:03:04.902  5829  5829 D AdapterServiceConfig: Adding PanService
,11-30 17:03:04.902  5829  5829 D AdapterServiceConfig: Adding GattService
11-30 17:03:04.902  5829  5829 D AdapterServiceConfig: Adding BluetoothMapService
11-30 17:03:04.903  5829  5829 D AdapterServiceConfig: Adding SapService
,11-30 17:03:04.910   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@237bd7c:true
,11-30 17:03:04.910   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@52d665a:true
,11-30 17:03:04.911  5829  5829 D BluetoothAdapterState: make() - Creating AdapterState
,11-30 17:03:04.913  5829  5829 I bt_bluedroid: init
,11-30 17:03:04.913  5829  5842 I BluetoothAdapterState: Entering OffState
,11-30 17:03:04.914  5829  5843 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-30 17:03:04.915  5829  5843 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-30 17:03:04.915  5829  5843 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-30 17:03:04.915  5829  5843 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-30 17:03:04.915  5829  5829 I bt_bluedroid: get_profile_interface socket
,11-30 17:03:04.917  5829  5829 I bt_bluedroid: get_profile_interface sdp
,11-30 17:03:04.917  5829  5846 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-30 17:03:04.918  5829  5846 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-30 17:03:04.920  5829  5840 I bt_bluedroid: config_hci_snoop_log
11-30 17:03:04.921   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-30 17:03:04.925  5829  5842 D BluetoothAdapterState: Current state: OFF, message: 0
,11-30 17:03:04.925  5829  5842 D BluetoothAdapterProperties: Setting state to 14
11-30 17:03:04.925  5829  5842 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-30 17:03:04.926  5829  5842 D BluetoothBondStateMachine: make
,11-30 17:03:04.927  5829  5847 I BluetoothBondStateMachine: StableState(): Entering Off State
11-30 17:03:04.929  5829  5842 I BluetoothAdapterState: Entering PendingCommandState
11-30 17:03:04.930  5829  5829 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-30 17:03:04.931  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
,11-30 17:03:04.932  5829  5829 D BtGatt.DebugUtils: handleDebugAction() action=null
11-30 17:03:04.932  5829  5829 D BtGatt.GattService: Received start request. Starting profile...
11-30 17:03:04.933  5829  5829 D BtGatt.GattService: start()
11-30 17:03:04.933  5829  5829 I bt_bluedroid: get_profile_interface gatt
,11-30 17:03:04.933  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
11-30 17:03:04.933  5829  5829 D BtGatt.AdvertiseManager: advertise manager created
,11-30 17:03:04.936  5829  5829 V BluetoothAdapterState: isTurningOff()=false
,11-30 17:03:04.937  5829  5829 V BluetoothAdapterState: isTurningOn()=false
11-30 17:03:04.937  5829  5829 V BluetoothAdapterState: isBleTurningOn()=true
11-30 17:03:04.937  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 17:03:04.937  5829  5842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-30 17:03:04.938  5829  5842 I bt_bluedroid: bt_bluedroid
11-30 17:03:04.938  5829  5843 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-30 17:03:04.938  5829  5843 I bt_hci  : start_up
,11-30 17:03:04.943  5829  5843 I bt_vendor: alloc value 0xf3f91871
,11-30 17:03:04.943  5829  5843 I bt_vendor: init
11-30 17:03:04.943  5829  5843 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-30 17:03:04.943  5829  5843 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-30 17:03:05.051  5829  5843 D bt_hci  : start_up starting async portion
11-30 17:03:05.051  5829  5851 I bt_hci  : event_finish_startup
,11-30 17:03:05.051  5829  5851 I bt_hci_h4: hal_open
11-30 17:03:05.051  5829  5851 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-30 17:03:05.047  5852  5852 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-30 17:03:05.052  5829  5851 I bt_userial_vendor: device fd = 54 open
,11-30 17:03:05.064  5829  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-30 17:03:05.066  5829  5851 D bt_hwcfg: Chipset BCM4358A3
11-30 17:03:05.066  5829  5851 D bt_hwcfg: Target name = [BCM4358A3]
,11-30 17:03:05.066  5829  5851 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-30 17:03:05.342  5829  5842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-30 17:03:05.473  5829  5851 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-30 17:03:05.473  5829  5851 D bt_hwcfg: Settlement delay -- 100 ms
,11-30 17:03:05.474  5829  5851 I bt_hwcfg: Setting fw settlement delay to 100 
,11-30 17:03:05.597  5829  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-30 17:03:05.597  5829  5851 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-30 17:03:05.599  5829  5851 I bt_hwcfg: vendor lib fwcfg completed
11-30 17:03:05.599  5829  5851 I bt_vendor: firmware callback
,11-30 17:03:05.599  5829  5851 I bt_hci  : firmware_config_callback
,11-30 17:03:05.610  5829  5854 I bt_btu  : btu_task pending for preload complete event
,11-30 17:03:05.610  5829  5854 I bt_btu_task: Bluetooth chip preload is complete
,11-30 17:03:05.611  5829  5854 I bt_btu  : btu_task received preload complete event
,11-30 17:03:05.617  5829  5854 I         : BTE_InitTraceLevels -- TRC_HCI
,11-30 17:03:05.617  5829  5854 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_AVDT
11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_A2D
11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_BTM
11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_GAP
11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_PAN
,11-30 17:03:05.618  5829  5854 I         : BTE_InitTraceLevels -- TRC_SDP
,11-30 17:03:05.619  5829  5854 I         : BTE_InitTraceLevels -- TRC_GATT
11-30 17:03:05.619  5829  5854 I         : BTE_InitTraceLevels -- TRC_SMP
11-30 17:03:05.619  5829  5854 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-30 17:03:05.619  5829  5854 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-30 17:03:05.703  5829  5854 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f0f549
,11-30 17:03:05.703  5829  5854 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f0f549 
,11-30 17:03:05.724  5829  5846 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-30 17:03:05.725  5829  5846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-30 17:03:05.726  5829  5846 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-30 17:03:05.729  5829  5846 D BluetoothAdapterProperties: Name is: Nexus 6P
11-30 17:03:05.732  5829  5846 D BluetoothAdapterProperties: Scan Mode:20
11-30 17:03:05.732  5829  5846 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 17:03:05.732  5829  5846 D bt_hci  : do_postload posting postload work item
,11-30 17:03:05.733  5829  5851 I bt_hci  : event_postload
11-30 17:03:05.733  5829  5851 I bt_vendor: sco_config_cb
11-30 17:03:05.733  5829  5851 I bt_hci  : sco_config_callback postload finished.
11-30 17:03:05.735  5829  5846 D bt_bte_conf: Device ID record 1 : primary
11-30 17:03:05.736  5829  5846 D bt_bte_conf:   vendorId            = 000f
,11-30 17:03:05.736  5829  5846 D bt_bte_conf:   vendorIdSource      = 0001
11-30 17:03:05.736  5829  5846 D bt_bte_conf:   product             = 1200
11-30 17:03:05.736  5829  5846 D bt_bte_conf:   version             = 1436
11-30 17:03:05.736  5829  5846 D bt_bte_conf:   clientExecutableURL = 
11-30 17:03:05.736  5829  5846 D bt_bte_conf:   serviceDescription  = 
11-30 17:03:05.736  5829  5846 D bt_bte_conf:   documentationURL    = 
11-30 17:03:05.736  5829  5846 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-30 17:03:05.737  5829  5843 D bt_stack_manager: event_start_up_stack finished
,11-30 17:03:05.737  5829  5842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-30 17:03:05.738  5829  5842 D BluetoothAdapterProperties: Setting state to 15
11-30 17:03:05.738  5829  5842 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-30 17:03:05.739  5829  5842 I BluetoothAdapterState: Entering BleOnState
,11-30 17:03:05.739  5829  5851 I bt_vendor: low_power_mode_cb
11-30 17:03:05.745  5829  5842 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-30 17:03:05.746  5829  5842 D BluetoothAdapterProperties: Setting state to 11
11-30 17:03:05.746  5829  5842 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-30 17:03:05.754  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
,11-30 17:03:05.755  5829  5829 D HeadsetService: Received start request. Starting profile...
11-30 17:03:05.757  5829  5829 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-30 17:03:05.758  5829  5829 D HeadsetStateMachine: make
,11-30 17:03:05.765  5829  5842 I BluetoothAdapterState: Entering PendingCommandState
,11-30 17:03:05.766  5829  5829 D HeadsetStateMachine: max_hf_connections = 1
,11-30 17:03:05.766  5829  5829 I bt_bluedroid: get_profile_interface handsfree
11-30 17:03:05.767  5829  5846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-30 17:03:05.767  5829  5846 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-30 17:03:05.770  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
,11-30 17:03:05.771  5829  5829 D A2dpService: Received start request. Starting profile...
11-30 17:03:05.771  3677  3677 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 17:03:05.772  5829  5829 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-30 17:03:05.772  5829  5829 I bt_bluedroid: get_profile_interface avrcp
,11-30 17:03:05.777  5829  5829 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-30 17:03:05.777  5829  5829 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-30 17:03:05.777  5829  5829 D A2dpStateMachine: make
11-30 17:03:05.778  5829  5829 I bt_bluedroid: get_profile_interface a2dp
11-30 17:03:05.779  5829  5846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-30 17:03:05.780  5829  5861 D A2dpStateMachine: Enter Disconnected: -2
,11-30 17:03:05.780  5829  5829 I BluetoothHidServiceJni: classInitNative: succeeds
,11-30 17:03:05.781  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
,11-30 17:03:05.782  5829  5829 D HidService: Received start request. Starting profile...
,11-30 17:03:05.783  5785  5785 D BluetoothInputDevice: Proxy object connected
11-30 17:03:05.783  5829  5829 I bt_bluedroid: get_profile_interface hidhost
11-30 17:03:05.783  5829  5829 D HidService: setHidService(): set to: null
11-30 17:03:05.783  5829  5846 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ef056d
11-30 17:03:05.783  5829  5846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-30 17:03:05.783  5829  5829 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-30 17:03:05.784  5785  5785 D HidProfile: Bluetooth service connected
11-30 17:03:05.784  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
11-30 17:03:05.785  5829  5829 D HealthService: Received start request. Starting profile...
,11-30 17:03:05.786  5829  5829 I bt_bluedroid: get_profile_interface health
,11-30 17:03:05.787  5829  5829 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-30 17:03:05.788  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
11-30 17:03:05.789  5785  5785 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 17:03:05.789  5829  5829 D PanService: Received start request. Starting profile...
11-30 17:03:05.789  5829  5829 D BluetoothPanServiceJni: initializeNative(L110): pan
11-30 17:03:05.789  5829  5829 I bt_bluedroid: get_profile_interface pan
11-30 17:03:05.789  5785  5785 D PanProfile: Bluetooth service connected
,11-30 17:03:05.789  5829  5846 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-30 17:03:05.792  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
,11-30 17:03:05.794  5785  5785 D BluetoothMap: Proxy object connected
,11-30 17:03:05.794  5785  5785 D MapProfile: Bluetooth service connected
11-30 17:03:05.794  5785  5785 D BluetoothMap: getConnectedDevices()
11-30 17:03:05.795  5829  5829 D BluetoothMapService: Received start request. Starting profile...
11-30 17:03:05.795  5829  5829 D BluetoothMapService: start()
11-30 17:03:05.797  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-30 17:03:05.798  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-30 17:03:05.798  5829  5829 D BluetoothMapAppObserver: createReceiver()
11-30 17:03:05.799  5829  5829 D BluetoothMapAppObserver: initObservers()
11-30 17:03:05.799  5829  5829 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-30 17:03:05.807  5829  5829 V SapService: SapBinder()
11-30 17:03:05.807  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
11-30 17:03:05.808  5829  5829 D SapService: Received start request. Starting profile...
11-30 17:03:05.808  5829  5829 V SapService: start()
11-30 17:03:05.809  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-30 17:03:05.809  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-30 17:03:05.809  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:05.809  5829  5859 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-30 17:03:05.809  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isTurningOff()=false
,11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:05.810  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isTurningOn()=true
,11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:05.811  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isTurningOff()=false
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isTurningOn()=true
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
11-30 17:03:05.812  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
11-30 17:03:05.813  5829  5842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-30 17:03:05.813  5829  5842 D BluetoothAdapterProperties: ScanMode =  20
11-30 17:03:05.813  5829  5842 D BluetoothAdapterProperties: State =  11
11-30 17:03:05.814  5785  5785 D BluetoothMap: Bluetooth is Not enabled
11-30 17:03:05.815  5829  5846 D BluetoothAdapterProperties: Scan Mode:21
11-30 17:03:05.815  5829  5842 D BluetoothAdapterProperties: Setting state to 12
11-30 17:03:05.815  5829  5842 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-30 17:03:05.815  5829  5846 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 17:03:05.816  3217  4082 D BluetoothMap: onBluetoothStateChange: up=true
11-30 17:03:05.816  5829  5842 I BluetoothAdapterState: Entering OnState
,11-30 17:03:05.817  3217  3217 D BluetoothMap: Proxy object connected
11-30 17:03:05.817  3862  4146 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 17:03:05.817  3217  3217 D MapProfile: Bluetooth service connected
11-30 17:03:05.817  3217  3217 D BluetoothMap: getConnectedDevices()
11-30 17:03:05.818  3217  3233 D BluetoothPbap: onBluetoothStateChange: up=true
11-30 17:03:05.819   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 17:03:05.819  3217  3238 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 17:03:05.820  3217  5722 D BluetoothPan: onBluetoothStateChange on: true
11-30 17:03:05.822  3217  3217 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 17:03:05.822  3217  3217 D PanProfile: Bluetooth service connected
11-30 17:03:05.822  5785  5796 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 17:03:05.822  5785  5795 D BluetoothMap: onBluetoothStateChange: up=true
11-30 17:03:05.822   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 17:03:05.823  3217  4082 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 17:03:05.824  3217  3217 D BluetoothInputDevice: Proxy object connected
11-30 17:03:05.824  5785  5796 D BluetoothPan: onBluetoothStateChange on: true
11-30 17:03:05.824  3217  3217 D HidProfile: Bluetooth service connected
11-30 17:03:05.825   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-30 17:03:05.825  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 17:03:05.825   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 17:03:05.825  3217  5722 D BluetoothA2dp: onBluetoothStateChange: up=true
11-30 17:03:05.826  5829  5829 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-30 17:03:05.827  5785  5795 D BluetoothPbap: onBluetoothStateChange: up=true
11-30 17:03:05.827  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:03:05.829   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-30 17:03:05.830  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:03:05.832  5829  5829 D ObexServerSockets: Succeed to create listening sockets 
11-30 17:03:05.832  5785  5785 D LocalBluetoothProfileManager: Adding local A2DP profile
11-30 17:03:05.832  5829  5829 D ObexServerSockets0: startAccept()
11-30 17:03:05.832  5829  5829 D ObexServerSockets0: prepareForNewConnect()
11-30 17:03:05.835  5829  5829 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-30 17:03:05.835  5829  5829 D BluetoothSdpJni: SDP Create record success - handle: 0
11-30 17:03:05.835  5829  5868 D ObexServerSockets0: Accepting socket connection...
11-30 17:03:05.835  5829  5869 D ObexServerSockets0: Accepting socket connection...
11-30 17:03:05.836   926   926 D BluetoothA2dp: Proxy object connected
11-30 17:03:05.836  3217  3217 D BluetoothA2dp: Proxy object connected
11-30 17:03:05.836  5829  5829 D BluetoothMapService: onReceive
11-30 17:03:05.836  5829  5829 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 17:03:05.836  5829  5829 D BluetoothMapService: STATE_ON
11-30 17:03:05.836  5785  5785 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-30 17:03:05.839  5829  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:03:05.841  5829  5870 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-30 17:03:05.841  5829  5870 D BluetoothSdpJni: SDP Create record success - handle: 1
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 17:03:05.845  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 17:03:05.845  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-30 17:03:05.848  5785  5785 D BluetoothA2dp: Proxy object connected
11-30 17:03:05.850  5723  5783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 17:03:05.852  5723  5770 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-30 17:03:05.853  3677  3677 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-30 17:03:05.853   926  3902 D WifiService: setWifiEnabled: false pid=5723, uid=10077
11-30 17:03:05.853   926  3902 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 17:03:05.854  5785  5785 D DockEventReceiver: finishStartingService: stopping service
11-30 17:03:05.854  5723  5770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 17:03:05.855   926  3047 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-30 17:03:05.855   926  3047 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-30 17:03:05.855   926  3047 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-30 17:03:05.855   926  3047 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-30 17:03:05.862  3217  3217 D BluetoothPbap: Proxy object connected
11-30 17:03:05.862  3217  3217 D PbapServerProfile: Bluetooth service connected
11-30 17:03:05.862  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 17:03:05.862  5829  5829 D ObexServerSockets0: prepareForNewConnect()
,11-30 17:03:05.863  5785  5785 D BluetoothPbap: Proxy object connected
11-30 17:03:05.864  5785  5785 D PbapServerProfile: Bluetooth service connected
,11-30 17:03:05.865   926  5485 D DhcpClient: Clearing IP address
,11-30 17:03:05.865   506   920 D CommandListener: Clearing all IP addresses on wlan0
,11-30 17:03:05.871  5829  5875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 17:03:05.875   506   920 D CommandListener: Setting iface cfg
,11-30 17:03:05.879  3677  5540 V NativeCrypto: Read error: ssl=0x7f7ea1d180: I/O error during system call, Connection timed out
,11-30 17:03:05.881  3677  5540 V NativeCrypto: SSL shutdown failed: ssl=0x7f7ea1d180: I/O error during system call, Broken pipe
11-30 17:03:05.881   926  5486 D DhcpClient: Receive thread stopped
11-30 17:03:05.883   926  3902 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-30 17:03:05.883   926  5483 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-30 17:03:05.886   926  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-30 17:03:05.886   926  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-30 17:03:05.887   926  5483 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-30 17:03:05.893   534   534 E Parcel  : Reading a NULL string not supported here.
11-30 17:03:05.893   926   926 D RttService: SCAN_AVAILABLE : 1
11-30 17:03:05.893   926  3156 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-30 17:03:05.893   926  3057 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-30 17:03:05.896  3835  4001 W QCNEJ   : |CORE| network lost: 100
11-30 17:03:05.896  5829  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:03:05.896  3835  4001 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-30 17:03:05.897  5829  5880 I BtOppRfcommListener: Accept thread started.
,11-30 17:03:05.903   926  3047 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-30 17:03:05.912   926  3047 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-30 17:03:05.918   926   926 D BluetoothHeadset: Proxy object connected
,11-30 17:03:05.919   926   926 D BluetoothHeadset: Proxy object connected
11-30 17:03:05.919  3217  4082 D BluetoothHeadset: Proxy object connected
11-30 17:03:05.919   926   943 D BluetoothHeadset: Proxy object connected
11-30 17:03:05.919  3217  3217 D HeadsetProfile: Bluetooth service connected
11-30 17:03:05.919  3217  3233 D BluetoothHeadset: Proxy object connected
11-30 17:03:05.920  3862  4880 D BluetoothHeadset: Proxy object connected
11-30 17:03:05.920   926   926 D BluetoothHeadset: Proxy object connected
11-30 17:03:05.921  3217  3217 D HeadsetProfile: Bluetooth service connected
,11-30 17:03:05.923   926   943 D BluetoothHeadset: Proxy object connected
,11-30 17:03:05.926   926   943 D BluetoothHeadset: Proxy object connected
,11-30 17:03:05.934   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 17:03:05.940  5785  5796 D BluetoothHeadset: Proxy object connected
,11-30 17:03:05.941  5785  5785 D HeadsetProfile: Bluetooth service connected
,11-30 17:03:05.955   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 17:03:05.955   506   920 D CommandListener: Clearing all IP addresses on wlan0
11-30 17:03:05.956   506   920 D TetherController: Setting IP forward enable = 0
,11-30 17:03:05.957   926  3057 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-30 17:03:05.957   926  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-30 17:03:05.959   926  3047 D DhcpClient: doQuit
,11-30 17:03:05.959   926  3047 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-30 17:03:05.959   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-30 17:03:05.959   926  5485 D DhcpClient: onQuitting
,11-30 17:03:05.960  3546  3546 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-30 17:03:05.971  5383  5383 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8c556a6 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-30 17:03:05.974  5150  5174 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-30 17:03:05.974  5150  5174 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 17:03:05.974  5150  5174 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-30 17:03:05.974  5150  5174 E SarControlService: no key has been found,reset the power
11-30 17:03:05.974  5150  5187 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-30 17:03:05.974  5150  5187 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-30 17:03:05.974  5150  5187 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-30 17:03:05.975  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 17:03:05.975  5175  5175 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-30 17:03:05.976  5150  5187 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-30 17:03:05.976  5150  5187 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 17:03:05.976  5150  5187 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 17:03:05.978  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-30 17:03:05.982  5175  5189 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@47a13c HexData = [00000000ea03000000000000ffffffff]
11-30 17:03:05.982  5175  5189 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 17:03:05.982  5175  5189 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-30 17:03:05.983  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 17:03:05.983  5150  5160 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-30 17:03:05.984  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 17:03:05.985  5175  5175 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-30 17:03:05.985  3937  3937 D SystemUpdateService: onCreate
11-30 17:03:05.988  3546  3546 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-30 17:03:05.989  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-30 17:03:05.992  5175  5189 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@47a13c HexData = [00000000eb03000000000000ffffffff]
11-30 17:03:05.992  5175  5189 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 17:03:05.992  5175  5189 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-30 17:03:05.993  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 17:03:05.993  5150  5161 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-30 17:03:05.997  3546  3546 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-30 17:03:06.000  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-30 17:03:06.005  3937  5896 I SystemUpdateService: active receiver: enabled
,11-30 17:03:06.006  3937  5510 I iu.UploadsManager: num queued entries: 0
,11-30 17:03:06.007  3937  5510 I iu.UploadsManager: num updated entries: 0
11-30 17:03:06.007  3937  5510 I iu.SyncManager: NEXT; no task
11-30 17:03:06.008  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-30 17:03:06.009  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-30 17:03:06.012  3937  5896 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-30 17:03:06.014  3937  5896 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-30 17:03:06.014  3937  5896 I SystemUpdateService: now status is 0 (complete)
11-30 17:03:06.014  3937  5896 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 17:03:06.014  3937  5896 I SystemUpdateService: file has been verified
11-30 17:03:06.014  3937  5896 I SystemUpdateService: OTA package size = 21989297
,11-30 17:03:06.020  3937  5896 I SystemUpdateService: showing system update notification
,11-30 17:03:06.023   926  3250 I ActivityManager: Start proc 5900:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-30 17:03:06.025   506   920 E Netd    : netlink response contains error (No such file or directory)
,11-30 17:03:06.026   506   920 D TetherController: Setting IP forward enable = 0
11-30 17:03:06.027   926  3057 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-30 17:03:06.036  3937  3937 D SystemUpdateService: onDestroy
,11-30 17:03:06.041  3546  3546 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-30 17:03:06.049  3546  3546 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-30 17:03:06.053   926  3047 D wifi    : In wifi stop Hal
,11-30 17:03:06.053   926  3047 D wifi    : halHandle = 0x7f7d9cee40, mVM = 0x7f9a04d140, mCls = 0x100a02
11-30 17:03:06.054   926  3545 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-30 17:03:06.054  5125  5125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-30 17:03:06.054   926  3545 D WifiHAL : Got a signal to exit!!!
11-30 17:03:06.054   926  3545 I WifiHAL : Exit wifi_event_loop
11-30 17:03:06.054   926  3047 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-30 17:03:06.054   926  3047 E WifiHAL : Event processing terminated
11-30 17:03:06.054   926  3047 D wifi    : In wifi cleaned up handler
,11-30 17:03:06.054   926  3047 I WifiHAL : Internal cleanup completed
11-30 17:03:06.056  4179  4324 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 17:03:06.067  5900  5900 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-30 17:03:06.070  5900  5900 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-30 17:03:06.076  5900  5900 D SprintDMHelper: simOperator: 
,11-30 17:03:06.076  5900  5900 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-30 17:03:06.076   926  3545 D wifi    : set interface wlan0 flags (DOWN)
11-30 17:03:06.076   926  3047 D WifiNative-HAL: HAL event thread stopped successfully
,11-30 17:03:06.088  5125  5914 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-30 17:03:06.100   926  3941 I ActivityManager: Start proc 5915:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-30 17:03:06.101   926  3941 I ActivityManager: Killing 5383:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-30 17:03:06.136  5915  5915 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-30 17:03:06.143   926   936 I ActivityManager: Killing 4787:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-30 17:03:06.282   926   943 D Tethering: InitialState.processMessage what=4
,11-30 17:03:06.289   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 17:03:06.365  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 17:03:06.370  5723  5783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-30 17:03:06.375   926  3941 D WifiService: setWifiEnabled: true pid=5723, uid=10077
,11-30 17:03:06.375   926  3941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 17:03:06.376  5723  5770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 17:03:06.382   506   920 D SoftapController: Softap fwReload - Ok
,11-30 17:03:06.385   506   920 D CommandListener: Setting iface cfg
,11-30 17:03:06.385   506   920 D CommandListener: Trying to bring down wlan0
,11-30 17:03:06.386   506   920 D CommandListener: Clearing all IP addresses on wlan0
,11-30 17:03:06.390   926  3047 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-30 17:03:06.884   926   937 D WifiService: setWifiEnabled: true pid=5723, uid=10077
,11-30 17:03:06.889   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 17:03:06.998   926  3047 D wifi    : set interface wlan0 flags (UP)
,11-30 17:03:06.999   926  3047 I WifiHAL : Initializing wifi
11-30 17:03:06.999   926  3047 I WifiHAL : Creating socket
11-30 17:03:07.004   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-30 17:03:07.007   926  3047 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-30 17:03:07.008   926  3047 D wifi    : Did set static halHandle = 0x7f7d9cee40
11-30 17:03:07.008   926  3047 D wifi    : halHandle = 0x7f7d9cee40, mVM = 0x7f9a04d140, mCls = 0x191a
11-30 17:03:07.008   926  3047 D wifi    : array field set
11-30 17:03:07.008   926  3047 I WifiNative-HAL: interface[0] = wlan0
,11-30 17:03:07.011   926  5931 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547568283200
,11-30 17:03:07.012   926  5931 D wifi    : waitForHalEvents called, vm = 0x7f9a04d140, obj = 0x191a, env = 0x7f800b7200
,11-30 17:03:07.090  5932  5932 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-30 17:03:07.110  5932  5932 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-30 17:03:07.118   926  3047 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-30 17:03:07.145  5932  5932 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-30 17:03:07.145  5932  5932 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-30 17:03:07.162   926  3047 D WifiConfigStore: Loading config and enabling all networks 
,11-30 17:03:07.171   926  3047 D WifiConfigStore: loaded 0 passpoint configs
,11-30 17:03:07.171   926  3047 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-30 17:03:07.172   926  3047 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-30 17:03:07.173   926  3047 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-30 17:03:07.174   926  3047 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-30 17:03:07.174   926  3047 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-30 17:03:07.174   926  3047 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-30 17:03:07.175   926  3047 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-30 17:03:07.178   926  3047 D WifiNative-HAL: Setting external_sim to 1
,11-30 17:03:07.178  5125  5125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 17:03:07.178   926  3047 D wifi    : setting dfs flag to true, 0x7f82b3e0c0
,11-30 17:03:07.180   926  3047 D WifiStateMachine: Setting OUI to DA-A1-19
11-30 17:03:07.180   926  3047 D wifi    : setting scan oui 0x7f82b3e0c0
11-30 17:03:07.180   926  3047 D WifiHAL : Sending mac address OUI
,11-30 17:03:07.185   926  3047 E native  : do suspend false
,11-30 17:03:07.192   926  3047 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-30 17:03:07.192   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-30 17:03:07.192   926   926 D RttService: SCAN_AVAILABLE : 3
11-30 17:03:07.192   926  3156 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-30 17:03:07.193   506   920 D CommandListener: Setting iface cfg
,11-30 17:03:07.197   926  3046 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-30 17:03:07.197   926  3046 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-30 17:03:07.205   926  3046 D WifiNative-HAL: p2pGetDeviceAddress
,11-30 17:03:07.206   926  3046 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-30 17:03:07.211   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106717 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 17:03:07.396  5723  5783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 17:03:07.401  5723  5783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-30 17:03:07.404  5723  5770 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 17:03:07.404   926  3948 D WifiService: setWifiEnabled: true pid=5723, uid=10077
11-30 17:03:07.405   926  3948 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 17:03:07.406  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 17:03:07.406  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 17:03:07.406  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-30 17:03:07.406  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@673e766 removed from the list
,11-30 17:03:07.406  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 17:03:07.407  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebecaa7 removed from the list
11-30 17:03:07.407  5723  5770 D io.jxcore.node.ConnectivityMonitor: stop
,11-30 17:03:07.409  5723  5770 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-30 17:03:07.412  5723  5770 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-30 17:03:07.413  5723  5770 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-30 17:03:07.415  5723  5770 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-30 17:03:07.417  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-30 17:03:07.417  5723  5770 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-30 17:03:07.418  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-30 17:03:07.418  5723  5770 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-30 17:03:07.419  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-30 17:03:07.421  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-30 17:03:07.421  5723  5770 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@491e140 Bundle[{}]
11-30 17:03:07.422  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-30 17:03:07.422  5723  5770 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-30 17:03:07.422  5723  5770 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-30 17:03:07.422  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-30 17:03:07.422  5723  5770 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-30 17:03:07.424  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-30 17:03:07.424  5723  5770 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-30 17:03:07.425  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-30 17:03:07.425  5723  5770 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-30 17:03:07.426  5723  5770 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-30 17:03:07.426  5723  5770 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-30 17:03:07.428  5723  5770 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-30 17:03:07.429  5723  5770 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-30 17:03:07.430  5723  5770 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-30 17:03:07.430  5723  5770 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-30 17:03:07.431  5723  5770 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-30 17:03:07.431  5723  5770 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-30 17:03:07.433  5723  5770 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-30 17:03:07.434  5723  5770 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-30 17:03:08.438  5723  5770 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-30 17:03:08.441  5723  5770 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-30 17:03:08.446  5723  5770 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-30 17:03:08.448  5723  5770 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-30 17:03:08.449  5723  5770 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-30 17:03:08.449  5723  5770 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,11-30 17:03:08.451  5723  5770 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-30 17:03:08.451  5723  5770 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-30 17:03:08.452  5723  5770 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,11-30 17:03:08.453  5723  5770 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-30 17:03:08.455  5723  5770 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-30 17:03:08.456  5723  5770 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-30 17:03:08.457  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-30 17:03:08.457  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b3aafd added. We now have 3 listener(s)
11-30 17:03:08.459  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:03:08.459  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 17:03:08.459  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-30 17:03:08.459  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 17:03:08.459  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44713f2 added. We now have 3 listener(s)
11-30 17:03:08.460  5723  5770 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 17:03:08.460  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 17:03:08.466  5723  5770 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-30 17:03:08.467  5723  5770 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-30 17:03:08.467  5723  5770 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-30 17:03:08.467  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-30 17:03:08.468  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.468  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.468  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.468  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 17:03:08.468  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-30 17:03:08.468  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 17:03:08.468  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:03:08.468  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 17:03:08.476  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 17:03:08.478  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-30 17:03:08.478  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-30 17:03:08.478  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 17:03:08.478  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 17:03:08.478  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-30 17:03:08.478  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 17:03:08.478  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:03:08.478  5723  5936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 17:03:08.479  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 17:03:08.480  5723  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 17:03:08.480  5867  5867 W Binder_4: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33412]" dev="sockfs" ino=33412 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 17:03:08.480  5867  5867 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33412]" dev="sockfs" ino=33412 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:03:08.484  5723  5936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 17:03:08.484  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 17:03:08.484  5723  5770 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 17:03:08.484  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 17:03:08.488  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:08.488  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 17:03:08.489  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 17:03:08.489  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 17:03:08.489  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-30 17:03:08.492  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:08.492  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.492  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 17:03:08.492  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 17:03:08.492  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:03:08.492  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
11-30 17:03:08.492  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:03:08.492  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:03:08.492  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:08.493  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 17:03:08.493  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:03:08.493  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.493  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.493  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.494  5723  5770 D BluetoothAdapter: STATE_ON
,11-30 17:03:08.498  5829  5867 D BtGatt.GattService: registerClient() - UUID=505a5252-2a2e-498c-a050-e99afde569ab
,11-30 17:03:08.498  5829  5846 D BtGatt.GattService: onClientRegistered() - UUID=505a5252-2a2e-498c-a050-e99afde569ab, clientIf=5
,11-30 17:03:08.499  5723  5734 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 17:03:08.502  5829  5849 D BtGatt.AdvertiseManager: message : 0
,11-30 17:03:08.504  5829  5849 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 17:03:08.516  5829  5846 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 17:03:08.523  5829  5846 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 17:03:08.523  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:08.523  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.524  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 17:03:08.524  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.524  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.524  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.524  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.524  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.524  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 17:03:08.525  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 17:03:08.525  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.526  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.527  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.527  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:08.527  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 17:03:08.527  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.527  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:08.527  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 17:03:08.527  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.527  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.527  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:08.528  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.528  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 17:03:08.528  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 17:03:08.528  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.52,8  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.528  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.528  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.528  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 17:03:08.531  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.531  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 17:03:08.531  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-30 17:03:08.531  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:08.531  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 17:03:09.032  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-30 17:03:09.033  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 17:03:09.033  5723  5723 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 17:03:10.363  5932  5932 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 17:03:10.367  5932  5932 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 17:03:10.373  5932  5932 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 17:03:10.451   926  3047 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-30 17:03:10.454   926  3047 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-30 17:03:10.454   926  3047 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 17:03:10.467   926  3047 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-30 17:03:10.502   926  3047 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-30 17:03:10.504  5932  5932 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-30 17:03:10.923  5932  5932 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-30 17:03:10.957  5932  5932 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-30 17:03:10.958  5932  5932 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-30 17:03:10.969   926  3047 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 17:03:10.969   926  3047 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-30 17:03:10.969   926  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-30 17:03:10.987   926  3047 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 17:03:11.001   506   920 D CommandListener: Setting iface cfg
,11-30 17:03:11.008   926  3047 D WifiStateMachine: Start Dhcp Watchdog 2
,11-30 17:03:11.014   926  5941 D DhcpClient: Receive thread started
,11-30 17:03:11.020   926  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:11.020   926  3047 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-30 17:03:11.020   926  3057 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-30 17:03:11.101   926  3047 E native  : do suspend false
,11-30 17:03:11.110   926  5940 D DhcpClient: Broadcasting DHCPDISCOVER
,11-30 17:03:11.123   926  5941 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172729, domain null
,11-30 17:03:11.123   926  5940 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172729 seconds
,11-30 17:03:11.124   926  5940 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-30 17:03:11.138   926  5941 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-30 17:03:11.138   926  5940 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-30 17:03:11.140   506   920 D CommandListener: Setting iface cfg
,11-30 17:03:11.144   926  3047 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-30 17:03:11.147   926  5940 D DhcpClient: Scheduling renewal in 86399s
,11-30 17:03:11.153   926  3047 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-30 17:03:11.153   926  3047 D WifiConfigStore: No blacklist allowed without epno enabled
11-30 17:03:11.154   926  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-30 17:03:11.155   926  3047 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-30 17:03:11.157   926  3057 D ConnectivityService: Adding iface wlan0 to network 101
,11-30 17:03:11.187   926  3057 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-30 17:03:11.187   926  3057 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-30 17:03:11.189   926  3057 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-30 17:03:11.191   926  3057 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-30 17:03:11.192   926  3057 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-30 17:03:11.198   926  3057 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:11.201   926  3057 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-30 17:03:11.201   926  3057 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-30 17:03:11.202   926  3057 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-30 17:03:11.202   926  3057 D ConnectivityService:    accepting network in place of null
11-30 17:03:11.202   926  3057 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 17:03:11.202   926  3047 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-30 17:03:11.209   926  3047 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-30 17:03:11.214   926  5939 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110721, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-30 17:03:11.224   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 17:03:11.242   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 17:03:11.247   926  3057 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-30 17:03:11.247   926  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-30 17:03:11.247  3835  4001 W QCNEJ   : |CORE| network available: 101
11-30 17:03:11.248   926  3057 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-30 17:03:11.249   926   943 D Tethering: MasterInitialState.processMessage what=3
11-30 17:03:11.250  3835  4001 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-30 17:03:11.251  3835  4001 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-30 17:03:11.252  3835  4001 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-30 17:03:11.260  5150  5174 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-30 17:03:11.260  5150  5174 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 17:03:11.260  5150  5174 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-30 17:03:11.260  5150  5174 E SarControlService: no key has been found,reset the power
11-30 17:03:11.260  5150  5187 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-30 17:03:11.260  5150  5187 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-30 17:03:11.260  5150  5187 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-30 17:03:11.261  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 17:03:11.261  5175  5175 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-30 17:03:11.262  5150  5187 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-30 17:03:11.262  5150  5187 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 17:03:11.262  5150  5187 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 17:03:11.262  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 17:03:11.263  5175  5175 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-30 17:03:11.265  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-30 17:03:11.269  5175  5189 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@47a13c HexData = [00000000ec03000000000000ffffffff]
,11-30 17:03:11.269  5175  5189 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 17:03:11.269  5175  5189 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-30 17:03:11.269  5175  5189 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@47a13c HexData = [00000000ed03000000000000ffffffff]
,11-30 17:03:11.269  5175  5189 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 17:03:11.269  5175  5189 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-30 17:03:11.270  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 17:03:11.270  5150  5160 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-30 17:03:11.271  3937  3937 D SystemUpdateService: onCreate
11-30 17:03:11.271  5175  5175 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 17:03:11.271  5150  5161 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-30 17:03:11.274  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-30 17:03:11.286  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-30 17:03:11.286   926  5938 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,11-30 17:03:11.292  3937  5510 I iu.UploadsManager: num queued entries: 0
,11-30 17:03:11.292  3937  5510 I iu.UploadsManager: num updated entries: 0
,11-30 17:03:11.297  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-30 17:03:11.298  3937  5951 I SystemUpdateService: active receiver: enabled
11-30 17:03:11.299  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-30 17:03:11.302  5900  5900 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-30 17:03:11.306  5900  5900 D SprintDMHelper: simOperator: 
,11-30 17:03:11.307  5900  5900 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-30 17:03:11.318  3937  5510 I iu.SyncManager: NEXT; no task
,11-30 17:03:11.319  3937  5951 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-30 17:03:11.340  3937  5951 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-30 17:03:11.340  3937  5951 I SystemUpdateService: now status is 0 (complete)
11-30 17:03:11.340  3937  5951 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 17:03:11.340  3937  5951 I SystemUpdateService: file has been verified
11-30 17:03:11.340  3937  5951 I SystemUpdateService: OTA package size = 21989297
,11-30 17:03:11.347   926  5938 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 30 Nov 2016 22:03:11 GMT], X-Android-Received-Millis=[1480543391346], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480543391318]}
,11-30 17:03:11.347  3937  5951 I SystemUpdateService: showing system update notification
,11-30 17:03:11.347   926  3057 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-30 17:03:11.347   926  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-30 17:03:11.348   926  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:11.349   926  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-30 17:03:11.360  3937  3937 D SystemUpdateService: onDestroy
,11-30 17:03:11.424  5125  5956 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-30 17:03:12.029  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-30 17:03:12.029  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-30 17:03:12.030  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-30 17:03:12.030  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 17:03:12.030  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 17:03:12.030  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-30 17:03:12.030  5723  5936 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 17:03:12.031  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 17:03:12.031  5723  5936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 17:03:12.031  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-30 17:03:12.031  5723  5936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 17:03:12.031  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 17:03:12.031  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-30 17:03:12.031  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 17:03:12.031  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.032  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-30 17:03:12.032  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 17:03:12.032  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.032  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.032  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.033  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.035  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:03:12.035  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 17:03:12.037  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:03:12.038  5723  5770 D BluetoothLeScanner: could not find callback wrapper
,11-30 17:03:12.038  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 17:03:12.038  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.038  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.038  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.039  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 17:03:12.039  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.041  5829  5849 D BtGatt.AdvertiseManager: message : 1
11-30 17:03:12.043  5829  5849 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 17:03:12.057  5829  5846 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 17:03:12.057  5829  5846 D BtGatt.GattService: Client app is not null!
,11-30 17:03:12.059  5829  5867 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 17:03:12.060  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 17:03:12.060  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.060  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-30 17:03:12.060  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.061  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.061  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.061  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 17:03:12.061  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 17:03:12.062  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 17:03:12.063  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.065  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.066  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:03:12.066  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.066  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.067  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 17:03:12.067  5723  5723 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 17:03:12.067  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 17:03:12.067  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-30 17:03:12.067  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:03:12.067  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:03:12.067  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:12.068  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 17:03:12.068  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 17:03:12.068  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 17:03:12.068  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.068  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-30 17:03:12.068  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.068  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:03:12.068  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.068  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 17:03:12.070  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.070  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.070  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-30 17:03:12.075  5723  5770 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-30 17:03:12.075  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 17:03:12.076  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 17:03:12.076  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-30 17:03:12.076  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-30 17:03:12.077  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:03:12.077  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 17:03:12.078  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-30 17:03:12.082  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 17:03:12.082  5723  5770 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 17:03:12.082  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 17:03:12.086  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.087  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-30 17:03:12.087  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 17:03:12.088  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 17:03:12.088  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-30 17:03:12.091  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-30 17:03:12.095  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-30 17:03:12.095  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.095  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 17:03:12.095  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-30 17:03:12.095  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-30 17:03:12.096  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-30 17:03:12.096  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.097  5723  5770 D BluetoothAdapter: STATE_ON
,11-30 17:03:12.100  5829  5840 D BtGatt.GattService: registerClient() - UUID=75709aa4-ed12-4657-ac99-517c38a2a46e
,11-30 17:03:12.102  5829  5846 D BtGatt.GattService: onClientRegistered() - UUID=75709aa4-ed12-4657-ac99-517c38a2a46e, clientIf=5
11-30 17:03:12.102  5723  5734 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-30 17:03:12.104  5829  5866 D BtGatt.GattService: start scan with filters
,11-30 17:03:12.108  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-30 17:03:12.108  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.108  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 17:03:12.108  5829  5850 D BtGatt.ScanManager: handling starting scan
11-30 17:03:12.109  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.109  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 17:03:12.109  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:12.109  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.109  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-30 17:03:12.109  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 17:03:12.109  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.109  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.110  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.110  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.110  5829  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e08617d
,11-30 17:03:12.110  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 17:03:12.111  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.113  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.114  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-30 17:03:12.114  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:12.114  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:12.114  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 17:03:12.118  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 17:03:12.118  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.118  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:12.118  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-30 17:03:12.118  5829  5846 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-30 17:03:12.118  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:12.119  5829  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-30 17:03:12.124  5829  5846 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-30 17:03:12.124  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:12.125  5829  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-30 17:03:12.125  5829  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-30 17:03:12.134  5829  5846 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-30 17:03:12.134  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 17:03:12.140  5829  5846 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-30 17:03:12.140  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 17:03:12.248   926  3057 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-30 17:03:12.619  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-30 17:03:12.619  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 17:03:12.619  5723  5723 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 17:03:13.969   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 17:03:13.969   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 17:03:14.041   926  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:15.116  5723  5770 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-30 17:03:15.117  5723  5770 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-30 17:03:15.117  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-30 17:03:15.117  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.118  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.118  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 17:03:15.118  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.118  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-30 17:03:15.119  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.119  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.119  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 17:03:15.119  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 17:03:15.119  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.121  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.121  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.129  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:03:15.130  5829  5866 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-30 17:03:15.131  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 17:03:15.131  5829  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 17:03:15.133  5723  5770 D BluetoothAdapter: STATE_ON
,11-30 17:03:15.134  5829  5839 D BtGatt.GattService: stopScan() - queue size =1
11-30 17:03:15.136  5829  5840 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 17:03:15.137  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 17:03:15.138  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.138  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-30 17:03:15.138  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.138  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 17:03:15.138  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.138  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.138  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 17:03:15.138  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-30 17:03:15.138  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-30 17:03:15.138  5829  5829 D BtGatt.ScanManager: awakened up at time 114645
11-30 17:03:15.139  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-30 17:03:15.139  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.141  5723  5770 D BluetoothAdapter: STATE_ON
,11-30 17:03:15.145  5829  5867 D BtGatt.GattService: registerClient() - UUID=00f071df-3499-4fce-94d4-c9244a4ca9f6
11-30 17:03:15.146  5829  5846 D BtGatt.GattService: onClientRegistered() - UUID=00f071df-3499-4fce-94d4-c9244a4ca9f6, clientIf=5
,11-30 17:03:15.148  5723  5733 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-30 17:03:15.148  5829  5840 D BtGatt.GattService: start scan with filters
,11-30 17:03:15.152  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-30 17:03:15.152  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.152  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 17:03:15.152  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.153  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.153  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:15.153  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 17:03:15.153  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.153  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-30 17:03:15.153  5723  5770 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-30 17:03:15.153  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 17:03:15.153  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 17:03:15.153  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.153  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 17:03:15.153  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.155  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 17:03:15.155  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 17:03:15.155  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 17:03:15.155  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-30 17:03:15.156  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 17:03:15.156  5723  5964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 17:03:15.156  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 17:03:15.156  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-30 17:03:15.156  5829  5846 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-30 17:03:15.156  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:15.156  5829  5846 D BtGatt.GattService: current time is 114663538951
11-30 17:03:15.156  5723  5964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 17:03:15.153  5867  5867 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34843]" dev="sockfs" ino=34843 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:03:15.153  5867  5867 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34843]" dev="sockfs" ino=34843 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 17:03:15.157  5829  5846 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -70, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -69, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -75, 112, 8, 38, 113, -28, 1, -128, -95, 30, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -100, 103, 104, 3, 2, -25, 23, 62, -7, 33, -128, 0]
11-30 17:03:15.157  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 17:03:15.157  5723  5770 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 17:03:15.158  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-30 17:03:15.159  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-30 17:03:15.159  5723  5964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 17:03:15.159  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, ,-74, -46, -4, -117, 6]
11-30 17:03:15.159  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-30 17:03:15.159  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-30 17:03:15.160  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -100, 103, 104, 3, 2, -25, 23, 62, -7, 33, -128]
11-30 17:03:15.164  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.164  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.164  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.164  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 17:03:15.164  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 17:03:15.164  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 17:03:15.164  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
11-30 17:03:15.164  5723  5770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:03:15.164  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 17:03:15.165  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.165  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 17:03:15.165  5829  5846 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-30 17:03:15.165  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:15.165  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 17:03:15.165  5829  5850 D BtGatt.ScanManager: stopping BLe Batch
11-30 17:03:15.165  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.165  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.165  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.166  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:03:15.170  5829  5846 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-30 17:03:15.170  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 17:03:15.170  5829  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 17:03:15.173  5829  5866 D BtGatt.GattService: registerClient() - UUID=fc9bb8fd-2c5e-476a-81b1-16c95de7fdec
,11-30 17:03:15.173  5829  5846 D BtGatt.GattService: onClientRegistered() - UUID=fc9bb8fd-2c5e-476a-81b1-16c95de7fdec, clientIf=6
11-30 17:03:15.174  5723  5734 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-30 17:03:15.175  5829  5849 D BtGatt.AdvertiseManager: message : 0
,11-30 17:03:15.175  5829  5846 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-30 17:03:15.175  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:15.177  5829  5850 D BtGatt.ScanManager: handling starting scan
,11-30 17:03:15.179  5829  5849 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 17:03:15.183  5829  5846 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-30 17:03:15.183  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:15.183  5829  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-30 17:03:15.191  5829  5846 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-30 17:03:15.195  5829  5846 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-30 17:03:15.195  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:15.195  5829  5850 D BtGatt.ScanManager: Starting BLE batch scan
11-30 17:03:15.195  5829  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-30 17:03:15.199  5829  5846 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-30 17:03:15.199  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.199  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.199  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 17:03:15.199  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.199  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.199  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.200  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.200  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.200  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.200  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.200  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.200  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-30 17:03:15.200  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
,11-30 17:03:15.200  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 17:03:15.201  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 17:03:15.201  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.204  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:15.204  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.204  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:15.204  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 17:03:15.205  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-30 17:03:15.205  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:15.205  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 17:03:15.205  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.205  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.205  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:15.205  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.206  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-30 17:03:15.206  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 17:03:15.206  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-30 17:03:15.206  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.206  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.206  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.206  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.207  5829  5846 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-30 17:03:15.207  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 17:03:15.209  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.209  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-30 17:03:15.209  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.209  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:15.210  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-30 17:03:15.212  5829  5846 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-30 17:03:15.212  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 17:03:15.711  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-30 17:03:15.711  5723  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 17:03:15.711  5723  5723 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 17:03:17.068   926  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:18.207  5723  5770 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-30 17:03:18.208  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 17:03:18.208  5723  5770 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-30 17:03:18.208  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 17:03:18.208  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 17:03:18.209  5723  5964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 17:03:18.209  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 17:03:18.210  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 17:03:18.210  5723  5770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 17:03:18.210  5723  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 17:03:18.209  5723  5964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 17:03:18.210  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-30 17:03:18.210  5723  5964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 17:03:18.211  5723  5770 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b3aafd removed from the list
11-30 17:03:18.211  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 17:03:18.211  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-30 17:03:18.211  5723  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 17:03:18.211  5723  5770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-30 17:03:18.211  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.211  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 17:03:18.211  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 17:03:18.212  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:18.212  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.213  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.213  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-30 17:03:18.213  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.215  5723  5770 D BluetoothAdapter: STATE_ON
11-30 17:03:18.216  5829  5839 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-30 17:03:18.217  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 17:03:18.217  5829  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-30 17:03:18.218  5723  5770 D BluetoothAdapter: STATE_ON
,11-30 17:03:18.219  5829  5866 D BtGatt.GattService: stopScan() - queue size =1
,11-30 17:03:18.222  5829  5840 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 17:03:18.224  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-30 17:03:18.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-30 17:03:18.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.225  5829  5829 D BtGatt.ScanManager: awakened up at time 117732
11-30 17:03:18.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:18.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.225  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-30 17:03:18.225  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.227  5829  5849 D BtGatt.AdvertiseManager: message : 1
11-30 17:03:18.229  5829  5849 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-30 17:03:18.245  5829  5846 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-30 17:03:18.245  5829  5846 D BtGatt.GattService: Client app is not null!
,11-30 17:03:18.247  5829  5866 D BtGatt.GattService: unregisterClient() - clientIf=6
11-30 17:03:18.247  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 17:03:18.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:18.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 17:03:18.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 17:03:18.248  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 17:03:18.248  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 17:03:18.249  5723  5770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 17:03:18.251  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.253  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.253  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:03:18.253  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.253  5723  5770 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 17:03:18.253  5723  5770 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44713f2 removed from the list
11-30 17:03:18.253  5723  5770 D io.jxcore.node.ConnectivityMonitor: stop
11-30 17:03:18.254  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:03:18.254  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 17:03:18.254  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-30 17:03:18.254  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.254  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 17:03:18.254  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-30 17:03:18.255  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.255  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 17:03:18.255  5723  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.255  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-30 17:03:18.255  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 17:03:18.255  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.255  5723  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.255  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-30 17:03:18.255  5723  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 17:03:18.255  5723  5770 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-30 17:03:18.255  5723  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.256  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.256  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-30 17:03:18.258  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-30 17:03:18.259  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-30 17:03:18.262  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-30 17:03:18.262  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.262  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.262  5723  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 17:03:18.263  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-30 17:03:18.263  5829  5846 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-30 17:03:18.263  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:18.263  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-30 17:03:18.264  5829  5846 D BtGatt.GattService: current time is 117770780149
11-30 17:03:18.264  5829  5846 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -68, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -74, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 50, -35, 86, -77, -92, -11, 1, 0, -92, 30, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -105, 100, 104, 3, 2, -33, 21, -106, -59, -72, -7, 28, 6, 8, 116, 105, 110, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -74, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -67, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-30 17:03:18.264  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-30 17:03:18.264  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-30 17:03:18.264  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-30 17:03:18.265  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -105, 100, 104, 3, 2, -33, 21, -106, -59, -72, -7, 6, 8, 116, 105, 110, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 17:03:18.265  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-30 17:03:18.265  5723  5770 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
11-30 17:03:18.265  5829  5846 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-30 17:03:18.265  5829  5846 E BtGatt.ContextMap: Context not found for ID 5
,11-30 17:03:18.276  5829  5846 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-30 17:03:18.276  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:18.277  5829  5850 D BtGatt.ScanManager: stopping BLe Batch
,11-30 17:03:18.282  5829  5846 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-30 17:03:18.282  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 17:03:18.282  5829  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 17:03:18.288  5829  5846 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-30 17:03:18.288  5829  5846 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 17:03:18.756  5723  5723 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 17:03:18.970   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:19.204   926  3057 D ConnectivityService: handlePromptUnvalidated 101
,11-30 17:03:19.971   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:20.088   926  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:20.269  5723  5770 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-30 17:03:20.429  5723  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 17:03:20.429  5723  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:20.797   926  3047 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-30 17:03:20.972   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:21.244  5723  5966 W !!      : call onHalfStreamCopied
,11-30 17:03:21.244  5723  5966 I testCopyDataAndClose: closing input stream
,11-30 17:03:21.973   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 17:03:22.017  5723  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 17:03:22.206   926  3047 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-30 17:03:22.974   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:23.975   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-30 17:03:25.803  5723  5770 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-30 17:03:25.892  5723  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 17:03:25.892  5723  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 193, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 17:03:27.524  5723  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 17:03:28.137   926  5939 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127644, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-30 17:03:28.976   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:29.167   926  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:29.977   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:30.979   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:31.263  5723  5770 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-30 17:03:31.266  5723  5968 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-30 17:03:31.266  5723  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: My test thread name). Connection data: Peer properties: [null null].
11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-30 17:03:31.267  5723  5968 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-30 17:03:31.268  5723  5968 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-30 17:03:31.268  5723  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-30 17:03:31.269  5723  5770 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-30 17:03:31.269  5723  5770 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-30 17:03:31.270  5723  5770 I StreamCopyingThreadTest: Starting test: testRunWithException
11-30 17:03:31.272  5723  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 17:03:31.272  5723  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 17:03:31.273  5723  5969 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 199, thread name: My test thread name): Test exception.
11-30 17:03:31.274  5723  5969 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 17:03:31.274  5723  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-30 17:03:31.274  5723  5969 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-30 17:03:31.274  5723  5969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 17:03:31.274  5723  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-30 17:03:31.276  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG UnitTest_app: 'Running unit tests'
11-30 17:03:31.276  5723  5770 I jxcore-log: 
11-30 17:03:31.276  5723  5770 I jxcore-log: *Native tests were executed*
11-30 17:03:31.276  5723  5770 I jxcore-log: 
11-30 17:03:31.277  5723  5770 I jxcore-log: Total number of executed tests:  81
11-30 17:03:31.277  5723  5770 I jxcore-log: 
,11-30 17:03:31.277  5723  5770 I jxcore-log: Number of passed tests:  79
11-30 17:03:31.277  5723  5770 I jxcore-log: 
11-30 17:03:31.277  5723  5770 I jxcore-log: Number of failed tests:  0
11-30 17:03:31.277  5723  5770 I jxcore-log: 
11-30 17:03:31.277  5723  5770 I jxcore-log: Number of ignored tests:  2
11-30 17:03:31.277  5723  5770 I jxcore-log: 
11-30 17:03:31.277  5723  5770 I jxcore-log: Total duration:  33915
11-30 17:03:31.277  5723  5770 I jxcore-log: 
11-30 17:03:31.279  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-30 17:03:31.279  5723  5770 I jxcore-log: 
,11-30 17:03:31.282  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 17:03:31.282  5723  5770 I jxcore-log: 
11-30 17:03:31.282  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 17:03:31.282  5723  5770 I jxcore-log: 
,11-30 17:03:31.283  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 17:03:31.283  5723  5770 I jxcore-log: 
11-30 17:03:31.283  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 17:03:31.283  5723  5770 I jxcore-log: 
11-30 17:03:31.284  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 17:03:31.284  5723  5770 I jxcore-log: 
11-30 17:03:31.285  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 17:03:31.285  5723  5770 I jxcore-log: 
11-30 17:03:31.285  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.285  5723  5770 I jxcore-log: 
11-30 17:03:31.285  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 17:03:31.285  5723  5770 I jxcore-log: 
11-30 17:03:31.286  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 17:03:31.286  5723  5770 I jxcore-log: 
11-30 17:03:31.286  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.286  5723  5770 I jxcore-log: 
11-30 17:03:31.286  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 17:03:31.286  5723  5770 I jxcore-log: 
11-30 17:03:31.286  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 17:03:31.286  5723  5770 I jxcore-log: 
11-30 17:03:31.286  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.286  5723  5770 I jxcore-log: 
11-30 17:03:31.287  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 17:03:31.287  5723  5770 I jxcore-log: 
11-30 17:03:31.287  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.287  5723  5770 I jxcore-log: 
11-30 17:03:31.287  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 17:03:31.287  5723  5770 I jxcore-log: 
,11-30 17:03:31.287  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 17:03:31.287  5723  5770 I jxcore-log: 
11-30 17:03:31.288  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 17:03:31.288  5723  5770 I jxcore-log: 
11-30 17:03:31.288  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.288  5723  5770 I jxcore-log: 
11-30 17:03:31.288  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 17:03:31.288  5723  5770 I jxcore-log: 
,11-30 17:03:31.288  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 17:03:31.288  5723  5770 I jxcore-log: 
11-30 17:03:31.288  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 17:03:31.288  5723  5770 I jxcore-log: 
11-30 17:03:31.289  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 17:03:31.289  5723  5770 I jxcore-log: 
11-30 17:03:31.289  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-30 17:03:31.289  5723  5770 I jxcore-log: 
11-30 17:03:31.289  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 17:03:31.289  5723  5770 I jxcore-log: 
11-30 17:03:31.289  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-30 17:03:31.289  5723  5770 I jxcore-log: 
11-30 17:03:31.290  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 17:03:31.290  5723  5770 I jxcore-log: 
11-30 17:03:31.290  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 17:03:31.290  5723  5770 I jxcore-log: 
11-30 17:03:31.290  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 17:03:31.290  5723  5770 I jxcore-log: 
11-30 17:03:31.291  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.291  5723  5770 I jxcore-log: 
11-30 17:03:31.292  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-30 17:03:31.292  5723  5770 I jxcore-log: 
,11-30 17:03:31.292  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 17:03:31.292  5723  5770 I jxcore-log: 
11-30 17:03:31.292  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.292  5723  5770 I jxcore-log: 
,11-30 17:03:31.293  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-30 17:03:31.293  5723  5770 I jxcore-log: 
11-30 17:03:31.293  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 17:03:31.293  5723  5770 I jxcore-log: 
11-30 17:03:31.293  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.293  5723  5770 I jxcore-log: 
11-30 17:03:31.293  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 17:03:31.293  5723  5770 I jxcore-log: 
11-30 17:03:31.293  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 17:03:31.293  5723  5770 I jxcore-log: 
,11-30 17:03:31.296  5723  5723 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-30 17:03:31.296  5723  5723 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-30 17:03:31.299  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-30 17:03:31.299  5723  5770 I jxcore-log: 
11-30 17:03:31.299  5723  5770 I jxcore-log: 2016-11-30 22:03:31 - WARN testUtils: 'myNameCallback not set!'
11-30 17:03:31.299  5723  5770 I jxcore-log: 
,11-30 17:03:31.980   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:32.185   926  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 17:03:32.981   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 17:03:33.364  5723  5770 I jxcore-log: 2016-11-30 22:03:33 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-30 17:03:33.364  5723  5770 I jxcore-log: 
,11-30 17:03:33.366  5723  5770 I jxcore-log: 2016-11-30 22:03:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-30 17:03:33.366  5723  5770 I jxcore-log: 
,11-30 17:03:33.703  5723  5770 I jxcore-log: 2016-11-30 22:03:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-30 17:03:33.703  5723  5770 I jxcore-log: 
,11-30 17:03:33.714  5723  5770 I jxcore-log: 2016-11-30 22:03:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-30 17:03:33.714  5723  5770 I jxcore-log: 
,11-30 17:03:33.982   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-30 17:03:34.805  5723  5770 I jxcore-log: 2016-11-30 22:03:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-30 17:03:34.805  5723  5770 I jxcore-log: 
,11-30 17:03:34.969  5723  5770 I jxcore-log: 2016-11-30 22:03:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-30 17:03:34.969  5723  5770 I jxcore-log: 
,11-30 17:03:34.973  5723  5770 I jxcore-log: 2016-11-30 22:03:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-30 17:03:34.973  5723  5770 I jxcore-log: 
,11-30 17:03:34.984  5723  5770 I jxcore-log: 2016-11-30 22:03:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-30 17:03:34.984  5723  5770 I jxcore-log: 
,11-30 17:03:35.465  5723  5770 I jxcore-log: 2016-11-30 22:03:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-30 17:03:35.465  5723  5770 I jxcore-log: 
,11-30 17:03:35.509  5723  5770 I jxcore-log: 2016-11-30 22:03:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-30 17:03:35.509  5723  5770 I jxcore-log: 
,11-30 17:03:35.522  5723  5770 I jxcore-log: 2016-11-30 22:03:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-30 17:03:35.522  5723  5770 I jxcore-log: 
,11-30 17:03:35.526  5723  5770 I jxcore-log: 2016-11-30 22:03:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-30 17:03:35.526  5723  5770 I jxcore-log: 
,11-30 17:03:35.800  5723  5770 I jxcore-log: 2016-11-30 22:03:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-30 17:03:35.800  5723  5770 I jxcore-log: 
,11-30 17:03:35.923  5723  5770 I jxcore-log: 2016-11-30 22:03:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-30 17:03:35.923  5723  5770 I jxcore-log: 
,11-30 17:03:36.299  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-30 17:03:36.299  5723  5770 I jxcore-log: 
,11-30 17:03:36.306  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-30 17:03:36.306  5723  5770 I jxcore-log: 
,11-30 17:03:36.310  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-30 17:03:36.310  5723  5770 I jxcore-log: 
,11-30 17:03:36.314  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-30 17:03:36.314  5723  5770 I jxcore-log: 
,11-30 17:03:36.319  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-30 17:03:36.319  5723  5770 I jxcore-log: 
,11-30 17:03:36.356  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-30 17:03:36.356  5723  5770 I jxcore-log: 
,11-30 17:03:36.362  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-30 17:03:36.362  5723  5770 I jxcore-log: 
,11-30 17:03:36.384  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-30 17:03:36.384  5723  5770 I jxcore-log: 
,11-30 17:03:36.422  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-30 17:03:36.422  5723  5770 I jxcore-log: 
,11-30 17:03:36.438  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-30 17:03:36.438  5723  5770 I jxcore-log: 
,11-30 17:03:36.445  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-30 17:03:36.445  5723  5770 I jxcore-log: 
,11-30 17:03:36.460  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-30 17:03:36.460  5723  5770 I jxcore-log: 
,11-30 17:03:36.475  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-30 17:03:36.475  5723  5770 I jxcore-log: 
,11-30 17:03:36.481  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-30 17:03:36.481  5723  5770 I jxcore-log: 
,11-30 17:03:36.486  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-30 17:03:36.486  5723  5770 I jxcore-log: 
,11-30 17:03:36.500  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-30 17:03:36.500  5723  5770 I jxcore-log: 
,11-30 17:03:36.517  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-30 17:03:36.517  5723  5770 I jxcore-log: 
,11-30 17:03:36.532  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-30 17:03:36.532  5723  5770 I jxcore-log: 
,11-30 17:03:36.542  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-30 17:03:36.542  5723  5770 I jxcore-log: 
,11-30 17:03:36.555  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-30 17:03:36.555  5723  5770 I jxcore-log: 
,11-30 17:03:36.565  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-30 17:03:36.565  5723  5770 I jxcore-log: 
,11-30 17:03:36.579  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-30 17:03:36.579  5723  5770 I jxcore-log: 
,11-30 17:03:36.588  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-30 17:03:36.588  5723  5770 I jxcore-log: 
,11-30 17:03:36.595  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-30 17:03:36.595  5723  5770 I jxcore-log: 
,11-30 17:03:36.616  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-30 17:03:36.616  5723  5770 I jxcore-log: 
,11-30 17:03:36.622  5723  5770 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-30 17:03:36.623  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO testUtils: 'BLE multiple advertisement supported'
11-30 17:03:36.623  5723  5770 I jxcore-log: 
,11-30 17:03:36.655  5723  5770 I jxcore-log: 2016-11-30 22:03:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-30 17:03:36.655  5723  5770 I jxcore-log: 
,11-30 17:03:37.192  5723  5770 I jxcore-log: 2016-11-30 22:03:37 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 17:03:37.192  5723  5770 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 17:03:37.192  5723  5770 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 17:03:37.192  5723  5770 I jxcore-log: emit@events.js:82:1
11-30 17:03:37.192  5723  5770 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 17:03:37.192  5723  5770 I jxcore-log: emit@events.js:82:1''
11-30 17:03:37.192  5723  5770 I jxcore-log: 
,11-30 17:03:37.194  5723  5770 I jxcore-log: 2016-11-30 22:03:37 - DEBUG CoordinatedClient: 'test client failed'
11-30 17:03:37.194  5723  5770 I jxcore-log: 
,11-30 17:03:37.210  5723  5770 I jxcore-log: 2016-11-30 22:03:37 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 17:03:37.210  5723  5770 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 17:03:37.210  5723  5770 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 17:03:37.210  5723  5770 I jxcore-log: emit@events.js:82:1
11-30 17:03:37.210  5723  5770 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 17:03:37.210  5723  5770 I jxcore-log: emit@events.js:82:1''
11-30 17:03:37.210  5723  5770 I jxcore-log: 
,11-30 17:03:37.210  5723  5770 I jxcore-log: 2016-11-30 22:03:37 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-30 17:03:37.210  5723  5770 I jxcore-log: 
,11-30 17:03:37.213  5723  5770 I jxcore-log: 2016-11-30 22:03:37 - ERROR runTests: 'websocket error
11-30 17:03:37.213  5723  5770 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 17:03:37.213  5723  5770 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 17:03:37.213  5723  5770 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 17:03:37.213  5723  5770 I jxcore-log: emit@events.js:82:1
11-30 17:03:37.213  5723  5770 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 17:03:37.213  5723  5770 I jxcore-log: emit@events.js:82:1'
11-30 17:03:37.213  5723  5770 I jxcore-log: 
,11-30 17:03:37.808  5970  5970 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-30 17:03:37.815  5970  5970 D AndroidRuntime: CheckJNI is OFF
,11-30 17:03:37.844  5970  5970 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-30 17:03:37.880  5970  5970 I Radio-JNI: register_android_hardware_Radio DONE
,11-30 17:03:37.897  5970  5970 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-30 17:03:37.907   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-30 17:03:37.908   926   939 I ActivityManager: Killing 5723:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-30 17:03:38.010   926  3921 I WindowState: WIN DEATH: Window{c8aadf9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-30 17:03:38.010   926  3948 D GraphicsStats: Buffer count: 2
11-30 17:03:38.011   926  3054 D WifiService: Client connection lost with reason: 4
,11-30 17:03:38.043   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-30 17:03:38.043   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-30 17:03:38.045   926   951 I art     : Starting a blocking GC Explicit
,11-30 17:03:38.045   926   939 E ActivityManager: Failure starting process com.test.thalitest
11-30 17:03:38.045   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-30 17:03:38.045   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:38.045   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.045   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 17:03:38.045   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-30 17:03:38.046   926   939 I ActivityManager:   Force finishing activity ActivityRecord{d534e1d u0 com.test.thalitest/.MainActivity t10}
,11-30 17:03:38.054   926  3250 W ActivityManager: Spurious death for ProcessRecord{36caf2c 0:com.test.thalitest/u0a77}, curProc for 5723: null
,11-30 17:03:38.058   926   944 W WindowManager: Attempted to add application window with unknown token Token{5b34892 ActivityRecord{d534e1d u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-30 17:03:38.058   926   944 W WindowManager: Token{5b34892 ActivityRecord{d534e1d u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{5b34892 ActivityRecord{d534e1d u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-30 17:03:38.058   926   944 W WindowManager: view not successfully added to wm, removing view
11-30 17:03:38.059   926   944 W WindowManager: Exception when adding starting window
11-30 17:03:38.059   926   944 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{4b412d7 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-30 17:03:38.059   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-30 17:03:38.059   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-30 17:03:38.059   926   944 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-30 17:03:38.059   926   944 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-30 17:03:38.059   926   944 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-30 17:03:38.059   926   944 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:38.059   926   944 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.059   926   944 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 17:03:38.059   926   944 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-30 17:03:38.128   926   951 I art     : Explicit concurrent mark sweep GC freed 66992(4MB) AllocSpace objects, 17(728KB) LOS objects, 33% free, 28MB/43MB, paused 1.445ms total 82.601ms
,11-30 17:03:38.148   926   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-30 17:03:38.151  5970  5970 I art     : System.exit called, status: 0
,11-30 17:03:38.151  5970  5970 I AndroidRuntime: VM exiting with result code 0.
,11-30 17:03:38.160   926   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
11-30 17:03:38.164   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-30 17:03:38.169  5829  5829 D BluetoothMapAppObserver: onReceive
11-30 17:03:38.169  5829  5829 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-30 17:03:38.173  3757  3757 I Keyboard.Facilitator: resetDictionaries() : en_US
11-30 17:03:38.175  4179  4276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-30 17:03:38.179   926  3039 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-30 17:03:38.222  3862  3862 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-30 17:03:38.224  3502  5982 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-30 17:03:38.225  3757  5981 I Keyboard.Facilitator.DecoderInitializer: run()
,11-30 17:03:38.242  3757  5981 I Decoder : createOrResetDecoder
,11-30 17:03:38.243  3677  3677 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-30 17:03:38.243  3677  3677 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-30 17:03:38.262  3937  5987 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-30 17:03:38.262  3937  5987 D AccountUtils: Clearing selected account for com.test.thalitest
11-30 17:03:38.264   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-30 17:03:38.260    29    29 W kworker/3:1: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 17:03:38.263    29    29 W kworker/3:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 17:03:38.270    29    29 W kworker/3:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 17:03:38.287   926   938 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-30 17:03:38.288  3897  4023 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-30 17:03:38.288   926   938 E PackageManager: Failed to write settings, restoring backup
11-30 17:03:38.288   926   938 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-30 17:03:38.288   926   938 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-30 17:03:38.288   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-30 17:03:38.288   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-30 17:03:38.288   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-30 17:03:38.288   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:38.288   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.288   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 17:03:38.293   926   939 E DropBoxManagerService: Can't write: system_server_wtf
11-30 17:03:38.293   926   939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-30 17:03:38.293   926   939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 17:03:38.293   926   939 E DropBoxManagerService: 	... 13 more
11-30 17:03:38.295  3502  3527 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj6DADE395B) - 
--------- beginning of crash
11-30 17:03:38.296  3502  3527 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-30 17:03:38.296  3502  3527 E AndroidRuntime: Process: android.process.acore, PID: 3502
11-30 17:03:38.296  3502  3527 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-30 17:03:38.296  3502  3527 E AndroidRun,time: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.296  3502  3527 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 17:03:38.302  3502  5982 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-30 17:03:38.302   926   936 I ActivityManager: Start proc 5990:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-30 17:03:38.303  3897  4023 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-30 17:03:38.303  3897  4023 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3897
11-30 17:03:38.303  3897  4023 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.303  3897  4023 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 17:03:38.305  3677  3677 I ConfigService: onCreate
,11-30 17:03:38.308  3502  5982 I Process : Sending signal. PID: 3502 SIG: 9
,11-30 17:03:38.309   926  6002 E DropBoxManagerService: Can't write: system_app_crash
11-30 17:03:38.309   926  6002 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 17:03:38.309   926  6002 E DropBoxManagerService: 	... 5 more
11-30 17:03:38.309   926  6001 E DropBoxManagerService: Can't write: system_app_crash
11-30 17:03:38.309   926  6001 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 17:03:38.309   926  6001 E DropBoxManagerService: 	... 5 more
,11-30 17:03:38.311  3677  5997 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-30 17:03:38.311  3677  5997 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-30 17:03:38.312  3677  5997 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-30 17:03:38.312   926   937 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-30 17:03:38.313  3677  5997 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-30 17:03:38.315  3897  4023 I Process : Sending signal. PID: 3897 SIG: 9
,11-30 17:03:38.336  3937  5987 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-30 17:03:38.337  3757  5981 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-30 17:03:38.365  3937  5987 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.365  3937  5987 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-30 17:03:38.375  3937  5987 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 17:03:38.376  3937  5987 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-30 17:03:38.447   926  3038 W InputDispatcher: channel '8ccbb4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-30 17:03:38.448   926   937 I WindowState: WIN DEATH: Window{8ccbb4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-30 17:03:38.448   926  3308 D GraphicsStats: Buffer count: 1
11-30 17:03:38.448   926  3038 E InputDispatcher: channel '8ccbb4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
11-30 17:03:38.448   926   937 W InputDispatcher: Attempted to unregister already unregistered input channel '8ccbb4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-30 17:03:38.453   926  3691 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3897) has died
,11-30 17:03:38.454   926  3691 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-30 17:03:38.473  3937  6009 I GMPM-SVC: App measurement is starting up
,11-30 17:03:38.478  3937  6009 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-30 17:03:38.479  3937  6009 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-30 17:03:38.494   926  3948 I ActivityManager: Process android.process.acore (pid 3502) has died
11-30 17:03:38.494   926  3948 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-30 17:03:38.652   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
