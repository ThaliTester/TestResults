#### Test 899757340363162_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-25 07:44:50.171   929   939 I ActivityManager: Killing 5317:org.codeaurora.ims/1001 (adj 15): empty #17
,--------- beginning of main
11-25 07:44:50.394  5619  5669 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-25 07:44:50.426  3722  3722 I ConfigFetchService: fetch service done; releasing wakelock
11-25 07:44:50.429  3722  5015 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-25 07:44:50.430  3722  3722 I ConfigFetchService: stopping self
11-25 07:44:50.504  3722  5015 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-25 07:44:50.533  5672  5672 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 07:44:50.535  5619  5669 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-25 07:44:50.536  5672  5672 D AndroidRuntime: CheckJNI is OFF
11-25 07:44:50.559  5672  5672 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 07:44:50.564  5619  5669 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-25 07:44:50.597  5672  5672 I Radio-JNI: register_android_hardware_Radio DONE
11-25 07:44:50.612  5672  5672 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-25 07:44:50.616   929  3237 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 07:44:50.655   929  3237 I ActivityManager: Start proc 5687:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 07:44:50.670  5672  5672 D AndroidRuntime: Shutting down VM
,11-25 07:44:50.984   929  3292 I WindowManager: Screenshot max retries 4 of Token{2b8ba7b ActivityRecord{f6b220a u0 com.test.thalitest/.MainActivity t10}} appWin=Window{535e862 u0 Starting com.test.thalitest} drawState=2
,11-25 07:44:51.061  5687  5687 I CordovaLog: Changing log level to DEBUG(3)
11-25 07:44:51.061  5687  5687 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 07:44:51.062  5687  5687 D CordovaActivity: CordovaActivity.onCreate()
,11-25 07:44:51.068  5687  5687 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-25 07:44:51.096  5687  5687 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-25 07:44:51.156  5687  5687 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 600-656)
,11-25 07:44:51.156  5687  5687 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 07:44:51.184  5687  5687 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d66de5c}
,11-25 07:44:51.185  5687  5687 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 07:44:51.185  5687  5687 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-25 07:44:51.191  5687  5687 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-25 07:44:51.192  5687  5687 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 07:44:51.253  5687  5687 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 07:44:51.283  5687  5687 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-25 07:44:51.284  5687  5687 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 07:44:51.284  5687  5687 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 07:44:51.284  5687  5687 I Adreno  : Build Date                       : 12/06/15
11-25 07:44:51.284  5687  5687 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 07:44:51.284  5687  5687 I Adreno  : Local Branch                     : mybranch17112971
11-25 07:44:51.284  5687  5687 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 07:44:51.284  5687  5687 I Adreno  : Remote Branch                    : NONE
11-25 07:44:51.284  5687  5687 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 07:44:51.362   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@969386b:true
,11-25 07:44:51.401   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27615]" dev="sockfs" ino=27615 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 07:44:51.401   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[27615]" dev="sockfs" ino=27615 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 07:44:51.421  5687  5687 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 07:44:51.437  5687  5687 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 07:44:51.445  5687  5687 D PluginManager: init()
,11-25 07:44:51.449  5687  5687 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 07:44:51.476  5687  5687 D CordovaActivity: Started the activity.
,11-25 07:44:51.476  5687  5687 D CordovaActivity: Resumed the activity.
,11-25 07:44:51.481  5687  5725 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-25 07:44:51.477   403   403 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34064]" dev="sockfs" ino=34064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 07:44:51.477   403   403 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34064]" dev="sockfs" ino=34064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 07:44:51.481  3906  3906 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14250]" dev="sockfs" ino=14250 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 07:44:51.481  3906  3906 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14250]" dev="sockfs" ino=14250 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 07:44:51.487  5687  5687 D CordovaActivity: Paused the activity.
,11-25 07:44:51.488   929   942 W ActivityManager: Activity pause timeout for ActivityRecord{f6b220a u0 com.test.thalitest/.MainActivity t10}
,11-25 07:44:51.493  5687  5712 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 07:44:51.525  5687  5725 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 07:44:51.539  5687  5687 D CordovaActivity: Stopped the activity.
,11-25 07:44:51.612   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +623ms (total +973ms)
,11-25 07:44:51.625  5687  5687 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 07:44:51.641  5687  5687 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5687
,11-25 07:44:51.755  5687  5687 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 07:44:51.903  5687  5728 D jxcore_app_log: JniHelper::setJavaVM(0xf54bc000), pthread_self() = -585361104
,11-25 07:44:51.907  5687  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 07:44:51.907  5687  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 07:44:51.907  5687  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 07:44:51.907  5687  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 07:44:51.907  5687  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-25 07:44:51.907  5687  5728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7ccd52 added. We now have 1 listener(s)
,11-25 07:44:51.910  5687  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-25 07:44:51.911  5687  5728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:44:51.911  5687  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 07:44:51.911  5687  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-25 07:44:51.913  5687  5728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3138ad9 added. We now have 1 listener(s)
11-25 07:44:51.913  5687  5728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:44:51.918   929  3056 D WifiService: New client listening to asynchronous messages
,11-25 07:44:51.919  5687  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:44:51.919  5687  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 07:44:51.919  5687  5728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-25 07:44:51.919  5687  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-25 07:44:51.919  5687  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 07:44:51.919  5687  5728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-25 07:44:51.920  5687  5728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-25 07:44:51.921  5687  5728 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 07:44:52.016  5687  5687 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 07:44:52.018  5687  5687 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-25 07:44:52.019  5687  5687 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 07:44:52.567   929  3055 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 07:44:52.735  5687  5734 W jxcore-log: Initializing JXcore engine
,11-25 07:44:52.735  5687  5734 W jxcore-log: JXcore engine is ready
11-25 07:44:52.757  5734  5734 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12456 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-25 07:44:52.757  5734  5734 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14442]" dev="sockfs" ino=14442 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-25 07:44:52.757  5734  5734 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-25 07:44:52.757  5734  5734 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34031]" dev="sockfs" ino=34031 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-25 07:44:52.769  5687  5734 W jxcore-log: Starting JXcore engine
,11-25 07:44:52.819  5687  5734 W jxcore-log: Platform android
11-25 07:44:52.819  5687  5734 W jxcore-log: 
,11-25 07:44:52.819  5687  5734 W jxcore-log: Process ARCH arm
11-25 07:44:52.819  5687  5734 W jxcore-log: 
,11-25 07:44:53.002  5687  5734 I jxcore-log: JXcore Cordova bridge is ready!
11-25 07:44:53.002  5687  5734 I jxcore-log: 
,11-25 07:44:53.002  5687  5734 W jxcore-log: JXcore engine is started
,11-25 07:44:53.016  5687  5728 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-25 07:44:53.023  5687  5687 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-25 07:44:53.023  5687  5687 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 07:44:53.944   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:44:54.945   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:44:55.439  3638  3638 I ConfigService: onDestroy
,11-25 07:44:55.946   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:44:56.947   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:44:57.948   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:44:58.949   601   601 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 07:44:59.863   929   929 I ActivityManager: Killing 5330:com.android.settings/1000 (adj 15): empty #17
,11-25 07:45:02.768  5687  5734 I jxcore-log: 2016-11-25 12:45:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 07:45:02.768  5687  5734 I jxcore-log: 
,11-25 07:45:02.769  5687  5734 I jxcore-log: 2016-11-25 12:45:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 07:45:02.769  5687  5734 I jxcore-log: 
,11-25 07:45:02.774  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:45:02.775  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 07:45:02.776  5687  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:45:02.779  5687  5734 I jxcore-log: 2016-11-25 12:45:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 07:45:02.779  5687  5734 I jxcore-log: 
11-25 07:45:02.780  5687  5734 I jxcore-log: 2016-11-25 12:45:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 07:45:02.780  5687  5734 I jxcore-log: 
,11-25 07:45:03.033  5687  5734 I jxcore-log: 2016-11-25 12:45:03 - DEBUG UnitTest_app: 'Running unit tests'
11-25 07:45:03.033  5687  5734 I jxcore-log: 
,11-25 07:45:03.033  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:45:03.034  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a11385 added. We now have 2 listener(s)
11-25 07:45:03.034  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:45:03.034  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:45:03.034  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 07:45:03.035  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:45:03.035  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36605da added. We now have 2 listener(s)
11-25 07:45:03.035  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:45:03.035  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:45:03.036  5687  5734 D executeNativeTests: Running unit tests
,11-25 07:45:03.081  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 07:45:03.081  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb added. We now have 3 listener(s)
,11-25 07:45:03.082  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:45:03.082  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 07:45:03.082  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 07:45:03.082  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:45:03.082  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 added. We now have 3 listener(s)
11-25 07:45:03.082  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:45:03.083  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:45:03.085  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 07:45:03.085  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:45:03.085  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 07:45:03.085  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:45:03.086  5687  5734 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-25 07:45:03.086  5687  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 07:45:03.086  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 07:45:03.086  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:45:03.086  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:45:03.086  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:45:03.087  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:03.087  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:03.087  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:03.087  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:03.088  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:03.088  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:45:03.088  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb removed from the list
11-25 07:45:03.088  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:03.088  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 removed from the list
,11-25 07:45:03.088  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:03.088  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.088  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.089  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.089  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.089  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:03.089  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:03.089  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:03.089  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:03.089  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:03.090  5687  5734 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-25 07:45:03.091  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:03.091  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:03.091  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:03.091  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:03.091  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:03.091  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:03.091  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:03.091  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:03.091  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:03.091  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.091  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.092  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.092  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.092  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.092  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:03.092  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:03.092  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:03.092  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 07:45:03.095  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-25 07:45:03.096  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 07:45:03.096  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 07:45:03.096  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 07:45:03.096  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 07:45:03.096  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 07:45:03.096  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 07:45:03.096  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:03.096  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:03.096  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 07:45:03.096  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:03.096  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:03.096  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:03.096  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:03.096  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:03.096  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:03.096  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.096  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.097  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.097  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.097  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.097  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:03.097  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:03.097  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:03.097  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:03.098  5687  5734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 07:45:03.099  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:03.099  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:45:03.111  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:45:03.116  5687  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:45:03.116  5687  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 07:45:03.116  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:45:03.116  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:45:03.117  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:45:03.117  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:03.117  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 07:45:03.119  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 07:45:03.119  5687  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:45:03.119  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 07:45:03.120  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:03.122  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.123  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 07:45:03.123  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:03.124  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:45:03.125  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:45:03.125  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:45:03.126  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-25 07:45:03.127  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 07:45:03.127  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.127  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:45:03.127  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:45:03.127  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:45:03.127  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:45:03.127  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:03.128  5687  5734 D BluetoothAdapter: STATE_ON
,11-25 07:45:03.130  4668  4684 D BtGatt.GattService: registerClient() - UUID=1d67fe3b-a26e-44c8-90d8-348df0efbbd1
,11-25 07:45:03.131  4668  4755 D BtGatt.GattService: onClientRegistered() - UUID=1d67fe3b-a26e-44c8-90d8-348df0efbbd1, clientIf=5
,11-25 07:45:03.133  5687  5697 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 07:45:03.134  4668  4924 D BtGatt.GattService: start scan with filters
11-25 07:45:03.139  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:45:03.139  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.139  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-25 07:45:03.139  4668  4760 D BtGatt.ScanManager: handling starting scan
11-25 07:45:03.139  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.139  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 07:45:03.139  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-25 07:45:03.139  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:45:03.140  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:45:03.140  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.140  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:45:03.140  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.140  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.141  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:03.141  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:45:03.141  5687  5734 I io.jxcore.node.ConnectionHelper: start: OK
,11-25 07:45:03.141  4668  4760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:45:03.142  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:45:03.142  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:45:03.143  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:45:03.143  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:45:03.143  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 07:45:03.148  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 07:45:03.148  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:45:03.148  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:03.148  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:03.148  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:45:03.150  4668  4755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:45:03.150  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:03.150  4668  4760 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 07:45:03.157  4668  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-25 07:45:03.157  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:03.158  4668  4760 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:45:03.158  4668  4760 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 07:45:03.169  4668  4755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 07:45:03.169  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:03.175  4668  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 07:45:03.175  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:03.623   929  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 07:45:03.650  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 07:45:03.650  5687  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:45:03.650  5687  5687 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 07:45:06.642   929  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 07:45:08.145  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:45:08.145  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:08.146  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 07:45:08.146  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 07:45:08.146  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 07:45:08.146  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:08.146  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 07:45:08.146  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:45:08.146  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.146  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:45:08.146  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:45:08.147  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.148  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.148  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.148  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:45:08.148  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.149  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:45:08.149  4668  4684 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:45:08.150  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:45:08.151  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:45:08.151  4668  4904 D BtGatt.GattService: stopScan() - queue size =1
11-25 07:45:08.152  4668  4760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:45:08.152  4668  4685 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:45:08.152  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:45:08.153  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.153  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:45:08.153  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.153  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.153  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.153  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.154  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:45:08.154  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.154  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.154  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:08.154  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:45:08.155  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:45:08.156  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:45:08.156  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.157  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.158  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:08.158  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.158  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:08.158  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:08.158  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:45:08.158  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:45:08.158  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:08.158  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:45:08.158  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:08.158  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:08.159  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:08.159  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:45:08.159  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:08.159  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:45:08.159  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:45:08.159  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.159  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-25 07:45:08.159  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:45:08.160  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.160  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.160  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.160  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:08.161  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.161  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.164  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.164  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:08.164  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 07:45:08.173  4668  4668 D BtGatt.ScanManager: awakened up at time 97673
,11-25 07:45:08.224  4668  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-25 07:45:08.225  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:08.225  4668  4755 D BtGatt.GattService: current time is 97724865049
,11-25 07:45:08.225  4668  4755 D BtGatt.GattService: Batch record : [-75, 112, 8, 38, 113, -28, 1, 0, -96, 99, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, 48, 77, 97, 3, 3, -25, 26, 62, 7, -23, 117, 28, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -68, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -66, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -69, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -68, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -73, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -75, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 07:45:08.227  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, 48, 77, 97, 3, 3, -25, 26, 62, 7, -23, 117, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-25 07:45:08.228  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-25 07:45:08.228  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 07:45:08.228  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-25 07:45:08.229  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-25 07:45:08.229  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 07:45:08.229  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-25 07:45:08.235  4668  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:45:08.235  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:08.235  4668  4760 D BtGatt.ScanManager: stopping BLe Batch
,11-25 07:45:08.241  4668  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 07:45:08.241  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:08.241  4668  4760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:45:08.248  4668  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 07:45:08.248  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:08.288  4912  4946 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-25 07:45:08.289  4912  4912 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-25 07:45:08.661  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:45:13.206  5687  5734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 07:45:13.212  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:13.213  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:45:13.228  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 07:45:13.232  5687  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:45:13.233  5687  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 07:45:13.233  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:45:13.233  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:45:13.233  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:45:13.233  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:13.233  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 07:45:13.239  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:13.241  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 07:45:13.241  5687  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:45:13.241  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:45:13.245  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:13.250  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.250  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:45:13.251  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:45:13.252  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:45:13.252  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:45:13.258  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.258  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:45:13.258  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-25 07:45:13.258  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:45:13.258  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-25 07:45:13.259  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.260  5687  5734 D BluetoothAdapter: STATE_ON
,11-25 07:45:13.264  4668  4904 D BtGatt.GattService: registerClient() - UUID=9d089fe4-9579-4d85-9956-a43f24601c35
,11-25 07:45:13.265  4668  4755 D BtGatt.GattService: onClientRegistered() - UUID=9d089fe4-9579-4d85-9956-a43f24601c35, clientIf=5
,11-25 07:45:13.265  5687  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 07:45:13.266  4668  4685 D BtGatt.GattService: start scan with filters
,11-25 07:45:13.271  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:45:13.271  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.271  4668  4760 D BtGatt.ScanManager: handling starting scan
11-25 07:45:13.271  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:45:13.271  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.271  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 07:45:13.272  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-25 07:45:13.272  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.272  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:45:13.272  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 07:45:13.272  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.272  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.272  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.273  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.274  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:45:13.274  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.279  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.279  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:45:13.279  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.279  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.279  5687  5734 I io.jxcore.node.ConnectionHelper: start: OK
11-25 07:45:13.280  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.281  4668  4755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:45:13.281  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:13.281  4668  4760 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 07:45:13.285  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 07:45:13.286  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.286  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 07:45:13.286  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:45:13.286  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:13.287  5687  5734 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 07:45:13.287  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:13.287  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 07:45:13.287  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 07:45:13.287  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 07:45:13.287  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:13.287  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 07:45:13.287  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:45:13.287  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.288  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:45:13.288  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:45:13.288  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.288  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.288  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.288  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-25 07:45:13.288  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.289  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:45:13.289  4668  4684 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:45:13.290  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:45:13.291  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:45:13.291  4668  4685 D BtGatt.GattService: stopScan() - queue size =1
,11-25 07:45:13.291  4668  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:45:13.291  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:13.292  4668  4760 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:45:13.292  4668  4760 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 07:45:13.292  4668  4684 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 07:45:13.292  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.293  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.294  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.294  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:45:13.294  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:45:13.295  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 07:45:13.295  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.297  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.297  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:13.297  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.297  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.298  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:13.298  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:45:13.298  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:45:13.298  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:45:13.298  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:45:13.298  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:45:13.298  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:45:13.298  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:13.298  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:13.298  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.298  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:13.298  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-25 07:45:13.298  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:13.298  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:45:13.298  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:45:13.298  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.298  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.298  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.299  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:13.299  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.299  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.301  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.301  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.301  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.301  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.301  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.302  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.303  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.303  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.303  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:13.303  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:13.303  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:13.303  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:13.304  5687  5734 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 07:45:13.306  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:13.306  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 07:45:13.310  4668  4755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:45:13.310  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:45:13.315  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 07:45:13.315  4668  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 07:45:13.315  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:13.316  5687  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:45:13.317  4668  4760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:45:13.317  5687  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 07:45:13.317  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:45:13.317  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:45:13.317  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:45:13.317  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:13.317  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 07:45:13.321  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 07:45:13.321  5687  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:45:13.321  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:45:13.323  4668  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:45:13.324  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:13.324  4668  4755 E BtGatt.ContextMap: Context not found for ID 5
11-25 07:45:13.324  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:45:13.325  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.325  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 07:45:13.325  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:45:13.325  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:45:13.325  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 07:45:13.329  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:45:13.329  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.329  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:45:13.329  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:45:13.329  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:45:13.329  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-25 07:45:13.329  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.330  5687  5734 D BluetoothAdapter: STATE_ON
,11-25 07:45:13.331  4668  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:45:13.331  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:13.331  4668  4760 D BtGatt.ScanManager: stopping BLe Batch
11-25 07:45:13.333  4668  4684 D BtGatt.GattService: registerClient() - UUID=aadde654-6ce1-4de2-9fba-c11b6f99af9f
11-25 07:45:13.334  4668  4755 D BtGatt.GattService: onClientRegistered() - UUID=aadde654-6ce1-4de2-9fba-c11b6f99af9f, clientIf=5
11-25 07:45:13.334  5687  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 07:45:13.334  4668  4924 D BtGatt.GattService: start scan with filters
,11-25 07:45:13.335  4668  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 07:45:13.335  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:13.335  4668  4760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:45:13.336  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:45:13.336  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.336  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:45:13.336  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:13.337  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 07:45:13.337  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:45:13.337  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.337  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:45:13.337  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:45:13.337  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.337  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.337  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.337  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 07:45:13.338  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:45:13.338  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.340  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.340  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:45:13.340  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.340  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:13.340  4668  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:45:13.340  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:13.340  5687  5734 I io.jxcore.node.ConnectionHelper: start: OK
11-25 07:45:13.340  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.341  4668  4760 D BtGatt.ScanManager: handling starting scan
,11-25 07:45:13.344  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 07:45:13.344  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.344  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:13.344  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:45:13.347  4668  4755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 07:45:13.347  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:13.347  4668  4760 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 07:45:13.351  4668  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-25 07:45:13.351  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:13.351  4668  4760 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:45:13.351  4668  4760 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 07:45:13.359  4668  4755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 07:45:13.359  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:13.363  4668  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 07:45:13.363  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:13.845  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 07:45:13.846  5687  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:45:13.846  5687  5687 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 07:45:18.340  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:45:18.341  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:45:18.341  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-25 07:45:18.341  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 07:45:18.341  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 07:45:18.341  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:45:18.342  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 07:45:18.342  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-25 07:45:18.342  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:18.342  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 07:45:18.342  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:45:18.343  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:18.343  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.343  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.343  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-25 07:45:18.343  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.345  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:45:18.346  4668  4685 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 07:45:18.346  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:45:18.348  4668  4760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:45:18.348  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:45:18.351  4668  4904 D BtGatt.GattService: stopScan() - queue size =1
11-25 07:45:18.352  4668  4924 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:45:18.353  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:45:18.354  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.354  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:45:18.354  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.354  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.354  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.355  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.355  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:45:18.355  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.355  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.355  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.355  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:45:18.356  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:45:18.357  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:45:18.357  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.359  4668  4668 D BtGatt.ScanManager: awakened up at time 107858
11-25 07:45:18.362   929  3921 I ActivityManager: Killing 5119:com.google.android.apps.maps/u0a58 (adj 15): empty #17
11-25 07:45:18.362  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.362  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:18.362  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.362  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:18.362  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:45:18.363  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 07:45:18.363  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:45:18.363  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:45:18.363  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:45:18.363  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:45:18.363  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:45:18.363  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:45:18.363  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:45:18.363  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:18.364  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 07:45:18.364  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:45:18.365  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:45:18.365  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:45:18.365  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 07:45:18.400  4668  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-25 07:45:18.400  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:18.401  4668  4755 D BtGatt.GattService: current time is 107900596559
,11-25 07:45:18.401  4668  4755 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -68, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -68, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -68, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -72, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -66, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -65, 29, 59, -65, 67, 82, 1, -128, -91, 64, 0, 27, 2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -67, 0, 70, 51, -95, -13, 27, -78, 18, -61, 124, -27, 55, 16, 2, 7, 0, 0]
,11-25 07:45:18.401  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 07:45:18.401  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 07:45:18.401  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 07:45:18.402  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 07:45:18.402  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 07:45:18.402  4668  4755 D BtGatt.GattService: ScanRecord : [2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -67, 0, 70, 51, -95, -13, 27, -78, 18, -61, 124, -27, 55, 16, 2, 7, 0]
11-25 07:45:18.402  4668  4755 E BtGatt.ContextMap: Context not found for ID 5
,11-25 07:45:18.409  4668  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:45:18.409  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:18.409  4668  4760 D BtGatt.ScanManager: stopping BLe Batch
,11-25 07:45:18.414  4668  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 07:45:18.414  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:45:18.414  4668  4760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:45:18.419  4668  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 07:45:18.419  4668  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:45:18.864  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:45:18.864  5687  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:18.865  5687  5687 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 07:45:20.419   929  5449 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109918, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 07:45:23.364  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:45:23.364  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:45:23.364  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.365  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:45:23.365  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:45:23.365  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:45:23.365  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.366  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
,11-25 07:45:23.366  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.366  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.366  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.366  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 07:45:23.370  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.370  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.374  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.374  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.374  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.374  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:23.374  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.375  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.375  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.376  5687  5734 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-25 07:45:23.378  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.378  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:23.378  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.378  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.379  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.379  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.379  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.379  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.379  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.379  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.380  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.382  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.383  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.383  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.383  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:45:23.383  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.383  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.383  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.384  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 07:45:23.384  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.384  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:23.384  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 07:45:23.385  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.385  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.385  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.385  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.385  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.385  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.385  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.385  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.386  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.386  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.386  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.387  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:23.387  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.387  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.387  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.388  5687  5734 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-25 07:45:23.388  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:45:23.388  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:23.388  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.388  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.388  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.388  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.388  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.388  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.388  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.388  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.389  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.390  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.390  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.390  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.390  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:23.390  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 07:45:23.390  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.390  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.391  5687  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-25 07:45:23.391  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.391  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:23.392  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.392  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.392  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.392  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.392  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.392  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.392  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.392  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.392  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.394  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.394  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.394  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.394  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:23.394  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.394  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.394  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.395  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 07:45:23.395  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:45:23.395  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:45:23.395  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 07:45:23.395  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:45:23.395  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:45:23.396  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 07:45:23.396  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 07:45:23.396  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:45:23.396  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.396  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:23.396  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.396  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.396  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.396  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.396  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.396  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.396  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.396  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.397  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.398  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.398  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.399  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.399  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:23.399  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.399  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:23.399  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.400  5687  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:45:23.400  5687  5734 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 07:45:23.400  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-25 07:45:23.403  5687  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:45:23.403  5687  5734 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 07:45:23.404  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 07:45:23.405  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 07:45:23.405  5687  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 07:45:23.407  5687  5734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 07:45:23.407  5687  5734 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 07:45:23.407  5687  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:45:23.407  5687  5734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 07:45:23.407  5687  5734 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-25 07:45:23.407  5687  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:45:23.407  5687  5734 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 07:45:23.407  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-25 07:45:23.411  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-25 07:45:23.412  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 07:45:23.412  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-25 07:45:23.413  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-25 07:45:23.413  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-25 07:45:23.413  5687  5734 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 07:45:23.413  5687  5734 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-25 07:45:23.414  5687  5734 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 07:45:23.414  5687  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
,11-25 07:45:23.414  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.414  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:45:23.414  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.415  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.415  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.414  5687  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-25 07:45:23.415  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-25 07:45:23.415  5687  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-25 07:45:23.415  5687  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-25 07:45:23.416  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.416  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:23.416  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.416  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.416  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.416  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.416  5687  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-25 07:45:23.416  5687  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 07:45:23.414  4685  4685 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31957]" dev="sockfs" ino=31957 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 07:45:23.414  4685  4685 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31957]" dev="sockfs" ino=31957 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 07:45:23.417  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.417  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.417  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.417  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:45:23.417  5687  5735 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-25 07:45:23.417  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.417  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.417  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.418  5687  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:45:23.418  5687  5734 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 07:45:23.419  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.419  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:23.419  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.419  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.419  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.419  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
,11-25 07:45:23.419  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.420  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.420  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.420  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.420  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.426  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.426  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.426  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.426  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:45:23.426  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.426  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.426  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:23.427  5687  5734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-25 07:45:23.427  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.427  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:45:23.427  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.427  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.427  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.427  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.427  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.428  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:23.428  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.428  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.428  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.429  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.429  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.429  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.429  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:45:23.429  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.429  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.430  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:23.430  5687  5734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 07:45:23.430  5687  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 07:45:23.431  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-25 07:45:23.431  5687  5734 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-25 07:45:23.431  5687  5734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 07:45:23.431  5687  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 07:45:23.431  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 07:45:23.431  5687  5734 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-25 07:45:23.431  5687  5734 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-25 07:45:23.431  5687  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 07:45:23.431  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 07:45:23.431  5687  5734 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-25 07:45:23.431  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:23.431  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:23.431  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:23.431  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:45:23.431  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.432  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.432  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.432  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.432  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:23.432  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.432  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.433  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.433  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:23.433  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:23.433  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:23.433  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:23.433  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.433  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:23.434  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:23.434  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:23.434  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:23.434  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:23.434  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:23.434  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:23.949   601   601 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 07:45:23.950   601   601 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 07:45:28.435  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:28.435  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.435  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:45:28.436  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:28.436  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:28.436  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:45:28.436  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:28.436  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 07:45:28.437  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:28.437  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:45:28.437  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:28.437  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:28.437  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.437  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:28.438  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.438  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.441  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.442  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.442  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.442  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:45:28.442  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:28.442  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:28.442  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:28.447  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-25 07:45:28.448  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:28.448  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:45:28.454  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-25 07:45:28.456  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-25 07:45:28.456  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-25 07:45:28.456  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-25 07:45:28.456  5687  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-25 07:45:28.456  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-25 07:45:28.456  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 07:45:28.456  5687  5687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-25 07:45:28.457  5687  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:45:28.457  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:28.457  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-25 07:45:28.457  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 07:45:28.457  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-25 07:45:28.458  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:45:28.458  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 07:45:28.458  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-25 07:45:28.458  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:28.458  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:28.458  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:45:28.458  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.458  5687  5687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 07:45:28.459  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:45:28.454  4924  4924 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31959]" dev="sockfs" ino=31959 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 07:45:28.454  4924  4924 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31959]" dev="sockfs" ino=31959 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 07:45:28.459  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:45:28.459  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.460  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.460  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:28.460  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.460  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.460  5687  5737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 07:45:28.461  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:28.461  5687  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-25 07:45:28.461  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:45:28.461  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:28.461  5687  5737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-25 07:45:28.461  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:28.461  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:45:28.461  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:28.461  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:45:28.461  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:28.461  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-25 07:45:28.461  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:28.461  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.461  5687  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-25 07:45:28.461  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.461  5687  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:28.461  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:28.461  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.461  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.463  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.463  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.463  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.463  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:28.463  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 07:45:28.463  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.463  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.465  5687  5734 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-25 07:45:28.465  5687  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 07:45:28.465  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 07:45:28.465  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:45:28.465  5687  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:45:28.465  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:28.465  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:28.465  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:28.466  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:28.466  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:45:28.466  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:28.466  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.466  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.466  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:28.466  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.466  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.467  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.468  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.468  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.468  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:28.468  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:28.468  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.468  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:28.474  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:45:28.474  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:45:28.474  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:28.475  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:28.475  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:28.475  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:28.475  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.475  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.475  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:28.475  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.475  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.476  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.476  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.476  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.476  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:28.476  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:28.476  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.476  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.477  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:45:28.477  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:45:28.477  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:45:28.477  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:45:28.477  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:45:28.478  5687  5734 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c649bfb not in the list
11-25 07:45:28.478  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.478  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
11-25 07:45:28.478  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:28.478  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.478  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:45:28.479  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.479  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.479  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:45:28.479  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:45:28.479  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:45:28.479  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:45:28.479  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7f1418 not in the list
,11-25 07:45:28.480  5687  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-25 07:45:28.480  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 07:45:28.480  5687  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-25 07:45:28.481  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 07:45:28.481  5687  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-25 07:45:28.481  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 07:45:28.482  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 07:45:28.483  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-25 07:45:28.483  5687  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-25 07:45:28.483  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 07:45:28.483  5687  5734 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 07:45:28.483  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 07:45:28.483  5687  5734 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-25 07:45:28.483  5687  5734 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-25 07:45:28.484  5687  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-25 07:45:28.484  5687  5734 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-25 07:45:28.484  5687  5734 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-25 07:45:28.484  5687  5734 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-25 07:45:28.484  5687  5734 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-25 07:45:28.484  5687  5734 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-25 07:45:28.485  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:45:28.485  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92b75e1 added. We now have 3 listener(s)
11-25 07:45:28.485  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:45:28.486  5687  5734 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 07:45:28.487   929  3928 D WifiService: setWifiEnabled: true pid=5687, uid=10077
,11-25 07:45:28.487   929  3928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:45:28.547  4668  4889 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-25 07:45:28.547  4668  4902 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-25 07:45:28.547  5687  5735 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-25 07:45:28.547  5687  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 07:45:28.547  5687  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-25 07:45:28.951   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:28.961  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:45:29.951   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:30.952   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:31.953   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:32.575   929  3055 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 07:45:32.954   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:33.492  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:45:33.492  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@271ef06 added. We now have 4 listener(s)
11-25 07:45:33.493  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:45:33.506  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:33.506  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@271ef06 removed from the list
11-25 07:45:33.507  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:33.509  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:45:33.509  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fac9c7 added. We now have 4 listener(s)
,11-25 07:45:33.509  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:45:33.513  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:33.513  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fac9c7 removed from the list
11-25 07:45:33.513  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:33.515  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:45:33.515  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2cbbf4 added. We now have 4 listener(s)
11-25 07:45:33.515  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:45:33.522   929  3653 D WifiService: setWifiEnabled: false pid=5687, uid=10077
,11-25 07:45:33.522   929  3653 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:45:33.530   929  3055 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 07:45:33.530   929  3055 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-25 07:45:33.530   929  3055 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 07:45:33.531   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 07:45:33.536  4668  4751 D BluetoothAdapterState: Current state: ON, message: 23
11-25 07:45:33.536  4668  4751 D BluetoothAdapterProperties: Setting state to 13
11-25 07:45:33.536  4668  4751 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 07:45:33.537  4668  4751 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 07:45:33.539  4668  4751 I BluetoothAdapterState: Entering PendingCommandState
11-25 07:45:33.542  4668  4668 D BluetoothMapService: onReceive
11-25 07:45:33.542  4668  4668 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 07:45:33.542  4668  4668 D BluetoothMapService: STATE_TURNING_OFF
11-25 07:45:33.543  4668  4668 D BluetoothMapService: MAP Service closeService in
11-25 07:45:33.543  4668  4668 D BluetoothMapMasInstance0: MAP Service shutdown
,11-25 07:45:33.543  4668  4668 D ObexServerSockets0: shutdown(block = true)
11-25 07:45:33.544  4668  4925 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-25 07:45:33.549  4668  4668 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 07:45:33.550  4668  4902 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 07:45:33.550  4668  4668 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 07:45:33.552  4668  4926 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-25 07:45:33.553  4668  4668 I BtOppRfcommListener: stopping Accept Thread
11-25 07:45:33.554  4668  5387 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 07:45:33.554  4668  5387 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 07:45:33.555   929  5450 D DhcpClient: Clearing IP address
11-25 07:45:33.555   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:45:33.559   509   928 D CommandListener: Setting iface cfg
,11-25 07:45:33.564   929   942 I ActivityManager: Start proc 5741:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-25 07:45:33.565  4668  4755 D BluetoothAdapterProperties: Scan Mode:20
,11-25 07:45:33.565  3638  5506 V NativeCrypto: Read error: ssl=0x7f6bf63c80: I/O error during system call, Connection timed out
11-25 07:45:33.566  4668  4751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 07:45:33.568  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:45:33.568  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 07:45:33.570  3638  5506 V NativeCrypto: SSL shutdown failed: ssl=0x7f6bf63c80: I/O error during system call, Broken pipe
11-25 07:45:33.573   929  3928 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-25 07:45:33.573   929  5448 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-25 07:45:33.574  4668  4668 D HeadsetService: Received stop request...Stopping profile...
11-25 07:45:33.575   929  5448 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-25 07:45:33.576   929   929 D BluetoothHeadset: Proxy object disconnected
,11-25 07:45:33.576   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-25 07:45:33.576   929  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 07:45:33.577  3883  3905 D BluetoothHeadset: Proxy object disconnected
,11-25 07:45:33.577   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:33.577   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:33.578  4668  4668 D A2dpService: Received stop request...Stopping profile...
,11-25 07:45:33.578  4668  4907 D A2dpStateMachine: Exit Disconnected: -1
,11-25 07:45:33.578   929  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 07:45:33.578  3197  5686 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:33.579  3197  3197 D HeadsetProfile: Bluetooth service disconnected
11-25 07:45:33.580   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-25 07:45:33.580  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:45:33.580  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 07:45:33.580   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-25 07:45:33.581  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:33.581  5687  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:45:33.581  5687  5734 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 07:45:33.582   599   599 E Parcel  : Reading a NULL string not supported here.
11-25 07:45:33.584  3197  3197 D BluetoothA2dp: Proxy object disconnected
11-25 07:45:33.585   929   929 D BluetoothA2dp: Proxy object disconnected
,11-25 07:45:33.586   929   929 D RttService: SCAN_AVAILABLE : 1
11-25 07:45:33.586   929  3163 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 07:45:33.588  4668  4668 D HidService: Received stop request...Stopping profile...
11-25 07:45:33.588  4668  4668 D HidService: Stopping Bluetooth HidService
11-25 07:45:33.588  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:33.588  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:45:33.589  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:33.589  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:33.589  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:33.589  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:33.589  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:45:33.589  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:45:33.591   929  3057 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-25 07:45:33.591  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:45:33.592  4668  4668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 07:45:33.592  3842  3989 W QCNEJ   : |CORE| network lost: 100
11-25 07:45:33.593  3842  3989 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 07:45:33.593  4668  4755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 07:45:33.593  4668  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:33.593  4668  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:33.593  4668  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:33.593  4668  4755 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-25 07:45:33.593  4668  4668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 07:45:33.594   929  5451 D DhcpClient: Receive thread stopped
11-25 07:45:33.594  4668  4668 D HealthService: Received stop request...Stopping profile...
11-25 07:45:33.596   929  3055 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-25 07:45:33.597  3197  3197 D BluetoothInputDevice: Proxy object disconnected
11-25 07:45:33.597  3197  3197 D HidProfile: Bluetooth service disconnected
11-25 07:45:33.599  4668  4668 D PanService: Received stop request...Stopping profile...
,11-25 07:45:33.602  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:33.602  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:33.602  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:33.602  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:33.603  4668  4755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 07:45:33.603  4668  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:33.604  4668  4668 D BluetoothMapService: Received stop request...Stopping profile...
11-25 07:45:33.604  4668  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:33.604  4668  4668 D BluetoothMapService: stop()
,11-25 07:45:33.604  4668  4889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 07:45:33.604  4668  4889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 07:45:33.604  4668  4889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 07:45:33.604  4668  4889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 07:45:33.604  4668  4668 D BluetoothMapAppObserver: deinitObservers()
11-25 07:45:33.604  4668  4668 D BluetoothMapAppObserver: removeReceiver()
,11-25 07:45:33.606   929  3055 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 07:45:33.611  4668  4668 V BluetoothAdapterState: isTurningOff()=true
,11-25 07:45:33.612  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:33.612  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 07:45:33.612  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:33.613  4668  4668 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-25 07:45:33.613  4668  4668 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 07:45:33.613  4668  4755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 07:45:33.613  4668  4668 D SapService: Received stop request...Stopping profile...
11-25 07:45:33.613  4668  4668 V SapService: stop()
11-25 07:45:33.615  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:33.615  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:33.615  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:33.615  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:33.615  4668  4668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 07:45:33.615  4668  4755 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 07:45:33.616  4668  4668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 07:45:33.616  4668  4668 V BluetoothAdapterState: isTurningOff()=true
,11-25 07:45:33.616  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:33.616  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:33.616  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:33.616  4668  4668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 07:45:33.616  4668  4668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 07:45:33.617  4668  4668 D BluetoothMapService: MAP Service closeService in
11-25 07:45:33.617  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:33.617  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:33.617  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:33.617  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:33.618  4668  4668 D BluetoothMapService: cleanup()
11-25 07:45:33.618  4668  4668 D BluetoothMapService: MAP Service closeService in
11-25 07:45:33.618  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:33.618  4668  4668 V BluetoothAdapterState: isTurningOn()=false
,11-25 07:45:33.618  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:33.618  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:33.618  4668  4751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 07:45:33.618  4668  4751 D BluetoothAdapterProperties: Setting state to 15
11-25 07:45:33.618  4668  4751 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 07:45:33.619  3197  3210 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:33.620  3197  3197 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 07:45:33.620  3197  3197 D PanProfile: Bluetooth service disconnected
11-25 07:45:33.620  3197  3197 D BluetoothMap: Proxy object disconnected
11-25 07:45:33.620  3197  3197 D MapProfile: Bluetooth service disconnected
11-25 07:45:33.620  3197  3213 D BluetoothMap: onBluetoothStateChange: up=false
11-25 07:45:33.621   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:33.621  3197  3210 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 07:45:33.621  4668  4751 I BluetoothAdapterState: Entering BleOnState
11-25 07:45:33.622  3883  3910 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 07:45:33.622   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:33.622  3197  4046 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 07:45:33.623  3197  5686 D BluetoothPan: onBluetoothStateChange on: false
11-25 07:45:33.623  3197  3213 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:45:33.624   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:33.624   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:45:33.625  4668  4751 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 07:45:33.625  4668  4751 D BluetoothAdapterProperties: Setting state to 16
11-25 07:45:33.625   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 07:45:33.625  4668  4751 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 07:45:33.625  4668  4751 D BluetoothAdapterProperties: onBleDisable
11-25 07:45:33.626  4668  4751 I BluetoothAdapterState: Entering PendingCommandState
11-25 07:45:33.626  4668  4752 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 07:45:33.627  4668  4755 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:45:33.627  4668  4889 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 07:45:33.627  4668  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:33.629  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:33.629  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 07:45:33.632  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:33.647   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 07:45:33.648   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:45:33.648   929  3057 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-25 07:45:33.648   509   928 D TetherController: Setting IP forward enable = 0
11-25 07:45:33.649   929  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:45:33.651   929   946 D Tethering: MasterInitialState.processMessage what=3
11-25 07:45:33.652   929  3055 D DhcpClient: doQuit
11-25 07:45:33.652   929  3055 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 07:45:33.653  5344  5344 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@928b908 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-25 07:45:33.653   929  5450 D DhcpClient: onQuitting
11-25 07:45:33.653  3518  3518 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 07:45:33.654  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:45:33.655  4021  4021 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-25 07:45:33.658  5107  5131 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 07:45:33.658  5107  5131 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 07:45:33.658  5107  5131 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 07:45:33.658  5107  5131 E SarControlService: no key has been found,reset the power
11-25 07:45:33.659  5107  5143 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 07:45:33.659  5107  5143 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 07:45:33.659  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:33.659  5107  5143 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:33.659  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 07:45:33.659  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:45:33.659  5132  5132 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 07:45:33.660  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:33.660  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:45:33.660  5107  5143 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 07:45:33.661  5107  5143 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 07:45:33.661  5107  5143 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 07:45:33.662  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:45:33.662  5132  5132 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 07:45:33.664  5132  5146 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@69fa12e HexData = [00000000ea03000000000000ffffffff]
11-25 07:45:33.665  5132  5146 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:45:33.665  5132  5146 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 07:45:33.665  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:45:33.665  5107  5117 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 07:45:33.672  5741  5741 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-25 07:45:33.672  5132  5146 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@69fa12e HexData = [00000000eb03000000000000ffffffff]
11-25 07:45:33.672  5132  5146 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:45:33.673  5132  5146 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-25 07:45:33.673  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:45:33.673  5107  5118 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 07:45:33.680  3518  3518 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-25 07:45:33.684  3518  3518 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-25 07:45:33.685  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:45:33.686   509   920 W SocketClient: write error (Broken pipe)
11-25 07:45:33.686   509   920 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-25 07:45:33.686   509   920 W SocketListener: Error sending broadcast (Broken pipe)
11-25 07:45:33.690   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423187a:true
11-25 07:45:33.692  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:45:33.706   509   928 E Netd    : netlink response contains error (No such file or directory)
11-25 07:45:33.707   509   928 D TetherController: Setting IP forward enable = 0
11-25 07:45:33.708   929  3057 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-25 07:45:33.708   929  3921 I ActivityManager: Start proc 5771:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-25 07:45:33.708   929  3057 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 07:45:33.712  3518  3518 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 07:45:33.714  5741  5741 D LocalBluetoothProfileManager: Adding local MAP profile
,11-25 07:45:33.717  5741  5741 D BluetoothMap: Create BluetoothMap proxy object
,11-25 07:45:33.726  5741  5741 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 07:45:33.730  3518  3518 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 07:45:33.741  5741  5741 D DockEventReceiver: finishStartingService: stopping service
,11-25 07:45:33.749  5771  5771 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-25 07:45:33.751   929   940 I ActivityManager: Killing 5040:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-25 07:45:33.835   929  3055 D wifi    : In wifi stop Hal
,11-25 07:45:33.835   929  3055 D wifi    : halHandle = 0x7f5a3c4e40, mVM = 0x7f76a8d140, mCls = 0x100a02
11-25 07:45:33.835   929  3517 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 07:45:33.835   929  3517 D WifiHAL : Got a signal to exit!!!
11-25 07:45:33.835   929  3517 I WifiHAL : Exit wifi_event_loop
11-25 07:45:33.836  4668  4755 I bt_hci  : shut_down
11-25 07:45:33.836   929  3055 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 07:45:33.836   929  3055 E WifiHAL : Event processing terminated
11-25 07:45:33.836   929  3055 D wifi    : In wifi cleaned up handler
11-25 07:45:33.836  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 07:45:33.837   929  3055 I WifiHAL : Internal cleanup completed
11-25 07:45:33.838  4130  4298 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 07:45:33.838  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:33.840  4668  4761 I bt_vendor: low_power_mode_cb
11-25 07:45:33.840  4668  4761 D bt_hwcfg: hw_epilog_process
11-25 07:45:33.842  4668  4761 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 07:45:33.842  4668  4761 I bt_vendor: epilog_cb
11-25 07:45:33.842  4668  4761 I bt_hci  : epilog_finished_callback
11-25 07:45:33.845  4668  4755 I bt_hci_h4: hal_close
11-25 07:45:33.846  4668  4755 I bt_userial_vendor: device fd = 54 close
,11-25 07:45:33.859   929  3517 D wifi    : set interface wlan0 flags (DOWN)
,11-25 07:45:33.860   929  3055 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 07:45:33.943  5771  5771 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.943  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 07:45:33.951  5771  5771 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:45:33.951  5771  5771 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:45:33.951  5771  5771 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:45:33.951  5771  5771 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.k.d(PG:583)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:45:33.951  5771  5771 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:45:33.951  5771  5771 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:45:33.951  5771  5771 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:45:33.951  5771  5771 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:45:33.955   601   601 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
11-25 07:45:33.957  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:45:33.958  4668  4752 D bt_stack_manager: event_shut_down_stack finished.
11-25 07:45:33.958  4668  4751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-25 07:45:33.960  4668  4668 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 07:45:33.960  4668  4751 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 07:45:33.961  4668  4668 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 07:45:33.961  4668  4668 D BtGatt.GattService: stop()
11-25 07:45:33.961  4668  4668 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 07:45:33.962  4668  4668 V BluetoothAdapterState: isTurningOff()=false
11-25 07:45:33.963  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:33.963  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:33.963  4668  4668 V BluetoothAdapterState: isBleTurningOff()=true
11-25 07:45:33.963  4668  4751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 07:45:33.963  4668  4751 D BluetoothAdapterProperties: Setting state to 10
11-25 07:45:33.963  4668  4751 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 07:45:33.964  4668  4751 I BluetoothAdapterState: Entering OffState
11-25 07:45:33.964  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:45:33.965   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-25 07:45:33.971  4668  4668 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-25 07:45:33.971  4668  4668 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 07:45:33.971  4668  4668 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 07:45:33.972  4668  4752 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 07:45:33.981  3722  3722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 07:45:33.986  4668  4752 D bt_stack_manager: event_clean_up_stack finished.
11-25 07:45:33.986  3722  3722 D SystemUpdateService: onCreate
11-25 07:45:33.989  3722  3722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 07:45:33.991  4668  4668 I art     : System.exit called, status: 0
11-25 07:45:33.992  4668  4668 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 07:45:33.996  3722  3722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-25 07:45:34.000  3722  5475 I iu.UploadsManager: num queued entries: 0
11-25 07:45:34.000  3722  5475 I iu.UploadsManager: num updated entries: 0
11-25 07:45:34.001  3722  5475 I iu.SyncManager: NEXT; no task
11-25 07:45:34.018  5741  5741 D DockEventReceiver: finishStartingService: stopping service
11-25 07:45:34.028  3722  3722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 07:45:34.030  3722  3722 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-25 07:45:34.031  5478  5478 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:45:34.035  5478  5478 D SprintDMHelper: simOperator: 
,11-25 07:45:34.035  5478  5478 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 07:45:34.045  3722  5804 I SystemUpdateService: active receiver: enabled
,11-25 07:45:34.045   929  3653 I ActivityManager: Process com.android.bluetooth (pid 4668) has died
,11-25 07:45:34.049  5081  5807 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 07:45:34.064   929   946 D Tethering: InitialState.processMessage what=4
,11-25 07:45:34.066   929  3653 I ActivityManager: Start proc 5808:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-25 07:45:34.067   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 07:45:34.068  3722  5804 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 07:45:34.078  3722  5804 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 07:45:34.079  3722  5804 I SystemUpdateService: now status is 0 (complete)
11-25 07:45:34.079  3722  5804 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 07:45:34.079  3722  5804 I SystemUpdateService: file has been verified
11-25 07:45:34.079  3722  5804 I SystemUpdateService: OTA package size = 21989297
,11-25 07:45:34.100  5808  5808 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-25 07:45:34.116   929  3237 I ActivityManager: Killing 5344:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-25 07:45:34.130  3722  5804 I SystemUpdateService: showing system update notification
,11-25 07:45:34.176  3722  3722 D SystemUpdateService: onDestroy
,11-25 07:45:34.178   929  3925 I ActivityManager: Killing 5555:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-25 07:45:34.296  5771  5791 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-25 07:45:34.308   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5004bef:true
,11-25 07:45:38.584   929  3653 D WifiService: setWifiEnabled: true pid=5687, uid=10077
,11-25 07:45:38.585   929  3653 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:45:38.596   509   928 D SoftapController: Softap fwReload - Ok
,11-25 07:45:38.602   509   928 D CommandListener: Setting iface cfg
,11-25 07:45:38.602   509   928 D CommandListener: Trying to bring down wlan0
,11-25 07:45:38.604   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:45:38.611   929  3055 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 07:45:38.956   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:39.185   929  3055 D wifi    : set interface wlan0 flags (UP)
11-25 07:45:39.186   929  3055 I WifiHAL : Initializing wifi
11-25 07:45:39.186   929  3055 I WifiHAL : Creating socket
,11-25 07:45:39.193   929  3055 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 07:45:39.194   929  3055 D wifi    : Did set static halHandle = 0x7f5a3c4e40
,11-25 07:45:39.194   929  3055 D wifi    : halHandle = 0x7f5a3c4e40, mVM = 0x7f76a8d140, mCls = 0x2018be
,11-25 07:45:39.194   929  3055 D wifi    : array field set
11-25 07:45:39.194   929  3055 I WifiNative-HAL: interface[0] = wlan0
11-25 07:45:39.195   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-25 07:45:39.197   929  5827 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546974748224
,11-25 07:45:39.197   929  5827 D wifi    : waitForHalEvents called, vm = 0x7f76a8d140, obj = 0x2018be, env = 0x7f5af1dfc0
,11-25 07:45:39.273  5828  5828 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 07:45:39.295  5828  5828 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:45:39.304  5828  5828 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:45:39.304  5828  5828 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
11-25 07:45:39.304   929  3055 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 07:45:39.315  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:39.325   929  3055 D WifiConfigStore: Loading config and enabling all networks 
,11-25 07:45:39.327  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:39.327  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:45:39.327  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:39.327  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 07:45:39.340   929  3055 D WifiConfigStore: loaded 0 passpoint configs
,11-25 07:45:39.340   929  3055 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-25 07:45:39.341   929  3055 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 07:45:39.342   929  3055 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-25 07:45:39.343   929  3055 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 07:45:39.344   929  3055 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-25 07:45:39.344   929  3055 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-25 07:45:39.344   929  3055 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 07:45:39.348   929  3055 D WifiNative-HAL: Setting external_sim to 1
,11-25 07:45:39.348  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 07:45:39.348   929  3055 D wifi    : setting dfs flag to true, 0x7f5af2cd40
11-25 07:45:39.349   929  3055 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 07:45:39.349   929  3055 D wifi    : setting scan oui 0x7f5af2cd40
,11-25 07:45:39.349   929  3055 D WifiHAL : Sending mac address OUI
,11-25 07:45:39.353   929  3055 E native  : do suspend false
,11-25 07:45:39.359   929  3055 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-25 07:45:39.360   509   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-25 07:45:39.360   929   929 D RttService: SCAN_AVAILABLE : 3
11-25 07:45:39.360   929  3163 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-25 07:45:39.361   509   928 D CommandListener: Setting iface cfg
,11-25 07:45:39.364   929  3054 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-25 07:45:39.364   929  3054 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 07:45:39.372   929  3054 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 07:45:39.372   929  3054 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-25 07:45:39.378   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128878 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-25 07:45:39.960   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:40.961   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:41.962   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:42.435  5828  5828 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:45:42.439  5828  5828 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:45:42.446  5828  5828 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:45:42.541   929  3055 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-25 07:45:42.542   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 07:45:42.542   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:45:42.554   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 07:45:42.584   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 07:45:42.587  5828  5828 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 07:45:42.963   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:43.017  5828  5828 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 07:45:43.054  5828  5828 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 07:45:43.055  5828  5828 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 07:45:43.064   929  3055 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 07:45:43.064   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 07:45:43.064   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 07:45:43.080   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:45:43.094   509   928 D CommandListener: Setting iface cfg
,11-25 07:45:43.100   929  3055 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 07:45:43.106   929  5834 D DhcpClient: Receive thread started
,11-25 07:45:43.111   929  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 07:45:43.111   929  3055 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 07:45:43.111   929  3057 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 07:45:43.193   929  3055 E native  : do suspend false
,11-25 07:45:43.209   929  5833 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 07:45:43.230   929  5834 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-25 07:45:43.231   929  5833 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-25 07:45:43.232   929  5833 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-25 07:45:43.262   929  5834 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 07:45:43.263   929  5833 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 07:45:43.266   509   928 D CommandListener: Setting iface cfg
,11-25 07:45:43.272   929  3055 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 07:45:43.274   929  5833 D DhcpClient: Scheduling renewal in 86399s
,11-25 07:45:43.283   929  3055 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-25 07:45:43.284   929  3055 D WifiConfigStore: No blacklist allowed without epno enabled
11-25 07:45:43.284   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 07:45:43.286   929  3057 D ConnectivityService: Adding iface wlan0 to network 101
,11-25 07:45:43.292   929  3055 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 07:45:43.329   929  3057 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 07:45:43.329   929  3057 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 07:45:43.334   929  3057 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-25 07:45:43.335   929  3057 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-25 07:45:43.337   929  3057 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-25 07:45:43.342   929  3057 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 07:45:43.347   929  3057 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-25 07:45:43.347   929  3057 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-25 07:45:43.347   929  3057 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 07:45:43.347   929  3055 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 07:45:43.347   929  3057 D ConnectivityService:    accepting network in place of null
,11-25 07:45:43.347   929  3055 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 07:45:43.348   929  3057 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 07:45:43.357   929  5832 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132856, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 07:45:43.372   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:45:43.393   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:45:43.397   929  3057 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-25 07:45:43.397   929  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:45:43.398  3842  3989 W QCNEJ   : |CORE| network available: 101
,11-25 07:45:43.398   929  3057 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-25 07:45:43.400   929   946 D Tethering: MasterInitialState.processMessage what=3
11-25 07:45:43.403  3842  3989 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-25 07:45:43.405  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 07:45:43.405  3842  3989 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:45:43.405  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:45:43.405  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:43.406  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:45:43.406  3842  3989 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-25 07:45:43.409  5107  5131 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 07:45:43.409  5107  5131 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 07:45:43.409  5107  5131 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 07:45:43.409  5107  5131 E SarControlService: no key has been found,reset the power
11-25 07:45:43.409  5107  5143 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 07:45:43.410  5107  5143 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-25 07:45:43.411  5107  5143 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 07:45:43.411  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 07:45:43.412  5132  5132 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 07:45:43.416  3722  3722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 07:45:43.420  5132  5146 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@69fa12e HexData = [00000000ec03000000000000ffffffff]
,11-25 07:45:43.420  5132  5146 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:45:43.420  5132  5146 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 07:45:43.420  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:45:43.420   929  5831 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 07:45:43.420  5107  5117 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 07:45:43.422  3722  3722 D SystemUpdateService: onCreate
11-25 07:45:43.416  5107  5143 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 07:45:43.423  5107  5143 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 07:45:43.423  5107  5143 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-25 07:45:43.424  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:45:43.424  5132  5132 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 07:45:43.413  4021  4021 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-25 07:45:43.427  5132  5146 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@69fa12e HexData = [00000000ed03000000000000ffffffff]
11-25 07:45:43.427  5132  5146 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:45:43.427  5132  5146 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-25 07:45:43.428  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 07:45:43.429  5107  5118 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 07:45:43.431  3722  3722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 07:45:43.439  3722  3722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 07:45:43.444  3722  5844 I SystemUpdateService: active receiver: enabled
,11-25 07:45:43.449  3722  5475 I iu.UploadsManager: num queued entries: 0
,11-25 07:45:43.449  3722  5475 I iu.UploadsManager: num updated entries: 0
11-25 07:45:43.450  3722  5475 I iu.SyncManager: NEXT; no task
,11-25 07:45:43.452  3722  3722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 07:45:43.453  3722  3722 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-25 07:45:43.454  5478  5478 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 07:45:43.457  5478  5478 D SprintDMHelper: simOperator: 
11-25 07:45:43.457  5478  5478 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 07:45:43.474  3722  5844 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 07:45:43.478   929  5831 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:45:43 GMT], X-Android-Received-Millis=[1480077943476], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480077943448]}
,11-25 07:45:43.479   929  3057 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 07:45:43.480   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-25 07:45:43.480   929  3057 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-25 07:45:43.481   929  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-25 07:45:43.491  3722  5844 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 07:45:43.491  3722  5844 I SystemUpdateService: now status is 0 (complete)
11-25 07:45:43.491  3722  5844 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 07:45:43.491  3722  5844 I SystemUpdateService: file has been verified
11-25 07:45:43.491  3722  5844 I SystemUpdateService: OTA package size = 21989297
,11-25 07:45:43.497  3722  5844 I SystemUpdateService: showing system update notification
,11-25 07:45:43.507  3722  3722 D SystemUpdateService: onDestroy
,11-25 07:45:43.585  5081  5849 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 07:45:43.594   929  3925 D WifiService: setWifiEnabled: false pid=5687, uid=10077
,11-25 07:45:43.594   929  3925 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:45:43.596   929  3055 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-25 07:45:43.596   929  3055 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 07:45:43.596   929  3055 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 07:45:43.596   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:45:43.603   929  5833 D DhcpClient: Clearing IP address
,11-25 07:45:43.604   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:45:43.605   509   928 D CommandListener: Setting iface cfg
,11-25 07:45:43.611  3638  5854 V NativeCrypto: Read error: ssl=0x7f6bf5d380: I/O error during system call, Connection timed out
,11-25 07:45:43.612  3638  5854 V NativeCrypto: SSL shutdown failed: ssl=0x7f6bf5d380: I/O error during system call, Broken pipe
,11-25 07:45:43.615   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-25 07:45:43.616   929  3057 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-25 07:45:43.619   599   599 E Parcel  : Reading a NULL string not supported here.
,11-25 07:45:43.622   929   929 D RttService: SCAN_AVAILABLE : 1
11-25 07:45:43.623   929  3163 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 07:45:43.623   929  3057 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-25 07:45:43.627  3842  3989 W QCNEJ   : |CORE| network lost: 101
11-25 07:45:43.627   929  3055 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 07:45:43.628  3842  3989 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 07:45:43.632   929  5834 D DhcpClient: Receive thread stopped
,11-25 07:45:43.643   929  3055 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 07:45:43.648   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:45:43.667   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:45:43.668   929  3057 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 07:45:43.668   509   928 D CommandListener: Clearing all IP addresses on wlan0
11-25 07:45:43.668   929  3057 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 07:45:43.669   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-25 07:45:43.671  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:43.671  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:45:43.671  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:43.671   929  3055 D DhcpClient: doQuit
,11-25 07:45:43.671  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:45:43.672   929  3055 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 07:45:43.672   929  5833 D DhcpClient: onQuitting
11-25 07:45:43.672  5828  5828 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 07:45:43.674  4021  4021 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-25 07:45:43.675  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:43.675  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:45:43.676  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:43.676  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:45:43.678  3722  3722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 07:45:43.680  5107  5131 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 07:45:43.680  5107  5131 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 07:45:43.680  5107  5131 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 07:45:43.680  5107  5131 E SarControlService: no key has been found,reset the power
11-25 07:45:43.680  5107  5143 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 07:45:43.680  5107  5143 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 07:45:43.681  5107  5143 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 07:45:43.682  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:45:43.682  5132  5132 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 07:45:43.682  5828  5828 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 07:45:43.686  3722  3722 D SystemUpdateService: onCreate
11-25 07:45:43.686  5107  5143 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 07:45:43.686  5107  5143 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 07:45:43.687  5828  5828 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-25 07:45:43.687  5107  5143 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 07:45:43.687  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:45:43.688  5132  5132 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 07:45:43.688  5132  5146 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@69fa12e HexData = [00000000ee03000000000000ffffffff]
11-25 07:45:43.688  5132  5146 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:45:43.689  5132  5146 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 07:45:43.689  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:45:43.689  5107  5118 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 07:45:43.692  3722  3722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 07:45:43.693  5132  5146 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@69fa12e HexData = [00000000ef03000000000000ffffffff]
11-25 07:45:43.693  5132  5146 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:45:43.693  5132  5146 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-25 07:45:43.694  5132  5132 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:45:43.694  5107  5117 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 07:45:43.698  3722  5864 I SystemUpdateService: active receiver: enabled
,11-25 07:45:43.702  3722  3722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 07:45:43.706  3722  5475 I iu.UploadsManager: num queued entries: 0
,11-25 07:45:43.707  3722  5475 I iu.UploadsManager: num updated entries: 0
11-25 07:45:43.708  3722  5475 I iu.SyncManager: NEXT; no task
,11-25 07:45:43.709  3722  5864 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 07:45:43.711  3722  3722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 07:45:43.712  3722  3722 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 07:45:43.714  5478  5478 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:45:43.718  5478  5478 D SprintDMHelper: simOperator: 
11-25 07:45:43.718  5478  5478 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 07:45:43.726  3722  5864 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 07:45:43.726  3722  5864 I SystemUpdateService: now status is 0 (complete)
11-25 07:45:43.726  3722  5864 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 07:45:43.727  3722  5864 I SystemUpdateService: file has been verified
,11-25 07:45:43.729  5081  5868 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 07:45:43.730  3722  5864 I SystemUpdateService: OTA package size = 21989297
,11-25 07:45:43.731   509   928 E Netd    : netlink response contains error (No such file or directory)
,11-25 07:45:43.742  5828  5828 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 07:45:43.748  3722  5864 I SystemUpdateService: showing system update notification
,11-25 07:45:43.750  5828  5828 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 07:45:43.756  3722  3722 D SystemUpdateService: onDestroy
,11-25 07:45:43.852   929  3055 D wifi    : In wifi stop Hal
,11-25 07:45:43.852   929  3055 D wifi    : halHandle = 0x7f5a3c4e40, mVM = 0x7f76a8d140, mCls = 0x2018be
11-25 07:45:43.853   929  5827 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 07:45:43.853   929  5827 D WifiHAL : Got a signal to exit!!!
11-25 07:45:43.853   929  5827 I WifiHAL : Exit wifi_event_loop
11-25 07:45:43.855   929  3055 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-25 07:45:43.855   929  3055 E WifiHAL : Event processing terminated
11-25 07:45:43.856   929  3055 D wifi    : In wifi cleaned up handler
11-25 07:45:43.856   929  3055 I WifiHAL : Internal cleanup completed
11-25 07:45:43.856  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:43.857  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 07:45:43.858  4130  4298 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 07:45:43.878   929  5827 D wifi    : set interface wlan0 flags (DOWN)
,11-25 07:45:43.878   929  3055 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 07:45:43.963   601   601 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 07:45:44.085   929   946 D Tethering: InitialState.processMessage what=4
,11-25 07:45:44.091   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 07:45:44.398   929  3057 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 07:45:48.633   929   946 I ActivityManager: Start proc 5870:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 07:45:48.729  5870  5870 D AdapterServiceConfig: Adding HeadsetService
11-25 07:45:48.729  5870  5870 D AdapterServiceConfig: Adding A2dpService
11-25 07:45:48.729  5870  5870 D AdapterServiceConfig: Adding HidService
11-25 07:45:48.729  5870  5870 D AdapterServiceConfig: Adding HealthService
11-25 07:45:48.730  5870  5870 D AdapterServiceConfig: Adding PanService
11-25 07:45:48.730  5870  5870 D AdapterServiceConfig: Adding GattService
11-25 07:45:48.730  5870  5870 D AdapterServiceConfig: Adding BluetoothMapService
,11-25 07:45:48.730  5870  5870 D AdapterServiceConfig: Adding SapService
,11-25 07:45:48.739   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc4baf2:true
,11-25 07:45:48.740  5870  5870 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 07:45:48.743  5870  5870 I bt_bluedroid: init
,11-25 07:45:48.743  5870  5882 I BluetoothAdapterState: Entering OffState
,11-25 07:45:48.745  5870  5883 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 07:45:48.745  5870  5883 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 07:45:48.745  5870  5883 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 07:45:48.745  5870  5883 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 07:45:48.746  5870  5870 I bt_bluedroid: get_profile_interface socket
,11-25 07:45:48.747  5870  5886 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 07:45:48.748  5870  5870 I bt_bluedroid: get_profile_interface sdp
11-25 07:45:48.749  5870  5886 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:45:48.752  5870  5881 I bt_bluedroid: config_hci_snoop_log
11-25 07:45:48.753   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 07:45:48.757  5870  5882 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 07:45:48.757  5870  5882 D BluetoothAdapterProperties: Setting state to 14
11-25 07:45:48.757  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 07:45:48.759  5870  5882 D BluetoothBondStateMachine: make
,11-25 07:45:48.760  5870  5887 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 07:45:48.762  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:45:48.763  5870  5870 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 07:45:48.765  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:45:48.766  5870  5870 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 07:45:48.766  5870  5870 D BtGatt.GattService: Received start request. Starting profile...
11-25 07:45:48.766  5870  5870 D BtGatt.GattService: start()
11-25 07:45:48.766  5870  5870 I bt_bluedroid: get_profile_interface gatt
,11-25 07:45:48.767  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:45:48.767  5870  5870 D BtGatt.AdvertiseManager: advertise manager created
,11-25 07:45:48.772  5870  5870 V BluetoothAdapterState: isTurningOff()=false
11-25 07:45:48.772  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:48.772  5870  5870 V BluetoothAdapterState: isBleTurningOn()=true
11-25 07:45:48.772  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:48.772  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 07:45:48.773  5870  5882 I bt_bluedroid: bt_bluedroid
,11-25 07:45:48.774  5870  5883 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 07:45:48.774  5870  5883 I bt_hci  : start_up
,11-25 07:45:48.778  5870  5883 I bt_vendor: alloc value 0xf4199871,
11-25 07:45:48.779  5870  5883 I bt_vendor: init
11-25 07:45:48.779  5870  5883 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 07:45:48.779  5870  5883 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 07:45:48.890  5870  5883 D bt_hci  : start_up starting async portion
,11-25 07:45:48.890  5870  5890 I bt_hci  : event_finish_startup
,11-25 07:45:48.891  5870  5890 I bt_hci_h4: hal_open
11-25 07:45:48.891  5870  5890 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-25 07:45:48.887  5891  5891 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-25 07:45:48.893  5870  5890 I bt_userial_vendor: device fd = 54 open
,11-25 07:45:48.907  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:45:48.909  5870  5890 D bt_hwcfg: Chipset BCM4358A3
,11-25 07:45:48.909  5870  5890 D bt_hwcfg: Target name = [BCM4358A3]
11-25 07:45:48.910  5870  5890 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 07:45:49.305  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-25 07:45:49.305  5870  5890 D bt_hwcfg: Settlement delay -- 100 ms
,11-25 07:45:49.305  5870  5890 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 07:45:49.440  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:45:49.441  5870  5890 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-25 07:45:49.442  5870  5890 I bt_hwcfg: vendor lib fwcfg completed
11-25 07:45:49.442  5870  5890 I bt_vendor: firmware callback
11-25 07:45:49.442  5870  5890 I bt_hci  : firmware_config_callback
,11-25 07:45:49.450  5870  5893 I bt_btu  : btu_task pending for preload complete event
,11-25 07:45:49.450  5870  5893 I bt_btu_task: Bluetooth chip preload is complete
11-25 07:45:49.450  5870  5893 I bt_btu  : btu_task received preload complete event
,11-25 07:45:49.457  5870  5893 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 07:45:49.457  5870  5893 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-25 07:45:49.457  5870  5893 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-25 07:45:49.457  5870  5893 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 07:45:49.458  5870  5893 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-25 07:45:49.458  5870  5893 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 07:45:49.458  5870  5893 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 07:45:49.458  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 07:45:49.458  5870  5893 I         : BTE_InitTraceLevels -- TRC_GAP
,11-25 07:45:49.458  5870  5893 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 07:45:49.458  5870  5893 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 07:45:49.459  5870  5893 I         : BTE_InitTraceLevels -- TRC_GATT
,11-25 07:45:49.459  5870  5893 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 07:45:49.459  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 07:45:49.459  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 07:45:49.545  5870  5893 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4117549
,11-25 07:45:49.546  5870  5893 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4117549 
,11-25 07:45:49.569  5870  5886 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 07:45:49.570  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 07:45:49.571  5870  5886 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 07:45:49.573  5870  5886 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:45:49.575  5870  5886 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:45:49.576  5870  5886 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 07:45:49.576  5870  5886 D bt_hci  : do_postload posting postload work item
11-25 07:45:49.576  5870  5890 I bt_hci  : event_postload
11-25 07:45:49.576  5870  5890 I bt_vendor: sco_config_cb
11-25 07:45:49.576  5870  5890 I bt_hci  : sco_config_callback postload finished.
,11-25 07:45:49.580  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:49.582  5870  5886 D bt_bte_conf: Device ID record 1 : primary
11-25 07:45:49.582  5870  5886 D bt_bte_conf:   vendorId            = 000f
11-25 07:45:49.582  5870  5886 D bt_bte_conf:   vendorIdSource      = 0001
11-25 07:45:49.582  5870  5886 D bt_bte_conf:   product             = 1200
11-25 07:45:49.582  5870  5886 D bt_bte_conf:   version             = 1436
11-25 07:45:49.582  5870  5886 D bt_bte_conf:   clientExecutableURL = 
11-25 07:45:49.582  5870  5886 D bt_bte_conf:   serviceDescription  = 
11-25 07:45:49.582  5870  5886 D bt_bte_conf:   documentationURL    = 
,11-25 07:45:49.582  5870  5886 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 07:45:49.582  5870  5890 I bt_vendor: low_power_mode_cb
11-25 07:45:49.582  5870  5883 D bt_stack_manager: event_start_up_stack finished
,11-25 07:45:49.583  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 07:45:49.583  5870  5882 D BluetoothAdapterProperties: Setting state to 15
11-25 07:45:49.583  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 07:45:49.584  5870  5882 I BluetoothAdapterState: Entering BleOnState
,11-25 07:45:49.587  5870  5882 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-25 07:45:49.587  5870  5882 D BluetoothAdapterProperties: Setting state to 11
11-25 07:45:49.587  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 07:45:49.591  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:45:49.592  5870  5870 D HeadsetService: Received start request. Starting profile...
11-25 07:45:49.593  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:45:49.594  5870  5870 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 07:45:49.594  5870  5870 D HeadsetStateMachine: make
,11-25 07:45:49.602  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:45:49.604  5870  5870 D HeadsetStateMachine: max_hf_connections = 1
,11-25 07:45:49.605  5870  5870 I bt_bluedroid: get_profile_interface handsfree
11-25 07:45:49.605  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 07:45:49.605  5870  5886 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-25 07:45:49.609  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:45:49.610  5870  5870 D A2dpService: Received start request. Starting profile...
11-25 07:45:49.610  5870  5870 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 07:45:49.611  5870  5870 I bt_bluedroid: get_profile_interface avrcp
,11-25 07:45:49.615  5870  5870 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 07:45:49.615  5870  5870 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 07:45:49.615  5870  5870 D A2dpStateMachine: make
,11-25 07:45:49.617  5870  5870 I bt_bluedroid: get_profile_interface a2dp
11-25 07:45:49.617  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 07:45:49.619  5870  5901 D A2dpStateMachine: Enter Disconnected: -2
11-25 07:45:49.621  5870  5870 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 07:45:49.621  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:45:49.621  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:45:49.624  5741  5741 D BluetoothInputDevice: Proxy object connected
,11-25 07:45:49.624  5870  5870 D HidService: Received start request. Starting profile...
11-25 07:45:49.624  5870  5870 I bt_bluedroid: get_profile_interface hidhost
11-25 07:45:49.624  5741  5741 D HidProfile: Bluetooth service connected
11-25 07:45:49.624  5870  5886 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40f856d
11-25 07:45:49.624  5870  5870 D HidService: setHidService(): set to: null
11-25 07:45:49.624  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 07:45:49.625  5870  5870 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 07:45:49.626  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:45:49.626  5870  5870 D HealthService: Received start request. Starting profile...
,11-25 07:45:49.627  5870  5870 I bt_bluedroid: get_profile_interface health
,11-25 07:45:49.628  5870  5870 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 07:45:49.629  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:45:49.630  5741  5741 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 07:45:49.630  5741  5741 D PanProfile: Bluetooth service connected
11-25 07:45:49.631  5870  5870 D PanService: Received start request. Starting profile...
11-25 07:45:49.631  5870  5870 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 07:45:49.631  5870  5870 I bt_bluedroid: get_profile_interface pan
11-25 07:45:49.631  5870  5886 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-25 07:45:49.633  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:45:49.635  5870  5870 D BluetoothMapService: Received start request. Starting profile...
,11-25 07:45:49.635  5870  5870 D BluetoothMapService: start()
,11-25 07:45:49.637  5870  5870 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-25 07:45:49.638  5870  5870 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 07:45:49.638  5870  5870 D BluetoothMapAppObserver: createReceiver()
11-25 07:45:49.639  5870  5870 D BluetoothMapAppObserver: initObservers()
11-25 07:45:49.639  5870  5870 D BluetoothMapAppObserver: getEnabledAccountItems()
11-25 07:45:49.639  5741  5741 D BluetoothMap: Proxy object connected
11-25 07:45:49.639  5741  5741 D MapProfile: Bluetooth service connected
11-25 07:45:49.639  5741  5741 D BluetoothMap: getConnectedDevices()
11-25 07:45:49.640  5741  5741 D BluetoothMap: Bluetooth is Not enabled
,11-25 07:45:49.645  5870  5870 V SapService: SapBinder()
,11-25 07:45:49.645  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:45:49.645  5870  5870 D SapService: Received start request. Starting profile...
11-25 07:45:49.646  5870  5870 V SapService: start()
,11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isTurningOn()=true
11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isTurningOn()=true
11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:49.647  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:49.647  5870  5898 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isTurningOff()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isTurningOn()=true
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isTurningOff()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isTurningOn()=true
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isTurningOn()=true
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:49.648  5870  5870 V BluetoothAdapterState: isTurningOff()=false
11-25 07:45:49.649  5870  5870 V BluetoothAdapterState: isTurningOn()=true
11-25 07:45:49.649  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:49.649  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:49.649  5870  5870 V BluetoothAdapterState: isTurningOff()=false
11-25 07:45:49.650  5870  5870 V BluetoothAdapterState: isTurningOn()=true
11-25 07:45:49.650  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:49.650  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:49.650  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-25 07:45:49.650  5870  5882 D BluetoothAdapterProperties: ScanMode =  20
11-25 07:45:49.650  5870  5882 D BluetoothAdapterProperties: State =  11
11-25 07:45:49.652  5870  5886 D BluetoothAdapterProperties: Scan Mode:21
11-25 07:45:49.652  5870  5882 D BluetoothAdapterProperties: Setting state to 12
11-25 07:45:49.652  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 07:45:49.652  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 07:45:49.652  5870  5886 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 07:45:49.653  3197  3210 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:45:49.653  5870  5882 I BluetoothAdapterState: Entering OnState
,11-25 07:45:49.654  3197  4046 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 07:45:49.655  3197  3197 D BluetoothMap: Proxy object connected
,11-25 07:45:49.656  3197  3197 D MapProfile: Bluetooth service connected
11-25 07:45:49.656  3197  3197 D BluetoothMap: getConnectedDevices()
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:49.656  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:45:49.657   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:45:49.657  3197  5686 D BluetoothPbap: onBluetoothStateChange: up=true
,11-25 07:45:49.658  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:45:49.659  3883  3910 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:45:49.659   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:45:49.659  5741  5759 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 07:45:49.660  5741  5758 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-25 07:45:49.660  5741  5759 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 07:45:49.661  3197  3210 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 07:45:49.662  3197  3197 D BluetoothInputDevice: Proxy object connected
11-25 07:45:49.663  3197  3197 D HidProfile: Bluetooth service connected
11-25 07:45:49.663  3197  3213 D BluetoothPan: onBluetoothStateChange on: true
,11-25 07:45:49.663  5870  5870 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 07:45:49.664  5870  5870 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 07:45:49.664  3197  3210 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:45:49.665  3197  3197 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 07:45:49.665  3197  3197 D PanProfile: Bluetooth service connected
,11-25 07:45:49.665  5870  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:45:49.666   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 07:45:49.666  5741  5758 D BluetoothPan: onBluetoothStateChange on: true
11-25 07:45:49.666   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:45:49.667  5870  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:45:49.668   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 07:45:49.669  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-25 07:45:49.670  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:49.671  5870  5870 D ObexServerSockets: Succeed to create listening sockets 
11-25 07:45:49.671  5870  5870 D ObexServerSockets0: startAccept()
11-25 07:45:49.671  5870  5870 D ObexServerSockets0: prepareForNewConnect()
,11-25 07:45:49.671  5741  5741 D LocalBluetoothProfileManager: Adding local A2DP profile
11-25 07:45:49.673  5870  5870 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-25 07:45:49.673  5870  5870 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 07:45:49.674  5870  5908 D ObexServerSockets0: Accepting socket connection...
11-25 07:45:49.674  5870  5909 D ObexServerSockets0: Accepting socket connection...
11-25 07:45:49.674   929   929 D BluetoothA2dp: Proxy object connected
11-25 07:45:49.674  5870  5870 D BluetoothMapService: onReceive
11-25 07:45:49.674  5870  5870 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-25 07:45:49.675  5870  5870 D BluetoothMapService: STATE_ON
,11-25 07:45:49.675  3197  3197 D BluetoothA2dp: Proxy object connected
,11-25 07:45:49.677  5870  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:45:49.678  5870  5910 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 07:45:49.678  5870  5910 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 07:45:49.678  5741  5741 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-25 07:45:49.684  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 07:45:49.686  5741  5741 D BluetoothA2dp: Proxy object connected
11-25 07:45:49.691  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:45:49.691  5741  5741 D DockEventReceiver: finishStartingService: stopping service
,11-25 07:45:49.697  3197  3197 D BluetoothPbap: Proxy object connected
,11-25 07:45:49.697  3197  3197 D PbapServerProfile: Bluetooth service connected
11-25 07:45:49.697  5741  5741 D BluetoothPbap: Proxy object connected
11-25 07:45:49.698  5741  5741 D PbapServerProfile: Bluetooth service connected
11-25 07:45:49.698  5870  5870 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 07:45:49.698  5870  5870 D ObexServerSockets0: prepareForNewConnect()
,11-25 07:45:49.706  5870  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:45:49.719  5870  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:45:49.720  5870  5918 I BtOppRfcommListener: Accept thread started.
,11-25 07:45:49.755   929   929 D BluetoothHeadset: Proxy object connected
,11-25 07:45:49.755  3883  4088 D BluetoothHeadset: Proxy object connected
11-25 07:45:49.755   929   929 D BluetoothHeadset: Proxy object connected
11-25 07:45:49.755   929   929 D BluetoothHeadset: Proxy object connected
11-25 07:45:49.756  3197  5686 D BluetoothHeadset: Proxy object connected
11-25 07:45:49.756  3197  3197 D HeadsetProfile: Bluetooth service connected
,11-25 07:45:49.757   929   946 D BluetoothHeadset: Proxy object connected
,11-25 07:45:49.760  3883  3905 D BluetoothHeadset: Proxy object connected
,11-25 07:45:49.761   929   946 D BluetoothHeadset: Proxy object connected
,11-25 07:45:49.767   929   946 D BluetoothHeadset: Proxy object connected
,11-25 07:45:49.780  5741  5758 D BluetoothHeadset: Proxy object connected
,11-25 07:45:49.781  5741  5741 D HeadsetProfile: Bluetooth service connected
,11-25 07:45:51.355   929  3057 D ConnectivityService: handlePromptUnvalidated 101
,11-25 07:45:53.615  5870  5882 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 07:45:53.616  5870  5882 D BluetoothAdapterProperties: Setting state to 13
,11-25 07:45:53.616  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 07:45:53.617  5870  5882 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 07:45:53.618  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:45:53.621  5870  5886 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:45:53.621  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 07:45:53.624  5870  5870 D BluetoothMapService: onReceive
11-25 07:45:53.624  5870  5870 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-25 07:45:53.624  5870  5870 D BluetoothMapService: STATE_TURNING_OFF
11-25 07:45:53.625  5870  5870 D BluetoothMapService: MAP Service closeService in
11-25 07:45:53.625  5870  5870 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 07:45:53.625  5870  5870 D ObexServerSockets0: shutdown(block = true)
11-25 07:45:53.627  5870  5870 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 07:45:53.627  5870  5870 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 07:45:53.627  5870  5895 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 07:45:53.627  5870  5908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-25 07:45:53.629  5870  5909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 07:45:53.631  5870  5870 I BtOppRfcommListener: stopping Accept Thread
11-25 07:45:53.632  5870  5918 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 07:45:53.633  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:45:53.633  5687  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:45:53.634  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:45:53.634  5870  5918 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 07:45:53.636  5687  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:45:53.636  5687  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 07:45:53.638  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:45:53.641  5870  5870 D HeadsetService: Received stop request...Stopping profile...
,11-25 07:45:53.642  5741  5741 D DockEventReceiver: finishStartingService: stopping service
11-25 07:45:53.643   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:53.643  3883  3910 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:53.644  5870  5870 D A2dpService: Received stop request...Stopping profile...
11-25 07:45:53.644  5741  5758 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:53.644   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:53.644   929   929 D BluetoothHeadset: Proxy object disconnected
,11-25 07:45:53.644  5870  5901 D A2dpStateMachine: Exit Disconnected: -1
11-25 07:45:53.645  3197  5686 D BluetoothHeadset: Proxy object disconnected
11-25 07:45:53.645  5741  5741 D HeadsetProfile: Bluetooth service disconnected
11-25 07:45:53.646   929   929 D BluetoothA2dp: Proxy object disconnected
11-25 07:45:53.646  5741  5741 D BluetoothA2dp: Proxy object disconnected
11-25 07:45:53.646  5870  5870 D HidService: Received stop request...Stopping profile...
11-25 07:45:53.647  5870  5870 D HidService: Stopping Bluetooth HidService
11-25 07:45:53.648  5741  5741 D BluetoothInputDevice: Proxy object disconnected
,11-25 07:45:53.648  5741  5741 D HidProfile: Bluetooth service disconnected
,11-25 07:45:53.648  5870  5870 D HealthService: Received stop request...Stopping profile...
,11-25 07:45:53.651  5870  5870 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:53.652  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:53.652  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:53.652  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:53.652  5870  5870 D PanService: Received stop request...Stopping profile...
,11-25 07:45:53.653  3197  3197 D HeadsetProfile: Bluetooth service disconnected
11-25 07:45:53.654  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:45:53.655  5741  5741 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-25 07:45:53.655  5741  5741 D PanProfile: Bluetooth service disconnected
,11-25 07:45:53.654  3197  3197 D BluetoothA2dp: Proxy object disconnected
11-25 07:45:53.656  5870  5870 D BluetoothMapService: Received stop request...Stopping profile...
11-25 07:45:53.662  5870  5870 D BluetoothMapService: stop()
11-25 07:45:53.662  3197  3197 D BluetoothInputDevice: Proxy object disconnected
,11-25 07:45:53.662  3197  3197 D HidProfile: Bluetooth service disconnected
11-25 07:45:53.662  3197  3197 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 07:45:53.662  3197  3197 D PanProfile: Bluetooth service disconnected
11-25 07:45:53.662  5870  5870 D BluetoothMapAppObserver: deinitObservers()
,11-25 07:45:53.663  5870  5870 D BluetoothMapAppObserver: removeReceiver()
11-25 07:45:53.664  3197  3197 D BluetoothMap: Proxy object disconnected
,11-25 07:45:53.664  3197  3197 D MapProfile: Bluetooth service disconnected
11-25 07:45:53.664  5741  5741 D BluetoothMap: Proxy object disconnected
11-25 07:45:53.664  5741  5741 D MapProfile: Bluetooth service disconnected
,11-25 07:45:53.665  5870  5870 D SapService: Received stop request...Stopping profile...
11-25 07:45:53.665  5870  5870 V SapService: stop()
11-25 07:45:53.667  5870  5870 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 07:45:53.667  5870  5870 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 07:45:53.667  5870  5870 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:53.667  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:53.667  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:53.667  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:53.668  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:53.669  5870  5870 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 07:45:53.669  5870  5870 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 07:45:53.669  5870  5870 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 07:45:53.669  5870  5870 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-25 07:45:53.670  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 07:45:53.670  5870  5893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:53.670  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 07:45:53.670  5870  5893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:53.670  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 07:45:53.670  5870  5893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:53.670  5870  5886 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 07:45:53.671  5870  5886 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 07:45:53.671  5870  5893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:53.671  5870  5893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:53.671  5870  5893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 07:45:53.671  5870  5893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 07:45:53.671  5870  5893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 07:45:53.671  5870  5893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 07:45:53.671  3197  3197 D BluetoothPbap: Proxy object disconnected
11-25 07:45:53.671  5741  5741 D BluetoothPbap: Proxy object disconnected
11-25 07:45:53.671  3197  3197 D PbapServerProfile: Bluetooth service disconnected
11-25 07:45:53.671  5741  5741 D PbapServerProfile: Bluetooth service disconnected
11-25 07:45:53.671  5870  5870 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:53.671  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:53.672  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 07:45:53.672  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:53.672  5870  5870 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 07:45:53.672  5870  5870 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 07:45:53.673  5870  5870 D BluetoothMapService: MAP Service closeService in
11-25 07:45:53.673  5870  5870 V BluetoothAdapterState: isTurningOff()=true
,11-25 07:45:53.673  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:53.673  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:53.673  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:53.674  5870  5870 D BluetoothMapService: cleanup()
11-25 07:45:53.674  5870  5870 D BluetoothMapService: MAP Service closeService in
11-25 07:45:53.674  5870  5870 V BluetoothAdapterState: isTurningOff()=true
11-25 07:45:53.674  5870  5870 V BluetoothAdapterState: isTurningOn()=false
,11-25 07:45:53.674  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:53.674  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:45:53.674  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 07:45:53.674  5870  5882 D BluetoothAdapterProperties: Setting state to 15
11-25 07:45:53.674  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 07:45:53.675  5870  5882 I BluetoothAdapterState: Entering BleOnState
,11-25 07:45:53.678  3197  5686 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 07:45:53.678  5741  5759 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-25 07:45:53.679  3197  3210 D BluetoothMap: onBluetoothStateChange: up=false
11-25 07:45:53.679   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:53.679  3197  4046 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 07:45:53.680  3883  4088 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:53.680   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 07:45:53.680  5741  5758 D BluetoothMap: onBluetoothStateChange: up=false
11-25 07:45:53.681  5741  5759 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 07:45:53.682  5741  5758 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 07:45:53.682  3197  3213 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 07:45:53.683  3197  5686 D BluetoothPan: onBluetoothStateChange on: false
11-25 07:45:53.683  5741  5759 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:53.684  3197  3210 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:45:53.684   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:45:53.684  5741  5758 D BluetoothPan: onBluetoothStateChange on: false
11-25 07:45:53.685   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:45:53.685  5870  5882 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 07:45:53.686  5870  5882 D BluetoothAdapterProperties: Setting state to 16
11-25 07:45:53.686  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 07:45:53.686  5870  5882 D BluetoothAdapterProperties: onBleDisable
11-25 07:45:53.686  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
11-25 07:45:53.686  5870  5883 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 07:45:53.688  5870  5886 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:45:53.688  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:45:53.689  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:45:53.689  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:45:53.690  5870  5893 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 07:45:53.690  5870  5893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:45:53.693  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 07:45:53.699  5741  5741 D DockEventReceiver: finishStartingService: stopping service
,11-25 07:45:53.898  5870  5886 I bt_hci  : shut_down
,11-25 07:45:53.903  5870  5890 D bt_hwcfg: hw_epilog_process
11-25 07:45:53.903  5870  5890 I bt_vendor: low_power_mode_cb
,11-25 07:45:53.905  5870  5890 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 07:45:53.905  5870  5890 I bt_vendor: epilog_cb
11-25 07:45:53.905  5870  5890 I bt_hci  : epilog_finished_callback
,11-25 07:45:53.907  5870  5886 I bt_hci_h4: hal_close
,11-25 07:45:53.908  5870  5886 I bt_userial_vendor: device fd = 54 close
,11-25 07:45:53.964   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:54.018  5870  5883 D bt_stack_manager: event_shut_down_stack finished.
,11-25 07:45:54.019  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 07:45:54.024  5870  5882 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-25 07:45:54.024  5870  5870 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 07:45:54.025  5870  5870 D BtGatt.GattService: Received stop request...Stopping profile...
,11-25 07:45:54.025  5870  5870 D BtGatt.GattService: stop()
,11-25 07:45:54.026  5870  5870 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 07:45:54.030  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:45:54.030  5870  5870 V BluetoothAdapterState: isTurningOn()=false
11-25 07:45:54.031  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:45:54.031  5870  5870 V BluetoothAdapterState: isBleTurningOff()=true
,11-25 07:45:54.031  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-25 07:45:54.032  5870  5882 D BluetoothAdapterProperties: Setting state to 10
,11-25 07:45:54.032  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 07:45:54.034  5870  5882 I BluetoothAdapterState: Entering OffState
11-25 07:45:54.034   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 07:45:54.051  5870  5870 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 07:45:54.052  5870  5870 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 07:45:54.052  5870  5883 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 07:45:54.054  5870  5870 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-25 07:45:54.059  5870  5870 I art     : System.exit called, status: 0
,11-25 07:45:54.060  5870  5870 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 07:45:54.094   929  3653 I ActivityManager: Process com.android.bluetooth (pid 5870) has died
,11-25 07:45:54.964   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:55.965   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:56.966   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:57.967   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:45:58.612  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:45:58.613  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 07:45:58.618  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:58.619  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2cbbf4 removed from the list
11-25 07:45:58.619  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:58.623  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:45:58.623  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d03b63 added. We now have 4 listener(s)
11-25 07:45:58.624  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:45:58.625  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:45:58.625  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d03b63 removed from the list
11-25 07:45:58.625  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:45:58.627  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:45:58.628  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@653a360 added. We now have 4 listener(s)
11-25 07:45:58.628  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:45:58.968   601   601 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 07:46:03.637  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:46:03.672   929   946 I ActivityManager: Start proc 5926:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 07:46:03.748  5926  5926 D AdapterServiceConfig: Adding HeadsetService
,11-25 07:46:03.748  5926  5926 D AdapterServiceConfig: Adding A2dpService
11-25 07:46:03.748  5926  5926 D AdapterServiceConfig: Adding HidService
11-25 07:46:03.748  5926  5926 D AdapterServiceConfig: Adding HealthService
11-25 07:46:03.748  5926  5926 D AdapterServiceConfig: Adding PanService
11-25 07:46:03.748  5926  5926 D AdapterServiceConfig: Adding GattService
11-25 07:46:03.749  5926  5926 D AdapterServiceConfig: Adding BluetoothMapService
,11-25 07:46:03.749  5926  5926 D AdapterServiceConfig: Adding SapService
,11-25 07:46:03.759   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8c3ad03:true
,11-25 07:46:03.760  5926  5926 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 07:46:03.762  5926  5926 I bt_bluedroid: init
,11-25 07:46:03.762  5926  5938 I BluetoothAdapterState: Entering OffState
,11-25 07:46:03.764  5926  5939 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 07:46:03.765  5926  5939 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 07:46:03.765  5926  5939 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 07:46:03.765  5926  5939 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-25 07:46:03.765  5926  5926 I bt_bluedroid: get_profile_interface socket
,11-25 07:46:03.767  5926  5942 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 07:46:03.767  5926  5926 I bt_bluedroid: get_profile_interface sdp
,11-25 07:46:03.769  5926  5942 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:46:03.772  5926  5937 I bt_bluedroid: config_hci_snoop_log
,11-25 07:46:03.773   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 07:46:03.776  5926  5938 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 07:46:03.777  5926  5938 D BluetoothAdapterProperties: Setting state to 14
11-25 07:46:03.777  5926  5938 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 07:46:03.778  5926  5938 D BluetoothBondStateMachine: make
,11-25 07:46:03.780  5926  5943 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 07:46:03.783  5926  5938 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:46:03.784  5926  5926 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 07:46:03.786  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:46:03.787  5926  5926 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 07:46:03.787  5926  5926 D BtGatt.GattService: Received start request. Starting profile...
11-25 07:46:03.787  5926  5926 D BtGatt.GattService: start()
11-25 07:46:03.788  5926  5926 I bt_bluedroid: get_profile_interface gatt
,11-25 07:46:03.788  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:46:03.789  5926  5926 D BtGatt.AdvertiseManager: advertise manager created
,11-25 07:46:03.793  5926  5926 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:46:03.793  5926  5926 V BluetoothAdapterState: isTurningOn()=false
11-25 07:46:03.794  5926  5926 V BluetoothAdapterState: isBleTurningOn()=true
11-25 07:46:03.794  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:46:03.794  5926  5938 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 07:46:03.795  5926  5938 I bt_bluedroid: bt_bluedroid
,11-25 07:46:03.795  5926  5939 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 07:46:03.796  5926  5939 I bt_hci  : start_up
,11-25 07:46:03.802  5926  5939 I bt_vendor: alloc value 0xf4199871
11-25 07:46:03.802  5926  5939 I bt_vendor: init
11-25 07:46:03.802  5926  5939 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 07:46:03.802  5926  5939 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 07:46:03.914  5926  5939 D bt_hci  : start_up starting async portion
,11-25 07:46:03.915  5926  5946 I bt_hci  : event_finish_startup
11-25 07:46:03.915  5926  5946 I bt_hci_h4: hal_open
11-25 07:46:03.915  5926  5946 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-25 07:46:03.914  5947  5947 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:46:03.919  5926  5946 I bt_userial_vendor: device fd = 54 open
,11-25 07:46:03.935  5926  5946 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:46:03.939  5926  5946 D bt_hwcfg: Chipset BCM4358A3
,11-25 07:46:03.939  5926  5946 D bt_hwcfg: Target name = [BCM4358A3]
11-25 07:46:03.940  5926  5946 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 07:46:04.463  5926  5946 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 07:46:04.464  5926  5946 D bt_hwcfg: Settlement delay -- 100 ms
11-25 07:46:04.464  5926  5946 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 07:46:04.598  5926  5946 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:46:04.598  5926  5946 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-25 07:46:04.600  5926  5946 I bt_hwcfg: vendor lib fwcfg completed
11-25 07:46:04.601  5926  5946 I bt_vendor: firmware callback
11-25 07:46:04.601  5926  5946 I bt_hci  : firmware_config_callback
,11-25 07:46:04.609  5926  5949 I bt_btu  : btu_task pending for preload complete event
11-25 07:46:04.609  5926  5949 I bt_btu_task: Bluetooth chip preload is complete
11-25 07:46:04.609  5926  5949 I bt_btu  : btu_task received preload complete event
,11-25 07:46:04.617  5926  5949 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 07:46:04.617  5926  5949 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 07:46:04.617  5926  5949 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 07:46:04.617  5926  5949 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_BTM
,11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 07:46:04.618  5926  5949 I         : BTE_InitTraceLevels -- TRC_SMP
,11-25 07:46:04.619  5926  5949 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 07:46:04.619  5926  5949 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 07:46:04.722  5926  5949 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4117549
,11-25 07:46:04.722  5926  5949 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4117549 
,11-25 07:46:04.740  5926  5942 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 07:46:04.742  5926  5942 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 07:46:04.742  5926  5942 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-25 07:46:04.745  5926  5942 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:46:04.747  5926  5942 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:46:04.748  5926  5942 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 07:46:04.748  5926  5942 D bt_hci  : do_postload posting postload work item
11-25 07:46:04.748  5926  5946 I bt_hci  : event_postload
11-25 07:46:04.748  5926  5946 I bt_vendor: sco_config_cb
11-25 07:46:04.748  5926  5946 I bt_hci  : sco_config_callback postload finished.
11-25 07:46:04.751  5926  5942 D bt_bte_conf: Device ID record 1 : primary
,11-25 07:46:04.751  5926  5942 D bt_bte_conf:   vendorId            = 000f
11-25 07:46:04.752  5926  5942 D bt_bte_conf:   vendorIdSource      = 0001
11-25 07:46:04.752  5926  5942 D bt_bte_conf:   product             = 1200
,11-25 07:46:04.752  5926  5942 D bt_bte_conf:   version             = 1436
,11-25 07:46:04.752  5926  5942 D bt_bte_conf:   clientExecutableURL = 
11-25 07:46:04.752  5926  5942 D bt_bte_conf:   serviceDescription  = 
11-25 07:46:04.752  5926  5942 D bt_bte_conf:   documentationURL    = 
11-25 07:46:04.752  5926  5942 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-25 07:46:04.752  5926  5939 D bt_stack_manager: event_start_up_stack finished
11-25 07:46:04.753  5926  5938 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 07:46:04.754  5926  5938 D BluetoothAdapterProperties: Setting state to 15
11-25 07:46:04.754  5926  5938 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 07:46:04.755  5926  5938 I BluetoothAdapterState: Entering BleOnState
11-25 07:46:04.756  5926  5946 I bt_vendor: low_power_mode_cb
,11-25 07:46:04.760  5926  5938 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 07:46:04.760  5926  5938 D BluetoothAdapterProperties: Setting state to 11
,11-25 07:46:04.761  5926  5938 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 07:46:04.771  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:46:04.771  5926  5926 D HeadsetService: Received start request. Starting profile...
,11-25 07:46:04.778  5926  5926 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-25 07:46:04.778  5926  5926 D HeadsetStateMachine: make
,11-25 07:46:04.783  5926  5938 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:46:04.787  5926  5926 D HeadsetStateMachine: max_hf_connections = 1
,11-25 07:46:04.787  5926  5926 I bt_bluedroid: get_profile_interface handsfree
11-25 07:46:04.788  5926  5942 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-25 07:46:04.788  5926  5942 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-25 07:46:04.790  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:46:04.791  5926  5926 D A2dpService: Received start request. Starting profile...
,11-25 07:46:04.792  5926  5926 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 07:46:04.792  5926  5926 I bt_bluedroid: get_profile_interface avrcp
,11-25 07:46:04.798  5926  5926 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-25 07:46:04.798  5926  5926 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 07:46:04.798  5926  5926 D A2dpStateMachine: make
,11-25 07:46:04.799  5926  5926 I bt_bluedroid: get_profile_interface a2dp
,11-25 07:46:04.800  5926  5942 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 07:46:04.802  5926  5957 D A2dpStateMachine: Enter Disconnected: -2
,11-25 07:46:04.802  5926  5926 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 07:46:04.803  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:46:04.804  5926  5926 D HidService: Received start request. Starting profile...
11-25 07:46:04.804  5926  5926 I bt_bluedroid: get_profile_interface hidhost
11-25 07:46:04.804  5926  5926 D HidService: setHidService(): set to: null
11-25 07:46:04.805  5926  5942 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40f856d
11-25 07:46:04.805  5926  5942 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-25 07:46:04.806  5926  5926 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 07:46:04.807  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:46:04.808  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 07:46:04.808  5926  5926 D HealthService: Received start request. Starting profile...
,11-25 07:46:04.809  5926  5926 I bt_bluedroid: get_profile_interface health
11-25 07:46:04.810  5926  5926 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 07:46:04.811  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:46:04.812  5926  5926 D PanService: Received start request. Starting profile...
11-25 07:46:04.812  5926  5926 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 07:46:04.812  5926  5926 I bt_bluedroid: get_profile_interface pan
,11-25 07:46:04.812  5926  5942 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-25 07:46:04.814  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:46:04.815  5926  5926 D BluetoothMapService: Received start request. Starting profile...
11-25 07:46:04.815  5926  5926 D BluetoothMapService: start()
,11-25 07:46:04.818  5926  5926 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 07:46:04.819  5926  5926 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 07:46:04.819  5926  5926 D BluetoothMapAppObserver: createReceiver()
,11-25 07:46:04.821  5926  5926 D BluetoothMapAppObserver: initObservers()
,11-25 07:46:04.821  5926  5926 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 07:46:04.828  5926  5926 V SapService: SapBinder()
,11-25 07:46:04.828  5926  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
,11-25 07:46:04.829  5926  5926 D SapService: Received start request. Starting profile...
11-25 07:46:04.829  5926  5926 V SapService: start()
,11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isTurningOff()=false
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isTurningOn()=true
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:46:04.833  5926  5955 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isTurningOff()=false
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isTurningOn()=true
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isTurningOn()=true
,11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:46:04.833  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isTurningOff()=false
11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isTurningOn()=true
11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isTurningOn()=true
11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:46:04.834  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:46:04.835  5926  5926 V BluetoothAdapterState: isTurningOff()=false
11-25 07:46:04.835  5926  5926 V BluetoothAdapterState: isTurningOn()=true
11-25 07:46:04.835  5926  5926 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:46:04.835  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:46:04.836  5926  5926 V BluetoothAdapterState: isTurningOff()=false
11-25 07:46:04.836  5926  5926 V BluetoothAdapterState: isTurningOn()=true
,11-25 07:46:04.836  5926  5926 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:46:04.836  5926  5926 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:46:04.836  5926  5938 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 07:46:04.836  5926  5938 D BluetoothAdapterProperties: ScanMode =  20
11-25 07:46:04.836  5926  5938 D BluetoothAdapterProperties: State =  11
11-25 07:46:04.837  5926  5942 D BluetoothAdapterProperties: Scan Mode:21
11-25 07:46:04.838  5926  5938 D BluetoothAdapterProperties: Setting state to 12
,11-25 07:46:04.838  5926  5938 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 07:46:04.838  5926  5942 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 07:46:04.838  3197  5686 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:46:04.839  5926  5938 I BluetoothAdapterState: Entering OnState
11-25 07:46:04.839  5741  5759 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 07:46:04.841  3197  4046 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 07:46:04.843   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:46:04.844  3197  3210 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 07:46:04.844  5741  5741 D BluetoothA2dp: Proxy object connected
11-25 07:46:04.844  3197  3197 D BluetoothMap: Proxy object connected
11-25 07:46:04.844  3197  3197 D MapProfile: Bluetooth service connected
11-25 07:46:04.844  3197  3197 D BluetoothMap: getConnectedDevices()
11-25 07:46:04.847  3883  3905 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:46:04.848   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 07:46:04.848  5741  5759 D BluetoothMap: onBluetoothStateChange: up=true
11-25 07:46:04.849  5926  5926 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 07:46:04.850  5926  5926 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-25 07:46:04.850  5741  5758 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 07:46:04.850  5741  5741 D BluetoothMap: Proxy object connected
11-25 07:46:04.850  5741  5741 D MapProfile: Bluetooth service connected
11-25 07:46:04.850  5741  5741 D BluetoothMap: getConnectedDevices()
11-25 07:46:04.851  5926  5926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:46:04.853  5926  5926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:46:04.854  5926  5926 D ObexServerSockets: Succeed to create listening sockets 
11-25 07:46:04.854  5926  5926 D ObexServerSockets0: startAccept()
11-25 07:46:04.854  5926  5926 D ObexServerSockets0: prepareForNewConnect()
11-25 07:46:04.856  5741  5759 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 07:46:04.856  5926  5926 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-25 07:46:04.857  5926  5926 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 07:46:04.857  5926  5964 D ObexServerSockets0: Accepting socket connection...
11-25 07:46:04.857  5926  5963 D ObexServerSockets0: Accepting socket connection...
,11-25 07:46:04.858  3197  4046 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 07:46:04.858  5741  5741 D BluetoothInputDevice: Proxy object connected
11-25 07:46:04.860  3197  3197 D BluetoothInputDevice: Proxy object connected
11-25 07:46:04.860  3197  3213 D BluetoothPan: onBluetoothStateChange on: true
11-25 07:46:04.860  5741  5741 D HidProfile: Bluetooth service connected
11-25 07:46:04.860  3197  3197 D HidProfile: Bluetooth service connected
,11-25 07:46:04.862  5741  5758 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 07:46:04.863  3197  3197 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 07:46:04.863  3197  3197 D PanProfile: Bluetooth service connected
11-25 07:46:04.863  3197  5686 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 07:46:04.866   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:46:04.866  3197  3197 D BluetoothA2dp: Proxy object connected
,11-25 07:46:04.866  5741  5962 D BluetoothPan: onBluetoothStateChange on: true
11-25 07:46:04.868   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:46:04.869   929   929 D BluetoothA2dp: Proxy object connected
11-25 07:46:04.869  5741  5741 D BluetoothPan: BluetoothPAN Proxy object connected
,11-25 07:46:04.869  5741  5741 D PanProfile: Bluetooth service connected
11-25 07:46:04.870  5926  5926 D BluetoothMapService: onReceive
11-25 07:46:04.870  5926  5926 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 07:46:04.871  5926  5926 D BluetoothMapService: STATE_ON
,11-25 07:46:04.873   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-25 07:46:04.874  5926  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:46:04.875  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:46:04.876  5926  5967 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 07:46:04.876  5926  5967 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 07:46:04.880  5741  5741 D DockEventReceiver: finishStartingService: stopping service
,11-25 07:46:04.881  3638  3638 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 07:46:04.888  5741  5741 D BluetoothPbap: Proxy object connected
11-25 07:46:04.888  5741  5741 D PbapServerProfile: Bluetooth service connected
,11-25 07:46:04.894  3197  3197 D BluetoothPbap: Proxy object connected
11-25 07:46:04.894  3197  3197 D PbapServerProfile: Bluetooth service connected
,11-25 07:46:04.896  5926  5926 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 07:46:04.896  5926  5926 D ObexServerSockets0: prepareForNewConnect()
,11-25 07:46:04.898  5926  5971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:46:04.914  5926  5975 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:46:04.915  5926  5975 I BtOppRfcommListener: Accept thread started.
,11-25 07:46:04.940   929   929 D BluetoothHeadset: Proxy object connected
,11-25 07:46:04.940  3883  3910 D BluetoothHeadset: Proxy object connected
,11-25 07:46:04.941  5741  5962 D BluetoothHeadset: Proxy object connected
11-25 07:46:04.941   929   929 D BluetoothHeadset: Proxy object connected
11-25 07:46:04.941   929   929 D BluetoothHeadset: Proxy object connected
11-25 07:46:04.941  3197  3210 D BluetoothHeadset: Proxy object connected
,11-25 07:46:04.941  3197  3197 D HeadsetProfile: Bluetooth service connected
,11-25 07:46:04.943  5741  5741 D HeadsetProfile: Bluetooth service connected
,11-25 07:46:04.944   929   946 D BluetoothHeadset: Proxy object connected
,11-25 07:46:04.948  3883  4088 D BluetoothHeadset: Proxy object connected
,11-25 07:46:04.948   929   946 D BluetoothHeadset: Proxy object connected
,11-25 07:46:04.963  5741  5759 D BluetoothHeadset: Proxy object connected
,11-25 07:46:04.963  5741  5741 D HeadsetProfile: Bluetooth service connected
11-25 07:46:04.965   929   946 D BluetoothHeadset: Proxy object connected
,11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:46:08.654  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 07:46:08.660  5687  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 07:46:08.661  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:46:08.661  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@653a360 removed from the list
11-25 07:46:08.661  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:46:08.663  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:46:08.665  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a40019 added. We now have 4 listener(s)
,11-25 07:46:08.665  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:46:08.669   929  3237 D WifiService: setWifiEnabled: false pid=5687, uid=10077
,11-25 07:46:08.669   929  3237 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:46:13.679  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:46:13.682   929  3920 D WifiService: setWifiEnabled: true pid=5687, uid=10077
,11-25 07:46:13.683   929  3920 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:46:13.690   509   928 D SoftapController: Softap fwReload - Ok
,11-25 07:46:13.695   509   928 D CommandListener: Setting iface cfg
,11-25 07:46:13.696   509   928 D CommandListener: Trying to bring down wlan0
11-25 07:46:13.698   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:46:13.704   929  3055 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 07:46:13.970   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:46:14.371   929  3055 D wifi    : set interface wlan0 flags (UP)
11-25 07:46:14.372   929  3055 I WifiHAL : Initializing wifi
,11-25 07:46:14.372   929  3055 I WifiHAL : Creating socket
11-25 07:46:14.378   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 07:46:14.382   929  3055 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 07:46:14.383   929  3055 D wifi    : Did set static halHandle = 0x7f5a3c4e40
11-25 07:46:14.383   929  3055 D wifi    : halHandle = 0x7f5a3c4e40, mVM = 0x7f76a8d140, mCls = 0x1017c2
11-25 07:46:14.383   929  3055 D wifi    : array field set
,11-25 07:46:14.383   929  3055 I WifiNative-HAL: interface[0] = wlan0
,11-25 07:46:14.388   929  5980 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546974748224
11-25 07:46:14.388   929  5980 D wifi    : waitForHalEvents called, vm = 0x7f76a8d140, obj = 0x1017c2, env = 0x7f5af1d300
,11-25 07:46:14.447  5981  5981 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 07:46:14.470  5981  5981 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:46:14.480  5981  5981 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:46:14.481  5981  5981 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 07:46:14.489   929  3055 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 07:46:14.504   929  3055 D WifiConfigStore: Loading config and enabling all networks 
,11-25 07:46:14.513   929  3055 D WifiConfigStore: loaded 0 passpoint configs
11-25 07:46:14.514   929  3055 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-25 07:46:14.514   929  3055 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-25 07:46:14.515   929  3055 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 07:46:14.516   929  3055 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 07:46:14.516   929  3055 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-25 07:46:14.516   929  3055 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-25 07:46:14.516   929  3055 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 07:46:14.519   929  3055 D WifiNative-HAL: Setting external_sim to 1
11-25 07:46:14.519  5081  5081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 07:46:14.519   929  3055 D wifi    : setting dfs flag to true, 0x7f5a410940
11-25 07:46:14.520   929  3055 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 07:46:14.520   929  3055 D wifi    : setting scan oui 0x7f5a410940
11-25 07:46:14.520   929  3055 D WifiHAL : Sending mac address OUI
,11-25 07:46:14.525   929  3055 E native  : do suspend false
,11-25 07:46:14.534   929  3055 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 07:46:14.534   509   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-25 07:46:14.535   929   929 D RttService: SCAN_AVAILABLE : 3
11-25 07:46:14.535   929  3163 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-25 07:46:14.535   509   928 D CommandListener: Setting iface cfg
,11-25 07:46:14.540   929  3054 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-25 07:46:14.540   929  3054 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 07:46:14.556   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164055 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-25 07:46:14.558   929  3054 D WifiNative-HAL: p2pGetDeviceAddress
11-25 07:46:14.558   929  3054 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-25 07:46:14.972   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:46:15.974   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:46:16.975   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:46:17.616  5981  5981 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:46:17.621  5981  5981 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:46:17.625  5981  5981 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:46:17.679   929  3055 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 07:46:17.681   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-25 07:46:17.681   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:46:17.694   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 07:46:17.727   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 07:46:17.729  5981  5981 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 07:46:17.975   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:46:18.704  5687  5734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 07:46:18.709  5687  5734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:46:18.710  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.710  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a40019 removed from the list
11-25 07:46:18.710  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:46:18.722  5687  5734 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-25 07:46:18.723  5687  5734 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-25 07:46:18.728  5687  5734 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@89d3e92 Bundle[{}]
,11-25 07:46:18.729  5687  5734 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 07:46:18.730  5687  5734 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-25 07:46:18.732  5687  5734 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-25 07:46:18.733  5687  5734 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-25 07:46:18.735  5687  5734 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-25 07:46:18.737  5687  5734 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-25 07:46:18.744  5687  5734 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-25 07:46:18.745  5687  5734 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-25 07:46:18.745  5687  5734 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-25 07:46:18.747  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.747  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f31d8de added. We now have 3 listener(s)
11-25 07:46:18.749  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:46:18.749  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 07:46:18.749  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.749  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.750  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2012abf added. We now have 4 listener(s)
11-25 07:46:18.750  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.751  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:46:18.752  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.753  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43f958c added. We now have 4 listener(s)
,11-25 07:46:18.755  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:46:18.755  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.756  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.756  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.756  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4eb84d5 added. We now have 5 listener(s)
11-25 07:46:18.756  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.756  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:46:18.756  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:46:18.756  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:46:18.756  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.756  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:46:18.756  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.757  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f31d8de removed from the list
11-25 07:46:18.757  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.757  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2012abf removed from the list
11-25 07:46:18.757  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:46:18.757  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.757  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.759  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.759  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.759  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.759  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.759  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.759  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.759  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2012abf not in the list
11-25 07:46:18.759  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.759  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.761  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.761  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.762  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.762  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.762  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:46:18.762  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.762  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4eb84d5 removed from the list
11-25 07:46:18.762  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:46:18.762  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:46:18.762  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.762  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43f958c removed from the list
11-25 07:46:18.763  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.763  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7ea4ea added. We now have 3 listener(s)
11-25 07:46:18.765  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:46:18.765  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.765  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.765  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.765  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f27b3db added. We now have 4 listener(s)
,11-25 07:46:18.765  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.766  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:46:18.768  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.768  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3167e78 added. We now have 4 listener(s)
11-25 07:46:18.770  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:46:18.770  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.770  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.770  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.770  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ec9951 added. We now have 5 listener(s)
11-25 07:46:18.770  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.770  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:46:18.771  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:46:18.771  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:46:18.771  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:46:18.771  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 07:46:18.772  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 07:46:18.777  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 07:46:18.777  5687  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:46:18.777  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:46:18.781  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.781  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:46:18.782  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 07:46:18.782  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:46:18.782  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:46:18.785  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.786  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:46:18.786  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:46:18.786  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:46:18.786  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:46:18.786  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.786  5687  5734 D BluetoothAdapter: STATE_ON
,11-25 07:46:18.789  5926  5936 D BtGatt.GattService: registerClient() - UUID=859f5b69-b567-4d86-8be0-a8d2a753cf9d
,11-25 07:46:18.790  5926  5942 D BtGatt.GattService: onClientRegistered() - UUID=859f5b69-b567-4d86-8be0-a8d2a753cf9d, clientIf=5
,11-25 07:46:18.791  5687  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 07:46:18.791  5926  5937 D BtGatt.GattService: start scan with filters
11-25 07:46:18.794  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:46:18.794  5926  5945 D BtGatt.ScanManager: handling starting scan
11-25 07:46:18.795  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.795  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:46:18.795  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.795  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 07:46:18.795  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:46:18.795  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.795  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:46:18.795  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:46:18.795  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.795  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.795  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.796  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.796  5926  5945 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8d38ec7
11-25 07:46:18.796  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:46:18.797  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.799  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.799  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:46:18.799  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.799  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.800  5687  5734 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 07:46:18.800  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 07:46:18.800  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 07:46:18.800  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:46:18.800  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:46:18.800  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:46:18.800  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 07:46:18.800  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.803  5926  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 07:46:18.803  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.803  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.803  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.803  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.803  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:46:18.803  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:46:18.803  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.804  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:46:18.804  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:46:18.804  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.804  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.804  5926  5945 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 07:46:18.804  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.804  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:46:18.804  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.805  5687  5734 D BluetoothAdapter: STATE_ON
,11-25 07:46:18.805  5926  5936 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:46:18.805  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:46:18.806  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:46:18.806  5926  5966 D BtGatt.GattService: stopScan() - queue size =1
11-25 07:46:18.807  5926  5965 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:46:18.807  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:46:18.807  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.807  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.808  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:46:18.808  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:46:18.809  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:46:18.809  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.810  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.810  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 07:46:18.810  5926  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:46:18.810  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.810  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.810  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.810  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:46:18.810  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:46:18.811  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:46:18.811  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.811  5926  5945 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:46:18.811  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:46:18.811  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:46:18.811  5926  5945 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 07:46:18.811  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.811  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.811  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.811  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:46:18.811  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.811  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.813  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.813  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.813  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.814  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:46:18.814  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:46:18.814  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:46:18.814  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.814  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:46:18.814  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.814  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7ea4ea removed from the list
11-25 07:46:18.814  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.814  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f27b3db removed from the list
11-25 07:46:18.814  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:46:18.814  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.815  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.815  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.815  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.815  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.815  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.815  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.815  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.816  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f27b3db not in the list
11-25 07:46:18.816  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.816  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.816  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.817  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.817  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.817  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 07:46:18.817  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.817  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.817  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ec9951 removed from the list
11-25 07:46:18.817  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.817  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:46:18.817  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.817  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3167e78 removed from the list
11-25 07:46:18.818  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.818  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1ae742 added. We now have 3 listener(s)
11-25 07:46:18.820  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:46:18.820  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.820  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 07:46:18.820  5926  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:46:18.820  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.820  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.820  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff6c353 added. We now have 4 listener(s)
11-25 07:46:18.820  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.821  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:46:18.822  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.822  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6a490 added. We now have 4 listener(s)
,11-25 07:46:18.824  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:46:18.824  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.824  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.824  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.824  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2182189 added. We now have 5 listener(s)
11-25 07:46:18.824  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.824  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:46:18.825  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 07:46:18.825  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:46:18.825  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:46:18.825  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:46:18.825  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 07:46:18.826  5926  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 07:46:18.826  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.827  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 07:46:18.828  5926  5945 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:46:18.829  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 07:46:18.829  5687  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:46:18.829  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:46:18.832  5926  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 07:46:18.833  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.833  5926  5942 E BtGatt.ContextMap: Context not found for ID 5
,11-25 07:46:18.834  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.834  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:46:18.834  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:46:18.835  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:46:18.835  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:46:18.838  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.838  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-25 07:46:18.838  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:46:18.838  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:46:18.838  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:46:18.838  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.839  5926  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 07:46:18.839  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.839  5926  5945 D BtGatt.ScanManager: stopping BLe Batch
11-25 07:46:18.839  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:46:18.841  5926  5954 D BtGatt.GattService: registerClient() - UUID=e4552900-7ebc-45c6-87c2-ffab806a6325
11-25 07:46:18.841  5926  5942 D BtGatt.GattService: onClientRegistered() - UUID=e4552900-7ebc-45c6-87c2-ffab806a6325, clientIf=5
11-25 07:46:18.842  5687  5698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 07:46:18.842  5926  5966 D BtGatt.GattService: start scan with filters
,11-25 07:46:18.845  5926  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 07:46:18.845  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.845  5926  5945 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:46:18.846  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 07:46:18.846  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.847  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-25 07:46:18.847  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.847  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 07:46:18.847  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:46:18.847  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.847  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:46:18.847  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:46:18.847  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.847  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.847  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.847  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.848  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-25 07:46:18.848  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.849  5926  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:46:18.849  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.850  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.850  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:46:18.850  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.850  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.850  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.850  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:46:18.850  5926  5945 D BtGatt.ScanManager: handling starting scan
11-25 07:46:18.850  5687  5734 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 07:46:18.850  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:46:18.850  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:46:18.850  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:46:18.850  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.851  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:46:18.851  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:46:18.851  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:46:18.851  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.851  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1ae742 removed from the list
11-25 07:46:18.851  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.851  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff6c353 removed from the list
11-25 07:46:18.851  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:46:18.851  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:46:18.851  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:46:18.851  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.851  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 07:46:18.851  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 07:46:18.851  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:46:18.851  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:46:18.851  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.852  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.852  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.852  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.852  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:46:18.853  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.853  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.853  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.853  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:46:18.853  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.853  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.853  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff6c353 not in the list
11-25 07:46:18.853  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:46:18.853  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.853  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:46:18.853  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:46:18.853  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.854  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.854  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.854  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:46:18.854  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.854  5687  5734 D BluetoothAdapter: STATE_ON
,11-25 07:46:18.854  5926  5965 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:46:18.855  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:46:18.855  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:46:18.856  5926  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:46:18.856  5926  5936 D BtGatt.GattService: stopScan() - queue size =1
11-25 07:46:18.856  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.856  5926  5945 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 07:46:18.856  5926  5954 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:46:18.856  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:46:18.856  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.856  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.857  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:46:18.857  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:46:18.858  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:46:18.858  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.859  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.859  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:46:18.859  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.859  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.859  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.859  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.860  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.860  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:46:18.860  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2182189 removed from the list
11-25 07:46:18.860  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.860  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 07:46:18.860  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:46:18.860  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:46:18.860  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.860  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.860  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6a490 removed from the list
11-25 07:46:18.860  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:46:18.860  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:46:18.860  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.860  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.860  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.860  5926  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:46:18.860  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:46:18.860  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.860  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.860  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.860  5926  5945 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:46:18.860  5926  5945 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 07:46:18.861  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.861  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1021c9a added. We now have 3 listener(s)
11-25 07:46:18.862  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.862  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.862  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.862  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:46:18.862  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.862  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.863  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.863  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb949cb added. We now have 4 listener(s)
11-25 07:46:18.863  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:46:18.867  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:46:18.868  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 07:46:18.868  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6275a8 added. We now have 4 listener(s)
,11-25 07:46:18.870  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:46:18.870  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.870  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.870  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:46:18.870  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b578c1 added. We now have 5 listener(s)
,11-25 07:46:18.870  5926  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:46:18.870  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.870  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.871  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:46:18.871  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:46:18.871  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:46:18.871  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:46:18.871  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:46:18.872  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 07:46:18.875  5926  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 07:46:18.875  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.875  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 07:46:18.875  5687  5734 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:46:18.875  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:46:18.876  5926  5945 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:46:18.879  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.879  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:46:18.880  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:46:18.880  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:46:18.880  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:46:18.881  5926  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:46:18.881  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.881  5926  5942 E BtGatt.ContextMap: Context not found for ID 5
,11-25 07:46:18.884  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.884  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:46:18.884  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:46:18.884  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:46:18.885  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:46:18.885  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.885  5687  5734 D BluetoothAdapter: STATE_ON
,11-25 07:46:18.887  5926  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:46:18.887  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.887  5926  5945 D BtGatt.ScanManager: stopping BLe Batch
11-25 07:46:18.887  5926  5954 D BtGatt.GattService: registerClient() - UUID=8155ed6c-4162-42ed-b4fb-305f749cd3c9
11-25 07:46:18.888  5926  5942 D BtGatt.GattService: onClientRegistered() - UUID=8155ed6c-4162-42ed-b4fb-305f749cd3c9, clientIf=5
,11-25 07:46:18.888  5687  5697 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 07:46:18.888  5926  5965 D BtGatt.GattService: start scan with filters
,11-25 07:46:18.892  5926  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 07:46:18.892  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:46:18.892  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.892  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.892  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:46:18.892  5926  5945 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:46:18.892  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.892  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 07:46:18.892  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:46:18.892  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.892  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:46:18.892  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:46:18.893  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.893  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.893  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.893  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.894  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:46:18.894  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.895  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.896  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:46:18.896  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.896  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.896  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.897  5926  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:46:18.897  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.898  5926  5945 D BtGatt.ScanManager: handling starting scan
11-25 07:46:18.898  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:46:18.898  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:46:18.898  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:46:18.898  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.898  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 07:46:18.899  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:46:18.899  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:46:18.899  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.899  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1021c9a removed from the list
11-25 07:46:18.899  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.899  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb949cb removed from the list
11-25 07:46:18.899  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:46:18.899  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:46:18.899  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:46:18.899  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.899  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-25 07:46:18.899  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 07:46:18.899  5687  5734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:46:18.899  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:46:18.899  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.899  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.899  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.899  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.899  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:46:18.900  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.900  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.900  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.900  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.900  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.900  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.900  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb949cb not in the list
11-25 07:46:18.900  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:46:18.900  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.900  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:46:18.900  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:46:18.900  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.901  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.901  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.901  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:46:18.901  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.901  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:46:18.901  5926  5937 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:46:18.902  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:46:18.902  5687  5734 D BluetoothAdapter: STATE_ON
11-25 07:46:18.902  5926  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:46:18.902  5926  5965 D BtGatt.GattService: stopScan() - queue size =1
11-25 07:46:18.902  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.903  5926  5945 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 07:46:18.903  5926  5954 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:46:18.903  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:46:18.903  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.903  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:46:18.903  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.903  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.904  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.904  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.904  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:46:18.904  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setS,tate: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.904  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.904  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.904  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:46:18.904  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:46:18.904  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:46:18.905  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.905  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.906  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:46:18.906  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.906  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.906  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.906  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.906  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.906  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:46:18.906  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b578c1 removed from the list
11-25 07:46:18.906  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:46:18.906  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:46:18.906  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:46:18.906  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.906  5687  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:46:18.906  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6275a8 removed from the list
11-25 07:46:18.906  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.906  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:46:18.906  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:46:18.906  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.906  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.906  5687  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 07:46:18.906  5687  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:46:18.907  5687  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.907  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.907  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.907  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3fa4f2 added. We now have 3 listener(s)
11-25 07:46:18.908  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.908  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.908  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:46:18.908  5687  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:46:18.908  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.908  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.908  5926  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:46:18.908  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:46:18.908  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.908  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@872743 added. We now have 4 listener(s)
11-25 07:46:18.908  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.908  5926  5945 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:46:18.908  5926  5945 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 07:46:18.909  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:46:18.910  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:46:18.910  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85451c0 added. We now have 4 listener(s)
11-25 07:46:18.911  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:46:18.911  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:46:18.911  5687  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:46:18.912  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:46:18.912  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74f7ef9 added. We now have 5 listener(s)
11-25 07:46:18.912  5687  5734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:46:18.912  5687  5734 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:46:18.912  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:46:18.912  5687  5734 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:46:18.912  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.912  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:46:18.912  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.912  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3fa4f2 removed from the list
11-25 07:46:18.912  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.912  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@872743 removed from the list
11-25 07:46:18.912  5687  5734 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:46:18.912  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.912  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.913  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.913  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.913  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.913  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.913  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.914  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.914  5687  5734 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@872743 not in the list
11-25 07:46:18.914  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.914  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.915  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 07:46:18.915  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.915  5687  5734 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 07:46:18.915  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:46:18.915  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:46:18.915  5687  5734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:46:18.915  5687  5734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74f7ef9 removed from the list
11-25 07:46:18.915  5687  5734 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:46:18.915  5687  5734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:46:18.915  5687  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:46:18.915  5687  5734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85451c0 removed from the list
11-25 07:46:18.916  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 07:46:18.916  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-25 07:46:18.916  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 07:46:18.916  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:46:18.916  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 07:46:18.916  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:46:18.917  5926  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:46:18.917  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.921  5926  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 07:46:18.921  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:46:18.922  5926  5945 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:46:18.926  5926  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 07:46:18.926  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.926  5926  5942 E BtGatt.ContextMap: Context not found for ID 5
,11-25 07:46:18.931  5926  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:46:18.931  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.931  5926  5945 D BtGatt.ScanManager: stopping BLe Batch
,11-25 07:46:18.936  5926  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 07:46:18.936  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:46:18.936  5926  5945 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:46:18.940  5926  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 07:46:18.940  5926  5942 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:46:18.976   601   601 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 07:46:19.092  5981  5981 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-25 07:46:19.312  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:46:19.361  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:46:19.407  5687  5687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:46:21.050  5687  5983 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 07:46:21.050  5687  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:46:21.861  5687  5983 W !!      : call onHalfStreamCopied
11-25 07:46:21.861  5687  5983 I testCopyDataAndClose: closing input stream
,11-25 07:46:22.151  5981  5981 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 07:46:22.223   929  3055 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-25 07:46:22.226   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 07:46:22.226   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:46:22.240   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 07:46:22.267   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 07:46:22.633  5687  5983 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 07:46:22.633  5687  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 07:46:22.634  5687  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 07:46:23.509  5981  5981 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-25 07:46:26.443  5687  5984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:26.443  5687  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:46:26.944  5981  5981 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 07:46:26.966  5981  5981 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:46:27.008   929  3055 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-25 07:46:27.010   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 07:46:27.010   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:46:27.026   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 07:46:27.063   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 07:46:28.318  5981  5981 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-25 07:46:28.442  5687  5734 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-25 07:46:28.442  5687  5734 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:46:28.442  5687  5734 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-25 07:46:28.506  5687  5984 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-25 07:46:28.506  5687  5984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:28.506  5687  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-25 07:46:28.557  5687  5985 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 07:46:28.557  5687  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 07:46:30.235  5687  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 07:46:32.166  5981  5981 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 07:46:32.228   929  3055 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 07:46:32.230   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 07:46:32.231   929  3055 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:46:32.247   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 07:46:32.273   929  3055 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 07:46:33.525  5981  5981 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,11-25 07:46:33.528  5981  5981 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
,11-25 07:46:33.530   929  3055 D WifiStateMachine: ConnectModeState SSID state=temp-disabled nid=0 [id=0 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED]
11-25 07:46:33.531   929  3055 E WifiConfigStore: SSID temp disabled for  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
,11-25 07:46:33.531   929  3055 E WifiConfigStore:  message=id=0 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
,11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-25 07:46:33.994  5687  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 07:46:33.995  5687  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 07:46:33.995  5687  5986 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-25 07:46:33.995  5687  5986 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 07:46:33.995  5687  5986 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:33.995  5687  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-25 07:46:33.997  5687  5734 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-25 07:46:33.999  5687  5987 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:33.999  5687  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:46:33.999  5687  5987 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
,11-25 07:46:34.000  5687  5987 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:34.000  5687  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-25 07:46:34.000  5687  5987 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-25 07:46:34.000  5687  5987 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:46:34.000  5687  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 07:46:34.003  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 07:46:34.003  5687  5734 I jxcore-log: 
11-25 07:46:34.003  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-25 07:46:34.003  5687  5734 I jxcore-log: 
11-25 07:46:34.003  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-25 07:46:34.003  5687  5734 I jxcore-log: 
,11-25 07:46:34.004  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 07:46:34.004  5687  5734 I jxcore-log: 
11-25 07:46:34.004  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG UnitTest_app: 'Total duration:  90922'
11-25 07:46:34.004  5687  5734 I jxcore-log: 
11-25 07:46:34.006  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 07:46:34.006  5687  5734 I jxcore-log: 
,11-25 07:46:34.009  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:46:34.009  5687  5734 I jxcore-log: 
11-25 07:46:34.010  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:46:34.010  5687  5734 I jxcore-log: 
11-25 07:46:34.010  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 07:46:34.010  5687  5734 I jxcore-log: 
11-25 07:46:34.011  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 07:46:34.011  5687  5734 I jxcore-log: 
11-25 07:46:34.011  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.011  5687  5734 I jxcore-log: 
11-25 07:46:34.011  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:46:34.011  5687  5734 I jxcore-log: 
11-25 07:46:34.011  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.011  5687  5734 I jxcore-log: 
,11-25 07:46:34.012  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:46:34.012  5687  5734 I jxcore-log: 
11-25 07:46:34.012  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:46:34.012  5687  5734 I jxcore-log: 
11-25 07:46:34.012  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 07:46:34.012  5687  5734 I jxcore-log: 
11-25 07:46:34.013  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 07:46:34.013  5687  5734 I jxcore-log: 
11-25 07:46:34.013  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.013  5687  5734 I jxcore-log: 
11-25 07:46:34.013  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:46:34.013  5687  5734 I jxcore-log: 
,11-25 07:46:34.013  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.013  5687  5734 I jxcore-log: 
11-25 07:46:34.013  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:46:34.013  5687  5734 I jxcore-log: 
11-25 07:46:34.014  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.014  5687  5734 I jxcore-log: 
11-25 07:46:34.014  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 07:46:34.014  5687  5734 I jxcore-log: 
11-25 07:46:34.014  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:46:34.014  5687  5734 I jxcore-log: 
,11-25 07:46:34.014  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 07:46:34.014  5687  5734 I jxcore-log: 
11-25 07:46:34.015  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 07:46:34.015  5687  5734 I jxcore-log: 
11-25 07:46:34.015  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:46:34.015  5687  5734 I jxcore-log: 
11-25 07:46:34.015  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 07:46:34.015  5687  5734 I jxcore-log: 
11-25 07:46:34.016  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 07:46:34.016  5687  5734 I jxcore-log: 
11-25 07:46:34.016  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 07:46:34.016  5687  5734 I jxcore-log: 
11-25 07:46:34.017  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 07:46:34.017  5687  5734 I jxcore-log: 
11-25 07:46:34.018  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 07:46:34.018  5687  5734 I jxcore-log: 
,11-25 07:46:34.018  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-25 07:46:34.018  5687  5734 I jxcore-log: 
11-25 07:46:34.018  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:46:34.018  5687  5734 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-25 07:46:34.018  5687  5734 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 07:46:34.018  5687  5734 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-25 07:46:34.019  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:46:34.019  5687  5734 I jxcore-log: 
11-25 07:46:34.019  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.019  5687  5734 I jxcore-log: 
11-25 07:46:34.019  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:46:34.019  5687  5734 I jxcore-log: 
11-25 07:46:34.019  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.019  5687  5734 I jxcore-log: 
11-25 07:46:34.019  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:46:34.019  5687  5734 I jxcore-log: 
11-25 07:46:34.020  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:46:34.020  5687  5734 I jxcore-log: 
,11-25 07:46:34.025  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 07:46:34.025  5687  5734 I jxcore-log: 
,11-25 07:46:34.025  5687  5734 I jxcore-log: 2016-11-25 12:46:34 - WARN testUtils: 'myNameCallback not set!'
11-25 07:46:34.025  5687  5734 I jxcore-log: 
,11-25 07:46:34.028  5687  5687 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-25 07:46:34.028  5687  5687 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-25 07:46:36.100  5687  5734 I jxcore-log: 2016-11-25 12:46:36 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 07:46:36.100  5687  5734 I jxcore-log: 
,11-25 07:46:36.102  5687  5734 I jxcore-log: 2016-11-25 12:46:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 07:46:36.102  5687  5734 I jxcore-log: 
,11-25 07:46:36.455  5687  5734 I jxcore-log: 2016-11-25 12:46:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 07:46:36.455  5687  5734 I jxcore-log: 
,11-25 07:46:36.467  5687  5734 I jxcore-log: 2016-11-25 12:46:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 07:46:36.467  5687  5734 I jxcore-log: 
,11-25 07:46:37.576  5687  5734 I jxcore-log: 2016-11-25 12:46:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 07:46:37.576  5687  5734 I jxcore-log: 
,11-25 07:46:37.770  5687  5734 I jxcore-log: 2016-11-25 12:46:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 07:46:37.770  5687  5734 I jxcore-log: 
,11-25 07:46:37.775  5687  5734 I jxcore-log: 2016-11-25 12:46:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 07:46:37.775  5687  5734 I jxcore-log: 
,11-25 07:46:37.780  5687  5734 I jxcore-log: 2016-11-25 12:46:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 07:46:37.780  5687  5734 I jxcore-log: 
,11-25 07:46:38.264  5687  5734 I jxcore-log: 2016-11-25 12:46:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 07:46:38.264  5687  5734 I jxcore-log: 
,11-25 07:46:38.309  5687  5734 I jxcore-log: 2016-11-25 12:46:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 07:46:38.309  5687  5734 I jxcore-log: 
,11-25 07:46:38.323  5687  5734 I jxcore-log: 2016-11-25 12:46:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 07:46:38.323  5687  5734 I jxcore-log: 
,11-25 07:46:38.327  5687  5734 I jxcore-log: 2016-11-25 12:46:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 07:46:38.327  5687  5734 I jxcore-log: 
,11-25 07:46:38.594  5687  5734 I jxcore-log: 2016-11-25 12:46:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 07:46:38.594  5687  5734 I jxcore-log: 
,11-25 07:46:38.719  5687  5734 I jxcore-log: 2016-11-25 12:46:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 07:46:38.719  5687  5734 I jxcore-log: 
,11-25 07:46:38.977   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:46:39.098  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 07:46:39.098  5687  5734 I jxcore-log: 
,11-25 07:46:39.106  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 07:46:39.106  5687  5734 I jxcore-log: 
,11-25 07:46:39.110  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 07:46:39.110  5687  5734 I jxcore-log: 
,11-25 07:46:39.115  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 07:46:39.115  5687  5734 I jxcore-log: 
,11-25 07:46:39.121  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 07:46:39.121  5687  5734 I jxcore-log: 
,11-25 07:46:39.150  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 07:46:39.150  5687  5734 I jxcore-log: 
,11-25 07:46:39.185  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 07:46:39.185  5687  5734 I jxcore-log: 
,11-25 07:46:39.191  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 07:46:39.191  5687  5734 I jxcore-log: 
,11-25 07:46:39.198  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 07:46:39.198  5687  5734 I jxcore-log: 
,11-25 07:46:39.213  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 07:46:39.213  5687  5734 I jxcore-log: 
,11-25 07:46:39.229  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 07:46:39.229  5687  5734 I jxcore-log: 
,11-25 07:46:39.235  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 07:46:39.235  5687  5734 I jxcore-log: 
,11-25 07:46:39.240  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 07:46:39.240  5687  5734 I jxcore-log: 
,11-25 07:46:39.253  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 07:46:39.253  5687  5734 I jxcore-log: 
,11-25 07:46:39.270  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 07:46:39.270  5687  5734 I jxcore-log: 
,11-25 07:46:39.285  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 07:46:39.285  5687  5734 I jxcore-log: 
,11-25 07:46:39.295  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 07:46:39.295  5687  5734 I jxcore-log: 
,11-25 07:46:39.308  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 07:46:39.308  5687  5734 I jxcore-log: 
,11-25 07:46:39.318  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 07:46:39.318  5687  5734 I jxcore-log: 
,11-25 07:46:39.332  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 07:46:39.332  5687  5734 I jxcore-log: 
,11-25 07:46:39.341  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 07:46:39.341  5687  5734 I jxcore-log: 
,11-25 07:46:39.348  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 07:46:39.348  5687  5734 I jxcore-log: 
,11-25 07:46:39.370  5687  5734 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 07:46:39.371  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 07:46:39.371  5687  5734 I jxcore-log: 
,11-25 07:46:39.402  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 07:46:39.402  5687  5734 I jxcore-log: 
,11-25 07:46:39.433  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 07:46:39.433  5687  5734 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 07:46:39.433  5687  5734 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 07:46:39.433  5687  5734 I jxcore-log: emit@events.js:82:1
11-25 07:46:39.433  5687  5734 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 07:46:39.433  5687  5734 I jxcore-log: emit@events.js:82:1''
11-25 07:46:39.433  5687  5734 I jxcore-log: 
,11-25 07:46:39.433  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - DEBUG CoordinatedClient: 'test client failed'
11-25 07:46:39.433  5687  5734 I jxcore-log: 
,11-25 07:46:39.439  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 07:46:39.439  5687  5734 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 07:46:39.439  5687  5734 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 07:46:39.439  5687  5734 I jxcore-log: emit@events.js:82:1
11-25 07:46:39.439  5687  5734 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 07:46:39.439  5687  5734 I jxcore-log: emit@events.js:82:1''
11-25 07:46:39.439  5687  5734 I jxcore-log: 
,11-25 07:46:39.439  5687  5734 I jxcore-log: 2016-11-25 12:46:39 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 07:46:39.439  5687  5734 I jxcore-log: 
,11-25 07:46:39.978   601   601 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:46:40.029  5988  5988 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 07:46:40.050  5988  5988 D AndroidRuntime: CheckJNI is OFF
,11-25 07:46:40.079  5988  5988 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 07:46:40.113  5988  5988 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 07:46:40.131  5988  5988 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 07:46:40.142   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-25 07:46:40.143   929   942 I ActivityManager: Killing 5687:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 07:46:40.237   929   939 D GraphicsStats: Buffer count: 2
,11-25 07:46:40.238   929  3056 D WifiService: Client connection lost with reason: 4
,11-25 07:46:40.238   929  3292 I WindowState: WIN DEATH: Window{a8bf636 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-25 07:46:40.284   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-25 07:46:40.286   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-25 07:46:40.287   929   942 E ActivityManager: Failure starting process com.test.thalitest
11-25 07:46:40.287   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-25 07:46:40.287   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.287   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.287   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 07:46:40.287   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-25 07:46:40.287   929   942 I ActivityManager:   Force finishing activity ActivityRecord{f6b220a u0 com.test.thalitest/.MainActivity t10}
,11-25 07:46:40.292   929   940 W ActivityManager: Spurious death for ProcessRecord{2ab6521 0:com.test.thalitest/u0a77}, curProc for 5687: null
,11-25 07:46:40.294   929   953 I art     : Starting a blocking GC Explicit
,11-25 07:46:40.302   929   947 W WindowManager: Attempted to add application window with unknown token Token{2b8ba7b ActivityRecord{f6b220a u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-25 07:46:40.303   929   947 W WindowManager: Token{2b8ba7b ActivityRecord{f6b220a u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{2b8ba7b ActivityRecord{f6b220a u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-25 07:46:40.303   929   947 W WindowManager: view not successfully added to wm, removing view
11-25 07:46:40.303   929   947 W WindowManager: Exception when adding starting window
11-25 07:46:40.303   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{8a50fa0 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-25 07:46:40.303   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-25 07:46:40.303   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-25 07:46:40.303   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-25 07:46:40.303   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-25 07:46:40.303   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-25 07:46:40.303   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.303   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.303   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 07:46:40.303   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-25 07:46:40.381   929   953 I art     : Explicit concurrent mark sweep GC freed 60675(4MB) AllocSpace objects, 28(1140KB) LOS objects, 33% free, 29MB/43MB, paused 1.601ms total 86.725ms
,11-25 07:46:40.400   929   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-25 07:46:40.403  5988  5988 I art     : System.exit called, status: 0
11-25 07:46:40.403  5988  5988 I AndroidRuntime: VM exiting with result code 0.
,11-25 07:46:40.418   929   953 I ActivityManager: Start proc 5998:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-25 07:46:40.418   929   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 07:46:40.429   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-25 07:46:40.437  3765  3765 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-25 07:46:40.441  5926  5926 D BluetoothMapAppObserver: onReceive
,11-25 07:46:40.441  5926  5926 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-25 07:46:40.445  4130  4268 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-25 07:46:40.450   929  3021 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-25 07:46:40.454  3765  6010 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 07:46:40.463  3765  6010 I Decoder : createOrResetDecoder
,11-25 07:46:40.494    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:46:40.497    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:46:40.507  3883  3883 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 07:46:40.507    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:46:40.519   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 07:46:40.521  3638  3638 I ConfigService: onCreate
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-25 07:46:40.528  3638  6016 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-25 07:46:40.528  3638  6016 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-25 07:46:40.531  3922  4012 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-25 07:46:40.531  3638  6016 W SQLiteOpenHelper: Opened config.db in read-only mode
11-25 07:46:40.532   929   941 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-25 07:46:40.532   929   941 E PackageManager: Failed to write settings, restoring backup
11-25 07:46:40.532   929   941 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-25 07:46:40.532   929   941 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-25 07:46:40.532   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-25 07:46:40.532   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-25 07:46:40.532   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-25 07:46:40.532   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.532   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.532   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 07:46:40.545   929  3920 I ActivityManager: Start proc 6017:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-25 07:46:40.546  3922  4012 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-25 07:46:40.546  3922  4012 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3922
11-25 07:46:40.546  3922  4012 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.546  3922  4012 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 07:46:40.552   929  3486 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 07:46:40.556   929  6022 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:46:40.556   929  6022 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:46:40.556   929  6022 E DropBoxManagerService: 	... 5 more
,11-25 07:46:40.556   929   942 E DropBoxManagerService: Can't write: system_server_wtf
11-25 07:46:40.556   929   942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-25 07:46:40.556   929   942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:46:40.556   929   942 E DropBoxManagerService: 	... 13 more
11-25 07:46:40.556  3922  4012 I Process : Sending signal. PID: 3922 SIG: 9
,11-25 07:46:40.558  3638  3638 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-25 07:46:40.559  3638  3638 D AndroidRuntime: Shutting down VM
,11-25 07:46:40.560  3638  3638 E AndroidRuntime: FATAL EXCEPTION: main
11-25 07:46:40.560  3638  3638 E AndroidRuntime: Process: com.google.process.gapps, PID: 3638
11-25 07:46:40.560  3638  3638 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-25 07:46:40.560  3638  3638 E AndroidRuntime: 	... 8 more
,11-25 07:46:40.564   929  6027 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:46:40.564   929  6027 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:46:40.564   929  6027 E DropBoxManagerService: 	... 5 more
,11-25 07:46:40.565  3638  3638 I Process : Sending signal. PID: 3638 SIG: 9
,11-25 07:46:40.572  3472  6013 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 07:46:40.585   929  3056 D WifiService: Client connection lost with reason: 4
,11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: Failed to get gconfig value
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: java.lang.NullPointerException: Attempt to invoke interface method 'java.lang.String com.google.android.gms.config.ConfigApi$Value.getAsString(java.lang.String)' on a null object reference
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at com.android.inputmethod.latin.GconfigFlagGetter.getInt(GconfigFlagGetter.java:83)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at com.android.inputmethod.latin.DecoderFlagGetter.getFlagValues(DecoderFlagGetter.java:67)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator.resetDecoderFlagValues(Delight3DictionaryFacilitator.java:94)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator.-wrap0(Delight3DictionaryFacilitator.java)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator$DecoderInitializer.run(Delight3DictionaryFacilitator.java:877)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at com.android.inputmethod.latin.utils.ExecutorUtils$RunnableChain.run(ExecutorUtils.java:148)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-25 07:46:40.588  3765  6010 W DecoderFlagGetter: 	at java.lang.Thread.run(Thread.java:818)
11-25 07:46:40.588  3765  6010 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-25 07:46:40.590   929  3920 I ActivityManager: Process com.google.process.gapps (pid 3638) has died
11-25 07:46:40.591   929  3920 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
11-25 07:46:40.591   929  3920 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 10999ms
11-25 07:46:40.591   929  3920 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
11-25 07:46:40.591   929  3920 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,11-25 07:46:40.615   929  3906 I ActivityManager: Start proc 6033:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,11-25 07:46:40.615  3472  3495 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj75C318962) - 
,11-25 07:46:40.660  6033  6033 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-25 07:46:40.661   929  3020 W InputDispatcher: channel 'e746f1f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-25 07:46:40.661   929  3020 E InputDispatcher: channel 'e746f1f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
11-25 07:46:40.661   929  3921 D GraphicsStats: Buffer count: 1
11-25 07:46:40.661   929  3928 I WindowState: WIN DEATH: Window{e746f1f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-25 07:46:40.662   929  3928 W InputDispatcher: Attempted to unregister already unregistered input channel 'e746f1f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-25 07:46:40.669  3472  3495 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-25 07:46:40.669  3472  3495 E AndroidRuntime: Process: android.process.acore, PID: 3472
11-25 07:46:40.669  3472  3495 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.669  3472  3495 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 07:46:40.675  6033  6033 I MultiDex: VM with version 2.1.0 has multidex support
11-25 07:46:40.672   929   939 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3922) has died
11-25 07:46:40.684  6033  6033 I MultiDex: install
11-25 07:46:40.684  6033  6033 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,11-25 07:46:40.684   929   939 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
11-25 07:46:40.686   929   939 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-25 07:46:40.691   929  6046 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:46:40.691   929  6046 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:46:40.691   929  6046 E DropBoxManagerService: 	... 5 more
,11-25 07:46:40.695  6033  6033 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm64
,11-25 07:46:40.700  6033  6033 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,11-25 07:46:40.702  6033  6033 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:46:40.702  6033  6033 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 07:46:40.703  6033  6033 D AndroidRuntime: Shutting down VM
11-25 07:46:40.704  6033  6033 E AndroidRuntime: FATAL EXCEPTION: main
11-25 07:46:40.704  6033  6033 E AndroidRuntime: Process: com.google.process.gapps, PID: 6033
11-25 07:46:40.704  6033  6033 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-25 07,:46:40.704  6033  6033 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 07:46:40.704  6033  6033 E AndroidRuntime: 	... 10 more
11-25 07:46:40.706   929   942 I ActivityManager: Start proc 6047:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 07:46:40.707  3472  3495 I Process : Sending signal. PID: 3472 SIG: 9
,11-25 07:46:40.709  6033  6033 I Process : Sending signal. PID: 6033 SIG: 9
,11-25 07:46:40.710   929  6052 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:46:40.710   929  6052 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:46:40.710   929  6052 E DropBoxManagerService: 	... 5 more
,11-25 07:46:40.743   929  3920 I ActivityManager: Process com.google.process.gapps (pid 6033) has died
11-25 07:46:40.743   929  3920 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{e3e0d2a u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
11-25 07:46:40.743   929  3920 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{c039ca8 u0 com.google.android.gms/.tapandpay.hce.service.TpHceService}
11-25 07:46:40.744   929  3920 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{be8d6eb u0 com.google.android.gms/.config.ConfigService}
11-25 07:46:40.744   929  3920 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{b08511f u0 com.google.android.gms/.gcm.GcmService}
,11-25 07:46:40.757  6047  6047 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:46:40.757  6047  6047 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 07:46:40.758  6047  6047 D AndroidRuntime: Shutting down VM
,11-25 07:46:40.764  6047  6047 E AndroidRuntime: FATAL EXCEPTION: main
11-25 07:46:40.764  6047  6047 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6047
11-25 07:46:40.764  6047  6047 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 07:46:40.764  6047  6047 E AndroidRuntime: 	... 10 more
11-25 07:46:40.767   929   940 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-25 07:46:40.767   929  6061 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:46:40.767   929  6061 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:46:40.767   929  6061 E DropBoxManagerService: 	... 5 more
11-25 07:46:40.768  6047  6047 I Process : Sending signal. PID: 6047 SIG: 9
,11-25 07:46:40.778   929  3653 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6047) has died
11-25 07:46:40.779   929  3653 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-25 07:46:40.794   929   942 I ActivityManager: Start proc 6062:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 07:46:40.845  6062  6062 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:46:40.845  6062  6062 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 07:46:40.845  6062  6062 D AndroidRuntime: Shutting down VM
,11-25 07:46:40.852  6062  6062 E AndroidRuntime: FATAL EXCEPTION: main
11-25 07:46:40.852  6062  6062 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6062
11-25 07:46:40.852  6062  6062 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 07:46:40.852  6062  6062 E AndroidRuntime: 	... 10 more
11-25 07:46:40.855   929  3921 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-25 07:46:40.856   929  6074 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:46:40.856   929  6074 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:46:40.856   929  6074 E DropBoxManagerService: 	... 5 more
11-25 07:46:40.856  6062  6062 I Process : Sending signal. PID: 6062 SIG: 9
,11-25 07:46:40.872   929  3653 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6062) has died
,11-25 07:46:40.874   929  3653 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-25 07:46:40.890   929   942 I ActivityManager: Start proc 6075:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 07:46:40.895   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
