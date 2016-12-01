#### Test 96008345ac97228_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
12-01 07:06:51.646  5559  5599 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
12-01 07:06:51.795   927  3110 I ActivityManager: Killing 5267:org.codeaurora.ims/1001 (adj 15): empty #17
12-01 07:06:52.015  5559  5607 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
12-01 07:06:52.040  3668  3668 I ConfigFetchService: fetch service done; releasing wakelock
12-01 07:06:52.041  3668  3668 I ConfigFetchService: stopping self
12-01 07:06:52.075  5559  5607 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
12-01 07:06:52.078  3668  4898 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
12-01 07:06:52.097  5608  5608 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-01 07:06:52.100  5608  5608 D AndroidRuntime: CheckJNI is OFF
12-01 07:06:52.122  5608  5608 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-01 07:06:52.148  5608  5608 I Radio-JNI: register_android_hardware_Radio DONE
12-01 07:06:52.156  3668  4898 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
12-01 07:06:52.162  5608  5608 D AndroidRuntime: Calling main entry com.android.commands.am.Am
12-01 07:06:52.167   927  3526 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
12-01 07:06:52.187  5559  5607 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
12-01 07:06:52.196   927  3526 I ActivityManager: Start proc 5624:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
12-01 07:06:52.211  5608  5608 D AndroidRuntime: Shutting down VM
,12-01 07:06:52.521   927  3537 I WindowManager: Screenshot max retries 4 of Token{f16ccdd ActivityRecord{3a58b4 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{74c0a4c u0 Starting com.test.thalitest} drawState=2
,12-01 07:06:52.605  5624  5624 I CordovaLog: Changing log level to DEBUG(3)
,12-01 07:06:52.605  5624  5624 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
12-01 07:06:52.605  5624  5624 D CordovaActivity: CordovaActivity.onCreate()
,12-01 07:06:52.612  5624  5624 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,12-01 07:06:52.645  5624  5624 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,12-01 07:06:52.703  5624  5624 I LibraryLoader: Time to load native libraries: 53 ms (timestamps 601-654)
,12-01 07:06:52.703  5624  5624 I LibraryLoader: Expected native library version number "",actual native library version number ""
,12-01 07:06:52.736  5624  5624 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c499cf6}
,12-01 07:06:52.737  5624  5624 I LibraryLoader: Expected native library version number "",actual native library version number ""
12-01 07:06:52.737  5624  5624 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,12-01 07:06:52.745  5624  5624 I BrowserStartupController: Initializing chromium process, singleProcess=true
,12-01 07:06:52.746  5624  5624 E SysUtils: ApplicationContext is null in ApplicationStatus
,12-01 07:06:52.787  5624  5624 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,12-01 07:06:52.812  5624  5624 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
12-01 07:06:52.812  5624  5624 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
12-01 07:06:52.812  5624  5624 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
12-01 07:06:52.812  5624  5624 I Adreno  : Build Date                       : 12/06/15
12-01 07:06:52.812  5624  5624 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
12-01 07:06:52.812  5624  5624 I Adreno  : Local Branch                     : mybranch17112971
12-01 07:06:52.812  5624  5624 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
12-01 07:06:52.812  5624  5624 I Adreno  : Remote Branch                    : NONE
12-01 07:06:52.812  5624  5624 I Adreno  : Reconstruct Branch               : NOTHING
,12-01 07:06:52.885   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4cfd50:true
,12-01 07:06:52.921   405   405 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26142]" dev="sockfs" ino=26142 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 07:06:52.921   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[26142]" dev="sockfs" ino=26142 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 07:06:52.939  5624  5624 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,12-01 07:06:52.949  5624  5624 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,12-01 07:06:52.953  5624  5624 D PluginManager: init()
,12-01 07:06:52.956  5624  5624 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,12-01 07:06:52.985  5624  5624 D CordovaActivity: Started the activity.
,12-01 07:06:52.985  5624  5624 D CordovaActivity: Resumed the activity.
,12-01 07:06:52.989  5624  5661 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,12-01 07:06:52.984   403   403 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34222]" dev="sockfs" ino=34222 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-01 07:06:52.988   403   403 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34222]" dev="sockfs" ino=34222 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 07:06:52.991   937   937 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[29735]" dev="sockfs" ino=29735 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 07:06:52.991   937   937 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29735]" dev="sockfs" ino=29735 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 07:06:52.995  5624  5624 D CordovaActivity: Paused the activity.
,12-01 07:06:52.997  5624  5648 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,12-01 07:06:53.017  5624  5661 I OpenGLRenderer: Initialized EGL, version 1.4
,12-01 07:06:53.027  5624  5624 D CordovaActivity: Stopped the activity.
,12-01 07:06:53.094   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +568ms (total +913ms)
,12-01 07:06:53.100  5624  5624 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,12-01 07:06:53.121  5624  5624 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5624
,12-01 07:06:53.264  5624  5624 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,12-01 07:06:53.433  5624  5663 D jxcore_app_log: JniHelper::setJavaVM(0xf4fbc000), pthread_self() = -584320720
,12-01 07:06:53.437  5624  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
12-01 07:06:53.437  5624  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
12-01 07:06:53.437  5624  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
12-01 07:06:53.437  5624  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
12-01 07:06:53.437  5624  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,12-01 07:06:53.437  5624  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@640d3bc added. We now have 1 listener(s)
,12-01 07:06:53.443  5624  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,12-01 07:06:53.444  5624  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,12-01 07:06:53.444  5624  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:06:53.444  5624  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
12-01 07:06:53.446  5624  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@123ebcb added. We now have 1 listener(s)
,12-01 07:06:53.446  5624  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:06:53.453   927  2929 D WifiService: New client listening to asynchronous messages
,12-01 07:06:53.454  5624  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 07:06:53.454  5624  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
12-01 07:06:53.454  5624  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
12-01 07:06:53.454  5624  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
12-01 07:06:53.454  5624  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
12-01 07:06:53.455  5624  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
12-01 07:06:53.455  5624  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
12-01 07:06:53.457  5624  5663 I io.jxcore.node.LifeCycleMonitor: start: OK
,12-01 07:06:53.512  5624  5624 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,12-01 07:06:53.513  5624  5624 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,12-01 07:06:53.514  5624  5624 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,12-01 07:06:53.646   927  2928 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 07:06:53.864  5624  5633 I art     : Background sticky concurrent mark sweep GC freed 74023(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 2.052ms total 233.074ms
,12-01 07:06:55.180  5624  5670 W jxcore-log: Initializing JXcore engine
,12-01 07:06:55.180  5624  5670 W jxcore-log: JXcore engine is ready
,12-01 07:06:55.201  5670  5670 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12441 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,12-01 07:06:55.201  5670  5670 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14381]" dev="sockfs" ino=14381 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
12-01 07:06:55.201  5670  5670 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
12-01 07:06:55.201  5670  5670 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34199]" dev="sockfs" ino=34199 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,12-01 07:06:55.212  5624  5670 W jxcore-log: Starting JXcore engine
,12-01 07:06:55.264  5624  5670 W jxcore-log: Platform android
12-01 07:06:55.264  5624  5670 W jxcore-log: 
,12-01 07:06:55.264  5624  5670 W jxcore-log: Process ARCH arm
12-01 07:06:55.264  5624  5670 W jxcore-log: 
,12-01 07:06:55.445  5624  5670 I jxcore-log: JXcore Cordova bridge is ready!
12-01 07:06:55.445  5624  5670 I jxcore-log: 
,12-01 07:06:55.445  5624  5670 W jxcore-log: JXcore engine is started
,12-01 07:06:55.450  5624  5663 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,12-01 07:06:55.453  5624  5624 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,12-01 07:06:55.453  5624  5624 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,12-01 07:06:56.553   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:06:57.051  3521  3521 I ConfigService: onDestroy
,12-01 07:06:57.554   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:06:58.555   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:06:59.556   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:00.328   927   927 I ActivityManager: Killing 5280:com.android.settings/1000 (adj 15): empty #17
,12-01 07:07:00.556   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:01.557   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,12-01 07:07:05.151  5624  5670 I jxcore-log: 2016-12-01 12:07:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
12-01 07:07:05.151  5624  5670 I jxcore-log: 
,12-01 07:07:05.152  5624  5670 I jxcore-log: 2016-12-01 12:07:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
12-01 07:07:05.152  5624  5670 I jxcore-log: 
,12-01 07:07:05.158  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 07:07:05.158  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 07:07:05.159  5624  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 07:07:05.162  5624  5670 I jxcore-log: 2016-12-01 12:07:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
12-01 07:07:05.162  5624  5670 I jxcore-log: 
,12-01 07:07:05.163  5624  5670 I jxcore-log: 2016-12-01 12:07:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
12-01 07:07:05.163  5624  5670 I jxcore-log: 
,12-01 07:07:05.414  5624  5670 I jxcore-log: 2016-12-01 12:07:05 - DEBUG UnitTest_app: 'Running unit tests'
12-01 07:07:05.414  5624  5670 I jxcore-log: 
,12-01 07:07:05.415  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 07:07:05.415  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3298204 added. We now have 2 listener(s)
12-01 07:07:05.416  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,12-01 07:07:05.416  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:07:05.416  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 07:07:05.416  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 07:07:05.416  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161c3ed added. We now have 2 listener(s)
,12-01 07:07:05.416  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:07:05.417  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 07:07:05.418  5624  5670 D executeNativeTests: Running unit tests
,12-01 07:07:05.458  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 07:07:05.458  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 added. We now have 3 listener(s)
12-01 07:07:05.459  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:07:05.459  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:07:05.459  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 07:07:05.459  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:07:05.459  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 added. We now have 3 listener(s)
12-01 07:07:05.459  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:07:05.466  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 07:07:05.470  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 07:07:05.470  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 07:07:05.470  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 07:07:05.470  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 07:07:05.471  5624  5670 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,12-01 07:07:05.471  5624  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
12-01 07:07:05.471  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 07:07:05.471  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 07:07:05.471  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 07:07:05.471  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 07:07:05.471  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:05.471  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 07:07:05.471  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:05.471  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:05.472  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:05.472  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:07:05.472  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 removed from the list
12-01 07:07:05.472  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:05.472  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 removed from the list
12-01 07:07:05.472  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:05.472  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.472  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.473  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.473  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.473  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.473  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:05.473  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:05.473  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:05.473  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:05.474  5624  5670 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
12-01 07:07:05.474  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:05.474  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:05.474  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:05.474  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:05.474  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:05.474  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:05.474  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:05.474  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:05.474  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:05.474  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:,07:05.475  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.475  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.475  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.475  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.475  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:05.475  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:05.475  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:05.475  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
12-01 07:07:05.478  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
12-01 07:07:05.479  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
12-01 07:07:05.479  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
12-01 07:07:05.479  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
12-01 07:07:05.479  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
12-01 07:07:05.479  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,12-01 07:07:05.479  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
12-01 07:07:05.479  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:05.479  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:05.479  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:05.479  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:05.479  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:05.479  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
,12-01 07:07:05.479  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:05.479  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:05.479  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:05.479  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.479  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.480  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.480  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.480  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.480  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:05.480  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:05.480  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:05.480  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:05.480  5624  5670 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
12-01 07:07:05.481  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:07:05.481  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 07:07:05.484  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 07:07:05.485  5624  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 07:07:05.485  5624  5670 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 07:07:05.485  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:07:05.485  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 07:07:05.485  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 07:07:05.485  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:07:05.485  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 07:07:05.488  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 07:07:05.488  5624  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 07:07:05.488  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 07:07:05.490  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:05.493  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:05.494  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.494  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 07:07:05.496  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 07:07:05.496  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 07:07:05.496  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 07:07:05.498  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
12-01 07:07:05.500  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
12-01 07:07:05.500  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.500  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 07:07:05.500  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 07:07:05.500  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 07:07:05.501  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 07:07:05.501  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.501  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:05.505  4556  4795 D BtGatt.GattService: registerClient() - UUID=2ec6e6b3-81f8-4c44-a14f-42c675cda6d1
12-01 07:07:05.505  4556  4638 D BtGatt.GattService: onClientRegistered() - UUID=2ec6e6b3-81f8-4c44-a14f-42c675cda6d1, clientIf=5
12-01 07:07:05.506  5624  5634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 07:07:05.508  4556  4775 D BtGatt.GattService: start scan with filters
12-01 07:07:05.511  4556  4641 D BtGatt.ScanManager: handling starting scan
12-01 07:07:05.512  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 07:07:05.512  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.512  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 07:07:05.512  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.512  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 07:07:05.512  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 07:07:05.512  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.513  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 07:07:05.513  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 07:07:05.513  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.513  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.513  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 07:07:05.513  4556  4641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:07:05.513  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.513  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.513  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.514  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.514  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:07:05.515  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.515  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:05.515  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.515  5624  5670 I io.jxcore.node.ConnectionHelper: start: OK
12-01 07:07:05.517  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.517  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.517  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:05.518  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,12-01 07:07:05.521  4556  4638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 07:07:05.521  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:05.521  4556  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 07:07:05.526  4556  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 07:07:05.526  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:05.526  4556  4641 D BtGatt.ScanManager: Starting BLE batch scan
12-01 07:07:05.527  4556  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 07:07:05.534  4556  4638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 07:07:05.534  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:05.539  4556  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 07:07:05.539  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:07:05.573  4798  4830 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,12-01 07:07:05.575  4798  4798 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,12-01 07:07:06.019  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,12-01 07:07:06.019  5624  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:07:06.019  5624  5624 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 07:07:10.519  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 07:07:10.520  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:10.520  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 07:07:10.520  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:07:10.520  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 07:07:10.520  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 07:07:10.520  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 07:07:10.520  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 07:07:10.521  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.521  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,12-01 07:07:10.521  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 07:07:10.522  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.522  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:10.522  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.522  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 07:07:10.522  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:10.523  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:10.524  4556  4577 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 07:07:10.524  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 07:07:10.526  4556  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:07:10.527  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:10.528  4556  4795 D BtGatt.GattService: stopScan() - queue size =1
,12-01 07:07:10.530  4556  4775 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 07:07:10.531  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 07:07:10.531  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:10.531  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 07:07:10.531  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.532  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.532  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.532  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.533  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 07:07:10.533  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.533  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.534  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.534  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 07:07:10.534  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 07:07:10.535  4556  4556 D BtGatt.ScanManager: awakened up at time 98485
12-01 07:07:10.536  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:07:10.537  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.539  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.539  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:10.539  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.540  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:10.540  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:10.540  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:07:10.540  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:07:10.540  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:07:10.540  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:07:10.540  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:10.540  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 07:07:10.540  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the, list
12-01 07:07:10.540  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.541  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:10.541  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 07:07:10.541  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:10.541  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 07:07:10.541  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:10.541  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.541  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 07:07:10.541  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.541  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.542  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:10.542  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.542  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.545  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.545  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:10.545  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,12-01 07:07:10.571  4556  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,12-01 07:07:10.572  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:10.572  4556  4638 D BtGatt.GattService: current time is 98523503533
12-01 07:07:10.573  4556  4638 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -67, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -65, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -24, -5, 124, 62, -54, -40, 1, 0, -95, 85, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, -124, 38, 105, 3, 1, -25, 23, 62, -41, 18, -87, 28, 6, 8, 116, 105, 115, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 37, -47, 14, -113, 116, -46, 1, -128, -76, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 48, -60, -48, -14, 51, -33, 1, 0, -94, 80, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 33, 34, 105, 3, 2, -29, 20, 61, 88, -122, -68, 28, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -71, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -70, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 86, -31, -99, 30, -52, -57, 1, 0, -93, 71, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, 38, 74, 105, 3, 2, -29, 20, 62, -65, -110, -78, 28, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 50, -35, 86, -77, -92, -11, 1, 0, -92, 4, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 99, 42, 105, 3, 2, -33, 21, -106, -1, 117, 121, 28, 6, 8, 116, 105, 110, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,12-01 07:07:10.575  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
12-01 07:07:10.577  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,12-01 07:07:10.577  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, -124, 38, 105, 3, 1, -25, 23, 62, -41, 18, -87, 6, 8, 116, 105, 115, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
12-01 07:07:10.578  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,12-01 07:07:10.578  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 33, 34, 105, 3, 2, -29, 20, 61, 88, -122, -68, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
12-01 07:07:10.579  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
12-01 07:07:10.579  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
12-01 07:07:10.580  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, 38, 74, 105, 3, 2, -29, 20, 62, -65, -110, -78, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
12-01 07:07:10.580  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 99, 42, 105, 3, 2, -33, 21, -106, -1, 117, 121, 6, 8, 116, 105, 110, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
12-01 07:07:10.586  4556  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 07:07:10.587  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:10.587  4556  4641 D BtGatt.ScanManager: stopping BLe Batch
,12-01 07:07:10.594  4556  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,12-01 07:07:10.594  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:10.594  4556  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:07:10.600  4556  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 07:07:10.600  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:07:11.044  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 07:07:15.545  5624  5670 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,12-01 07:07:15.551  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,12-01 07:07:15.551  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 07:07:15.565  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 07:07:15.569  5624  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 07:07:15.570  5624  5670 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 07:07:15.570  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:07:15.570  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,12-01 07:07:15.570  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 07:07:15.570  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:07:15.571  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 07:07:15.576  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:15.579  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,12-01 07:07:15.579  5624  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 07:07:15.580  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 07:07:15.582  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:15.588  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:15.588  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,12-01 07:07:15.590  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,12-01 07:07:15.590  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 07:07:15.590  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 07:07:15.598  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.598  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 07:07:15.598  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 07:07:15.598  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 07:07:15.598  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 07:07:15.598  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.600  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:15.605  4556  4577 D BtGatt.GattService: registerClient() - UUID=deaa343c-953b-425c-9f2d-1e346b83bd7d
12-01 07:07:15.606  4556  4638 D BtGatt.GattService: onClientRegistered() - UUID=deaa343c-953b-425c-9f2d-1e346b83bd7d, clientIf=5
12-01 07:07:15.606  5624  5634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 07:07:15.607  4556  4796 D BtGatt.GattService: start scan with filters
12-01 07:07:15.611  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 07:07:15.611  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.611  4556  4641 D BtGatt.ScanManager: handling starting scan
12-01 07:07:15.611  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,12-01 07:07:15.611  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.611  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 07:07:15.612  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 07:07:15.612  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.612  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 07:07:15.612  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 07:07:15.614  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 07:07:15.614  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.612  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.616  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.616  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.616  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,12-01 07:07:15.617  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.617  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.617  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.617  5624  5670 I io.jxcore.node.ConnectionHelper: start: OK
12-01 07:07:15.617  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,12-01 07:07:15.625  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,12-01 07:07:15.625  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:07:15.626  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,12-01 07:07:15.626  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.626  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:07:15.626  4556  4638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 07:07:15.626  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.626  4556  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,12-01 07:07:15.628  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 07:07:15.628  5624  5670 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
12-01 07:07:15.628  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:15.628  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,12-01 07:07:15.628  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:07:15.628  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 07:07:15.628  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:15.628  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 07:07:15.629  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 07:07:15.629  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:15.629  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 07:07:15.629  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 07:07:15.629  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.629  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.629  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.629  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 07:07:15.630  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.632  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:15.633  4556  4775 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 07:07:15.633  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 07:07:15.634  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:15.635  4556  4577 D BtGatt.GattService: stopScan() - queue size =1
12-01 07:07:15.635  4556  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 07:07:15.635  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.635  4556  4641 D BtGatt.ScanManager: Starting BLE batch scan
12-01 07:07:15.635  4556  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 07:07:15.636  4556  4796 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 07:07:15.636  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 07:07:15.636  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.636  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.637  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 07:07:15.637  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 07:07:15.638  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:07:15.638  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.640  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.640  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:15.641  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.641  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.641  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:15.641  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:07:15.641  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:07:15.641  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:07:15.641  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:15.641  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:15.641  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:07:15.641  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:15.641  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:15.641  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 07:07:15.641  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:15.641  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.642  5624  5670 I org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 07:07:15.642  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 07:07:15.642  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 07:07:15.642  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.642  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.642  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.642  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:15.642  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.643  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.645  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.645  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.646  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.646  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.646  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.647  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.648  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.648  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.648  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:15.648  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:15.648  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:15.648  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:15.649  5624  5670 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
12-01 07:07:15.651  4556  4638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 07:07:15.651  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.651  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:07:15.651  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,12-01 07:07:15.659  4556  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 07:07:15.659  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 07:07:15.660  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 07:07:15.661  4556  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:07:15.663  5624  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 07:07:15.663  5624  5670 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 07:07:15.663  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:07:15.663  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 07:07:15.663  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 07:07:15.663  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:07:15.663  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 07:07:15.666  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:15.668  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,12-01 07:07:15.668  5624  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 07:07:15.668  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 07:07:15.668  4556  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 07:07:15.668  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.670  4556  4638 E BtGatt.ContextMap: Context not found for ID 5
12-01 07:07:15.670  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:15.673  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:15.673  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 07:07:15.673  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 07:07:15.673  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 07:07:15.673  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 07:07:15.678  4556  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 07:07:15.678  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:07:15.678  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:15.678  4556  4641 D BtGatt.ScanManager: stopping BLe Batch
12-01 07:07:15.678  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 07:07:15.678  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 07:07:15.678  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 07:07:15.678  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,12-01 07:07:15.678  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.679  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:15.681  4556  4795 D BtGatt.GattService: registerClient() - UUID=df5a31b5-5bde-42f4-ac6e-7a75603c3480
12-01 07:07:15.682  4556  4638 D BtGatt.GattService: onClientRegistered() - UUID=df5a31b5-5bde-42f4-ac6e-7a75603c3480, clientIf=5
12-01 07:07:15.682  5624  5635 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,12-01 07:07:15.683  4556  4775 D BtGatt.GattService: start scan with filters
12-01 07:07:15.683  4556  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 07:07:15.684  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.684  4556  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:07:15.686  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 07:07:15.686  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.686  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 07:07:15.686  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.686  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 07:07:15.686  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,12-01 07:07:15.686  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.686  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 07:07:15.686  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 07:07:15.687  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.687  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.687  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.687  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.687  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 07:07:15.687  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.690  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.690  4556  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 07:07:15.690  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,12-01 07:07:15.690  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.690  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.690  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:15.690  5624  5670 I io.jxcore.node.ConnectionHelper: start: OK
12-01 07:07:15.691  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.691  4556  4641 D BtGatt.ScanManager: handling starting scan
12-01 07:07:15.693  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.693  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,12-01 07:07:15.693  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:15.693  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,12-01 07:07:15.697  4556  4638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,12-01 07:07:15.697  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.697  4556  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,12-01 07:07:15.701  4556  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,12-01 07:07:15.701  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:15.702  4556  4641 D BtGatt.ScanManager: Starting BLE batch scan
12-01 07:07:15.702  4556  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 07:07:15.710  4556  4638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 07:07:15.710  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:07:15.715  4556  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,12-01 07:07:15.715  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:07:16.194  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
12-01 07:07:16.195  5624  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,12-01 07:07:16.195  5624  5624 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 07:07:16.847   927  2930 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 07:07:19.874   927  2930 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 07:07:20.690  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 07:07:20.691  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:20.691  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,12-01 07:07:20.691  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:07:20.691  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 07:07:20.691  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 07:07:20.691  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 07:07:20.692  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 07:07:20.692  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.692  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 07:07:20.692  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 07:07:20.693  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.693  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.693  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.693  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 07:07:20.693  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.696  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:07:20.696  4556  4795 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 07:07:20.697  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,12-01 07:07:20.698  4556  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 07:07:20.699  5624  5670 D BluetoothAdapter: STATE_ON
,12-01 07:07:20.701  4556  4577 D BtGatt.GattService: stopScan() - queue size =1
12-01 07:07:20.703  4556  4575 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 07:07:20.704  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 07:07:20.704  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.704  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 07:07:20.704  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.705  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.705  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.705  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.705  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 07:07:20.706  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:20.706  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.706  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.706  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 07:07:20.706  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 07:07:20.707  4556  4556 D BtGatt.ScanManager: awakened up at time 108658
,12-01 07:07:20.709  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:07:20.709  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.711   927   937 I ActivityManager: Killing 5058:com.google.android.apps.maps/u0a58 (adj 15): empty #17
12-01 07:07:20.711  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:20.712  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:20.712  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.712  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:20.712  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:07:20.712  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,12-01 07:07:20.713  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 07:07:20.713  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:07:20.713  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 07:07:20.713  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 07:07:20.713  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,12-01 07:07:20.713  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 07:07:20.713  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:07:20.713  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:20.714  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,12-01 07:07:20.714  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:07:20.716  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:07:20.716  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:07:20.716  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,12-01 07:07:20.765  4556  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,12-01 07:07:20.766  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:20.766  4556  4638 D BtGatt.GattService: current time is 108717108842
12-01 07:07:20.766  4556  4638 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -65, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 93, 88, 93, 14, -117, 80, 1, -128, -100, 78, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0, 37, -47, 14, -113, 116, -46, 1, -128, -72, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -68, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -66, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -24, -5, 124, 62, -54, -40, 1, 0, -98, 81, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, -114, 38, 105, 3, 1, -25, 23, 62, -77, 79, -31, 28, 6, 8, 116, 105, 115, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -72, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 48, -60, -48, -14, 51, -33, 1, 0, -97, 77, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 44, 34, 105, 3, 2, -29, 20, 61, 104, -24, -116, 28, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -77, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,12-01 07:07:20.766  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
12-01 07:07:20.767  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
12-01 07:07:20.767  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
12-01 07:07:20.767  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,12-01 07:07:20.767  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
12-01 07:07:20.767  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, -114, 38, 105, 3, 1, -25, 23, 62, -77, 79, -31, 6, 8, 116, 105, 115, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
12-01 07:07:20.768  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
12-01 07:07:20.768  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 44, 34, 105, 3, 2, -29, 20, 61, 104, -24, -116, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
12-01 07:07:20.768  4556  4638 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,12-01 07:07:20.775  4556  4638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 07:07:20.775  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:20.775  4556  4641 D BtGatt.ScanManager: stopping BLe Batch
,12-01 07:07:20.781  4556  4638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,12-01 07:07:20.781  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:07:20.781  4556  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:07:20.786  4556  4638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,12-01 07:07:20.787  4556  4638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:07:21.215  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 07:07:21.216  5624  5624 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:21.216  5624  5624 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 07:07:21.753   927  5385 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 07:07:25.714  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 07:07:25.714  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 07:07:25.714  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.714  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.714  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:07:25.715  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,12-01 07:07:25.715  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 07:07:25.715  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.715  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.716  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.716  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:07:25.716  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 07:07:25.721  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.722  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.725  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.726  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.726  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.726  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.726  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 07:07:25.726  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.726  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.728  5624  5670 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,12-01 07:07:25.730  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 07:07:25.730  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:25.730  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.730  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 07:07:25.730  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.731  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.731  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:25.731  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.731  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.731  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.731  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.734  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.734  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.734  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.734  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.734  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.734  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:25.735  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.737  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
12-01 07:07:25.737  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.737  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:25.737  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,12-01 07:07:25.737  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.737  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.738  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.738  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:25.738  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.738  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.738  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.738  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.740  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.741  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.741  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.741  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.741  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 07:07:25.741  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.741  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.743  5624  5670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
12-01 07:07:25.743  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.743  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 07:07:25.743  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.744  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.744  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.744  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
,12-01 07:07:25.744  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:25.744  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.744  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.744  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.745  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.747  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.748  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.748  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.748  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.748  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.748  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.748  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
,12-01 07:07:25.750  5624  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
12-01 07:07:25.750  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.750  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 07:07:25.750  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.750  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.751  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.751  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.751  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.751  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.751  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.751  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.751  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.753  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.754  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.754  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.754  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 07:07:25.754  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.754  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.754  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.755  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 07:07:25.755  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,12-01 07:07:25.756  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 07:07:25.756  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 07:07:25.756  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 07:07:25.756  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 07:07:25.756  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 07:07:25.756  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 07:07:25.756  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 07:07:25.756  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.756  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:25.757  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.757  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.757  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.757  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.757  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.757  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
,12-01 07:07:25.757  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.757  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.757  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.759  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:25.759  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.759  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.760  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 07:07:25.760  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.760  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.760  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.761  5624  5670 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,12-01 07:07:25.761  5624  5670 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
12-01 07:07:25.761  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
12-01 07:07:25.767  5624  5670 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,12-01 07:07:25.768  5624  5670 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
12-01 07:07:25.768  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
12-01 07:07:25.768  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
12-01 07:07:25.768  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
12-01 07:07:25.768  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,12-01 07:07:25.768  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,12-01 07:07:25.768  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
12-01 07:07:25.768  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,12-01 07:07:25.769  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
12-01 07:07:25.770  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,12-01 07:07:25.771  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
12-01 07:07:25.771  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
12-01 07:07:25.771  5624  5670 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
12-01 07:07:25.771  5624  5670 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 07:07:25.771  5624  5670 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
12-01 07:07:25.772  5624  5670 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 07:07:25.772  5624  5670 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 07:07:25.772  5624  5670 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
12-01 07:07:25.772  5624  5670 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 07:07:25.773  5624  5670 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 07:07:25.773  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
12-01 07:07:25.778  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
12-01 07:07:25.778  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
12-01 07:07:25.779  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
12-01 07:07:25.779  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
12-01 07:07:25.780  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
12-01 07:07:25.780  5624  5670 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
12-01 07:07:25.780  5624  5670 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 07:07:25.780  5624  5670 E io.jxcore.node.ConnectionHelper: connect: Callback is null
12-01 07:07:25.780  5624  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
12-01 07:07:25.780  5624  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
12-01 07:07:25.781  5624  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
12-01 07:07:25.781  5624  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
12-01 07:07:25.781  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.781  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:25.781  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.782  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.782  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.782  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
12-01 07:07:25.783  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.783  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.783  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.783  5624  5672 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
12-01 07:07:25.783  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.783  5624  5672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:07:25.783  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.783  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.784  5624  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
12-01 07:07:25.784  5624  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
12-01 07:07:25.784  5624  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
12-01 07:07:25.785  5624  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
12-01 07:07:25.785  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.785  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.785  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.785  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.785  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.785  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.785  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.786  5624  5670 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
12-01 07:07:25.788  4775  4775 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32666]" dev="sockfs" ino=32666 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 07:07:25.787  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.787  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:25.787  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.787  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.787  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.787  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.787  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.787  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.787  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.788  4775  4775 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32666]" dev="sockfs" ino=32666 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 07:07:25.788  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.788  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.789  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.789  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.789  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.789  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.789  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.789  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.789  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.790  5624  5672 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
12-01 07:07:25.790  5624  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
12-01 07:07:25.790  5624  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
12-01 07:07:25.791  5624  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
12-01 07:07:25.792  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.792  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:25.792  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.792  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.792  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.794  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.794  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.794  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.794  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.794  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.795  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.796  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.796  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.796  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.796  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.796  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.796  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.796  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.797  5624  5670 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
12-01 07:07:25.797  5624  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
12-01 07:07:25.797  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 07:07:25.797  5624  5670 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
12-01 07:07:25.797  5624  5670 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
12-01 07:07:25.797  5624  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
12-01 07:07:25.797  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
12-01 07:07:25.797  5624  5670 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
12-01 07:07:25.797  5624  5670 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
12-01 07:07:25.797  5624  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
12-01 07:07:25.798  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
12-01 07:07:25.798  5624  5670 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
12-01 07:07:25.798  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:25.798  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:25.798  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:25.798  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.798  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.798  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.798  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.798  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.798  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:25.798  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.798  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.799  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.800  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.800  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:25.800  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:25.800  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:25.800  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.800  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.800  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:25.801  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:25.801  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:25.801  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:25.801  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:25.801  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:07:26.558   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
12-01 07:07:26.558   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,12-01 07:07:30.801  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:30.802  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.802  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:30.802  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:30.802  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
,12-01 07:07:30.803  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:30.803  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:30.803  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,12-01 07:07:30.803  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:30.804  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:30.804  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:30.804  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:30.804  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.804  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:30.805  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.805  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.808  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.808  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.809  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.809  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 07:07:30.809  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:30.809  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:30.810  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.813  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,12-01 07:07:30.814  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:07:30.815  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,12-01 07:07:30.821  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,12-01 07:07:30.825  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
12-01 07:07:30.825  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,12-01 07:07:30.825  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,12-01 07:07:30.826  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,12-01 07:07:30.826  5624  5624 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
12-01 07:07:30.826  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 07:07:30.827  5624  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,12-01 07:07:30.827  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 07:07:30.827  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,12-01 07:07:30.827  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,12-01 07:07:30.828  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
12-01 07:07:30.828  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,12-01 07:07:30.828  5624  5674 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 07:07:30.829  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
12-01 07:07:30.829  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
12-01 07:07:30.829  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
,12-01 07:07:30.829  5624  5624 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
12-01 07:07:30.829  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:30.829  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 07:07:30.830  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.830  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 07:07:30.830  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 07:07:30.830  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.831  4775  4775 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34252]" dev="sockfs" ino=34252 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 07:07:30.831  4775  4775 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34252]" dev="sockfs" ino=34252 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,12-01 07:07:30.833  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.833  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:30.833  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.834  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.834  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.834  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:07:30.834  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:30.834  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:07:30.834  5624  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
12-01 07:07:30.834  5624  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
12-01 07:07:30.834  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:30.834  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:07:30.835  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:30.835  5624  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
12-01 07:07:30.835  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:30.835  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
12-01 07:07:30.835  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:30.835  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:30.835  5624  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
12-01 07:07:30.836  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.836  5624  5624 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:30.836  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:30.836  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.836  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.840  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.841  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.841  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.841  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:30.841  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:30.841  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:30.841  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
,12-01 07:07:30.845  5624  5670 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,12-01 07:07:30.845  5624  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
12-01 07:07:30.845  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 07:07:30.846  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,12-01 07:07:30.846  5624  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,12-01 07:07:30.846  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 07:07:30.846  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 07:07:30.846  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:30.846  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:30.847  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 07:07:30.847  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
12-01 07:07:30.847  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:30.847  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.847  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:30.847  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.847  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.851  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.851  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.851  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.852  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:30.852  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:30.852  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:30.852  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.858  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:30.858  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:30.858  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,12-01 07:07:30.858  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:30.858  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:30.859  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
,12-01 07:07:30.859  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:30.859  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.859  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:30.859  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.859  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.861  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.861  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.861  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.861  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:30.861  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:30.861  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:30.861  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.862  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:07:30.862  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:07:30.862  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:07:30.862  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:07:30.862  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:07:30.862  5624  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40607d2 not in the list
,12-01 07:07:30.863  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:30.863  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
12-01 07:07:30.863  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:07:30.863  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.863  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.864  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:07:30.864  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.864  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:07:30.864  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:07:30.864  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:07:30.864  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:07:30.865  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5f80a3 not in the list
,12-01 07:07:30.866  5624  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
12-01 07:07:30.866  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 07:07:30.866  5624  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
12-01 07:07:30.866  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 07:07:30.866  5624  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
12-01 07:07:30.866  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,12-01 07:07:30.868  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
12-01 07:07:30.868  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
12-01 07:07:30.869  5624  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
12-01 07:07:30.869  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
12-01 07:07:30.869  5624  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
12-01 07:07:30.869  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
12-01 07:07:30.869  5624  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,12-01 07:07:30.869  5624  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
12-01 07:07:30.870  5624  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
12-01 07:07:30.870  5624  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
12-01 07:07:30.870  5624  5670 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
12-01 07:07:30.870  5624  5670 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
12-01 07:07:30.870  5624  5670 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,12-01 07:07:30.870  5624  5670 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
12-01 07:07:30.871  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:07:30.871  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f830d0 added. We now have 3 listener(s)
12-01 07:07:30.871  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:07:30.875  5624  5670 D BluetoothAdapter: enable(): BT is already enabled..!
12-01 07:07:30.875   927  3683 D WifiService: setWifiEnabled: true pid=5624, uid=10077
12-01 07:07:30.875   927  3683 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 07:07:30.913  4556  4754 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,12-01 07:07:30.913  4556  4772 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,12-01 07:07:31.336  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 07:07:31.559   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:32.560   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:33.561   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:33.652   927  2928 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 07:07:34.563   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:35.564   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:35.881  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 07:07:35.882  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66c58c9 added. We now have 4 listener(s)
,12-01 07:07:35.882  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:07:35.895  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:35.895  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66c58c9 removed from the list
12-01 07:07:35.895  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:07:35.897  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 07:07:35.897  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a53bce added. We now have 4 listener(s)
12-01 07:07:35.898  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:07:35.902  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:07:35.902  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a53bce removed from the list
12-01 07:07:35.902  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:07:35.903  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 07:07:35.903  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e76aef added. We now have 4 listener(s)
12-01 07:07:35.903  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:07:35.906   927  3683 D WifiService: setWifiEnabled: false pid=5624, uid=10077
,12-01 07:07:35.906   927  3683 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 07:07:35.910   927  2928 D WifiStateMachine: WifiStateMachine: Leaving Connected state
12-01 07:07:35.910   927  2928 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
12-01 07:07:35.910   927  2928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,12-01 07:07:35.910   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 07:07:35.919  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,12-01 07:07:35.919  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
12-01 07:07:35.922  4556  4634 D BluetoothAdapterState: Current state: ON, message: 23
12-01 07:07:35.922  4556  4634 D BluetoothAdapterProperties: Setting state to 13
12-01 07:07:35.922  4556  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
12-01 07:07:35.923  4556  4634 D BluetoothAdapterProperties: onBluetoothDisable()
,12-01 07:07:35.923  4556  4634 I BluetoothAdapterState: Entering PendingCommandState
,12-01 07:07:35.925  4556  4556 D BluetoothMapService: onReceive
,12-01 07:07:35.925  4556  4556 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 07:07:35.926  4556  4556 D BluetoothMapService: STATE_TURNING_OFF
12-01 07:07:35.926  4556  4556 D BluetoothMapService: MAP Service closeService in
12-01 07:07:35.926  4556  4556 D BluetoothMapMasInstance0: MAP Service shutdown
12-01 07:07:35.926  4556  4556 D ObexServerSockets0: shutdown(block = true)
12-01 07:07:35.927  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 07:07:35.927  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 07:07:35.927  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 07:07:35.927  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 07:07:35.927  4556  4772 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
12-01 07:07:35.927  4556  4809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
12-01 07:07:35.927  4556  4810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
12-01 07:07:35.929  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:35.930  5624  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 07:07:35.930  5624  5670 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 07:07:35.930   927  5386 D DhcpClient: Clearing IP address
12-01 07:07:35.931   506   921 D CommandListener: Clearing all IP addresses on wlan0
12-01 07:07:35.933  4556  4556 I BtOppRfcommListener: stopping Accept Thread
12-01 07:07:35.933  4556  5313 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
12-01 07:07:35.933  4556  5313 I BtOppRfcommListener: BluetoothSocket listen thread finished
,12-01 07:07:35.935  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:35.938  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:35.938   506   921 D CommandListener: Setting iface cfg
12-01 07:07:35.941  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:35.944   927  5387 D DhcpClient: Receive thread stopped
,12-01 07:07:35.945  3521  5441 V NativeCrypto: Read error: ssl=0x7f60554680: I/O error during system call, Connection timed out
,12-01 07:07:35.947  3521  5441 V NativeCrypto: SSL shutdown failed: ssl=0x7f60554680: I/O error during system call, Broken pipe
,12-01 07:07:35.948   927  3673 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
12-01 07:07:35.948   927  5384 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
12-01 07:07:35.950   927   940 I ActivityManager: Start proc 5678:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
12-01 07:07:35.951  4556  4638 D BluetoothAdapterProperties: Scan Mode:20
,12-01 07:07:35.951  4556  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,12-01 07:07:35.954   927  5384 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
12-01 07:07:35.954   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
12-01 07:07:35.955   927  2930 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
12-01 07:07:35.955  4556  4556 D HeadsetService: Received stop request...Stopping profile...
,12-01 07:07:35.956   927   927 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:35.956   927   927 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:35.957   927  2930 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
12-01 07:07:35.957  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:35.957  3756  3791 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:35.957   927   927 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:35.958  3074  5623 D BluetoothHeadset: Proxy object disconnected
,12-01 07:07:35.959  3074  3074 D HeadsetProfile: Bluetooth service disconnected
12-01 07:07:35.960  4556  4556 D A2dpService: Received stop request...Stopping profile...
12-01 07:07:35.960   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,12-01 07:07:35.961   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
12-01 07:07:35.961  4556  4789 D A2dpStateMachine: Exit Disconnected: -1
12-01 07:07:35.962   533   533 E Parcel  : Reading a NULL string not supported here.
,12-01 07:07:35.967   927   927 D BluetoothA2dp: Proxy object disconnected
,12-01 07:07:35.968  4556  4556 V BluetoothAdapterState: isTurningOff()=true
,12-01 07:07:35.968  4556  4556 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:35.968  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:35.968  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:35.968   927  2930 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
12-01 07:07:35.968  4556  4556 D HidService: Received stop request...Stopping profile...
12-01 07:07:35.968  4556  4556 D HidService: Stopping Bluetooth HidService
12-01 07:07:35.969   927   927 D RttService: SCAN_AVAILABLE : 1
12-01 07:07:35.969   927  3038 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
12-01 07:07:35.970  3735  3871 W QCNEJ   : |CORE| network lost: 100
12-01 07:07:35.970  3735  3871 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
12-01 07:07:35.972  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
12-01 07:07:35.972  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,12-01 07:07:35.973  4556  4638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
12-01 07:07:35.973  4556  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:35.973  4556  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:35.973  4556  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:35.973  4556  4638 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
12-01 07:07:35.973  4556  4556 D HealthService: Received stop request...Stopping profile...
,12-01 07:07:35.976  4556  4556 D PanService: Received stop request...Stopping profile...
,12-01 07:07:35.977  4556  4556 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:35.977  4556  4556 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:35.977  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:35.977  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:35.977  4556  4556 D BluetoothMapService: Received stop request...Stopping profile...
12-01 07:07:35.978  4556  4556 D BluetoothMapService: stop()
12-01 07:07:35.978  4556  4556 D BluetoothMapAppObserver: deinitObservers()
12-01 07:07:35.978  4556  4556 D BluetoothMapAppObserver: removeReceiver()
12-01 07:07:35.982  4556  4556 D SapService: Received stop request...Stopping profile...
12-01 07:07:35.982  4556  4556 V SapService: stop()
,12-01 07:07:35.985  4556  4556 V BluetoothAdapterState: isTurningOff()=true
,12-01 07:07:35.986  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,12-01 07:07:35.986  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 07:07:35.986  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 07:07:35.986  4556  4638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,12-01 07:07:35.986  4556  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:35.986  4556  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:35.986  4556  4754 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 07:07:35.986  4556  4754 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 07:07:35.986  4556  4754 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 07:07:35.986  4556  4754 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 07:07:35.987  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
12-01 07:07:35.987  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
12-01 07:07:35.987  4556  4638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 07:07:35.988  4556  4556 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:35.989  4556  4556 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:35.989  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:35.989  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:35.990  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,12-01 07:07:35.990  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
12-01 07:07:35.990  4556  4638 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
12-01 07:07:35.990   927  2928 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,12-01 07:07:35.991  4556  4556 V BluetoothAdapterState: isTurningOff()=true
,12-01 07:07:35.991  4556  4556 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:35.991  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:35.991  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:35.991  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,12-01 07:07:35.991  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,12-01 07:07:35.991  3074  3074 D BluetoothA2dp: Proxy object disconnected
,12-01 07:07:35.992  3074  3074 D BluetoothInputDevice: Proxy object disconnected
,12-01 07:07:35.992  3074  3074 D HidProfile: Bluetooth service disconnected
,12-01 07:07:35.993  4556  4556 D BluetoothMapService: MAP Service closeService in
12-01 07:07:35.993  4556  4556 V BluetoothAdapterState: isTurningOff()=true
,12-01 07:07:35.993  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,12-01 07:07:35.993  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 07:07:35.993  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 07:07:35.993  3074  3074 D BluetoothPan: BluetoothPAN Proxy object disconnected
12-01 07:07:35.993  3074  3074 D PanProfile: Bluetooth service disconnected
12-01 07:07:35.993  4556  4556 D BluetoothMapService: cleanup()
12-01 07:07:35.993  3074  3074 D BluetoothMap: Proxy object disconnected
12-01 07:07:35.994  3074  3074 D MapProfile: Bluetooth service disconnected
12-01 07:07:35.994  4556  4556 D BluetoothMapService: MAP Service closeService in
12-01 07:07:35.994  4556  4556 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:35.994  4556  4556 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:35.995  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 07:07:35.995  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:35.995  4556  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
12-01 07:07:35.995  4556  4634 D BluetoothAdapterProperties: Setting state to 15
12-01 07:07:35.995  4556  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
12-01 07:07:35.995  4556  4634 I BluetoothAdapterState: Entering BleOnState
12-01 07:07:35.996  3074  3085 D BluetoothPbap: onBluetoothStateChange: up=false
12-01 07:07:35.997   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:35.997  3074  3942 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:35.998   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:35.998   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:35.998  3074  3085 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 07:07:35.998  3074  5623 D BluetoothMap: onBluetoothStateChange: up=false
12-01 07:07:36.000  3756  3791 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:36.000  3074  3087 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 07:07:36.000   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 07:07:36.001  3074  3942 D BluetoothPan: onBluetoothStateChange on: false
12-01 07:07:36.002   927  2928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 07:07:36.005  4556  4634 D BluetoothAdapterState: Current state: BLE ON, message: 20
12-01 07:07:36.005  4556  4634 D BluetoothAdapterProperties: Setting state to 16
12-01 07:07:36.005  4556  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,12-01 07:07:36.006  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:36.006  4556  4634 D BluetoothAdapterProperties: onBleDisable
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:07:36.006  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 07:07:36.006  4556  4634 I BluetoothAdapterState: Entering PendingCommandState
12-01 07:07:36.006  4556  4635 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
12-01 07:07:36.007  4556  4638 D BluetoothAdapterProperties: Scan Mode:20
12-01 07:07:36.007   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
12-01 07:07:36.007  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,12-01 07:07:36.007  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 07:07:36.008  4556  4754 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
12-01 07:07:36.008  4556  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:36.009  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:36.014  5678  5678 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,12-01 07:07:36.033  5678  5678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 07:07:36.037   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 07:07:36.037   506   921 D CommandListener: Clearing all IP addresses on wlan0
12-01 07:07:36.037   506   921 D TetherController: Setting IP forward enable = 0
12-01 07:07:36.038   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e5887a4:true
,12-01 07:07:36.038   927  2930 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,12-01 07:07:36.038   927  2930 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
12-01 07:07:36.039  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 07:07:36.042   927   944 D Tethering: MasterInitialState.processMessage what=3
12-01 07:07:36.044   927  2928 D DhcpClient: doQuit
12-01 07:07:36.044   927  2928 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
12-01 07:07:36.045  3407  3407 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
12-01 07:07:36.045   927  5386 D DhcpClient: onQuitting
12-01 07:07:36.045  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:36.046  5298  5298 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9379142 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,12-01 07:07:36.050  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:07:36.050  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 07:07:36.050  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:36.051  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 07:07:36.051  4910  4910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
12-01 07:07:36.053  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
12-01 07:07:36.053  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 07:07:36.053  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
12-01 07:07:36.053  5046  5070 E SarControlService: no key has been found,reset the power
12-01 07:07:36.053  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,12-01 07:07:36.053  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 07:07:36.053  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 07:07:36.054  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 07:07:36.054  5071  5071 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 07:07:36.055  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 07:07:36.055  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 07:07:36.055  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
12-01 07:07:36.058  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ea03000000000000ffffffff]
12-01 07:07:36.058  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 07:07:36.058  5071  5085 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,12-01 07:07:36.058   927  3526 I ActivityManager: Start proc 5703:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,12-01 07:07:36.059  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 07:07:36.059  5071  5071 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
12-01 07:07:36.060  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 07:07:36.061  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 07:07:36.063  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000eb03000000000000ffffffff]
12-01 07:07:36.063  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 07:07:36.063  5071  5085 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
12-01 07:07:36.064  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,12-01 07:07:36.064  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,12-01 07:07:36.077  5678  5678 D LocalBluetoothProfileManager: Adding local MAP profile
,12-01 07:07:36.076  3407  3407 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
12-01 07:07:36.079  5678  5678 D BluetoothMap: Create BluetoothMap proxy object
,12-01 07:07:36.085  3407  3407 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,12-01 07:07:36.090   506   921 E Netd    : netlink response contains error (No such file or directory)
,12-01 07:07:36.090   506   921 D TetherController: Setting IP forward enable = 0
12-01 07:07:36.091  5678  5678 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
12-01 07:07:36.091   927  2930 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
12-01 07:07:36.091   927  2930 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,12-01 07:07:36.105  5678  5678 D DockEventReceiver: finishStartingService: stopping service
12-01 07:07:36.107  5703  5703 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
12-01 07:07:36.114  3407  3407 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
12-01 07:07:36.114   927  3526 I ActivityManager: Killing 4949:com.google.android.calendar/u0a36 (adj 15): empty #17
,12-01 07:07:36.130  3407  3407 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,12-01 07:07:36.214  4556  4638 I bt_hci  : shut_down
,12-01 07:07:36.217  4556  4642 D bt_hwcfg: hw_epilog_process
,12-01 07:07:36.218  4556  4642 I bt_vendor: low_power_mode_cb
,12-01 07:07:36.220  4556  4642 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,12-01 07:07:36.220  4556  4642 I bt_vendor: epilog_cb
,12-01 07:07:36.220  4556  4642 I bt_hci  : epilog_finished_callback
12-01 07:07:36.222  4556  4638 I bt_hci_h4: hal_close
12-01 07:07:36.223  4556  4638 I bt_userial_vendor: device fd = 54 close
,12-01 07:07:36.232   927  2928 D wifi    : In wifi stop Hal
12-01 07:07:36.232   927  2928 D wifi    : halHandle = 0x7f5edd6400, mVM = 0x7f7b44d140, mCls = 0x100a02
12-01 07:07:36.233   927  3404 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,12-01 07:07:36.233   927  3404 D WifiHAL : Got a signal to exit!!!
12-01 07:07:36.233   927  3404 I WifiHAL : Exit wifi_event_loop
12-01 07:07:36.233   927  2928 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
12-01 07:07:36.233   927  2928 E WifiHAL : Event processing terminated
12-01 07:07:36.233   927  2928 D wifi    : In wifi cleaned up handler
12-01 07:07:36.233   927  2928 I WifiHAL : Internal cleanup completed
,12-01 07:07:36.234  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 07:07:36.235  4033  4183 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
12-01 07:07:36.236  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:36.255   927  3404 D wifi    : set interface wlan0 flags (DOWN)
,12-01 07:07:36.255   927  2928 D WifiNative-HAL: HAL event thread stopped successfully
,12-01 07:07:36.314  5703  5703 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.File.doAccess(File.java:281)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.File.exists(File.java:361)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.314  5703  5703 D StrictMode: 	,at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.314  5703  5703 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.314  5703  5703 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrap,per.java:177)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.314  5703  5703 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.k.d(PG:1187)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.k.a(PG:2107)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.v.a(PG:1161)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.y.a(PG:2188)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.e.b(PG:170)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.e.b(PG:15188)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApp,lication.a(PG:206)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.314  5703  5703 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.k.d(PG:1187)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.k.c(PG:18147)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.k.d(PG:583)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.v.a(PG:1161)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.y.a(PG:2188)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.e.b(PG:170)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.r.e.b(PG:15188)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.314  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.315  5703  5703 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.io.File.doAccess(File.java:281)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.io.File.exists(File.java:361)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.315  5703  5703 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.io.File.doAccess(File.java:281)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.io.File.exists(File.java:361)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.315  5703  5703 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.io.File.lastModified(File.java:569)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
12-01 07:07:36.315  5703  5703 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
12-01 07:07:36.331  4556  4635 D bt_stack_manager: event_shut_down_stack finished.
12-01 07:07:36.332  4556  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
12-01 07:07:36.335  4556  4634 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
12-01 07:07:36.335  4556  4556 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 07:07:36.335  4556  4556 D BtGatt.GattService: Received stop request...Stopping profile...
12-01 07:07:36.335  4556  4556 D BtGatt.GattService: stop()
12-01 07:07:36.335  4556  4556 D BtGatt.AdvertiseManager: advertise clients cleared
12-01 07:07:36.337  5678  5678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 07:07:36.337  4556  4556 V BluetoothAdapterState: isTurningOff()=false
12-01 07:07:36.337  4556  4556 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:36.337  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:36.337  4556  4556 V BluetoothAdapterState: isBleTurningOff()=true
12-01 07:07:36.338  4556  4634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
12-01 07:07:36.338  4556  4634 D BluetoothAdapterProperties: Setting state to 10
12-01 07:07:36.338  4556  4634 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
12-01 07:07:36.338  4556  4634 I BluetoothAdapterState: Entering OffState
12-01 07:07:36.340   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
12-01 07:07:36.342  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 07:07:36.350  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
12-01 07:07:36.351  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth Health object
12-01 07:07:36.351  4556  4556 I BluetoothServiceJni: cleanupNative: return from cleanup
12-01 07:07:36.351  4556  4635 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
12-01 07:07:36.352  3668  3668 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
12-01 07:07:36.363  3668  3668 D SystemUpdateService: onCreate
12-01 07:07:36.365  4556  4635 D bt_stack_manager: event_clean_up_stack finished.
12-01 07:07:36.376  3668  3668 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
12-01 07:07:36.381  5678  5678 D DockEventReceiver: finishStartingService: stopping service
12-01 07:07:36.383  4556  4556 I art     : System.exit called, status: 0
12-01 07:07:36.384  4556  4556 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
12-01 07:07:36.385  3668  3668 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
12-01 07:07:36.388  3668  5412 I iu.UploadsManager: num queued entries: 0
12-01 07:07:36.388  3668  5412 I iu.UploadsManager: num updated entries: 0
12-01 07:07:36.388  3668  5412 I iu.SyncManager: NEXT; no task
,12-01 07:07:36.400  3668  3668 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,12-01 07:07:36.402  3668  3668 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,12-01 07:07:36.403  5414  5414 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 07:07:36.407  5414  5414 D SprintDMHelper: simOperator: 
,12-01 07:07:36.407  5414  5414 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 07:07:36.418  5017  5743 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,12-01 07:07:36.422  3668  5741 I SystemUpdateService: active receiver: enabled
,12-01 07:07:36.433   927  3537 I ActivityManager: Start proc 5744:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,12-01 07:07:36.437  3668  5741 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,12-01 07:07:36.452   927  3683 I ActivityManager: Process com.android.bluetooth (pid 4556) has died
,12-01 07:07:36.454  3668  5741 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,12-01 07:07:36.454  3668  5741 I SystemUpdateService: now status is 0 (complete)
12-01 07:07:36.454  3668  5741 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,12-01 07:07:36.454  3668  5741 I SystemUpdateService: file has been verified
,12-01 07:07:36.457   927   944 D Tethering: InitialState.processMessage what=4
,12-01 07:07:36.460   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,12-01 07:07:36.472  5744  5744 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,12-01 07:07:36.474  3668  5741 I SystemUpdateService: OTA package size = 21989297
,12-01 07:07:36.494   927   938 I ActivityManager: Killing 5298:com.google.android.music:main/u0a59 (adj 15): empty #17
,12-01 07:07:36.516  3668  5741 I SystemUpdateService: showing system update notification
,12-01 07:07:36.564   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,12-01 07:07:36.567  3668  3668 D SystemUpdateService: onDestroy
,12-01 07:07:36.570   927   937 I ActivityManager: Killing 5494:com.android.defcontainer/u0a7 (adj 15): empty #17
,12-01 07:07:36.668  5703  5729 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,12-01 07:07:36.681   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bac4bb1:true
,12-01 07:07:40.933   927  3683 D WifiService: setWifiEnabled: true pid=5624, uid=10077
12-01 07:07:40.933   927  3683 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 07:07:40.942   506   921 D SoftapController: Softap fwReload - Ok
,12-01 07:07:40.947   506   921 D CommandListener: Setting iface cfg
,12-01 07:07:40.947   506   921 D CommandListener: Trying to bring down wlan0
12-01 07:07:40.948   506   921 D CommandListener: Clearing all IP addresses on wlan0
,12-01 07:07:40.954   927  2928 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 07:07:41.530   927  2928 D wifi    : set interface wlan0 flags (UP)
,12-01 07:07:41.532   927  2928 I WifiHAL : Initializing wifi
,12-01 07:07:41.533   927  2928 I WifiHAL : Creating socket
12-01 07:07:41.534   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,12-01 07:07:41.537   927  2928 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
12-01 07:07:41.537   927  2928 D wifi    : Did set static halHandle = 0x7f5edd6400
12-01 07:07:41.537   927  2928 D wifi    : halHandle = 0x7f5edd6400, mVM = 0x7f7b44d140, mCls = 0x193a
12-01 07:07:41.537   927  2928 D wifi    : array field set
12-01 07:07:41.538   927  2928 I WifiNative-HAL: interface[0] = wlan0
12-01 07:07:41.539   927  5763 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547052413952
,12-01 07:07:41.540   927  5763 D wifi    : waitForHalEvents called, vm = 0x7f7b44d140, obj = 0x193a, env = 0x7f5e29d8c0
,12-01 07:07:41.564   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:41.600  5764  5764 I wpa_supplicant: Successfully initialized wpa_supplicant
,12-01 07:07:41.623  5764  5764 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 07:07:41.633  5764  5764 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 07:07:41.633  5764  5764 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,12-01 07:07:41.641   927  2928 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,12-01 07:07:41.645  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:41.657  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:07:41.657  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 07:07:41.657  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:41.657  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 07:07:41.658   927  2928 D WifiConfigStore: Loading config and enabling all networks 
,12-01 07:07:41.670   927  2928 D WifiConfigStore: loaded 0 passpoint configs
,12-01 07:07:41.670   927  2928 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
12-01 07:07:41.671   927  2928 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,12-01 07:07:41.672   927  2928 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,12-01 07:07:41.673   927  2928 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,12-01 07:07:41.673   927  2928 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
12-01 07:07:41.673   927  2928 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
12-01 07:07:41.673   927  2928 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,12-01 07:07:41.676   927  2928 D WifiNative-HAL: Setting external_sim to 1
,12-01 07:07:41.676  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 07:07:41.676   927  2928 D wifi    : setting dfs flag to true, 0x7f616198e0
12-01 07:07:41.676   927  2928 D WifiStateMachine: Setting OUI to DA-A1-19
12-01 07:07:41.676   927  2928 D wifi    : setting scan oui 0x7f616198e0
12-01 07:07:41.676   927  2928 D WifiHAL : Sending mac address OUI
,12-01 07:07:41.680   927  2928 E native  : do suspend false
,12-01 07:07:41.687   927  2928 D wifi    : android_net_wifi_setLinkLayerStats: 1
,12-01 07:07:41.687   927   927 D RttService: SCAN_AVAILABLE : 3
12-01 07:07:41.687   927  3038 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
12-01 07:07:41.687   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,12-01 07:07:41.688   506   921 D CommandListener: Setting iface cfg
,12-01 07:07:41.691   927  2927 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,12-01 07:07:41.691   927  2927 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,12-01 07:07:41.699   927  2927 D WifiNative-HAL: p2pGetDeviceAddress
12-01 07:07:41.700   927  2927 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,12-01 07:07:41.716   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129667 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=24 mControllerEnergyUsed=91 }
,12-01 07:07:42.565   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:43.566   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:44.567   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:44.863  5764  5764 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 07:07:44.872  5764  5764 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 07:07:44.877  5764  5764 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 07:07:44.907   927  2928 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,12-01 07:07:44.908   927  2928 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
12-01 07:07:44.908   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 07:07:44.918   927  2928 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,12-01 07:07:44.951   927  2928 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,12-01 07:07:44.953  5764  5764 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,12-01 07:07:45.382  5764  5764 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,12-01 07:07:45.415  5764  5764 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,12-01 07:07:45.416  5764  5764 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,12-01 07:07:45.427   927  2928 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 07:07:45.427   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
12-01 07:07:45.427   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,12-01 07:07:45.442   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 07:07:45.453   506   921 D CommandListener: Setting iface cfg
,12-01 07:07:45.459   927  2928 D WifiStateMachine: Start Dhcp Watchdog 2
,12-01 07:07:45.465   927  5772 D DhcpClient: Receive thread started
,12-01 07:07:45.469   927  2930 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 07:07:45.469   927  2928 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
12-01 07:07:45.469   927  2930 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,12-01 07:07:45.551   927  2928 E native  : do suspend false
,12-01 07:07:45.565   927  5771 D DhcpClient: Broadcasting DHCPDISCOVER
,12-01 07:07:45.568   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:45.582   927  5772 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,12-01 07:07:45.583   927  5771 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,12-01 07:07:45.585   927  5771 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,12-01 07:07:45.602   927  5772 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,12-01 07:07:45.603   927  5771 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,12-01 07:07:45.605   506   921 D CommandListener: Setting iface cfg
,12-01 07:07:45.610   927  2928 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,12-01 07:07:45.613   927  5771 D DhcpClient: Scheduling renewal in 86399s
,12-01 07:07:45.625   927  2928 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,12-01 07:07:45.626   927  2928 D WifiConfigStore: No blacklist allowed without epno enabled
12-01 07:07:45.627   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
12-01 07:07:45.629   927  2930 D ConnectivityService: Adding iface wlan0 to network 101
12-01 07:07:45.632   927  2928 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,12-01 07:07:45.679   927  2930 E ConnectivityService: Unexpected mtu value: 0, wlan0
,12-01 07:07:45.679   927  2930 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,12-01 07:07:45.682   927  2930 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,12-01 07:07:45.684   927  2930 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,12-01 07:07:45.686   927  2930 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,12-01 07:07:45.692   927  2930 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 07:07:45.699   927  2930 D ConnectivityService: scheduleUnvalidatedPrompt 101
,12-01 07:07:45.700   927  2930 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
12-01 07:07:45.700   927  2930 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
12-01 07:07:45.700   927  2930 D ConnectivityService:    accepting network in place of null
12-01 07:07:45.700   927  2928 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
12-01 07:07:45.700   927  2928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 07:07:45.701   927  2930 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 07:07:45.721   927  5770 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133672, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 07:07:45.723   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 07:07:45.743   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 07:07:45.747   927  2930 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,12-01 07:07:45.747  3735  3871 W QCNEJ   : |CORE| network available: 101
12-01 07:07:45.747   927  2930 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,12-01 07:07:45.748   927  2930 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,12-01 07:07:45.748  3735  3871 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
12-01 07:07:45.750  3735  3871 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
12-01 07:07:45.750  3735  3871 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
12-01 07:07:45.750   927   944 D Tethering: MasterInitialState.processMessage what=3
12-01 07:07:45.754  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 07:07:45.754  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 07:07:45.754  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:45.755  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 07:07:45.759  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
12-01 07:07:45.759  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 07:07:45.760  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
12-01 07:07:45.760  5046  5070 E SarControlService: no key has been found,reset the power
12-01 07:07:45.760  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 07:07:45.760  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,12-01 07:07:45.760  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,12-01 07:07:45.761  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 07:07:45.761  5071  5071 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 07:07:45.763  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 07:07:45.763  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 07:07:45.763  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
12-01 07:07:45.765  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 07:07:45.765  5071  5071 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
12-01 07:07:45.767  4910  4910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,12-01 07:07:45.769  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ec03000000000000ffffffff]
,12-01 07:07:45.770  3668  3668 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
12-01 07:07:45.770  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 07:07:45.771  5071  5085 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,12-01 07:07:45.773  3668  3668 D SystemUpdateService: onCreate
,12-01 07:07:45.774  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 07:07:45.774  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 07:07:45.778  3668  3668 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
12-01 07:07:45.779  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ed03000000000000ffffffff]
12-01 07:07:45.779  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 07:07:45.780  5071  5085 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
12-01 07:07:45.780  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 07:07:45.780  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,12-01 07:07:45.789  3668  3668 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,12-01 07:07:45.794  3668  5412 I iu.UploadsManager: num queued entries: 0
,12-01 07:07:45.794  3668  5412 I iu.UploadsManager: num updated entries: 0
12-01 07:07:45.795  3668  5412 I iu.SyncManager: NEXT; no task
,12-01 07:07:45.797  3668  5782 I SystemUpdateService: active receiver: enabled
,12-01 07:07:45.800  3668  3668 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,12-01 07:07:45.801  3668  3668 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,12-01 07:07:45.803  5414  5414 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 07:07:45.807  5414  5414 D SprintDMHelper: simOperator: 
12-01 07:07:45.807  5414  5414 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 07:07:45.828  3668  5782 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,12-01 07:07:45.840  3668  5782 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,12-01 07:07:45.840  3668  5782 I SystemUpdateService: now status is 0 (complete)
12-01 07:07:45.840  3668  5782 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 07:07:45.840  3668  5782 I SystemUpdateService: file has been verified
12-01 07:07:45.840  3668  5782 I SystemUpdateService: OTA package size = 21989297
,12-01 07:07:45.846  3668  5782 I SystemUpdateService: showing system update notification
,12-01 07:07:45.854  3668  3668 D SystemUpdateService: onDestroy
,12-01 07:07:45.871   927  5769 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:81a::200e
,12-01 07:07:45.940   927   938 D WifiService: setWifiEnabled: false pid=5624, uid=10077
,12-01 07:07:45.940   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 07:07:45.945   927  2928 D WifiStateMachine: WifiStateMachine: Leaving Connected state
12-01 07:07:45.945   927  2928 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
12-01 07:07:45.945   927  2928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 07:07:45.946   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 07:07:45.960   927  5771 D DhcpClient: Clearing IP address
,12-01 07:07:45.960   506   921 D CommandListener: Clearing all IP addresses on wlan0
,12-01 07:07:45.962   506   921 D CommandListener: Setting iface cfg
,12-01 07:07:45.967   927  5772 D DhcpClient: Receive thread stopped
,12-01 07:07:45.968  3521  5783 V NativeCrypto: SSL handshake aborted: ssl=0x7f7158a880: I/O error during system call, Connection timed out
12-01 07:07:45.969   927  5769 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81a::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
12-01 07:07:45.970   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
12-01 07:07:45.971  5017  5787 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,12-01 07:07:45.982   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,12-01 07:07:45.982   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,12-01 07:07:45.986   533   533 E Parcel  : Reading a NULL string not supported here.
12-01 07:07:45.986   927   927 D RttService: SCAN_AVAILABLE : 1
,12-01 07:07:45.987   927  3038 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
12-01 07:07:45.988   927  2930 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
12-01 07:07:45.989   927  2928 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
12-01 07:07:45.991  3735  3871 W QCNEJ   : |CORE| network lost: 101
,12-01 07:07:45.992   927  2928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 07:07:45.993  3735  3871 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.22.14 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnec,ted(IoBridge.java:223)
12-01 07:07:46.000  5017  5787 W Babel_NetworkConnectionCheckingService: 	... 23 more
12-01 07:07:46.000  5017  5787 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,12-01 07:07:46.016   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 07:07:46.039   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
12-01 07:07:46.039   506   921 D CommandListener: Clearing all IP addresses on wlan0
12-01 07:07:46.039   927  2930 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,12-01 07:07:46.040   927  2930 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,12-01 07:07:46.041   927   944 D Tethering: MasterInitialState.processMessage what=3
,12-01 07:07:46.043  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:07:46.043  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 07:07:46.043  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:46.043  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 07:07:46.044   927  2928 D DhcpClient: doQuit
12-01 07:07:46.044   927  2928 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
12-01 07:07:46.044   927  5771 D DhcpClient: onQuitting
,12-01 07:07:46.045  5764  5764 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
12-01 07:07:46.046  4910  4910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,12-01 07:07:46.050  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,12-01 07:07:46.051  3668  3668 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
12-01 07:07:46.051  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:07:46.051  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 07:07:46.051  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:46.051  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 07:07:46.051  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 07:07:46.051  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
12-01 07:07:46.051  5046  5070 E SarControlService: no key has been found,reset the power
12-01 07:07:46.051  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 07:07:46.051  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 07:07:46.052  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 07:07:46.053  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 07:07:46.053  5071  5071 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 07:07:46.053  5764  5764 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
12-01 07:07:46.055  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 07:07:46.055  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 07:07:46.055  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,12-01 07:07:46.056  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,12-01 07:07:46.056  5071  5071 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,12-01 07:07:46.056  5764  5764 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
12-01 07:07:46.059  3668  3668 D SystemUpdateService: onCreate
12-01 07:07:46.060  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ee03000000000000ffffffff]
12-01 07:07:46.061  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,12-01 07:07:46.061  5071  5085 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
12-01 07:07:46.061  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 07:07:46.061  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 07:07:46.064  3668  3668 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
12-01 07:07:46.064  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000ef03000000000000ffffffff]
,12-01 07:07:46.064  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 07:07:46.064  5071  5085 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
12-01 07:07:46.065  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 07:07:46.065  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
12-01 07:07:46.072  3668  5799 I SystemUpdateService: active receiver: enabled
,12-01 07:07:46.074  3668  3668 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,12-01 07:07:46.079  3668  5412 I iu.UploadsManager: num queued entries: 0
12-01 07:07:46.079  3668  5412 I iu.UploadsManager: num updated entries: 0
12-01 07:07:46.080  3668  5412 I iu.SyncManager: NEXT; no task
,12-01 07:07:46.082  5764  5764 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,12-01 07:07:46.082  3668  3668 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,12-01 07:07:46.083  3668  3668 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,12-01 07:07:46.085  5414  5414 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 07:07:46.090  5414  5414 D SprintDMHelper: simOperator: 
12-01 07:07:46.090  5414  5414 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 07:07:46.092  5764  5764 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,12-01 07:07:46.097  3668  5799 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,12-01 07:07:46.098   506   921 E Netd    : netlink response contains error (No such file or directory)
,12-01 07:07:46.099   927  2930 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,12-01 07:07:46.102  5017  5803 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,12-01 07:07:46.104  3668  5799 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,12-01 07:07:46.104  3668  5799 I SystemUpdateService: now status is 0 (complete)
12-01 07:07:46.104  3668  5799 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 07:07:46.104  3668  5799 I SystemUpdateService: file has been verified
12-01 07:07:46.104  3668  5799 I SystemUpdateService: OTA package size = 21989297
,12-01 07:07:46.119  3668  5799 I SystemUpdateService: showing system update notification
,12-01 07:07:46.127  3668  3668 D SystemUpdateService: onDestroy
,12-01 07:07:46.197   927  2928 D wifi    : In wifi stop Hal
,12-01 07:07:46.197   927  2928 D wifi    : halHandle = 0x7f5edd6400, mVM = 0x7f7b44d140, mCls = 0x193a
12-01 07:07:46.197   927  5763 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,12-01 07:07:46.197   927  5763 D WifiHAL : Got a signal to exit!!!
12-01 07:07:46.197   927  5763 I WifiHAL : Exit wifi_event_loop
12-01 07:07:46.198   927  2928 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
12-01 07:07:46.198   927  2928 E WifiHAL : Event processing terminated
12-01 07:07:46.198   927  2928 D wifi    : In wifi cleaned up handler
12-01 07:07:46.198   927  2928 I WifiHAL : Internal cleanup completed
12-01 07:07:46.198  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
12-01 07:07:46.200  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:46.200  4033  4183 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 07:07:46.220   927  5763 D wifi    : set interface wlan0 flags (DOWN)
,12-01 07:07:46.221   927  2928 D WifiNative-HAL: HAL event thread stopped successfully
,12-01 07:07:46.427   927   944 D Tethering: InitialState.processMessage what=4
,12-01 07:07:46.433   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,12-01 07:07:46.569   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,12-01 07:07:46.747   927  2930 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,12-01 07:07:50.977   927   944 I ActivityManager: Start proc 5805:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,12-01 07:07:51.059  5805  5805 D AdapterServiceConfig: Adding HeadsetService
,12-01 07:07:51.059  5805  5805 D AdapterServiceConfig: Adding A2dpService
12-01 07:07:51.060  5805  5805 D AdapterServiceConfig: Adding HidService
12-01 07:07:51.060  5805  5805 D AdapterServiceConfig: Adding HealthService
12-01 07:07:51.060  5805  5805 D AdapterServiceConfig: Adding PanService
,12-01 07:07:51.060  5805  5805 D AdapterServiceConfig: Adding GattService
12-01 07:07:51.060  5805  5805 D AdapterServiceConfig: Adding BluetoothMapService
12-01 07:07:51.060  5805  5805 D AdapterServiceConfig: Adding SapService
,12-01 07:07:51.071   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc0cacf:true
,12-01 07:07:51.071  5805  5805 D BluetoothAdapterState: make() - Creating AdapterState
,12-01 07:07:51.074  5805  5805 I bt_bluedroid: init
12-01 07:07:51.074  5805  5817 I BluetoothAdapterState: Entering OffState
,12-01 07:07:51.076  5805  5818 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,12-01 07:07:51.076  5805  5818 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
12-01 07:07:51.076  5805  5818 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,12-01 07:07:51.076  5805  5818 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
12-01 07:07:51.077  5805  5805 I bt_bluedroid: get_profile_interface socket
,12-01 07:07:51.079  5805  5821 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,12-01 07:07:51.079  5805  5805 I bt_bluedroid: get_profile_interface sdp
,12-01 07:07:51.080  5805  5821 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 07:07:51.084  5805  5816 I bt_bluedroid: config_hci_snoop_log
,12-01 07:07:51.085   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
12-01 07:07:51.088  5805  5817 D BluetoothAdapterState: Current state: OFF, message: 0
12-01 07:07:51.088  5805  5817 D BluetoothAdapterProperties: Setting state to 14
,12-01 07:07:51.089  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,12-01 07:07:51.090  5805  5817 D BluetoothBondStateMachine: make
,12-01 07:07:51.092  5805  5822 I BluetoothBondStateMachine: StableState(): Entering Off State
,12-01 07:07:51.094  5805  5817 I BluetoothAdapterState: Entering PendingCommandState
,12-01 07:07:51.095  5805  5805 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,12-01 07:07:51.097  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:07:51.098  5805  5805 D BtGatt.DebugUtils: handleDebugAction() action=null
,12-01 07:07:51.099  5805  5805 D BtGatt.GattService: Received start request. Starting profile...
12-01 07:07:51.099  5805  5805 D BtGatt.GattService: start()
,12-01 07:07:51.099  5805  5805 I bt_bluedroid: get_profile_interface gatt
12-01 07:07:51.100  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:07:51.100  5805  5805 D BtGatt.AdvertiseManager: advertise manager created
,12-01 07:07:51.105  5805  5805 V BluetoothAdapterState: isTurningOff()=false
,12-01 07:07:51.105  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:51.105  5805  5805 V BluetoothAdapterState: isBleTurningOn()=true
12-01 07:07:51.105  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:51.105  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,12-01 07:07:51.106  5805  5817 I bt_bluedroid: bt_bluedroid
12-01 07:07:51.106  5805  5818 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,12-01 07:07:51.107  5805  5818 I bt_hci  : start_up
,12-01 07:07:51.113  5805  5818 I bt_vendor: alloc value 0xf3c65871
,12-01 07:07:51.113  5805  5818 I bt_vendor: init
12-01 07:07:51.113  5805  5818 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
12-01 07:07:51.113  5805  5818 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,12-01 07:07:51.224  5805  5818 D bt_hci  : start_up starting async portion
,12-01 07:07:51.225  5805  5825 I bt_hci  : event_finish_startup
,12-01 07:07:51.225  5805  5825 I bt_hci_h4: hal_open
,12-01 07:07:51.225  5805  5825 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
12-01 07:07:51.224  5826  5826 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
12-01 07:07:51.228  5805  5825 I bt_userial_vendor: device fd = 54 open
,12-01 07:07:51.243  5805  5825 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 07:07:51.246  5805  5825 D bt_hwcfg: Chipset BCM4358A3
,12-01 07:07:51.246  5805  5825 D bt_hwcfg: Target name = [BCM4358A3]
12-01 07:07:51.246  5805  5825 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,12-01 07:07:51.379   927  2735 I hubconnection: sensorhub said: 'set_bias 3: -4.8000, 0.0000, 0.0000'
,12-01 07:07:51.648  5805  5825 I bt_hwcfg: bt vendor lib: set UART baud 115200
,12-01 07:07:51.648  5805  5825 D bt_hwcfg: Settlement delay -- 100 ms
12-01 07:07:51.649  5805  5825 I bt_hwcfg: Setting fw settlement delay to 100 
,12-01 07:07:51.782  5805  5825 I bt_hwcfg: bt vendor lib: set UART baud 3000000
12-01 07:07:51.783  5805  5825 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
12-01 07:07:51.784  5805  5825 I bt_hwcfg: vendor lib fwcfg completed
12-01 07:07:51.785  5805  5825 I bt_vendor: firmware callback
12-01 07:07:51.785  5805  5825 I bt_hci  : firmware_config_callback
,12-01 07:07:51.793  5805  5828 I bt_btu  : btu_task pending for preload complete event
,12-01 07:07:51.793  5805  5828 I bt_btu_task: Bluetooth chip preload is complete
12-01 07:07:51.793  5805  5828 I bt_btu  : btu_task received preload complete event
,12-01 07:07:51.800  5805  5828 I         : BTE_InitTraceLevels -- TRC_HCI
,12-01 07:07:51.801  5805  5828 I         : BTE_InitTraceLevels -- TRC_L2CAP
12-01 07:07:51.801  5805  5828 I         : BTE_InitTraceLevels -- TRC_RFCOMM
12-01 07:07:51.801  5805  5828 I         : BTE_InitTraceLevels -- TRC_AVDT
12-01 07:07:51.801  5805  5828 I         : BTE_InitTraceLevels -- TRC_AVRC
12-01 07:07:51.801  5805  5828 I         : BTE_InitTraceLevels -- TRC_A2D
,12-01 07:07:51.801  5805  5828 I         : BTE_InitTraceLevels -- TRC_BNEP
12-01 07:07:51.801  5805  5828 I         : BTE_InitTraceLevels -- TRC_BTM
12-01 07:07:51.802  5805  5828 I         : BTE_InitTraceLevels -- TRC_GAP
,12-01 07:07:51.802  5805  5828 I         : BTE_InitTraceLevels -- TRC_PAN
12-01 07:07:51.802  5805  5828 I         : BTE_InitTraceLevels -- TRC_SDP
12-01 07:07:51.802  5805  5828 I         : BTE_InitTraceLevels -- TRC_GATT
12-01 07:07:51.802  5805  5828 I         : BTE_InitTraceLevels -- TRC_SMP
,12-01 07:07:51.802  5805  5828 I         : BTE_InitTraceLevels -- TRC_BTAPP
12-01 07:07:51.802  5805  5828 I         : BTE_InitTraceLevels -- TRC_BTIF
,12-01 07:07:51.887  5805  5828 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3be3549
,12-01 07:07:51.887  5805  5828 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3be3549 
,12-01 07:07:51.910  5805  5821 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,12-01 07:07:51.911  5805  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,12-01 07:07:51.911  5805  5821 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,12-01 07:07:51.914  5805  5821 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 07:07:51.916  5805  5821 D BluetoothAdapterProperties: Scan Mode:20
,12-01 07:07:51.917  5805  5821 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 07:07:51.917  5805  5821 D bt_hci  : do_postload posting postload work item
12-01 07:07:51.917  5805  5825 I bt_hci  : event_postload
12-01 07:07:51.918  5805  5825 I bt_vendor: sco_config_cb
12-01 07:07:51.918  5805  5825 I bt_hci  : sco_config_callback postload finished.
12-01 07:07:51.921  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:07:51.923  5805  5821 D bt_bte_conf: Device ID record 1 : primary
,12-01 07:07:51.923  5805  5821 D bt_bte_conf:   vendorId            = 000f
12-01 07:07:51.923  5805  5821 D bt_bte_conf:   vendorIdSource      = 0001
12-01 07:07:51.923  5805  5821 D bt_bte_conf:   product             = 1200
,12-01 07:07:51.923  5805  5821 D bt_bte_conf:   version             = 1436
12-01 07:07:51.923  5805  5821 D bt_bte_conf:   clientExecutableURL = 
,12-01 07:07:51.923  5805  5821 D bt_bte_conf:   serviceDescription  = 
12-01 07:07:51.923  5805  5821 D bt_bte_conf:   documentationURL    = 
12-01 07:07:51.923  5805  5821 D bt_bte_conf: bte_load_did_conf no section named DID2.
12-01 07:07:51.924  5805  5818 D bt_stack_manager: event_start_up_stack finished
,12-01 07:07:51.924  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
12-01 07:07:51.924  5805  5817 D BluetoothAdapterProperties: Setting state to 15
12-01 07:07:51.925  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,12-01 07:07:51.925  5805  5825 I bt_vendor: low_power_mode_cb
,12-01 07:07:51.926  5805  5817 I BluetoothAdapterState: Entering BleOnState
,12-01 07:07:51.929  5805  5817 D BluetoothAdapterState: Current state: BLE ON, message: 1
,12-01 07:07:51.929  5805  5817 D BluetoothAdapterProperties: Setting state to 11
12-01 07:07:51.929  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
12-01 07:07:51.933  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:07:51.934  5805  5805 D HeadsetService: Received start request. Starting profile...
,12-01 07:07:51.937  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:51.938  5805  5805 I BluetoothHeadsetServiceJni: classInitNative: succeeds
12-01 07:07:51.938  5805  5805 D HeadsetStateMachine: make
,12-01 07:07:51.946  5805  5817 I BluetoothAdapterState: Entering PendingCommandState
,12-01 07:07:51.947  5805  5805 D HeadsetStateMachine: max_hf_connections = 1
12-01 07:07:51.947  5805  5805 I bt_bluedroid: get_profile_interface handsfree
12-01 07:07:51.947  5805  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
12-01 07:07:51.947  5805  5821 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,12-01 07:07:51.952  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:07:51.952  5805  5805 D A2dpService: Received start request. Starting profile...
,12-01 07:07:51.953  5805  5805 I BluetoothAvrcpServiceJni: classInitNative: succeeds
12-01 07:07:51.953  5805  5805 I bt_bluedroid: get_profile_interface avrcp
,12-01 07:07:51.958  5805  5805 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,12-01 07:07:51.958  5805  5805 I BluetoothA2dpServiceJni: classInitNative: succeeds
12-01 07:07:51.958  5805  5805 D A2dpStateMachine: make
12-01 07:07:51.959  5805  5805 I bt_bluedroid: get_profile_interface a2dp
12-01 07:07:51.959  5805  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,12-01 07:07:51.961  5805  5836 D A2dpStateMachine: Enter Disconnected: -2
,12-01 07:07:51.961  5805  5805 I BluetoothHidServiceJni: classInitNative: succeeds
12-01 07:07:51.962  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:07:51.963  5678  5678 D BluetoothInputDevice: Proxy object connected
,12-01 07:07:51.963  5678  5678 D HidProfile: Bluetooth service connected
12-01 07:07:51.964  5805  5805 D HidService: Received start request. Starting profile...
12-01 07:07:51.965  5805  5805 I bt_bluedroid: get_profile_interface hidhost
12-01 07:07:51.965  5805  5805 D HidService: setHidService(): set to: null
12-01 07:07:51.965  5805  5821 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bc456d
12-01 07:07:51.965  5805  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
12-01 07:07:51.965  5805  5805 I BluetoothHealthServiceJni: classInitNative: succeeds
,12-01 07:07:51.966  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:07:51.967  5805  5805 D HealthService: Received start request. Starting profile...
,12-01 07:07:51.968  5805  5805 I bt_bluedroid: get_profile_interface health
,12-01 07:07:51.969  5805  5805 I BluetoothPanServiceJni: classInitNative(L105): succeeds
12-01 07:07:51.970  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:07:51.971  5678  5678 D BluetoothPan: BluetoothPAN Proxy object connected
,12-01 07:07:51.971  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 07:07:51.971  5678  5678 D PanProfile: Bluetooth service connected
12-01 07:07:51.972  5805  5805 D PanService: Received start request. Starting profile...
12-01 07:07:51.972  5805  5805 D BluetoothPanServiceJni: initializeNative(L110): pan
12-01 07:07:51.972  5805  5805 I bt_bluedroid: get_profile_interface pan
12-01 07:07:51.973  5805  5821 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
12-01 07:07:51.975  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:07:51.977  5805  5805 D BluetoothMapService: Received start request. Starting profile...
12-01 07:07:51.977  5805  5805 D BluetoothMapService: start()
,12-01 07:07:51.980  5805  5805 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
12-01 07:07:51.980  5805  5805 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
12-01 07:07:51.980  5805  5805 D BluetoothMapAppObserver: createReceiver()
,12-01 07:07:51.982  5805  5805 D BluetoothMapAppObserver: initObservers()
12-01 07:07:51.982  5805  5805 D BluetoothMapAppObserver: getEnabledAccountItems()
,12-01 07:07:51.988  5805  5805 V SapService: SapBinder()
,12-01 07:07:51.988  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:07:51.989  5805  5805 D SapService: Received start request. Starting profile...
,12-01 07:07:51.989  5805  5805 V SapService: start()
12-01 07:07:51.989  5678  5678 D BluetoothMap: Proxy object connected
12-01 07:07:51.990  5678  5678 D MapProfile: Bluetooth service connected
12-01 07:07:51.990  5678  5678 D BluetoothMap: getConnectedDevices()
12-01 07:07:51.990  5805  5805 V BluetoothAdapterState: isTurningOff()=false
,12-01 07:07:51.990  5805  5805 V BluetoothAdapterState: isTurningOn()=true
12-01 07:07:51.990  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:51.991  5805  5834 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
12-01 07:07:51.991  5678  5678 D BluetoothMap: Bluetooth is Not enabled
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isTurningOff()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isTurningOn()=true
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isTurningOff()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isTurningOn()=true
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isTurningOff()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isTurningOn()=true
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:51.991  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isTurningOff()=false
12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isTurningOn()=true
12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isTurningOff()=false
12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isTurningOn()=true
12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 07:07:51.992  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:51.993  5805  5805 V BluetoothAdapterState: isTurningOff()=false
,12-01 07:07:51.993  5805  5805 V BluetoothAdapterState: isTurningOn()=true
12-01 07:07:51.993  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:51.993  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:51.994  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
12-01 07:07:51.994  5805  5817 D BluetoothAdapterProperties: ScanMode =  20
12-01 07:07:51.994  5805  5817 D BluetoothAdapterProperties: State =  11
12-01 07:07:51.994  5805  5817 D BluetoothAdapterProperties: Setting state to 12
12-01 07:07:51.994  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,12-01 07:07:51.994  5805  5817 I BluetoothAdapterState: Entering OnState
12-01 07:07:51.995  3074  3087 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 07:07:51.996  5805  5821 D BluetoothAdapterProperties: Scan Mode:21
12-01 07:07:51.997  5805  5821 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 07:07:51.997  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,12-01 07:07:51.998   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 07:07:51.998  3074  3942 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 07:07:51.998   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 07:07:51.999  5678  5691 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 07:07:52.000   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 07:07:52.000  3074  3085 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:07:52.002  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 07:07:52.002  3074  5623 D BluetoothMap: onBluetoothStateChange: up=true
12-01 07:07:52.003  3074  3074 D BluetoothA2dp: Proxy object connected
12-01 07:07:52.003  3756  4000 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 07:07:52.004  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 07:07:52.004  5678  5689 D BluetoothPan: onBluetoothStateChange on: true
12-01 07:07:52.004  3074  3085 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 07:07:52.005  3074  3074 D BluetoothMap: Proxy object connected
12-01 07:07:52.005  3074  3074 D MapProfile: Bluetooth service connected
12-01 07:07:52.005  3074  3074 D BluetoothMap: getConnectedDevices()
12-01 07:07:52.006  5678  5691 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 07:07:52.006   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 07:07:52.006   927   927 D BluetoothA2dp: Proxy object connected
12-01 07:07:52.006  5678  5689 D BluetoothMap: onBluetoothStateChange: up=true
12-01 07:07:52.007  3074  3942 D BluetoothPan: onBluetoothStateChange on: true
12-01 07:07:52.007  3074  3074 D BluetoothInputDevice: Proxy object connected
12-01 07:07:52.007  3074  3074 D HidProfile: Bluetooth service connected
12-01 07:07:52.007  5805  5805 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,12-01 07:07:52.008  5805  5805 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
12-01 07:07:52.009  3074  3074 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 07:07:52.009  3074  3074 D PanProfile: Bluetooth service connected
12-01 07:07:52.009  5805  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:07:52.010   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
12-01 07:07:52.010  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,12-01 07:07:52.012  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:52.013  5805  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:07:52.013  5678  5678 D LocalBluetoothProfileManager: Adding local A2DP profile
,12-01 07:07:52.014  5805  5805 D ObexServerSockets: Succeed to create listening sockets 
12-01 07:07:52.015  5805  5805 D ObexServerSockets0: startAccept()
,12-01 07:07:52.015  5805  5805 D ObexServerSockets0: prepareForNewConnect()
,12-01 07:07:52.017  5678  5678 D LocalBluetoothProfileManager: Adding local HEADSET profile
,12-01 07:07:52.017  5805  5805 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
12-01 07:07:52.017  5805  5805 D BluetoothSdpJni: SDP Create record success - handle: 0
12-01 07:07:52.018  5805  5843 D ObexServerSockets0: Accepting socket connection...
12-01 07:07:52.018  5805  5844 D ObexServerSockets0: Accepting socket connection...
12-01 07:07:52.018  5805  5805 D BluetoothMapService: onReceive
12-01 07:07:52.018  5805  5805 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 07:07:52.018  5805  5805 D BluetoothMapService: STATE_ON
12-01 07:07:52.020  5805  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:07:52.021  5805  5845 D BluetoothSdpJni: sdpCreateSapsRecordNative:
12-01 07:07:52.021  5805  5845 D BluetoothSdpJni: SDP Create record success - handle: 1
12-01 07:07:52.023  5678  5678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 07:07:52.026  5678  5678 D BluetoothA2dp: Proxy object connected
,12-01 07:07:52.029  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 07:07:52.031  5678  5678 D DockEventReceiver: finishStartingService: stopping service
,12-01 07:07:52.036  5678  5678 D BluetoothPbap: Proxy object connected
,12-01 07:07:52.037  5678  5678 D PbapServerProfile: Bluetooth service connected
,12-01 07:07:52.042  5805  5805 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,12-01 07:07:52.042  3074  3074 D BluetoothPbap: Proxy object connected
12-01 07:07:52.042  5805  5805 D ObexServerSockets0: prepareForNewConnect()
12-01 07:07:52.042  3074  3074 D PbapServerProfile: Bluetooth service connected
,12-01 07:07:52.047  5805  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 07:07:52.060  5805  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 07:07:52.061  5805  5853 I BtOppRfcommListener: Accept thread started.
,12-01 07:07:52.100   927   927 D BluetoothHeadset: Proxy object connected
12-01 07:07:52.100   927   927 D BluetoothHeadset: Proxy object connected
12-01 07:07:52.101   927   944 D BluetoothHeadset: Proxy object connected
,12-01 07:07:52.101  3756  3791 D BluetoothHeadset: Proxy object connected
12-01 07:07:52.101   927   927 D BluetoothHeadset: Proxy object connected
12-01 07:07:52.102  3074  3087 D BluetoothHeadset: Proxy object connected
12-01 07:07:52.102  3074  3074 D HeadsetProfile: Bluetooth service connected
,12-01 07:07:52.104  3756  3784 D BluetoothHeadset: Proxy object connected
,12-01 07:07:52.121  5678  5689 D BluetoothHeadset: Proxy object connected
12-01 07:07:52.122  5678  5678 D HeadsetProfile: Bluetooth service connected
,12-01 07:07:53.706   927  2930 D ConnectivityService: handlePromptUnvalidated 101
,12-01 07:07:55.958  5805  5817 D BluetoothAdapterState: Current state: ON, message: 23
12-01 07:07:55.959  5805  5817 D BluetoothAdapterProperties: Setting state to 13
,12-01 07:07:55.959  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
12-01 07:07:55.960  5805  5817 D BluetoothAdapterProperties: onBluetoothDisable()
12-01 07:07:55.962  5805  5817 I BluetoothAdapterState: Entering PendingCommandState
,12-01 07:07:55.965  5805  5805 D BluetoothMapService: onReceive
,12-01 07:07:55.965  5805  5805 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,12-01 07:07:55.966  5805  5805 D BluetoothMapService: STATE_TURNING_OFF
12-01 07:07:55.966  5805  5805 D BluetoothMapService: MAP Service closeService in
12-01 07:07:55.966  5805  5805 D BluetoothMapMasInstance0: MAP Service shutdown
12-01 07:07:55.966  5805  5805 D ObexServerSockets0: shutdown(block = true)
12-01 07:07:55.967  5805  5805 D ObexServerSockets0: shutdown called from another thread - interrupt().
,12-01 07:07:55.967  5805  5805 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 07:07:55.968  5805  5844 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,12-01 07:07:55.968  5805  5843 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
12-01 07:07:55.969  5805  5830 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
12-01 07:07:55.971  5805  5821 D BluetoothAdapterProperties: Scan Mode:20
12-01 07:07:55.971  5805  5805 I BtOppRfcommListener: stopping Accept Thread
12-01 07:07:55.972  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,12-01 07:07:55.974  5805  5853 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
12-01 07:07:55.978  5805  5853 I BtOppRfcommListener: BluetoothSocket listen thread finished
12-01 07:07:55.979  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:07:55.979  5624  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 07:07:55.980  5805  5805 D HeadsetService: Received stop request...Stopping profile...
12-01 07:07:55.981  5624  5624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 07:07:55.981  5624  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 07:07:55.984  5678  5678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 07:07:55.985  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:55.988   927   927 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:55.988   927   927 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:55.988  3756  3993 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:55.989  5678  5691 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:55.990   927   927 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:55.990  3074  3085 D BluetoothHeadset: Proxy object disconnected
12-01 07:07:55.992  5805  5805 D A2dpService: Received stop request...Stopping profile...
12-01 07:07:55.993  5805  5836 D A2dpStateMachine: Exit Disconnected: -1
12-01 07:07:55.994  5678  5678 D DockEventReceiver: finishStartingService: stopping service
12-01 07:07:55.995  5678  5678 D HeadsetProfile: Bluetooth service disconnected
,12-01 07:07:55.997   927   927 D BluetoothA2dp: Proxy object disconnected
12-01 07:07:55.997  5678  5678 D BluetoothA2dp: Proxy object disconnected
12-01 07:07:55.998  3074  3074 D HeadsetProfile: Bluetooth service disconnected
12-01 07:07:55.998  3074  3074 D BluetoothA2dp: Proxy object disconnected
,12-01 07:07:56.000  5805  5805 D HidService: Received stop request...Stopping profile...
12-01 07:07:56.000  5805  5805 D HidService: Stopping Bluetooth HidService
12-01 07:07:56.001  3074  3074 D BluetoothInputDevice: Proxy object disconnected
,12-01 07:07:56.001  3074  3074 D HidProfile: Bluetooth service disconnected
12-01 07:07:56.002  5805  5805 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:56.002  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.002  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.002  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:56.003  5805  5805 D HealthService: Received stop request...Stopping profile...
12-01 07:07:56.005  5678  5678 D BluetoothInputDevice: Proxy object disconnected
,12-01 07:07:56.005  5678  5678 D HidProfile: Bluetooth service disconnected
12-01 07:07:56.007  5805  5805 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
12-01 07:07:56.007  5805  5805 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
12-01 07:07:56.007  5805  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
12-01 07:07:56.007  5805  5828 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:56.007  5805  5828 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:56.007  5805  5828 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,12-01 07:07:56.008  5805  5821 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
12-01 07:07:56.008  5805  5805 D PanService: Received stop request...Stopping profile...
12-01 07:07:56.010  3074  3074 D BluetoothPan: BluetoothPAN Proxy object disconnected
12-01 07:07:56.010  3074  3074 D PanProfile: Bluetooth service disconnected
12-01 07:07:56.011  5805  5805 D BluetoothMapService: Received stop request...Stopping profile...
12-01 07:07:56.011  5805  5805 D BluetoothMapService: stop()
,12-01 07:07:56.012  5678  5678 D BluetoothPan: BluetoothPAN Proxy object disconnected
12-01 07:07:56.012  5678  5678 D PanProfile: Bluetooth service disconnected
12-01 07:07:56.012  5805  5805 D BluetoothMapAppObserver: deinitObservers()
12-01 07:07:56.012  5805  5805 D BluetoothMapAppObserver: removeReceiver()
12-01 07:07:56.012  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 07:07:56.015  3074  3074 D BluetoothMap: Proxy object disconnected
,12-01 07:07:56.015  3074  3074 D MapProfile: Bluetooth service disconnected
,12-01 07:07:56.018  5805  5805 D SapService: Received stop request...Stopping profile...
,12-01 07:07:56.018  5805  5805 V SapService: stop()
,12-01 07:07:56.020  5805  5805 V BluetoothAdapterState: isTurningOff()=true
,12-01 07:07:56.020  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.020  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.020  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:56.021  5805  5828 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:56.021  5805  5805 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:56.021  5805  5828 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 07:07:56.021  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.021  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.021  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:56.021  5805  5828 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 07:07:56.021  5805  5828 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 07:07:56.021  5805  5828 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 07:07:56.021  5805  5828 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 07:07:56.021  5805  5805 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
12-01 07:07:56.021  5805  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
12-01 07:07:56.021  5805  5805 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
12-01 07:07:56.022  5805  5805 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:56.022  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.022  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.022  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:56.022  5678  5678 D BluetoothMap: Proxy object disconnected
12-01 07:07:56.022  5678  5678 D MapProfile: Bluetooth service disconnected
12-01 07:07:56.022  5805  5821 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 07:07:56.022  5805  5805 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
12-01 07:07:56.022  5805  5821 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,12-01 07:07:56.022  5805  5805 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
12-01 07:07:56.023  5805  5805 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:56.023  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.023  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.023  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:56.023  5805  5805 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
12-01 07:07:56.023  5805  5805 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,12-01 07:07:56.026  5805  5805 D BluetoothMapService: MAP Service closeService in
12-01 07:07:56.026  3074  3074 D BluetoothPbap: Proxy object disconnected
12-01 07:07:56.026  3074  3074 D PbapServerProfile: Bluetooth service disconnected
12-01 07:07:56.026  5805  5805 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:56.026  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.026  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.026  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:07:56.026  5805  5805 D BluetoothMapService: cleanup()
,12-01 07:07:56.026  5805  5805 D BluetoothMapService: MAP Service closeService in
12-01 07:07:56.027  5805  5805 V BluetoothAdapterState: isTurningOff()=true
12-01 07:07:56.027  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.027  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.027  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 07:07:56.027  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
12-01 07:07:56.027  5805  5817 D BluetoothAdapterProperties: Setting state to 15
12-01 07:07:56.027  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
12-01 07:07:56.027  5805  5817 I BluetoothAdapterState: Entering BleOnState
,12-01 07:07:56.030  3074  3085 D BluetoothPbap: onBluetoothStateChange: up=false
12-01 07:07:56.030   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:56.031  3074  3087 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:56.031   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:56.031  5678  5689 D BluetoothPbap: onBluetoothStateChange: up=false
,12-01 07:07:56.032   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 07:07:56.033  3074  3942 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 07:07:56.034  3074  5623 D BluetoothMap: onBluetoothStateChange: up=false
12-01 07:07:56.035  5678  5691 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 07:07:56.035  3756  4114 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 07:07:56.036  5678  5689 D BluetoothPan: onBluetoothStateChange on: false
12-01 07:07:56.036  3074  3085 D BluetoothInputDevice: onBluetoothStateChange: up=false
,12-01 07:07:56.037  5678  5691 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 07:07:56.037   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 07:07:56.038  5678  5689 D BluetoothMap: onBluetoothStateChange: up=false
12-01 07:07:56.038  3074  3087 D BluetoothPan: onBluetoothStateChange on: false
12-01 07:07:56.039  5678  5691 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 07:07:56.039  5805  5817 D BluetoothAdapterState: Current state: BLE ON, message: 20
12-01 07:07:56.039  5805  5817 D BluetoothAdapterProperties: Setting state to 16
12-01 07:07:56.039  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
12-01 07:07:56.040  5678  5678 D BluetoothPbap: Proxy object disconnected
12-01 07:07:56.040  5678  5678 D PbapServerProfile: Bluetooth service disconnected
12-01 07:07:56.040  5805  5817 D BluetoothAdapterProperties: onBleDisable
12-01 07:07:56.040  5805  5817 I BluetoothAdapterState: Entering PendingCommandState
12-01 07:07:56.041  5805  5818 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
12-01 07:07:56.042  5805  5828 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
12-01 07:07:56.042  5805  5828 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,12-01 07:07:56.043  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:56.044  5805  5821 D BluetoothAdapterProperties: Scan Mode:20
12-01 07:07:56.045  5678  5678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 07:07:56.047  5624  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 07:07:56.052  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 07:07:56.052  5678  5678 D DockEventReceiver: finishStartingService: stopping service
,12-01 07:07:56.265  5805  5821 I bt_hci  : shut_down
,12-01 07:07:56.277  5805  5825 D bt_hwcfg: hw_epilog_process
,12-01 07:07:56.277  5805  5825 I bt_vendor: low_power_mode_cb
,12-01 07:07:56.280  5805  5825 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,12-01 07:07:56.280  5805  5825 I bt_vendor: epilog_cb
12-01 07:07:56.280  5805  5825 I bt_hci  : epilog_finished_callback
,12-01 07:07:56.286  5805  5821 I bt_hci_h4: hal_close
,12-01 07:07:56.287  5805  5821 I bt_userial_vendor: device fd = 54 close
,12-01 07:07:56.404  5805  5818 D bt_stack_manager: event_shut_down_stack finished.
,12-01 07:07:56.405  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,12-01 07:07:56.410  5805  5817 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
12-01 07:07:56.410  5805  5805 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 07:07:56.411  5805  5805 D BtGatt.GattService: Received stop request...Stopping profile...
12-01 07:07:56.411  5805  5805 D BtGatt.GattService: stop()
12-01 07:07:56.411  5805  5805 D BtGatt.AdvertiseManager: advertise clients cleared
,12-01 07:07:56.415  5805  5805 V BluetoothAdapterState: isTurningOff()=false
12-01 07:07:56.415  5805  5805 V BluetoothAdapterState: isTurningOn()=false
12-01 07:07:56.415  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:07:56.415  5805  5805 V BluetoothAdapterState: isBleTurningOff()=true
,12-01 07:07:56.416  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,12-01 07:07:56.417  5805  5817 D BluetoothAdapterProperties: Setting state to 10
12-01 07:07:56.417  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
12-01 07:07:56.419  5805  5817 I BluetoothAdapterState: Entering OffState
,12-01 07:07:56.421   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,12-01 07:07:56.435  5805  5805 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,12-01 07:07:56.436  5805  5805 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,12-01 07:07:56.436  5805  5805 I BluetoothServiceJni: cleanupNative: return from cleanup
,12-01 07:07:56.438  5805  5818 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,12-01 07:07:56.446  5805  5805 I art     : System.exit called, status: 0
,12-01 07:07:56.446  5805  5805 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,12-01 07:07:56.476   927  3673 I ActivityManager: Process com.android.bluetooth (pid 5805) has died
,12-01 07:07:56.569   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:57.570   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:58.571   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:07:59.572   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:00.573   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:00.957  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:08:00.957  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 07:08:00.963  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:00.963  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e76aef removed from the list
12-01 07:08:00.963  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:08:00.965  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:00.966  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7dd46da added. We now have 4 listener(s)
12-01 07:08:00.966  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:08:00.968  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 07:08:00.968  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7dd46da removed from the list
12-01 07:08:00.968  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:08:00.970  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 07:08:00.971  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b69c70b added. We now have 4 listener(s)
12-01 07:08:00.971  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:08:01.574   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,12-01 07:08:05.983  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:08:06.020   927   944 I ActivityManager: Start proc 5861:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,12-01 07:08:06.119  5861  5861 D AdapterServiceConfig: Adding HeadsetService
,12-01 07:08:06.120  5861  5861 D AdapterServiceConfig: Adding A2dpService
12-01 07:08:06.120  5861  5861 D AdapterServiceConfig: Adding HidService
,12-01 07:08:06.120  5861  5861 D AdapterServiceConfig: Adding HealthService
12-01 07:08:06.120  5861  5861 D AdapterServiceConfig: Adding PanService
12-01 07:08:06.120  5861  5861 D AdapterServiceConfig: Adding GattService
12-01 07:08:06.120  5861  5861 D AdapterServiceConfig: Adding BluetoothMapService
12-01 07:08:06.120  5861  5861 D AdapterServiceConfig: Adding SapService
,12-01 07:08:06.133   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@88fe525:true
12-01 07:08:06.134  5861  5861 D BluetoothAdapterState: make() - Creating AdapterState
,12-01 07:08:06.137  5861  5861 I bt_bluedroid: init
12-01 07:08:06.137  5861  5873 I BluetoothAdapterState: Entering OffState
,12-01 07:08:06.140  5861  5874 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,12-01 07:08:06.140  5861  5874 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
12-01 07:08:06.140  5861  5874 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
12-01 07:08:06.150  5861  5874 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,12-01 07:08:06.153  5861  5861 I bt_bluedroid: get_profile_interface socket
,12-01 07:08:06.155  5861  5861 I bt_bluedroid: get_profile_interface sdp
12-01 07:08:06.155  5861  5877 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,12-01 07:08:06.159  5861  5877 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 07:08:06.159  5861  5872 I bt_bluedroid: config_hci_snoop_log
,12-01 07:08:06.161   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,12-01 07:08:06.165  5861  5873 D BluetoothAdapterState: Current state: OFF, message: 0
,12-01 07:08:06.165  5861  5873 D BluetoothAdapterProperties: Setting state to 14
12-01 07:08:06.165  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,12-01 07:08:06.167  5861  5873 D BluetoothBondStateMachine: make
,12-01 07:08:06.168  5861  5879 I BluetoothBondStateMachine: StableState(): Entering Off State
,12-01 07:08:06.171  5861  5873 I BluetoothAdapterState: Entering PendingCommandState
,12-01 07:08:06.172  5861  5861 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,12-01 07:08:06.174  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:08:06.175  5861  5861 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 07:08:06.175  5861  5861 D BtGatt.GattService: Received start request. Starting profile...
12-01 07:08:06.175  5861  5861 D BtGatt.GattService: start()
12-01 07:08:06.175  5861  5861 I bt_bluedroid: get_profile_interface gatt
,12-01 07:08:06.176  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:08:06.176  5861  5861 D BtGatt.AdvertiseManager: advertise manager created
,12-01 07:08:06.181  5861  5861 V BluetoothAdapterState: isTurningOff()=false
,12-01 07:08:06.181  5861  5861 V BluetoothAdapterState: isTurningOn()=false
12-01 07:08:06.181  5861  5861 V BluetoothAdapterState: isBleTurningOn()=true
12-01 07:08:06.181  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:08:06.181  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,12-01 07:08:06.183  5861  5873 I bt_bluedroid: bt_bluedroid
12-01 07:08:06.183  5861  5874 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,12-01 07:08:06.183  5861  5874 I bt_hci  : start_up
,12-01 07:08:06.188  5861  5874 I bt_vendor: alloc value 0xf3c65871
,12-01 07:08:06.188  5861  5874 I bt_vendor: init
12-01 07:08:06.188  5861  5874 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
12-01 07:08:06.188  5861  5874 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,12-01 07:08:06.299  5861  5874 D bt_hci  : start_up starting async portion
12-01 07:08:06.300  5861  5882 I bt_hci  : event_finish_startup
12-01 07:08:06.300  5861  5882 I bt_hci_h4: hal_open
12-01 07:08:06.300  5861  5882 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,12-01 07:08:06.298  5883  5883 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 07:08:06.303  5861  5882 I bt_userial_vendor: device fd = 54 open
,12-01 07:08:06.320  5861  5882 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 07:08:06.323  5861  5882 D bt_hwcfg: Chipset BCM4358A3
,12-01 07:08:06.324  5861  5882 D bt_hwcfg: Target name = [BCM4358A3]
12-01 07:08:06.324  5861  5882 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,12-01 07:08:06.838  5861  5882 I bt_hwcfg: bt vendor lib: set UART baud 115200
,12-01 07:08:06.839  5861  5882 D bt_hwcfg: Settlement delay -- 100 ms
,12-01 07:08:06.839  5861  5882 I bt_hwcfg: Setting fw settlement delay to 100 
,12-01 07:08:06.973  5861  5882 I bt_hwcfg: bt vendor lib: set UART baud 3000000
12-01 07:08:06.973  5861  5882 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
12-01 07:08:06.975  5861  5882 I bt_hwcfg: vendor lib fwcfg completed
12-01 07:08:06.975  5861  5882 I bt_vendor: firmware callback
12-01 07:08:06.975  5861  5882 I bt_hci  : firmware_config_callback
,12-01 07:08:06.984  5861  5885 I bt_btu  : btu_task pending for preload complete event
12-01 07:08:06.984  5861  5885 I bt_btu_task: Bluetooth chip preload is complete
,12-01 07:08:06.984  5861  5885 I bt_btu  : btu_task received preload complete event
,12-01 07:08:06.990  5861  5885 I         : BTE_InitTraceLevels -- TRC_HCI
12-01 07:08:06.990  5861  5885 I         : BTE_InitTraceLevels -- TRC_L2CAP
,12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_RFCOMM
12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_AVDT
12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_AVRC
,12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_A2D
,12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_BNEP
12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_BTM
12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_GAP
,12-01 07:08:06.991  5861  5885 I         : BTE_InitTraceLevels -- TRC_PAN
12-01 07:08:06.992  5861  5885 I         : BTE_InitTraceLevels -- TRC_SDP
,12-01 07:08:06.992  5861  5885 I         : BTE_InitTraceLevels -- TRC_GATT
12-01 07:08:06.992  5861  5885 I         : BTE_InitTraceLevels -- TRC_SMP
12-01 07:08:06.992  5861  5885 I         : BTE_InitTraceLevels -- TRC_BTAPP
12-01 07:08:06.992  5861  5885 I         : BTE_InitTraceLevels -- TRC_BTIF
,12-01 07:08:07.087  5861  5885 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3be3549
,12-01 07:08:07.087  5861  5885 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3be3549 
,12-01 07:08:07.108  5861  5877 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,12-01 07:08:07.110  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,12-01 07:08:07.111  5861  5877 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,12-01 07:08:07.114  5861  5877 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 07:08:07.116  5861  5877 D BluetoothAdapterProperties: Scan Mode:20
12-01 07:08:07.117  5861  5877 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 07:08:07.117  5861  5877 D bt_hci  : do_postload posting postload work item
12-01 07:08:07.117  5861  5882 I bt_hci  : event_postload
12-01 07:08:07.117  5861  5882 I bt_vendor: sco_config_cb
12-01 07:08:07.117  5861  5882 I bt_hci  : sco_config_callback postload finished.
12-01 07:08:07.118  5861  5877 D bt_bte_conf: Device ID record 1 : primary
12-01 07:08:07.119  5861  5877 D bt_bte_conf:   vendorId            = 000f
12-01 07:08:07.119  5861  5877 D bt_bte_conf:   vendorIdSource      = 0001
12-01 07:08:07.119  5861  5877 D bt_bte_conf:   product             = 1200
12-01 07:08:07.119  5861  5877 D bt_bte_conf:   version             = 1436
12-01 07:08:07.119  5861  5877 D bt_bte_conf:   clientExecutableURL = 
12-01 07:08:07.119  5861  5877 D bt_bte_conf:   serviceDescription  = 
12-01 07:08:07.119  5861  5877 D bt_bte_conf:   documentationURL    = 
12-01 07:08:07.120  5861  5877 D bt_bte_conf: bte_load_did_conf no section named DID2.
12-01 07:08:07.120  5861  5874 D bt_stack_manager: event_start_up_stack finished
12-01 07:08:07.121  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,12-01 07:08:07.121  5861  5873 D BluetoothAdapterProperties: Setting state to 15
12-01 07:08:07.121  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
12-01 07:08:07.125  5861  5873 I BluetoothAdapterState: Entering BleOnState
,12-01 07:08:07.128  5861  5882 I bt_vendor: low_power_mode_cb
12-01 07:08:07.132  5861  5873 D BluetoothAdapterState: Current state: BLE ON, message: 1
12-01 07:08:07.132  5861  5873 D BluetoothAdapterProperties: Setting state to 11
,12-01 07:08:07.132  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,12-01 07:08:07.138  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:08:07.142  5861  5861 D HeadsetService: Received start request. Starting profile...
12-01 07:08:07.146  5861  5861 I BluetoothHeadsetServiceJni: classInitNative: succeeds
12-01 07:08:07.146  5861  5861 D HeadsetStateMachine: make
,12-01 07:08:07.157  5861  5873 I BluetoothAdapterState: Entering PendingCommandState
,12-01 07:08:07.162  5861  5861 D HeadsetStateMachine: max_hf_connections = 1
,12-01 07:08:07.162  5861  5861 I bt_bluedroid: get_profile_interface handsfree
12-01 07:08:07.162  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
12-01 07:08:07.162  5861  5877 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,12-01 07:08:07.165  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:08:07.165  5861  5861 D A2dpService: Received start request. Starting profile...
12-01 07:08:07.166  5861  5861 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,12-01 07:08:07.166  5861  5861 I bt_bluedroid: get_profile_interface avrcp
,12-01 07:08:07.172  5861  5861 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,12-01 07:08:07.172  5861  5861 I BluetoothA2dpServiceJni: classInitNative: succeeds
12-01 07:08:07.172  5861  5861 D A2dpStateMachine: make
,12-01 07:08:07.173  5861  5861 I bt_bluedroid: get_profile_interface a2dp
12-01 07:08:07.174  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,12-01 07:08:07.179  5861  5892 D A2dpStateMachine: Enter Disconnected: -2
,12-01 07:08:07.180  5861  5861 I BluetoothHidServiceJni: classInitNative: succeeds
,12-01 07:08:07.181  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:08:07.181  5861  5861 D HidService: Received start request. Starting profile...
12-01 07:08:07.181  5861  5861 I bt_bluedroid: get_profile_interface hidhost
12-01 07:08:07.182  5861  5861 D HidService: setHidService(): set to: null
12-01 07:08:07.182  5861  5877 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bc456d
12-01 07:08:07.182  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
12-01 07:08:07.183  5861  5861 I BluetoothHealthServiceJni: classInitNative: succeeds
,12-01 07:08:07.184  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:08:07.185  5861  5861 D HealthService: Received start request. Starting profile...
12-01 07:08:07.185  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 07:08:07.186  5861  5861 I bt_bluedroid: get_profile_interface health
12-01 07:08:07.187  5861  5861 I BluetoothPanServiceJni: classInitNative(L105): succeeds
12-01 07:08:07.188  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:08:07.188  5861  5861 D PanService: Received start request. Starting profile...
,12-01 07:08:07.188  5861  5861 D BluetoothPanServiceJni: initializeNative(L110): pan
12-01 07:08:07.189  5861  5861 I bt_bluedroid: get_profile_interface pan
12-01 07:08:07.189  5861  5877 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,12-01 07:08:07.191  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:08:07.192  5861  5861 D BluetoothMapService: Received start request. Starting profile...
,12-01 07:08:07.192  5861  5861 D BluetoothMapService: start()
12-01 07:08:07.194  5861  5861 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
12-01 07:08:07.195  5861  5861 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
12-01 07:08:07.195  5861  5861 D BluetoothMapAppObserver: createReceiver()
12-01 07:08:07.196  5861  5861 D BluetoothMapAppObserver: initObservers()
12-01 07:08:07.196  5861  5861 D BluetoothMapAppObserver: getEnabledAccountItems()
,12-01 07:08:07.203  5861  5861 V SapService: SapBinder()
12-01 07:08:07.203  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
,12-01 07:08:07.204  5861  5861 D SapService: Received start request. Starting profile...
,12-01 07:08:07.204  5861  5861 V SapService: start()
,12-01 07:08:07.206  5861  5861 V BluetoothAdapterState: isTurningOff()=false
12-01 07:08:07.207  5861  5861 V BluetoothAdapterState: isTurningOn()=true
12-01 07:08:07.207  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:08:07.207  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:08:07.207  5861  5861 V BluetoothAdapterState: isTurningOff()=false
12-01 07:08:07.207  5861  5861 V BluetoothAdapterState: isTurningOn()=true
12-01 07:08:07.207  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:08:07.207  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isTurningOff()=false
,12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isTurningOn()=true
12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:08:07.208  5861  5890 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isTurningOff()=false
,12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isTurningOn()=true
12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isTurningOff()=false
12-01 07:08:07.208  5861  5861 V BluetoothAdapterState: isTurningOn()=true
12-01 07:08:07.209  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:08:07.209  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:08:07.209  5861  5861 V BluetoothAdapterState: isTurningOff()=false
12-01 07:08:07.209  5861  5861 V BluetoothAdapterState: isTurningOn()=true
12-01 07:08:07.209  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:08:07.209  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:08:07.210  5861  5861 V BluetoothAdapterState: isTurningOff()=false
12-01 07:08:07.210  5861  5861 V BluetoothAdapterState: isTurningOn()=true
12-01 07:08:07.210  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
12-01 07:08:07.210  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
12-01 07:08:07.210  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
12-01 07:08:07.210  5861  5873 D BluetoothAdapterProperties: ScanMode =  20
12-01 07:08:07.210  5861  5873 D BluetoothAdapterProperties: State =  11
12-01 07:08:07.212  5861  5877 D BluetoothAdapterProperties: Scan Mode:21
12-01 07:08:07.212  5861  5877 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 07:08:07.213  5861  5873 D BluetoothAdapterProperties: Setting state to 12
12-01 07:08:07.213  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
12-01 07:08:07.213  5861  5873 I BluetoothAdapterState: Entering OnState
12-01 07:08:07.213  3074  3085 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 07:08:07.215   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 07:08:07.215  3074  3087 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 07:08:07.216   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 07:08:07.216  5678  5691 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 07:08:07.218   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 07:08:07.218  3074  3942 D BluetoothA2dp: onBluetoothStateChange: up=true
,12-01 07:08:07.220  3074  5623 D BluetoothMap: onBluetoothStateChange: up=true
,12-01 07:08:07.221  3074  3074 D BluetoothA2dp: Proxy object connected
12-01 07:08:07.221  5678  5689 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 07:08:07.221  5861  5861 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 07:08:07.222  5861  5861 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
12-01 07:08:07.224  5678  5678 D BluetoothA2dp: Proxy object connected
12-01 07:08:07.224  5861  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:08:07.225  3756  3993 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 07:08:07.225  5678  5691 D BluetoothPan: onBluetoothStateChange on: true
12-01 07:08:07.228  5861  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:08:07.229  3074  3942 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 07:08:07.229  5861  5861 D ObexServerSockets: Succeed to create listening sockets 
12-01 07:08:07.229  5861  5861 D ObexServerSockets0: startAccept()
12-01 07:08:07.229  5861  5861 D ObexServerSockets0: prepareForNewConnect()
,12-01 07:08:07.232  5861  5861 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,12-01 07:08:07.232  5861  5861 D BluetoothSdpJni: SDP Create record success - handle: 0
12-01 07:08:07.232  5861  5899 D ObexServerSockets0: Accepting socket connection...
12-01 07:08:07.233  5861  5898 D ObexServerSockets0: Accepting socket connection...
12-01 07:08:07.234  3074  3074 D BluetoothMap: Proxy object connected
12-01 07:08:07.234  5678  5689 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 07:08:07.234  3074  3074 D MapProfile: Bluetooth service connected
12-01 07:08:07.234  3074  3074 D BluetoothMap: getConnectedDevices()
,12-01 07:08:07.237   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
,12-01 07:08:07.237  3074  3074 D BluetoothInputDevice: Proxy object connected
12-01 07:08:07.237  3074  3074 D HidProfile: Bluetooth service connected
12-01 07:08:07.238  5678  5897 D BluetoothMap: onBluetoothStateChange: up=true
12-01 07:08:07.238   927   927 D BluetoothA2dp: Proxy object connected
,12-01 07:08:07.240  3074  5623 D BluetoothPan: onBluetoothStateChange on: true
12-01 07:08:07.242  3074  3074 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 07:08:07.242  5678  5689 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 07:08:07.242  3074  3074 D PanProfile: Bluetooth service connected
,12-01 07:08:07.244  5678  5678 D BluetoothPan: BluetoothPAN Proxy object connected
,12-01 07:08:07.244  5678  5678 D PanProfile: Bluetooth service connected
12-01 07:08:07.244  5678  5678 D BluetoothInputDevice: Proxy object connected
,12-01 07:08:07.244  5678  5678 D HidProfile: Bluetooth service connected
12-01 07:08:07.246  5861  5861 D BluetoothMapService: onReceive
12-01 07:08:07.246  5861  5861 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 07:08:07.246   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
12-01 07:08:07.246  5861  5861 D BluetoothMapService: STATE_ON
12-01 07:08:07.248  5678  5678 D BluetoothMap: Proxy object connected
12-01 07:08:07.248  5678  5678 D MapProfile: Bluetooth service connected
12-01 07:08:07.248  5678  5678 D BluetoothMap: getConnectedDevices()
12-01 07:08:07.249  5861  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:08:07.251  5861  5902 D BluetoothSdpJni: sdpCreateSapsRecordNative:
12-01 07:08:07.251  5861  5902 D BluetoothSdpJni: SDP Create record success - handle: 1
,12-01 07:08:07.254  5678  5678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 07:08:07.260  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 07:08:07.266  5678  5678 D DockEventReceiver: finishStartingService: stopping service
,12-01 07:08:07.269  5678  5678 D BluetoothPbap: Proxy object connected
,12-01 07:08:07.269  5678  5678 D PbapServerProfile: Bluetooth service connected
12-01 07:08:07.270  3074  3074 D BluetoothPbap: Proxy object connected
,12-01 07:08:07.270  3074  3074 D PbapServerProfile: Bluetooth service connected
,12-01 07:08:07.273  5861  5861 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 07:08:07.274  5861  5861 D ObexServerSockets0: prepareForNewConnect()
,12-01 07:08:07.278  5861  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 07:08:07.295  5861  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 07:08:07.296  5861  5910 I BtOppRfcommListener: Accept thread started.
,12-01 07:08:07.316   927   927 D BluetoothHeadset: Proxy object connected
,12-01 07:08:07.316   927   927 D BluetoothHeadset: Proxy object connected
12-01 07:08:07.317  3756  4114 D BluetoothHeadset: Proxy object connected
12-01 07:08:07.317  5678  5689 D BluetoothHeadset: Proxy object connected
,12-01 07:08:07.317   927   927 D BluetoothHeadset: Proxy object connected
,12-01 07:08:07.317  3074  3085 D BluetoothHeadset: Proxy object connected
12-01 07:08:07.318  3074  3074 D HeadsetProfile: Bluetooth service connected
12-01 07:08:07.318   927   944 D BluetoothHeadset: Proxy object connected
12-01 07:08:07.319  5678  5678 D HeadsetProfile: Bluetooth service connected
,12-01 07:08:07.325  3756  4000 D BluetoothHeadset: Proxy object connected
,12-01 07:08:07.343  5678  5691 D BluetoothHeadset: Proxy object connected
,12-01 07:08:07.344  5678  5678 D HeadsetProfile: Bluetooth service connected
,12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 07:08:10.998  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 07:08:11.004  5624  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 07:08:11.005  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:11.005  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b69c70b removed from the list
12-01 07:08:11.005  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:08:11.007  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 07:08:11.008  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43149e8 added. We now have 4 listener(s)
12-01 07:08:11.008  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:11.011   927  3110 D WifiService: setWifiEnabled: false pid=5624, uid=10077
,12-01 07:08:11.011   927  3110 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 07:08:16.020  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 07:08:16.022   927  3812 D WifiService: setWifiEnabled: true pid=5624, uid=10077
12-01 07:08:16.022   927  3812 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 07:08:16.030   506   921 D SoftapController: Softap fwReload - Ok
,12-01 07:08:16.035   506   921 D CommandListener: Setting iface cfg
,12-01 07:08:16.035   506   921 D CommandListener: Trying to bring down wlan0
,12-01 07:08:16.037   506   921 D CommandListener: Clearing all IP addresses on wlan0
,12-01 07:08:16.042   927  2928 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 07:08:16.576   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:16.720   927  2928 D wifi    : set interface wlan0 flags (UP)
,12-01 07:08:16.723   927  2928 I WifiHAL : Initializing wifi
,12-01 07:08:16.723   927  2928 I WifiHAL : Creating socket
,12-01 07:08:16.727   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,12-01 07:08:16.734   927  2928 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,12-01 07:08:16.734   927  2928 D wifi    : Did set static halHandle = 0x7f5edd6400
12-01 07:08:16.735   927  2928 D wifi    : halHandle = 0x7f5edd6400, mVM = 0x7f7b44d140, mCls = 0x101912
,12-01 07:08:16.735   927  2928 D wifi    : array field set
12-01 07:08:16.735   927  2928 I WifiNative-HAL: interface[0] = wlan0
,12-01 07:08:16.737   927  5915 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547052413952
,12-01 07:08:16.737   927  5915 D wifi    : waitForHalEvents called, vm = 0x7f7b44d140, obj = 0x101912, env = 0x7f5ede3580
,12-01 07:08:16.797  5916  5916 I wpa_supplicant: Successfully initialized wpa_supplicant
,12-01 07:08:16.817  5916  5916 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 07:08:16.842   927  2928 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,12-01 07:08:16.861  5916  5916 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 07:08:16.861  5916  5916 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,12-01 07:08:16.876   927  2928 D WifiConfigStore: Loading config and enabling all networks 
,12-01 07:08:16.893   927  2928 D WifiConfigStore: loaded 0 passpoint configs
,12-01 07:08:16.894   927  2928 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
12-01 07:08:16.894   927  2928 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,12-01 07:08:16.895   927  2928 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,12-01 07:08:16.896   927  2928 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,12-01 07:08:16.896   927  2928 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
12-01 07:08:16.896   927  2928 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
12-01 07:08:16.896   927  2928 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,12-01 07:08:16.899   927  2928 D WifiNative-HAL: Setting external_sim to 1
,12-01 07:08:16.900   927  2928 D wifi    : setting dfs flag to true, 0x7f61618520
12-01 07:08:16.900  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 07:08:16.900   927  2928 D WifiStateMachine: Setting OUI to DA-A1-19
12-01 07:08:16.900   927  2928 D wifi    : setting scan oui 0x7f61618520
12-01 07:08:16.900   927  2928 D WifiHAL : Sending mac address OUI
,12-01 07:08:16.904   927  2928 E native  : do suspend false
,12-01 07:08:16.912   927  2928 D wifi    : android_net_wifi_setLinkLayerStats: 1
12-01 07:08:16.913   927   927 D RttService: SCAN_AVAILABLE : 3
12-01 07:08:16.913   927  3038 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
12-01 07:08:16.913   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,12-01 07:08:16.914   506   921 D CommandListener: Setting iface cfg
,12-01 07:08:16.919   927  2927 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,12-01 07:08:16.919   927  2927 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,12-01 07:08:16.929   927  2927 D WifiNative-HAL: p2pGetDeviceAddress
,12-01 07:08:16.930   927  2927 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,12-01 07:08:16.935   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164885 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,12-01 07:08:17.577   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:18.578   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:19.580   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:20.075  5916  5916 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 07:08:20.080  5916  5916 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 07:08:20.086  5916  5916 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 07:08:20.157   927  2928 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,12-01 07:08:20.158   927  2928 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
12-01 07:08:20.158   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 07:08:20.169   927  2928 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,12-01 07:08:20.201   927  2928 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,12-01 07:08:20.203  5916  5916 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,12-01 07:08:20.580   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:20.638  5916  5916 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,12-01 07:08:20.684  5916  5916 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,12-01 07:08:20.684  5916  5916 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,12-01 07:08:20.697   927  2928 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 07:08:20.698   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
12-01 07:08:20.698   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,12-01 07:08:20.715   927  2928 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 07:08:20.729   506   921 D CommandListener: Setting iface cfg
,12-01 07:08:20.734   927  2928 D WifiStateMachine: Start Dhcp Watchdog 3
,12-01 07:08:20.741   927  5921 D DhcpClient: Receive thread started
,12-01 07:08:20.745   927  2928 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,12-01 07:08:20.745   927  2930 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
12-01 07:08:20.745   927  2930 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,12-01 07:08:20.827   927  2928 E native  : do suspend false
,12-01 07:08:20.841   927  5920 D DhcpClient: Broadcasting DHCPDISCOVER
,12-01 07:08:20.868   927  5921 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,12-01 07:08:20.869   927  5920 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,12-01 07:08:20.871   927  5920 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,12-01 07:08:20.885   927  5921 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,12-01 07:08:20.887   927  5920 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,12-01 07:08:20.890   506   921 D CommandListener: Setting iface cfg
12-01 07:08:20.894   927  2928 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,12-01 07:08:20.899   927  5920 D DhcpClient: Scheduling renewal in 86399s
,12-01 07:08:20.907   927  2928 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,12-01 07:08:20.908   927  2928 D WifiConfigStore: No blacklist allowed without epno enabled
12-01 07:08:20.909   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
12-01 07:08:20.911   927  2930 D ConnectivityService: Adding iface wlan0 to network 102
,12-01 07:08:20.917   927  2928 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,12-01 07:08:20.962   927  2930 E ConnectivityService: Unexpected mtu value: 0, wlan0
,12-01 07:08:20.963   927  2930 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,12-01 07:08:20.964   927  2930 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,12-01 07:08:20.966   927  2930 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,12-01 07:08:20.968   927  2930 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,12-01 07:08:20.976   927  2930 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 07:08:20.982   927  2930 D ConnectivityService: scheduleUnvalidatedPrompt 102
,12-01 07:08:20.982   927  2930 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
12-01 07:08:20.982   927  2930 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
12-01 07:08:20.982   927  2928 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
12-01 07:08:20.982   927  2930 D ConnectivityService:    accepting network in place of null
,12-01 07:08:20.982   927  2928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,12-01 07:08:20.983   927  2930 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 07:08:20.996   927  5919 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168947, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 07:08:21.012   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 07:08:21.036  5624  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 07:08:21.038  5624  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 07:08:21.039  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.039  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43149e8 removed from the list
12-01 07:08:21.039  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:08:21.042   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 07:08:21.047   927  2930 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,12-01 07:08:21.048  3735  3871 W QCNEJ   : |CORE| network available: 102
12-01 07:08:21.048   927  2930 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
12-01 07:08:21.048  5624  5670 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
12-01 07:08:21.049  5624  5670 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
12-01 07:08:21.049   927  2930 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
12-01 07:08:21.051  3735  3871 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
12-01 07:08:21.051  5624  5670 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c9cafc Bundle[{}]
12-01 07:08:21.052   927   944 D Tethering: MasterInitialState.processMessage what=3
12-01 07:08:21.052  5624  5670 I io.jxcore.node.LifeCycleMonitor: start: OK
12-01 07:08:21.053  5624  5670 I io.jxcore.node.LifeCycleMonitor: stop: OK
12-01 07:08:21.054  3735  3871 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
12-01 07:08:21.054  3735  3871 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
12-01 07:08:21.054  5624  5670 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
12-01 07:08:21.055  5624  5670 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,12-01 07:08:21.057  5624  5670 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,12-01 07:08:21.058  5624  5670 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
12-01 07:08:21.066  5624  5670 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
12-01 07:08:21.067  5624  5670 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
12-01 07:08:21.067  5624  5670 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
12-01 07:08:21.067  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,12-01 07:08:21.068  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,12-01 07:08:21.068  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
12-01 07:08:21.068  5046  5070 E SarControlService: no key has been found,reset the power
12-01 07:08:21.068  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 07:08:21.068  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 07:08:21.068  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 07:08:21.069  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.069  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef15801 added. We now have 3 listener(s)
12-01 07:08:21.070  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 07:08:21.070  5071  5071 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 07:08:21.071  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 07:08:21.071  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 07:08:21.071   927  5918 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:81a::200e
12-01 07:08:21.071  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
12-01 07:08:21.072  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,12-01 07:08:21.072  5071  5071 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
12-01 07:08:21.073  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.073  4910  4910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
12-01 07:08:21.073  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.073  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.074  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.074  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@758f6a6 added. We now have 4 listener(s)
12-01 07:08:21.074  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.076  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 07:08:21.077  3668  3668 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,12-01 07:08:21.078  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.078  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66bc8e7 added. We now have 4 listener(s)
12-01 07:08:21.078  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000f003000000000000ffffffff]
,12-01 07:08:21.078  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,12-01 07:08:21.078  5071  5085 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
12-01 07:08:21.079  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 07:08:21.079  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 07:08:21.079  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ebad3b8 HexData = [00000000f103000000000000ffffffff]
12-01 07:08:21.079  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.079  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 07:08:21.080  5071  5085 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,12-01 07:08:21.080  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.080  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.080  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.080  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc51c94 added. We now have 5 listener(s)
12-01 07:08:21.080  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.080  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 07:08:21.080  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:08:21.080  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:08:21.080  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:08:21.080  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
12-01 07:08:21.080  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 07:08:21.080  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 07:08:21.080  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,12-01 07:08:21.080  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef15801 removed from the list
12-01 07:08:21.080  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.081  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@758f6a6 removed from the list
12-01 07:08:21.081  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:08:21.081  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.081  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.082  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.082  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.082  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.082  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.082  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.082  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.083  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@758f6a6 not in the list
12-01 07:08:21.083  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.083  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.084  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.084  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.085  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.085  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.085  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.085  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.085  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc51c94 removed from the list
12-01 07:08:21.085  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:08:21.085  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.085  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.086  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66bc8e7 removed from the list
12-01 07:08:21.086  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.086  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a733d added. We now have 3 listener(s)
12-01 07:08:21.087  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.087  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.087  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.088  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.088  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dd732 added. We now have 4 listener(s)
12-01 07:08:21.088  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.088  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 07:08:21.089  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.089  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a20c83 added. We now have 4 listener(s)
12-01 07:08:21.090  3668  3668 D SystemUpdateService: onCreate
12-01 07:08:21.092  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.093  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.093  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.093  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.093  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c216e00 added. We now have 5 listener(s)
12-01 07:08:21.093  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.093  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:08:21.093  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 07:08:21.093  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 07:08:21.093  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:08:21.093  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
12-01 07:08:21.094  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 07:08:21.095  3668  3668 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
12-01 07:08:21.097  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 07:08:21.097  5624  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 07:08:21.097  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,12-01 07:08:21.101  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.101  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 07:08:21.102  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 07:08:21.102  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 07:08:21.102  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 07:08:21.105  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.106  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 07:08:21.106  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 07:08:21.106  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 07:08:21.106  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 07:08:21.106  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.106  5624  5670 D BluetoothAdapter: STATE_ON
,12-01 07:08:21.109  5861  5901 D BtGatt.GattService: registerClient() - UUID=dca68904-857a-4c12-b677-27cc50659a11
,12-01 07:08:21.110  5861  5877 D BtGatt.GattService: onClientRegistered() - UUID=dca68904-857a-4c12-b677-27cc50659a11, clientIf=5
12-01 07:08:21.110  3668  3668 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
12-01 07:08:21.111  5624  5634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 07:08:21.112  5861  5878 D BtGatt.GattService: start scan with filters
12-01 07:08:21.114  3668  5412 I iu.UploadsManager: num queued entries: 0
12-01 07:08:21.114  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 07:08:21.114  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.115  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,12-01 07:08:21.115  5861  5881 D BtGatt.ScanManager: handling starting scan
12-01 07:08:21.115  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.115  3668  5412 I iu.UploadsManager: num updated entries: 0
12-01 07:08:21.115  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 07:08:21.115  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 07:08:21.115  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.115  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 07:08:21.115  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 07:08:21.115  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.115  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,12-01 07:08:21.116  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.116  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.116  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 07:08:21.116  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.116  5861  5881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aef35c9
12-01 07:08:21.117  3668  5932 I SystemUpdateService: active receiver: enabled
12-01 07:08:21.118  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.118  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:08:21.118  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.118  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.118  5624  5670 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
12-01 07:08:21.118  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 07:08:21.118  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 07:08:21.119  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.119  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:08:21.119  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.119  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 07:08:21.120  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.120  3668  3668 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
12-01 07:08:21.122  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.122  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.122  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.122  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:08:21.122  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 07:08:21.122  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.122  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 07:08:21.122  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 07:08:21.122  3668  3668 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
12-01 07:08:21.122  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.122  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.123  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.123  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,12-01 07:08:21.123  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.123  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:08:21.124  5861  5901 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 07:08:21.124  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 07:08:21.124  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:08:21.125  5414  5414 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 07:08:21.125  5861  5871 D BtGatt.GattService: stopScan() - queue size =1
,12-01 07:08:21.125  5861  5877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 07:08:21.125  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.126  5861  5900 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 07:08:21.126  5861  5881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.126  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.127  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 07:08:21.127  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 07:08:21.127  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,12-01 07:08:21.127  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.128  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.128  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:08:21.128  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.128  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.130  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,12-01 07:08:21.130  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.130  5861  5881 D BtGatt.ScanManager: Starting BLE batch scan
12-01 07:08:21.130  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:08:21.130  5861  5881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 07:08:21.130  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:08:21.131  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 07:08:21.131  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.131  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 07:08:21.131  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,12-01 07:08:21.131  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.131  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.131  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.131  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:08:21.131  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.131  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.132  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:08:21.132  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:08:21.132  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.132  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:08:21.132  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.132  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:08:21.132  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.132  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.132  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.132  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a733d removed from the list
12-01 07:08:21.132  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.132  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dd732 removed from the list
,12-01 07:08:21.132  5414  5414 D SprintDMHelper: simOperator: 
,12-01 07:08:21.133  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:08:21.133  5414  5414 D SprintDMReceiver: Not Sprint UICC, don't do anything.
12-01 07:08:21.133  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.133  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.135  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.136  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.136  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.136  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.136  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 07:08:21.136  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.136  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dd732 not in the list
12-01 07:08:21.136  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.136  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.137  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.137  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.137  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.138  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.138  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.138  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.138  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c216e00 removed from the list
12-01 07:08:21.138  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:08:21.138  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.138  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.138  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a20c83 removed from the list
12-01 07:08:21.138  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.138  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@691ccf5 added. We now have 3 listener(s)
12-01 07:08:21.142  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.143  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.143  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.143  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.143  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3051a8a added. We now have 4 listener(s)
12-01 07:08:21.143  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.144  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 07:08:21.146  3668  5412 I iu.SyncManager: NEXT; no task
12-01 07:08:21.149  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 07:08:21.149  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fe88fb added. We now have 4 listener(s)
12-01 07:08:21.149  5861  5877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 07:08:21.149  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.150  3668  5932 I SystemUpdateService: Already downloaded, skipping offpeak checks.
12-01 07:08:21.150  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.150  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.150  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.150  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.150  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23efd18 added. We now have 5 listener(s)
12-01 07:08:21.150  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.151  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,12-01 07:08:21.151  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:08:21.151  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 07:08:21.151  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 07:08:21.151  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:08:21.151  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
12-01 07:08:21.155  3668  5932 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
12-01 07:08:21.155  3668  5932 I SystemUpdateService: now status is 0 (complete)
12-01 07:08:21.155  3668  5932 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 07:08:21.155  3668  5932 I SystemUpdateService: file has been verified
12-01 07:08:21.155  3668  5932 I SystemUpdateService: OTA package size = 21989297
,12-01 07:08:21.156  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 07:08:21.156  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.157  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 07:08:21.159  5861  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:08:21.161  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,12-01 07:08:21.161  5624  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 07:08:21.161  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 07:08:21.164  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.164  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 07:08:21.164  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 07:08:21.165  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 07:08:21.165  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 07:08:21.165  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,12-01 07:08:21.166  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:08:21.166  5861  5877 E BtGatt.ContextMap: Context not found for ID 5
12-01 07:08:21.169  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.169  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 07:08:21.169  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 07:08:21.169  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 07:08:21.169  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 07:08:21.169  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.171  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:08:21.172  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 07:08:21.172  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.173  5861  5881 D BtGatt.ScanManager: stopping BLe Batch
,12-01 07:08:21.175  5861  5900 D BtGatt.GattService: registerClient() - UUID=ee75deb0-2b03-4fd0-b9f3-f15f5ed36f67
,12-01 07:08:21.175  5861  5877 D BtGatt.GattService: onClientRegistered() - UUID=ee75deb0-2b03-4fd0-b9f3-f15f5ed36f67, clientIf=5
12-01 07:08:21.175  5624  5635 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 07:08:21.176  5861  5901 D BtGatt.GattService: start scan with filters
,12-01 07:08:21.176  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 07:08:21.176  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.177  5861  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:08:21.180  3668  5932 I SystemUpdateService: showing system update notification
,12-01 07:08:21.181  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 07:08:21.182  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.182  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 07:08:21.182  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.182  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 07:08:21.182  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:08:21.182  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 07:08:21.182  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 07:08:21.182  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.183  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 07:08:21.183  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 07:08:21.183  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.183  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.183  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.183  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,12-01 07:08:21.184  5861  5881 D BtGatt.ScanManager: handling starting scan
12-01 07:08:21.184  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 07:08:21.184  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.187  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.187  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:08:21.187  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.188  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.188  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:08:21.188  5624  5670 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
12-01 07:08:21.188  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:08:21.188  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:08:21.188  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:08:21.188  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:08:21.188  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.188  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:08:21.188  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.188  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.189  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.189  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@691ccf5 removed from the list
12-01 07:08:21.189  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.189  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3051a8a removed from the list
12-01 07:08:21.189  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:08:21.189  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.189  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,12-01 07:08:21.189  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.189  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.189  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
12-01 07:08:21.189  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.189  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:08:21.190  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.190  5861  5877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 07:08:21.190  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.190  5861  5881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 07:08:21.191  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.191  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.191  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.191  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.191  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.191  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.191  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.192  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3051a8a not in the list
12-01 07:08:21.192  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.192  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.192  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 07:08:21.192  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:08:21.192  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.192  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 07:08:21.192  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 07:08:21.192  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.192  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.193  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.193  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 07:08:21.193  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.194  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:08:21.194  5861  5878 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 07:08:21.194   927  5918 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Dec 2016 12:08:21 GMT], X-Android-Received-Millis=[1480594101193], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480594101119]}
12-01 07:08:21.194  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 07:08:21.196  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 07:08:21.196  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.196   927  2930 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
12-01 07:08:21.196  5861  5881 D BtGatt.ScanManager: Starting BLE batch scan
12-01 07:08:21.196  5861  5881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 07:08:21.196   927  2930 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
12-01 07:08:21.196  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:08:21.196   927  2930 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 07:08:21.196  5861  5871 D BtGatt.GattService: stopScan() - queue size =1
,12-01 07:08:21.197  5861  5900 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 07:08:21.197   927  2930 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
12-01 07:08:21.197  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 07:08:21.197  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.197  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.198  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 07:08:21.198  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 07:08:21.198  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 07:08:21.199  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.200  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.200  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,12-01 07:08:21.200  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.200  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.200  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.200  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.200  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.200  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:08:21.200  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23efd18 removed from the list
12-01 07:08:21.200  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:08:21.200  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:08:21.200  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.201  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.201  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 07:08:21.201  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fe88fb removed from the list
12-01 07:08:21.201  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.201  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 07:08:21.201  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 07:08:21.201  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.201  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.201  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.201  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:08:21.201  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.201  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.201  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.201  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f3a5ad added. We now have 3 listener(s)
12-01 07:08:21.202  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.202  5624  5670 D org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.203  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.203  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.203  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20670e2 added. We now have 4 listener(s)
12-01 07:08:21.203  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.203  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.203  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.203  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.203  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 07:08:21.204  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.204  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef1c73 added. We now have 4 listener(s)
12-01 07:08:21.204  5861  5877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,12-01 07:08:21.204  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.205  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.205  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.205  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.205  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.206  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6c5730 added. We now have 5 listener(s)
12-01 07:08:21.206  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 07:08:21.206  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:08:21.206  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 07:08:21.206  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 07:08:21.206  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 07:08:21.206  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
12-01 07:08:21.208  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 07:08:21.208  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.209  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 07:08:21.209  5861  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 07:08:21.210  3521  5942 I VacuumService: Vacuum at: now=1480594101210 tag=VacuumService
12-01 07:08:21.211  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 07:08:21.211  5624  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 07:08:21.211  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 07:08:21.211  3668  3668 D SystemUpdateService: onDestroy
12-01 07:08:21.215  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 07:08:21.215  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.215  5861  5877 E BtGatt.ContextMap: Context not found for ID 5
12-01 07:08:21.219  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.219  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 07:08:21.220  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 07:08:21.220  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 07:08:21.220  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 07:08:21.224  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 07:08:21.224  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.224  5861  5881 D BtGatt.ScanManager: stopping BLe Batch
,12-01 07:08:21.227  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.227  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 07:08:21.227  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 07:08:21.227  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 07:08:21.227  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 07:08:21.227  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.229  5624  5670 D BluetoothAdapter: STATE_ON
,12-01 07:08:21.232  5861  5871 D BtGatt.GattService: registerClient() - UUID=c87b57cb-c21a-42f2-b9c0-57f87c6843e5
12-01 07:08:21.233  5861  5877 D BtGatt.GattService: onClientRegistered() - UUID=c87b57cb-c21a-42f2-b9c0-57f87c6843e5, clientIf=5
,12-01 07:08:21.233  5624  5634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 07:08:21.233  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 07:08:21.233  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.233  5861  5900 D BtGatt.GattService: start scan with filters
12-01 07:08:21.233  5861  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:08:21.238  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,12-01 07:08:21.238  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:08:21.240  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started,
,12-01 07:08:21.241  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.241  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 07:08:21.241  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.241  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 07:08:21.241  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 07:08:21.241  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.241  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 07:08:21.241  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 07:08:21.241  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.241  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.241  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,12-01 07:08:21.241  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.242  3521  5945 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
12-01 07:08:21.242  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 07:08:21.242  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.243  5861  5881 D BtGatt.ScanManager: handling starting scan
12-01 07:08:21.244  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.245  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:08:21.245  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.245  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.245  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.247  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:08:21.247  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 07:08:21.247  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:08:21.247  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:08:21.247  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.247  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:08:21.247  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.247  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.247  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f3a5ad removed from the list
12-01 07:08:21.247  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.247  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20670e2 removed from the list
,12-01 07:08:21.247  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 07:08:21.247  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.247  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:08:21.248  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.248  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.248  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
12-01 07:08:21.248  5624  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 07:08:21.248  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 07:08:21.248  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.248  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.248  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.249  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.249  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 07:08:21.249  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.250  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.250  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.250  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.250  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20670e2 not in the list
12-01 07:08:21.250  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.250  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 07:08:21.250  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.251  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:08:21.251  5861  5900 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 07:08:21.252  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 07:08:21.253  5624  5670 D BluetoothAdapter: STATE_ON
12-01 07:08:21.254  5861  5872 D BtGatt.GattService: stopScan() - queue size =1
,12-01 07:08:21.255  5861  5877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 07:08:21.255  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.255  5861  5878 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 07:08:21.256  5861  5881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 07:08:21.256  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 07:08:21.256  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.256  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 07:08:21.256  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.256  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.256  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.256  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.257  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 07:08:21.257  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.257  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.257  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.257  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 07:08:21.257  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 07:08:21.257  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 07:08:21.258  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.259  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.259  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:08:21.259  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.259  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.259  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.259  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.259  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.259  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6c5730 removed from the list
12-01 07:08:21.259  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:08:21.259  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 07:08:21.259  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.259  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 07:08:21.259  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.259  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef1c73 removed from the list
12-01 07:08:21.259  5624  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 07:08:21.259  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.260  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 07:08:21.260  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscov,erer: updateState: stateSet: [SCANNING]
12-01 07:08:21.260  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.260  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.260  5624  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.260  5624  5624 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 07:08:21.260  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.260  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@430dd65 added. We now have 3 listener(s)
12-01 07:08:21.260  5624  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.260  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.261  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
12-01 07:08:21.261  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.261  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.261  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.261  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.261  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.261  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d613a3a added. We now have 4 listener(s)
12-01 07:08:21.262  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.261  5624  5624 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 07:08:21.262  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,12-01 07:08:21.262  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.262  5861  5881 D BtGatt.ScanManager: Starting BLE batch scan
12-01 07:08:21.262  5861  5881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 07:08:21.267  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 07:08:21.268  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 07:08:21.268  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ffa6eb added. We now have 4 listener(s)
,12-01 07:08:21.269  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,12-01 07:08:21.269  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 07:08:21.270  5624  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 07:08:21.270  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 07:08:21.270  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a77dc48 added. We now have 5 listener(s)
12-01 07:08:21.270  5624  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 07:08:21.270  5624  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 07:08:21.270  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:08:21.270  5624  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 07:08:21.270  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 07:08:21.270  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 07:08:21.270  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.270  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@430dd65 removed from the list
12-01 07:08:21.270  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.270  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d613a3a removed from the list
12-01 07:08:21.270  5624  5670 D io.jxcore.node.ConnectivityMonitor: stop
12-01 07:08:21.270  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.270  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.271  5861  5877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 07:08:21.271  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:08:21.271  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.271  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.271  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.271  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 07:08:21.272  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.272  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.272  5624  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d613a3a not in the list
12-01 07:08:21.272  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.272  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.273  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,12-01 07:08:21.273  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.273  5624  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
12-01 07:08:21.273  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 07:08:21.273  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 07:08:21.273  5624  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 07:08:21.273  5624  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a77dc48 removed from the list
12-01 07:08:21.273  5624  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 07:08:21.273  5624  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 07:08:21.273  5624  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 07:08:21.273  5624  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ffa6eb removed from the list
12-01 07:08:21.274  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
12-01 07:08:21.274  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,12-01 07:08:21.274  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
12-01 07:08:21.274  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:08:21.274  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
12-01 07:08:21.274  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 07:08:21.276  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,12-01 07:08:21.276  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.277  5861  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 07:08:21.282  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,12-01 07:08:21.282  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.282  5861  5877 E BtGatt.ContextMap: Context not found for ID 5
,12-01 07:08:21.287  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,12-01 07:08:21.287  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.287  5861  5881 D BtGatt.ScanManager: stopping BLe Batch
,12-01 07:08:21.290  3521  5943 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-01 07:08:21.291  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 07:08:21.291  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 07:08:21.292  5861  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 07:08:21.292  3521  5943 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-01 07:08:21.296  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,12-01 07:08:21.296  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 07:08:21.335  3521  5943 W Uploader:  no longer exists, so no auth token.
,12-01 07:08:21.338  5017  5936 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,12-01 07:08:21.340  3521  5945 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 07:08:21.581   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,12-01 07:08:21.632  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 07:08:21.701  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 07:08:21.760  5624  5624 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 07:08:21.971  3521  5955 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 07:08:22.049  3521  5943 W Uploader:  no longer exists, so no auth token.
,12-01 07:08:22.060  3521  5956 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 07:08:22.148  3521  5955 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 07:08:23.407  5624  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 07:08:23.407  5624  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 07:08:23.770   927  2930 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 07:08:24.211  5624  5958 W !!      : call onHalfStreamCopied
,12-01 07:08:24.211  5624  5958 I testCopyDataAndClose: closing input stream
,12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 07:08:24.980  5624  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,12-01 07:08:28.706  5624  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:28.706  5624  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 07:08:28.988   927  2930 D ConnectivityService: handlePromptUnvalidated 102
,12-01 07:08:30.705  5624  5670 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
12-01 07:08:30.705  5624  5670 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 07:08:30.706  5624  5670 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,12-01 07:08:30.755  5624  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,12-01 07:08:30.755  5624  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:30.755  5624  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,12-01 07:08:30.861  5624  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 07:08:30.861  5624  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 07:08:31.938   927  2928 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,12-01 07:08:32.486  5624  5960 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 07:08:32.486  5624  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 07:08:32.487  5624  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,12-01 07:08:36.225  5624  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:36.225  5624  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 07:08:36.226  5624  5961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:36.226  5624  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 07:08:36.226  5624  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 07:08:36.226  5624  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 07:08:36.226  5624  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
12-01 07:08:36.226  5624  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,12-01 07:08:36.227  5624  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
12-01 07:08:36.227  5624  5961 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
12-01 07:08:36.227  5624  5961 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
12-01 07:08:36.227  5624  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:36.227  5624  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,12-01 07:08:36.229  5624  5670 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
12-01 07:08:36.231  5624  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:36.231  5624  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 07:08:36.232  5624  5962 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
12-01 07:08:36.232  5624  5962 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:36.232  5624  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,12-01 07:08:36.233  5624  5962 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,12-01 07:08:36.233  5624  5962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
12-01 07:08:36.233  5624  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,12-01 07:08:36.238  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
12-01 07:08:36.238  5624  5670 I jxcore-log: 
,12-01 07:08:36.238  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Number of passed tests:  81'
12-01 07:08:36.238  5624  5670 I jxcore-log: 
12-01 07:08:36.238  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Number of failed tests:  1'
12-01 07:08:36.238  5624  5670 I jxcore-log: 
,12-01 07:08:36.238  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
12-01 07:08:36.238  5624  5670 I jxcore-log: 
12-01 07:08:36.239  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Total duration:  90777'
12-01 07:08:36.239  5624  5670 I jxcore-log: 
12-01 07:08:36.240  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Failures: 
12-01 07:08:36.240  5624  5670 I jxcore-log:  DiscoveryManager isRunning should return true
12-01 07:08:36.240  5624  5670 I jxcore-log: Expected: is <true>
12-01 07:08:36.240  5624  5670 I jxcore-log:      but: was <false>
12-01 07:08:36.240  5624  5670 I jxcore-log: '
12-01 07:08:36.240  5624  5670 I jxcore-log: 
12-01 07:08:36.240  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Failed to execute UT.'
12-01 07:08:36.240  5624  5670 I jxcore-log: 
12-01 07:08:36.241  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
12-01 07:08:36.241  5624  5670 I jxcore-log: 
,12-01 07:08:36.244  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 07:08:36.244  5624  5670 I jxcore-log: 
12-01 07:08:36.245  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 07:08:36.245  5624  5670 I jxcore-log: 
12-01 07:08:36.246  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
12-01 07:08:36.246  5624  5670 I jxcore-log: 
12-01 07:08:36.246  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
12-01 07:08:36.246  5624  5670 I jxcore-log: 
12-01 07:08:36.246  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.246  5624  5670 I jxcore-log: 
,12-01 07:08:36.246  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 07:08:36.246  5624  5670 I jxcore-log: 
,12-01 07:08:36.247  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.247  5624  5670 I jxcore-log: 
12-01 07:08:36.247  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 07:08:36.247  5624  5670 I jxcore-log: 
12-01 07:08:36.247  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 07:08:36.247  5624  5670 I jxcore-log: 
12-01 07:08:36.248  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
12-01 07:08:36.248  5624  5670 I jxcore-log: 
12-01 07:08:36.248  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
12-01 07:08:36.248  5624  5670 I jxcore-log: 
12-01 07:08:36.248  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.248  5624  5670 I jxcore-log: 
12-01 07:08:36.248  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 07:08:36.248  5624  5670 I jxcore-log: 
12-01 07:08:36.248  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.248  5624  5670 I jxcore-log: 
12-01 07:08:36.249  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 07:08:36.249  5624  5670 I jxcore-log: 
12-01 07:08:36.249  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.249  5624  5670 I jxcore-log: 
12-01 07:08:36.249  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 07:08:36.249  5624  5670 I jxcore-log: 
,12-01 07:08:36.249  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 07:08:36.249  5624  5670 I jxcore-log: 
12-01 07:08:36.250  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 07:08:36.250  5624  5670 I jxcore-log: 
12-01 07:08:36.250  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 07:08:36.250  5624  5670 I jxcore-log: 
12-01 07:08:36.250  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 07:08:36.250  5624  5670 I jxcore-log: 
12-01 07:08:36.250  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 07:08:36.250  5624  5670 I jxcore-log: 
12-01 07:08:36.252  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 07:08:36.252  5624  5670 I jxcore-log: 
,12-01 07:08:36.252  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
12-01 07:08:36.252  5624  5670 I jxcore-log: 
12-01 07:08:36.253  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 07:08:36.253  5624  5670 I jxcore-log: 
12-01 07:08:36.253  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
12-01 07:08:36.253  5624  5670 I jxcore-log: 
12-01 07:08:36.253  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 07:08:36.253  5624  5670 I jxcore-log: 
12-01 07:08:36.253  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 07:08:36.253  5624  5670 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,12-01 07:08:36.254  5624  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 07:08:36.254  5624  5670 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
12-01 07:08:36.254  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 07:08:36.254  5624  5670 I jxcore-log: 
12-01 07:08:36.254  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.254  5624  5670 I jxcore-log: 
12-01 07:08:36.254  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 07:08:36.254  5624  5670 I jxcore-log: 
,12-01 07:08:36.254  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.254  5624  5670 I jxcore-log: 
12-01 07:08:36.255  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 07:08:36.255  5624  5670 I jxcore-log: 
12-01 07:08:36.255  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 07:08:36.255  5624  5670 I jxcore-log: 
12-01 07:08:36.255  5624  5624 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
12-01 07:08:36.256  5624  5624 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,12-01 07:08:36.260  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
12-01 07:08:36.260  5624  5670 I jxcore-log: 
12-01 07:08:36.260  5624  5670 I jxcore-log: 2016-12-01 12:08:36 - WARN testUtils: 'myNameCallback not set!'
12-01 07:08:36.260  5624  5670 I jxcore-log: 
,12-01 07:08:38.368  5624  5670 I jxcore-log: 2016-12-01 12:08:38 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
12-01 07:08:38.368  5624  5670 I jxcore-log: 
,12-01 07:08:38.370  5624  5670 I jxcore-log: 2016-12-01 12:08:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
12-01 07:08:38.370  5624  5670 I jxcore-log: 
,12-01 07:08:38.727  5624  5670 I jxcore-log: 2016-12-01 12:08:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
12-01 07:08:38.727  5624  5670 I jxcore-log: 
,12-01 07:08:38.737  5624  5670 I jxcore-log: 2016-12-01 12:08:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
12-01 07:08:38.737  5624  5670 I jxcore-log: 
,12-01 07:08:39.859  5624  5670 I jxcore-log: 2016-12-01 12:08:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
12-01 07:08:39.859  5624  5670 I jxcore-log: 
,12-01 07:08:40.051  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
12-01 07:08:40.051  5624  5670 I jxcore-log: 
,12-01 07:08:40.056  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
12-01 07:08:40.056  5624  5670 I jxcore-log: 
,12-01 07:08:40.061  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
12-01 07:08:40.061  5624  5670 I jxcore-log: 
,12-01 07:08:40.548  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
12-01 07:08:40.548  5624  5670 I jxcore-log: 
,12-01 07:08:40.593  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
12-01 07:08:40.593  5624  5670 I jxcore-log: 
,12-01 07:08:40.607  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
12-01 07:08:40.607  5624  5670 I jxcore-log: 
,12-01 07:08:40.637  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
12-01 07:08:40.637  5624  5670 I jxcore-log: 
,12-01 07:08:40.641  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
12-01 07:08:40.641  5624  5670 I jxcore-log: 
,12-01 07:08:40.904  5624  5670 I jxcore-log: 2016-12-01 12:08:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
12-01 07:08:40.904  5624  5670 I jxcore-log: 
,12-01 07:08:41.031  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
12-01 07:08:41.031  5624  5670 I jxcore-log: 
,12-01 07:08:41.393  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
12-01 07:08:41.393  5624  5670 I jxcore-log: 
,12-01 07:08:41.401  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
12-01 07:08:41.401  5624  5670 I jxcore-log: 
,12-01 07:08:41.405  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
12-01 07:08:41.405  5624  5670 I jxcore-log: 
,12-01 07:08:41.411  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
12-01 07:08:41.411  5624  5670 I jxcore-log: 
,12-01 07:08:41.416  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
12-01 07:08:41.416  5624  5670 I jxcore-log: 
,12-01 07:08:41.443  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
12-01 07:08:41.443  5624  5670 I jxcore-log: 
,12-01 07:08:41.479  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
12-01 07:08:41.479  5624  5670 I jxcore-log: 
,12-01 07:08:41.487  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
12-01 07:08:41.487  5624  5670 I jxcore-log: 
,12-01 07:08:41.493  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
12-01 07:08:41.493  5624  5670 I jxcore-log: 
,12-01 07:08:41.509  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
12-01 07:08:41.509  5624  5670 I jxcore-log: 
,12-01 07:08:41.524  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
12-01 07:08:41.524  5624  5670 I jxcore-log: 
,12-01 07:08:41.530  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
12-01 07:08:41.530  5624  5670 I jxcore-log: 
,12-01 07:08:41.535  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
12-01 07:08:41.535  5624  5670 I jxcore-log: 
,12-01 07:08:41.549  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
12-01 07:08:41.549  5624  5670 I jxcore-log: 
,12-01 07:08:41.566  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
12-01 07:08:41.566  5624  5670 I jxcore-log: 
,12-01 07:08:41.580  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
12-01 07:08:41.580  5624  5670 I jxcore-log: 
,12-01 07:08:41.582   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:41.591  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
12-01 07:08:41.591  5624  5670 I jxcore-log: 
,12-01 07:08:41.604  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
12-01 07:08:41.604  5624  5670 I jxcore-log: 
,12-01 07:08:41.614  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
12-01 07:08:41.614  5624  5670 I jxcore-log: 
,12-01 07:08:41.627  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
12-01 07:08:41.627  5624  5670 I jxcore-log: 
,12-01 07:08:41.637  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
12-01 07:08:41.637  5624  5670 I jxcore-log: 
,12-01 07:08:41.644  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
12-01 07:08:41.644  5624  5670 I jxcore-log: 
,12-01 07:08:41.658  5624  5670 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,12-01 07:08:41.658  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO testUtils: 'BLE multiple advertisement supported'
12-01 07:08:41.658  5624  5670 I jxcore-log: 
,12-01 07:08:41.689  5624  5670 I jxcore-log: 2016-12-01 12:08:41 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
12-01 07:08:41.689  5624  5670 I jxcore-log: 
,12-01 07:08:42.029  5624  5670 I jxcore-log: 2016-12-01 12:08:42 - DEBUG CoordinatedClient: 'connected to the test server'
12-01 07:08:42.029  5624  5670 I jxcore-log: 
,12-01 07:08:42.583   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:42.662  5624  5670 I jxcore-log: 2016-12-01 12:08:42 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
12-01 07:08:42.662  5624  5670 I jxcore-log: 
,12-01 07:08:42.665  5624  5670 I jxcore-log: 2016-12-01 12:08:42 - DEBUG CoordinatedClient: 'test client failed'
12-01 07:08:42.665  5624  5670 I jxcore-log: 
,12-01 07:08:42.669  5624  5670 I jxcore-log: 2016-12-01 12:08:42 - DEBUG CoordinatedClient: 'device disconnected from the test server'
12-01 07:08:42.669  5624  5670 I jxcore-log: 
,12-01 07:08:42.676  5624  5670 I jxcore-log: 2016-12-01 12:08:42 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:251:22
12-01 07:08:42.676  5624  5670 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
12-01 07:08:42.676  5624  5670 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
12-01 07:08:42.676  5624  5670 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
12-01 07:08:42.676  5624  5670 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
12-01 07:08:42.676  5624  5670 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
12-01 07:08:42.676  5624  5670 I jxcore-log: 
,12-01 07:08:42.676  5624  5670 I jxcore-log: 2016-12-01 12:08:42 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
12-01 07:08:42.676  5624  5670 I jxcore-log: 
,12-01 07:08:43.151  5971  5971 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,12-01 07:08:43.157  5971  5971 D AndroidRuntime: CheckJNI is OFF
,12-01 07:08:43.189  5971  5971 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,12-01 07:08:43.224  5971  5971 I Radio-JNI: register_android_hardware_Radio DONE
,12-01 07:08:43.240  5971  5971 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,12-01 07:08:43.248   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,12-01 07:08:43.249   927   940 I ActivityManager: Killing 5624:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,12-01 07:08:43.351   927  3526 I WindowState: WIN DEATH: Window{7825a80 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,12-01 07:08:43.351   927  2929 D WifiService: Client connection lost with reason: 4
12-01 07:08:43.351   927   937 D GraphicsStats: Buffer count: 2
,12-01 07:08:43.406   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,12-01 07:08:43.407   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
12-01 07:08:43.408   927   940 E ActivityManager: Failure starting process com.test.thalitest
12-01 07:08:43.408   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
12-01 07:08:43.408   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:08:43.408   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:08:43.408   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 07:08:43.408   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
12-01 07:08:43.409   927   940 I ActivityManager:   Force finishing activity ActivityRecord{3a58b4 u0 com.test.thalitest/.MainActivity t10}
,12-01 07:08:43.413   927  3822 W ActivityManager: Spurious death for ProcessRecord{87329d0 0:com.test.thalitest/u0a77}, curProc for 5624: null
12-01 07:08:43.417   927   945 W WindowManager: Attempted to add application window with unknown token Token{f16ccdd ActivityRecord{3a58b4 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
12-01 07:08:43.418   927   945 W WindowManager: Token{f16ccdd ActivityRecord{3a58b4 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{f16ccdd ActivityRecord{3a58b4 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
12-01 07:08:43.418   927   945 W WindowManager: view not successfully added to wm, removing view
12-01 07:08:43.418   927   950 I art     : Starting a blocking GC Explicit
,12-01 07:08:43.419   927   945 W WindowManager: Exception when adding starting window
12-01 07:08:43.419   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{78ba40b V.E...... R.....ID 0,0-0,0} not attached to window manager
12-01 07:08:43.419   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
12-01 07:08:43.419   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
12-01 07:08:43.419   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
12-01 07:08:43.419   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
12-01 07:08:43.419   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
12-01 07:08:43.419   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:08:43.419   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:08:43.419   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 07:08:43.419   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,12-01 07:08:43.502   927   950 I art     : Explicit concurrent mark sweep GC freed 53235(3MB) AllocSpace objects, 9(292KB) LOS objects, 33% free, 28MB/43MB, paused 1.547ms total 83.467ms
,12-01 07:08:43.523   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,12-01 07:08:43.525  5971  5971 I art     : System.exit called, status: 0
,12-01 07:08:43.526  5971  5971 I AndroidRuntime: VM exiting with result code 0.
,12-01 07:08:43.540   927   950 I ActivityManager: Start proc 5981:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,12-01 07:08:43.541   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,12-01 07:08:43.545   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,12-01 07:08:43.550  5861  5861 D BluetoothMapAppObserver: onReceive
,12-01 07:08:43.550  5861  5861 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
12-01 07:08:43.551  4033  4152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
12-01 07:08:43.562  3650  3650 I Keyboard.Facilitator: resetDictionaries() : en_US
12-01 07:08:43.563   927  2900 I InputReader: Reconfiguring input devices.  changes=0x00000010
,12-01 07:08:43.580  3650  5993 I Keyboard.Facilitator.DecoderInitializer: run()
,12-01 07:08:43.584   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 07:08:43.584  3650  5993 I Decoder : createOrResetDecoder
,12-01 07:08:43.598  3756  3756 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,12-01 07:08:43.605  3351  5995 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,12-01 07:08:43.616  3521  3521 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,12-01 07:08:43.616  3521  3521 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,12-01 07:08:43.630   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,12-01 07:08:43.639  3668  6000 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,12-01 07:08:43.640  3668  6000 D AccountUtils: Clearing selected account for com.test.thalitest
,12-01 07:08:43.644    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 07:08:43.651    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 07:08:43.664    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 07:08:43.669  3521  3521 I ConfigService: onCreate
,12-01 07:08:43.671  3521  6002 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
12-01 07:08:43.671  3521  6002 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
12-01 07:08:43.671  3521  6002 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,12-01 07:08:43.675  3521  6002 W SQLiteOpenHelper: Opened config.db in read-only mode
,12-01 07:08:43.698  3650  5993 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,12-01 07:08:43.708  3351  5995 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
12-01 07:08:43.709  3351  5995 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
12-01 07:08:43.709  3351  5995 E AndroidRuntime: Process: android.process.acore, PID: 3351
12-01 07:08:43.709  3351  5995 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:08:43.709  3351  5995 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,12-01 07:08:43.715   927  6004 E DropBoxManagerService: Can't write: system_app_crash
12-01 07:08:43.715   927  6004 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
12-01 07:08:43.715   927  6004 E DropBoxManagerService: 	... 5 more
,12-01 07:08:43.724  3668  6000 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,12-01 07:08:43.741  3668  6000 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:08:43.741  3668  6000 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
12-01 07:08:43.741  3668  6000 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
12-01 07:08:43.741  3668  6000 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,12-01 07:08:43.742  3668  6000 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,12-01 07:08:43.747  3351  5995 I Process : Sending signal. PID: 3351 SIG: 9
,12-01 07:08:43.818  3668  6008 I GMPM-SVC: App measurement is starting up
,12-01 07:08:43.829  3668  6008 E GMPM-SVC: AppMeasurementService not registered/enabled
,12-01 07:08:43.830  3668  6008 E GMPM-SVC: Uploading is not possible. App measurement disabled
,12-01 07:08:43.846   927  3111 I ActivityManager: Process android.process.acore (pid 3351) has died
,12-01 07:08:43.846   927  3111 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,12-01 07:08:44.036   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
